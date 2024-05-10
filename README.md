# Projeto: API Rest de um Crud para um Sistema de Gerenciamento de Professores utilizando Mongodb

## Sobre o Projeto
Este projeto utiliza o Nest.js, um framework para construção de aplicativos Node.js eficientes e escaláveis.

<p align="center">
  <a href="http://nestjs.com/" target="blank"><img src="https://nestjs.com/img/logo-small.svg" width="200" alt="Nest Logo" /></a>
</p>

## Banco de Dados
Para este projeto, é utilizado um banco de dados MongoDB hospedado no [cloud.mongodb.com](http://cloud.mongodb.com). Este é um servidor online que permite a criação gratuita de um banco de dados simples. Caso seu sistema cresça, pode ser interessante migrar seu banco de dados para serviços mais robustos, como a AWS, por exemplo, ou mesmo utilizar uma versão paga.

## Instalação
Para instalar as dependências do projeto, é necessário primeiro instalar o Mongoose, que é uma biblioteca do Node.js para modelagem de objetos MongoDB. Execute o seguinte comando:

npm install --save mongoose @nestjs/mongoose

## Criando a Estrutura do Projeto
A estrutura do projeto pode ser definida da seguinte maneira:

1. **Criando o Módulo Teacher**
nest g module teacher

2. **Criando o Controlador Teacher**
nest g controller teacher

3. **Criando o Serviço Teacher**
nest g service teacher

## Executando o Projeto
Para iniciar o projeto, execute o seguinte comando:

npm start

Este comando irá iniciar o servidor e seu aplicativo estará pronto para uso.





