# Literalura

Literalura é um software desenvolvido em Java com Spring que faz consultas na API Gutendex, armazena as informações dos livros, autores e idiomas, e permite diversas operações locais sobre esses dados. A aplicação permite que o usuário interaja com um menu para buscar livros, listar registros e consultar dados de autores e livros armazenados em um banco de dados H2.

## Funcionalidades

- API Gutendex (Consulta livros) (https://gutendex.com).
- Armazena informações de livros, autores e idiomas.
- Lista livros salvos localmente.
- Lista autores salvos localmente.
- Busca livros por idioma localmente.
- Busca autores vivos por ano informado.

## Tecnologias Utilizadas

- Java 21: Linguagem de programação.

- Spring Boot: Framework para simplificar o desenvolvimento de aplicações Java.

- Spring Data JPA: Para persistência de dados e interação com o banco de dados.

- Hibernate: Implementação da JPA.

- Maven: Gerenciador de dependências e build do projeto.

- H2 Database: Banco de dados em memória, ideal para desenvolvimento.

- Jackson Databind: Biblioteca para processar e mapear dados JSON.

- API Gutendex: Fonte de dados para a busca de livros.
