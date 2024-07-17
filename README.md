# ForoHub - Desafio Backend

Este projeto é parte do desafio ForoHub, onde desenvolvemos uma API REST utilizando Spring para gerenciar tópicos.

<p align="center">
<img src="https://github.com/VSawyerHub/ForoHub/blob/master/Badge-Spring.png" />
</p>

Este é o nosso desafio, chamado de FórumHub: nele, vamos replicar este processo no nível do back end e, para isso, criaremos uma API REST usando Spring.

Nossa API se concentrará especificamente nos tópicos, e deve permitir aos usuários:

Criar um novo tópico;
Mostrar todos os tópicos criados;
Mostrar um tópico específico;
Atualizar um tópico;
Eliminar um tópico.
É o que conhecemos normalmente como CRUD (CREATE, READ, UPDATE, DELETE)* e é muito parecido com o que desenvolvemos no LiterAlura, mas agora de forma completa, agregando as operações de UPDATE e DELETE, e usando um framework que facilitará muito o nosso trabalho.

*Tradução livre (em ordem): Criar, Consultar, Atualizar e Deletar.

Em resumo, nosso objetivo com este challenge é implementar uma API REST com as seguintes funcionalidades:

API com rotas implementadas seguindo as melhores práticas do modelo REST;
Validações realizadas segundo as regras de negócio;
Implementação de uma base de dados relacional para a persistência da informação;
Serviço de autenticação/autorização para restringir o acesso à informação.

## Funcionalidades

A API permite aos usuários realizar as seguintes operações:

- **Criar um novo tópico**: Permite que um usuário crie um novo tópico com título, conteúdo e autor.
- **Listar todos os tópicos**: Retorna uma lista de todos os tópicos existentes.
- **Buscar um tópico específico**: Retorna os detalhes de um tópico específico baseado no ID.
- **Atualizar um tópico**: Permite a atualização do título e/ou conteúdo de um tópico existente.
- **Excluir um tópico**: Remove um tópico da base de dados.

## Tecnologias Utilizadas

- **Spring Boot**: Framework utilizado para criar a aplicação em Java.
- **Spring Data JPA**: Facilita o acesso e a persistência de dados em bancos relacionais.
- **H2 Database**: Banco de dados em memória para facilitar o desenvolvimento e testes.
- **Maven**: Gerenciador de dependências e build do projeto.


## Como Usar

### Pré-requisitos

- JDK 8 ou superior
- Maven
- IDE de sua preferência (Eclipse, IntelliJ IDEA, etc.)

### Configuração

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/forumhub.git

2. Execute o projeto:

  ```bash
mvn spring-boot:run


