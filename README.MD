# Vulnerabilidade de Cross-Site Scripting

## Descrição

Este projeto visa explorar e analisar a vulnerabilidade de Cross-Site Scripting (XSS) em aplicações web. Através de uma análise detalhada, testes práticos e propostas de soluções eficazes, buscamos fortalecer a segurança do software contra essa ameaça comum e perigosa.

## Objetivos

- Realizar uma análise abrangente de áreas suscetíveis a ataques XSS.
- Utilizar ferramentas automatizadas e testes manuais para identificar vulnerabilidades potenciais.
- Propor soluções e recomendações para mitigar os riscos associados ao XSS.

## Configuração do Ambiente

Certifique-se de ter as seguintes ferramentas instaladas antes de executar as APIs:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (geralmente vem com o Node.js)
- Outras dependências específicas do seu projeto, se houver
  ```bash
  npm install
  ```

## Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/carla-reis-cr/sec_xss.git
   cd ahm-xss

   ```

2. APIs

- Simula um banco

  ```bash
  cd api-bank
  npm install
  node index.js

  ```

- Simula a hacker
  ```bash
  cd api-bank
  npm install
  node index.js
  ```

3. Front-end

   ```bash
   cd frontend
   serve
   ```

   O frontend estará disponível em http://localhost:3000.

Video -> https://www.youtube.com/watch?v=SQo-K0uO66Q
