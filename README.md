# NLW2_PROFFY
Aplicativo desenvolvido com NodeJS, React e React Native, apresentando um projeto de ligação entre alunos e professores para aprendizado.
Todo o conhecimento foi trazido pela [RocketSeat](http://rocketseat.com.br/).

Primeiramente, após baixar o NLW2_PROFFY, você precisa instalar as dependências para cada um dos diretórios server, web e mobile com:

```
yarn
ou
npm install
```

## Database

A primeira coisa a fazer é criar o banco de dados e para isso é necessário rodar dentro de server, o comando:

```
yarn knex:migrate
ou
npm run knex:migrate
```

## Rodar a api

Criado o banco de danos, você pode deixar rodando em um terminal a parte, dentro da pasta server o comando:

```
yarn start
ou 
npm run start
```
para que a api esteja funcionando e você possa melhor usufruir da web ou mobile.

## Web

Na web, é onde você conseue criar e visualizar diversas features da aplicação, podendo rodar em diversos tipos de telas, graças ao fato de ser responsivo.

Para rodar a versão web, só é necessário executar na pasta web:
```
yarn start
ou
npm run start
```

## Mobile

No mobile é necessário primeiramente você alterar o ip de services/api para o ip da sua máquina.
Feito isso é só rodar na pasta mobile:

```
yarn start
ou
npm run start
```
Para executar o projeto.
Vai-se abrir uma página onde você poderá executar em emuladores ou no dispositivo físico. Se for no dispositivo físico é necessário baixar o app Expo e scannear o QR code.

Obs: este projeto foi adaptado para celulares de tamanhos similares ao G4. 

De resto, algumas coisas foram implementadas a mais, como o uso do useRef e um código mais limpo com a ajuda do esLint.




