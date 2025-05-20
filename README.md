# Projeto DSList - API de Catálogo de Games

---

Bem-vindo ao repositório do **Projeto DSList**, uma API RESTful completa para gerenciamento de um catálogo de games, desenvolvida durante o **Intensivão Java Spring do Professor Nelio Alves (Devsuperior)**. Este projeto tem como objetivo consolidar os conhecimentos em desenvolvimento back-end com Java e o poderoso framework Spring Boot, aplicando as melhores práticas e padrões do mercado.

---

## Sobre o Projeto

O DSList é uma API que permite listar, organizar e manipular informações de jogos. Ao longo do Intensivão, construímos um sistema robusto e escalável, abordando desde os fundamentos do Spring até conceitos mais avançados de arquitetura e persistência de dados.

---

## Tecnologias Utilizadas

* **Java 17+**: Linguagem de programação principal.
* **Spring Boot 3.x**: Framework para construção de aplicações Java.
* **Spring Data JPA**: Abstração para acesso a dados com ORM (Object-Relational Mapping).
* **Hibernate**: Implementação de JPA.
* **PostgreSQL**: Sistema de gerenciamento de banco de dados relacional (utilizado em produção/dev).
* **H2 Database**: Banco de dados em memória para testes e desenvolvimento rápido.
* **Maven**: Ferramenta de gerenciamento de dependências e construção de projetos.
* **Docker / Docker Compose**: Para orquestração e gerenciamento de contêineres (ambiente de banco de dados).
* **Insomnia / Postman**: Ferramentas para testar as APIs REST.

---

## Conceitos Abordados

Este projeto é uma jornada de aprendizado que cobre os seguintes conceitos essenciais:

* **Sistemas Web e Recursos**: Entendimento de como as aplicações web funcionam e interagem com recursos.
* **Cliente/Servidor, HTTP, JSON**: Fundamentos da comunicação web, protocolos e formatos de dados.
* **Padrão REST para API Web**: Construção de APIs seguindo os princípios RESTful para comunicação eficiente e padronizada.
* **Estruturação de Projeto Spring Rest**: Organização de um projeto Spring Boot para APIs REST.
* **Entidades e ORM (Object-Relational Mapping)**: Mapeamento de objetos Java para tabelas de banco de dados e vice-versa, utilizando JPA.
* **Database Seeding**: Popular o banco de dados com dados iniciais para testes e demonstração.
* **Padrão de Camadas (Layered Architecture)**: Organização do código em camadas distintas (Controller, Service, Repository) para promover a separação de responsabilidades e facilitar a manutenção.
    * **Controller**: Responsável por receber as requisições HTTP e retornar as respostas (camada de interface/API).
    * **Service**: Contém a lógica de negócio da aplicação (camada de serviço).
    * **Repository**: Interage diretamente com o banco de dados (camada de persistência).
* **Padrão DTO (Data Transfer Object)**: Utilização de objetos DTO para transferir dados entre as camadas da aplicação, otimizando a comunicação e evitando a exposição desnecessária das entidades.
* **Consultas Personalizadas com JPQL (Java Persistence Query Language)**: Criação de consultas mais complexas para manipulação de dados.
* **Gerenciamento de Dependências com Maven**: Como adicionar e gerenciar bibliotecas externas.
* **Tratamento de Exceções**: Implementação de mecanismos robustos para lidar com erros e exceções na API.
* **Validação de Dados**: Garantindo a integridade dos dados de entrada.
* **Paginação e Ordenação**: Para lidar com grandes volumes de dados.
* **Docker e Docker Compose**: Configuração de ambientes de desenvolvimento e produção com contêineres.
