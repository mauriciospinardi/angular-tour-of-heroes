# Angular: Tour of Heroes + Spring Boot Web/H2/JPA

_Tour of Heroes_ para _framework_ Angular, conforme
[angular.io](https://angular.io/tutorial), acrescido de servidor Spring Boot
Web/H2/JPA para testes de uso e integração.

## Ambiente de desenvolvimento

- [Node.js®](https://nodejs.org/en/) 12.18.3 LTS
  - npm package manager 6.14.6
- [Apache Maven](https://maven.apache.org/index.html) 3.6.3
- [JA SE Development Kit](https://www.oracle.com/technetwork/java/javase/downloads/index.html) 11.0.8

## Modo de operação

- `cd angular-client`
- `npm install` (para instalar as dependências do cliente)
- `npx ng build --prod` (para construir o cliente)
- `cd ../spring-boot-web-h2-jpa-server`
- `mvn clean install` (para instalar as dependências e construir o servidor)
- `mvn spring-boot:run` (para lançar o servidor)

Endereço de operação: http://localhost:8080
