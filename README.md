# Be the Hero
Semana OmniStack 11

## Comandos utilizados no terminal
### Backend

`npm init -y` Cria um projeto Node.

`npm install express` Adiciona o Express no projeto.

`node index` ou `node index.js` Executa o projeto.

`npm install nodemon -D` Instala o pacote Nodemon como uma dependência de desenvolvimento.

`npm start` Executa o projeto. (Executa o script que está definido no arquivo `package.json`)

`npm install knex` Instala o Knex.

`npm install sqlite3` Instala o Driver SQLite.

`npx knex init` Cria o arquivo de configuração do banco de dados.

`npx knex migrate:make create_ongs` Cria o arquivo de migration dentro da pasta que está configurada no `knexfile.js`.

`npx knex migrate:latest` Roda a migration criada acima.

`npx knex migrate:make create_incidents` Cria a migration dentro da pasta que está configurada no `knexfile.js`.

`npx knex` Lista os comandos do knex.

`npm install cors` Adiciona módulo de segurança.

### Frontend

`npx create-react-app frontend` Cria um projeto React.

`npm start` Executa o projeto. (Executa o script que está definido no arquivo `package.json`)