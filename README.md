# ![Logo](https://github.com/Math-rm1/sds2/blob/main/front-web/src/Navbar/logo.svg) DSDelivery
DSDelivery é uma aplicação web full-stack e mobile construída durante a 2ª edição da **Semana DevSuperior** (#sds2), evento organizado pela [DevSuperior](https://devsuperior.com.br "Site da DevSuperior").

## :earth_americas: Hospedagem da aplicação

[![Netlify Status](https://api.netlify.com/api/v1/badges/b2aea278-5f93-4cd1-a928-462fbbe6d16f/deploy-status)](https://app.netlify.com/sites/math-sds2/deploys)

https://math-sds2.netlify.app

> Obs.: Durante a primeira execução, os produtos podem demorar alguns segundos para carregar devido ao tempo de inatividade do servidor Heroku.

## :book: Sobre o projeto

Sistema de pedidos chamado DSDelivery que simula o pedido e a entrega de uma pizzaria fictícia. O usuário é capaz de registrar pedidos através do sistema.

### :iphone: Layout mobile
  <img height="500px" alt="Mobile 01" src="https://github.com/Math-rm1/sds2/blob/main/assets/mobile-01.jpg"/> <img height="500px" alt="Mobile 02" src="https://github.com/Math-rm1/sds2/blob/main/assets/mobile-02.jpg"/>  <img height="500px" alt="Mobile 03" src="https://github.com/Math-rm1/sds2/blob/main/assets/mobile-03.jpg"/>

### :computer: Layout web
  <img alt="Web-01" src="https://github.com/Math-rm1/sds2/blob/main/assets/web-01.png"/>
  <img alt="Web-01" src="https://github.com/Math-rm1/sds2/blob/main/assets/web-02.png"/>
  <img alt="Web-01" src="https://github.com/Math-rm1/sds2/blob/main/assets/web-03.png"/>

### :diamond_shape_with_a_dot_inside: Modelo conceitual
![Modelo Conceitual](https://raw.githubusercontent.com/devsuperior/sds2/master/assets/modelo-conceitual.png)

## :rocket: Tecnologias utilizadas
### Back end
- Java
- Spring Boot
- JPA / Hibernate
- Maven
### Front end e mobile
- HTML / CSS / JS / TypeScript
- ReactJS
- React Native
- Expo
- Axios
### API
- Mapbox
### Implantação em produção
- Back end: Heroku
- Front end web: Netlify
- Banco de dados: Postgresql

## :wrench: Como executar o projeto

### Back end
Pré-requisitos: Java 11

```bash
# clonar repositório
git clone https://github.com/Math-rm1/sds2

# entrar na pasta do projeto back end
cd backend

# executar o projeto
./mvnw spring-boot:run
```

### Front end web
Pré-requisitos: npm / yarn

```bash
# clonar repositório
git clone https://github.com/Math-rm1/sds2

# entrar na pasta do projeto front end web
cd front-web

# instalar dependências
npm install

# executar o projeto
npm start
```

### Front end mobile
Pré-requisitos: npm / expo

```bash
# clonar repositório
git clone https://github.com/Math-rm1/sds2

# entrar na pasta do projeto front end web
cd front-mobile

# instalar dependências
expo install @react-navigation/stack @react-native-community/masked-view react-native-screens react-native-gesture-handler @react-navigation/native expo-app-loading @expo-google-fonts/open-sans expo-font

# executar o projeto
npm start
```

## :pencil: Licença

[![NPM](https://img.shields.io/npm/l/react)](https://github.com/Math-rm1/sds2/blob/main/LICENSE)

Esse projeto está sob a licença MIT. Veja o arquivo LICENSE para mais detalhes.

## :bust_in_silhouette: Autor

[![Matheus](https://img.shields.io/badge/linkedin%20-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-r-mariano)

Matheus Rodrigues Mariano
