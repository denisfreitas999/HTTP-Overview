# executa o backend e o disponibiliza através de um servidor no endereço http://localhost:8000
npm run start-auth

# compila o frontend e o disponibiliza através de um servidor no endereço http://localhost:3000
npm start

# comando para instalar a versão HTTPS no projeto
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt

# instalar biblioteca que permite o uso do http2
npm i spdy

# criar o build do projeto do http2
npm run build

# criar arquivo server_http2.js
const spdy = require("spdy")
const express = require("express")
const fs = require("fs")

const app = express()

app.use(express.static("build"))

spdy.createServer(
    {
        key: fs.readFileSync("./server.key"),
        cert: fs.readFileSync("./server.crt")
    },
    app
).listen(3002, (err) => {
    if(err){
        throw new Error(err)
    }
    console.log("Listening on port 3002")
})

# executar server com http2 
node .\server_http2.js