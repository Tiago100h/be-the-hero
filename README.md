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

`npm install celebrate` Adiciona biblioteca para fazer validações.

`npm install jest -D` Adiciona framework de teste.

`npx jest --init` Inicializa o jest.

`npm test` Executa os testes.

`npm install cross-env` Instala o pacote para gerenciar variáveis ambiente.

`npm install supertest -D` Instala o pacote para testes de integração.

### Frontend

`npx create-react-app frontend` Cria um projeto React.

`npm start` Executa o projeto. (Executa o script que está definido no arquivo `package.json`)

`npm install react-icons` Instala pacote de ícones.

`npm install react-router-dom` Instala pacote de rotas.

`npm install axios` Instala cliente http.

### Mobile

`npm install -g expo-cli` Instalar o pacote Expo de forma global

`expo -h` Mostra os comandos do expo

`expo init mobile` Cria o projeto Mobile

`yarn start` Executa o projeto

`npm install @react-navigation/native` Instala pacote de rotas. (https://reactnavigation.org/docs/getting-started)

`expo install expo-constants` Instala pacote expo-constants.

`expo install expo-mail-composer` Instala pacote de e-mail.

`npm install axios` Instala client http.

`npm install intl` Instala pacote de internacionalização.

## Dicas Deploy
### Node
deploy heroku node (para testes/plano gratuito)

digital ocean (aplicação pequena) (deploy node.js youtube)

### Frontend
netlify (aplicação pequena)

### Mobile
gerando apk expo (youtube)
`expo publish` Update Over the Air

## Dicas estudos
Padrões de código: ESLint, Prettier

Autenticação JWT

Styled Components
