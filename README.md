# 🪙 Financewalk

O **financewalk** é uma API RESTful desenvolvida com Java e Spring Boot para um sistema de gestão financeira. O principal objetivo do projeto é oferecer um conjunto de endpoints que permitem gerenciar dados financeiros de forma eficiente e segura.

## ⚡ Tecnologias e dependências

O projeto foi construído com as seguintes tecnologias e dependências:

- **Java 17:** linguagem de programação com versão LTS.

- **Spring Boot:** framework principal para a construção da aplicação, incluindo as dependências spring-boot-starter-web (para APIs RESTful) e spring-boot-starter-data-jpa (para persistência de dados).

- **Maven:** ferramenta de gerenciamento de dependências.

- **Lombok:** biblioteca para reduzir código boilerplate (getters, setters, construtores, etc.).

- **H2 Database:** banco de dados em memória, utilizado para facilitar o desenvolvimento e os testes.

- **Bean Validation:** ferramenta para validação de dados em entidades.

- **Spring AI:** framework para integração com modelos de IA, neste caso, o modelo da OpenAI.

- Insomnia: ferramenta de teste de integração.

## 🛞 Como rodar o projeto?

Para executar o projeto localmente, siga os seguintes passos:

1. Clone o repositório:
```bash
git clone https://github.com/GabrielRossi01/financewalk.git
```

2. Abra na IDE: importe o projeto para sua IDE de preferência (IntelliJ, VS Code, Eclipse, etc.).

3. Execute a aplicação: execute a classe principal da aplicação, que possui a anotação @SpringBootApplication.

4. Acesse a API: a API estará disponível em http://localhost:8080.
