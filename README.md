# Resumo:

Este projeto é uma rede social simples, construída com React para o frontend e Node.js com GraphQL para o backend. A aplicação permite que os usuários se registrem, façam login, criem postagens, curtam e comentem em postagens de outros usuários.

## Tecnologias Utilizadas:

* Frontend:

React: Biblioteca JavaScript para a construção da interface do usuário.
Semantic UI React: Biblioteca de componentes para estilizar a interface.

* Backend:

  * Node.js: Ambiente de execução JavaScript no servidor.
  * GraphQL: Linguagem de consulta e manipulação de dados eficiente.
  * Apollo Server: Implementação GraphQL para Node.js.
  * MongoDB: Banco de dados NoSQL para armazenar dados.
  * Mongoose: Biblioteca para modelar objetos MongoDB.

* Autenticação:

  * JSON Web Tokens (JWT): Utilizado para autenticar usuários e manter sessões.

* Controle de Estado:

  * Context API (React): Utilizado para gerenciar o estado global da autenticação do usuário.

* Estilo e Componentes:

  * Semantic UI CSS: Estilos predefinidos para melhorar a estética.
  * MyPopup: Componente personalizado para pop-ups informativos.

* Manipulação de Dados:

  * Apollo Client (React Hooks): Utilizado para consumir dados do servidor GraphQL.

* Roteamento:

  * React Router DOM: Utilizado para a navegação entre páginas da aplicação.

* Outros:

  * Moment.js: Biblioteca para manipulação de datas e horas.
  * JWT Decode: Utilizado para decodificar tokens JWT no frontend.
  * Service Worker: Configurado para proporcionar funcionalidades offline (PWA).

## Instruções de Execução:

1. Clone o repositório.
2. Instale as dependências utilizando npm install nos diretórios client e server.
3. Configure o arquivo .env no diretório server com as variáveis apropriadas.
4. Inicie o servidor com npm start no diretório server.
5. Inicie o cliente com npm start no diretório client.

## Observações:

* Este projeto foi desenvolvido com fins educativos e pode ser expandido com novos recursos e melhorias.
* Certifique-se de ter o Node.js e o MongoDB instalados em sua máquina antes de executar o projeto.

## Licença:
Este projeto é licenciado sob a Licença MIT.
