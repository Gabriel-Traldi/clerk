# Repositório para Validação do Clerk

Este repositório contém dois projetos relacionados à validação do Clerk, uma ferramenta de gerenciamento de usuários.

## Projetos

### 1. auth-clerk

O projeto "auth-clerk" é uma aplicação construída com Next.js. Esta aplicação tem como objetivo validar e testar o Clerk, gerando uma tela de login e fazendo o controle de rotas privadas/públicas. Para executar este projeto, você precisará ter o Node.js instalado em seu ambiente.

Para iniciar o projeto, siga os passos abaixo:

1. Instale as dependências do projeto executando o comando:
   ```
   npm install
   ```

2. Inicie o servidor de desenvolvimento local executando o comando:
   ```
   npm run dev
   ```

3. Acesse a aplicação no navegador através da URL:
   ```
   http://localhost:3000
   ```

### 2. auth-clerk-server

O projeto "auth-clerk-server" é uma aplicação construída com Node.js e utiliza o framework Fastify. Esta API oferece um endpoint privado, que retornas as informações do usuário, persistidas no Clerk.

Para iniciar o projeto, siga os passos abaixo:

1. Instale as dependências do projeto executando o comando:
   ```
   npm install
   ```

2. Inicie o servidor local executando o comando:
   ```
   npm start
   ```

3. A API estará disponível para acesso em:
   ```
   http://localhost:3333
   ```
