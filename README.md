# oministack-backend
API desenvolvida utilizando nodejs, expressjs e knexjs (para o banco de dados com sqlite)
Para rodar a aplicação basta instalar as dependências com ```npm install``` e iniciar ```npm start``` ou ```npm start``` para iniciar com o nodemon. O servidor estará rodando localhost na porta 3001 ```localhost:3001```
Utilizei as seguintes dependências:
- ```cors``` para permitir outras URLs se conectarem com a aplicação
- ```nodemon``` para atualizar o código automaticamente quando fizer alterações sem precisar parar o node
- ```sqlite3``` para o banco de dados
- ```knexjs``` para conexão com o banco de dados
- ```express``` para facilitar a criação de rotas

Deploy da aplicação feito com Heroku, utilizando o Heroku CLI para acessar o terminal
https://devcenter.heroku.com/articles/heroku-cli#download-and-install
