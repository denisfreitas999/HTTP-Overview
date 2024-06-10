# HTTP: Entendendo a Web - Alura Course Overview

## Índice
1. [Conhecendo o Protocolo HTTP](#1-conhecendo-o-protocolo-http)
2. [Aprendendo sobre URLs](#2-aprendendo-sobre-urls)
3. [Inspecionando o Protocolo HTTP](#3-inspecionando-o-protocolo-http)
4. [Protegendo a WEB com o HTTPS](#4-protegendo-a-web-com-o-https)
5. [Controlando o HTTP](#5-controlando-o-http)
6. [Conhecendo as Evoluções](#6-conhecendo-as-evoluções)

## 1. Conhecendo o Protocolo HTTP
Na primeira etapa do curso, foquei em compreender os fundamentos do protocolo HTTP e sua importância para a web:
- **Configuração do AluraBooks**: Iniciei configurando o projeto que foi utilizado ao longo do curso.
- **Contextualização do HTTP**: Entendi o papel do HTTP nas camadas da Internet.
- **Componentes do HTTP**: Caracterizei o HTTP e seus principais componentes.
- **Arquitetura das Comunicações**: Identifiquei a arquitetura das comunicações utilizando HTTP.

## 2. Aprendendo sobre URLs
Na segunda etapa, aprofundei meu conhecimento sobre URLs e sua importância no protocolo HTTP:
- **Identificação de URLs**: Aprendi a identificar uma URL e entender seu papel no protocolo HTTP.
- **Configuração de URLs**: Configurei URLs para utilizar protocolos, domínios, portas e caminhos específicos.
- **Porta Padrão**: Utilize a porta padrão nas URLs com o protocolo HTTP.
- **Nomes de Domínios**: Usei nomes de domínios ao invés de endereços IP para acessar diferentes sites na web.

## 3. Inspecionando o Protocolo HTTP
Na terceira etapa, explorei ferramentas para inspecionar e depurar mensagens HTTP:
- **Telnet**: Inspecionei mensagens HTTP no terminal usando o telnet, verificando que são baseadas em texto.
- **Estrutura das Mensagens HTTP**: Verifiquei que as mensagens HTTP são divididas em cabeçalho e corpo.
- **Postman**: Depurei os métodos HTTP usando o Postman, permitindo ler e criar recursos no backend do AluraBooks.
- **Configuração de Cabeçalhos**: Configurei cabeçalhos em requisições para o backend, permitindo o acesso a conteúdos que exigem login.
- **Códigos de Resposta HTTP**: Depurei os códigos de resposta HTTP, entendendo as classes como 2xx (sucesso) e 4xx (erro do cliente).

## 4. Protegendo a WEB com o HTTPS
Na quarta etapa, foquei em entender e configurar a segurança na web utilizando HTTPS:
- **Wireshark**: Utilizei a ferramenta Wireshark para verificar que o HTTP estava expondo dados sensíveis.
- **Configuração do HTTPS**: Configurei o backend para habilitar o HTTPS, garantindo que os dados sejam criptografados antes do envio.
- **Certificados Digitais**: Caracterizei o que são certificados digitais e chaves públicas, fundamentais para a segurança dos websites através do HTTPS.

## 5. Controlando o HTTP
Na quinta etapa, aprendi a controlar e manipular parâmetros e cabeçalhos HTTP:
- **Query Params e POST**: Especifiquei parâmetros com GET através dos Query Params e com POST através do corpo da requisição.
- **Servindo HTML**: Criei uma rota de documentação no AluraBooks, servindo HTML ao invés de JSON.
- **Content-Type e Accept**: Aprendi a informar o formato do conteúdo no corpo da mensagem HTTP através do cabeçalho Content-Type e a indicar o formato esperado da resposta com o cabeçalho Accept.

## 6. Conhecendo as Evoluções
Na última etapa, explorei as evoluções do protocolo HTTP e suas melhorias:
- **HTTP/1.1 vs HTTP/2 vs HTTP/3**: Identifiquei as limitações do HTTP/1.1 e as melhorias trazidas pelo HTTP/2 e HTTP/3.
- **Configuração do HTTP/2**: Configurei o HTTP/2 na API do AluraBooks.
- **Verificação do HTTP/2**: Verifiquei que o HTTP/2 estava ativo, utilizando a ferramenta de inspeção do navegador, e observei que o HTTP/3 utiliza menos conexões TCP.
