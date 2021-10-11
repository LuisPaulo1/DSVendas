# DSVendas
[![NPM](https://img.shields.io/npm/l/react)](https://github.com/LuisPaulo1/spring-react/blob/master/LICENSE) 

# Sobre o projeto

https://luis-paulo-dsvendas.netlify.app/

DSVendas é uma aplicação full stack web construída durante a 3ª edição da **Semana DevSuperior** (#sds3), evento organizado pela [DevSuperior](https://devsuperior.com "Site da DevSuperior").

Esta aplicação consiste em exibir um dashboard a partir de dados fornecidos por um backend construído com Spring Boot.

## Layout web
![Web 1](https://github.com/LuisPaulo1/assets/blob/master/dsvendas/pagina-inicial.png)

![Web 2](https://github.com/LuisPaulo1/assets/blob/master/dsvendas/Dashboard.jpeg)

## Modelo conceitual
![Modelo Conceitual](https://github.com/LuisPaulo1/assets/blob/master/dsvendas/Diagrama-de-classes.png)

## Arquitetura da aplicação
![Arquitetura](https://github.com/LuisPaulo1/assets/blob/master/dsvendas/Padrao-camadas.png)

# Tecnologias utilizadas
## Backend
- Java
- Spring Boot
- JPA / Hibernate
- Maven
## Frontend
- HTML / CSS / JS / TypeScript
- ReactJS
- Apex Charts
- Axios
## Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

# Como executar o projeto

## Clonar o repositório
```bash
git clone https://github.com/LuisPaulo1/DSVendas.git
```

## Para executar o backend
Pré-requisitos: Java 11

```bash
# entrar na pasta do projeto backend
cd DSVendas/backend

# executar o projeto
./mvnw spring-boot:run
```

## Para executar o frontend
Pré-requisitos: yarn

```bash
# entrar na pasta do projeto frontend
cd DSVendas/frontend

# instalar dependências
yarn

# executar o projeto
yarn start
```

# Autor

Luis Paulo

https://www.linkedin.com/in/luis-paulo-souza-a54358134/
