# Microcommerce
Mini e-commerce system using a microservice architecture.

## About
I use Java Spring Boot to develop an e-commerce system using a microservice architecture. This microservice will manage the products for sale, it must be able to add, delete, update and display the products. It will expose a REST API that proposes all CRUD database operations (Create, Read, Update, Delete).

The component is composed of:
- Product class that shows the characteristics of a product (name, price, etc.)
- A controller that responds to GET, PUT, POST and DELETE requests and does the necessary operations.
- the Data Acccess Object (DAO) to communicate with the database

## Java Spring Boot
Spring Boot is a framework that facilitates the development of Spring-based applications by providing tools to obtain a packaged application in jar.

![image1](https://github.com/nicolaschen1/Microcommerce/blob/master/spring-boot-490x257.png)

## Requirements
- Jackson: parses JSON and links Java classes to JSON content.
- Tomcat
- Hibernate
- Logging through logback and others

## Test de l'API
[Postman](https://www.getpostman.com/) is a software that focuses on API testing.
It allows to test microservices.

## Supported platforms
- Windows

## How to use
Run the microservice with Intellij IDEA, then go to 
http://localhost:9090/Produits
in order to display the products (JSON format), then test some requests with Postman.

## License
MIT License

Copyright (c) 2019 Nicolas Chen

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
