# executa o backend e o disponibiliza através de um servidor no endereço http://localhost:8000
npm run start-auth

# compila o frontend e o disponibiliza através de um servidor no endereço http://localhost:3000
npm start

# comando para instalar a versão HTTPS no projeto
openssl req -x509 -sha256 -nodes -days 365 -newkey rsa:2048 -keyout server.key -out server.crt