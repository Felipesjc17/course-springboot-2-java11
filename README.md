## course-springboot-2-java11
# Projeto Web Service com Spring Boot desenvolvido durante o curso de java completo do professor Nelio Alves.

OBS. É possível acompanhar a evolução do projeto a partir de cada commit realizado.

O Projeto é um Web Service construído em java utilizando Spring boot, contém um CRUD sendo cadastro de usuários, produtos e ordens. Foram utilizados a IDE STS4(Spring Tool Suite 4), Hibernate e JPA, construído em camadas lógicas e fazendo o correto tratamento de exceções, foi feito o deploy da aplicação no Heroku. Como banco de dados foi usado o H2 e Postgresql para testes, no Heroku foi provisionado na aplicação o Heroku Postgres, assim definindo o banco de dados de produção.
Endereço para consulta do projeto funcionando no Heroku https://course-javasb-projeto-spring.herokuapp.com/users

## Modelo de Domínio do projeto 
![Captura de tela 2022-01-23 114625](https://user-images.githubusercontent.com/87396979/150684246-3d51ee34-926d-4371-9bd9-f454ac7e4694.png)

## Camadas Lógicas Resource, Service e Repository
![Captura de tela 2022-01-23 114350](https://user-images.githubusercontent.com/87396979/150684348-26ab51e0-c201-4088-9f4d-27a8db4a5d53.png)

## Cada Pacote com suas classes bem definidas
![Captura de tela 2022-01-23 130424](https://user-images.githubusercontent.com/87396979/150689241-06824385-4768-4df8-be0f-8d2f92cb16a5.png)

## Perfis de banco de dados para teste e produção
![Captura de tela 2022-01-23 130052](https://user-images.githubusercontent.com/87396979/150689289-aa8e12c6-2863-44b4-8760-55afb18a16b7.png)

## Teste com banco de dados H2 (perfil test)
![Testeh2](https://user-images.githubusercontent.com/87396979/150689309-3ee50292-92fb-403a-9bcb-5bfda2c694ef.png)

## Teste com banco de dados PostgreSQL (perfil dev)
![Captura de tela 2022-01-23 123506](https://user-images.githubusercontent.com/87396979/150689318-ffb98925-4f23-4e36-98d9-79fa658d2bdd.png)

## Deploy da aplicação no Heroku acessando banco de dados PostgreSQL provisionando no Heroku (perfil prod)
![Captura de tela 2022-01-23 141721](https://user-images.githubusercontent.com/87396979/150690041-6da54155-9d74-4437-b4e1-f567e0ecfd10.png)

![Captura de tela 2022-01-23 123506](https://user-images.githubusercontent.com/87396979/150689339-f50da581-8d9a-4339-8f49-a89d96d17460.png)

## Aplicação funcionando, fazendo uma simples busca de usuários https://course-javasb-projeto-spring.herokuapp.com/users
![Captura de tela 2022-01-23 131044](https://user-images.githubusercontent.com/87396979/150689376-b4a4d721-4a32-45cd-b166-e9f452351001.png)
