# Projeto Spring Boot - Hello World API

## Descrição
Este é um projeto simples desenvolvido com Spring Boot que expõe uma API REST na rota `/test`, retornando a mensagem "Hello, World!".

## Tecnologias Utilizadas
- Java 17+
- Spring Boot
- Spring Web

## Configuração do Projeto
O projeto foi gerado utilizando o [Spring Initializr](https://start.spring.io/) com a seguinte dependência:
- **Spring Web**: Necessário para criar aplicações web RESTful.

## Estrutura do Projeto
```
/hello-world-api
  |-- src/main/java/com/seuprojeto/controller/HelloController.java
  |-- src/main/resources/application.properties
  |-- pom.xml
  |-- README.md
```

## Instalação e Execução
### 1. Clonar o repositório
```sh
git clone <URL_DO_REPOSITORIO>
cd hello-world-api
```

### 2. Compilar e executar o projeto
Se estiver usando **Maven**, rode o seguinte comando:
```sh
mvn spring-boot:run
```
Se estiver usando **Java diretamente**, compile e execute:
```sh
./mvnw spring-boot:run
```

### 3. Acessar a API
Após iniciar a aplicação, acesse a URL:
```
http://localhost:8080/test
```
O retorno esperado será:
```
Hello, World!
```

## Publicação no GitHub
O projeto foi versionado utilizando **Git** e publicado no GitHub.
Para clonar e contribuir, acesse:
[Repositório no GitHub](<URL_DO_REPOSITORIO>)

## Autor
Desenvolvido por Thales Augusto.

