## Esta  a página de documentação do Projeto Solidarize

Este projeto esta sendo desenvolvido para a cadeira de proejto e desenvolvimento da Faculdade SENACRS. Este projeto tem como objetivo possibilitar que pessoas que queiram efetuar atividades de voluntariado tenha um lugar para achar tais eventos.

### Funcionalidades importantes
O Solidarize tem como principais funcionalidades:
- Cadastro de voluntários e instituíções;
- Cadastro de eventos que precisam de voluntários;
- Notificação por e-mail para que os voluntrios cadastrados tenham recebam quais são os eventos que irão ocorrer nos próximos dias.
- Feedback dos voluntários sobre o evento(Em andamento);
- Adicionar "likes" aos eventos(Em andamento);



### Arquitetura

A arquitetura do projeto tem como **guideline** o [12FactorApp](https://12factor.net/). Neste momento temos alguns repositórios e cada um tem um **tech stack** específica como o de front-end utiliza [node.js](https://nodejs.org/en/) e os repositórios de **back-end** tem a base com **Java 8** e [Spring Boot](https://projects.spring.io/spring-boot/). 

Utilizamos o serviço do [Travis-CI](https://travis-ci.org/) para rodar os nosso builds automatizados no server para a integração contínua e apra fazer o deploy das aplicações. Para **PaaS** utilizamos o [Heroku](heroku.com).

### Contribuidores

Os contribuídores deste projeto são:
- @antoniogabrielti
- @deckerjeferson
- @lucianoortizsilva
- @mrissi
- @willmenn

### Contato

Para contato ou qualquer problema envolvendo o sistema, porfavor crie uma **issue** neste repositório que iremos endereçar o problema.
