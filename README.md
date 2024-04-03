
# UserJavaCrud

Este é um projeto Java Spring Boot para um CRUD básico de usuários.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

-   **controller**: Contém as classes responsáveis por lidar com as requisições HTTP e direcioná-las para o serviço apropriado.
-   **model**: Contém as classes que representam os objetos de domínio do sistema, neste caso, a entidade User.
-   **service**: Contém as classes que implementam a lógica de negócio do sistema.

## Controller

O controller `UserController` lida com as requisições relacionadas aos usuários.

### Endpoints

-   **POST /users/create**: Cria um novo usuário.
-   **GET /users/{id}**: Retorna um usuário específico com base no ID fornecido.
-   **GET /users**: Retorna uma lista de todos os usuários.
-   **DELETE /users/{id}**: Exclui um usuário com base no ID fornecido.
-   **PUT /users/{id}**: Atualiza um usuário com base no ID fornecido.

## Utilização

Para utilizar este projeto, é necessário cloná-lo e executá-lo em um ambiente de desenvolvimento Java Spring Boot.

Certifique-se de ter o ambiente configurado corretamente com as dependências necessárias, como Maven e JDK.
