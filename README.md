# Projeto Blog Pessoal

## Descrição
O Projeto Blog Pessoal é uma aplicação web desenvolvida com o framework Spring Boot. O objetivo deste projeto é criar uma plataforma de blog onde os usuários podem criar, editar, visualizar e excluir postagens e comentários. O projeto implementa as principais funcionalidades do Spring, incluindo configuração, controladores, modelos, repositórios, segurança e serviços.

## Funcionalidades Principais
- **CRUD de Postagens**: Criação, leitura, atualização e exclusão de postagens do blog.
- **CRUD de Comentários**: Criação, leitura, atualização e exclusão de comentários nas postagens.
- **Autenticação e Autorização**: Implementação de segurança utilizando Spring Security e JWT.
- **Documentação da API**: Configuração do Swagger para documentação interativa da API.
- **Serviços de Negócio**: Lógica de negócios encapsulada em serviços.

## Como Utilizar

### Pré-requisitos
- Java Development Kit (JDK) instalado.
- IDE Java (Eclipse, IntelliJ, NetBeans, etc.).
- Maven ou Gradle para gerenciamento de dependências.
- Banco de dados (por exemplo, MySQL ou PostgreSQL).

### Passos para Executar
1. Clone o repositório para o seu ambiente local:
   ```bash
   git clone https://github.com/Leticia0587/Blog-Pessoal.git
   ```
2. Navegue até a pasta do projeto:
   ```bash
   cd blog-pessoal
   ```
3. Importe o projeto em sua IDE Java preferida.
4. Configure as dependências necessárias utilizando Maven ou Gradle.
5. Configure as propriedades do banco de dados em `application.properties`:
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/blogpessoal
   spring.datasource.username=seu-usuario
   spring.datasource.password=sua-senha
   spring.jpa.hibernate.ddl-auto=update
   ```
6. Execute a aplicação:
   - Na linha de comando: `mvn spring-boot:run` ou `./mvnw spring-boot:run`
   - Na IDE: Execute a classe principal `BlogPessoalApplication.java`.

## Contribuição
Contribuições são bem-vindas!

## Licença
Este projeto é licenciado sob a [Licença MIT](LICENSE).
