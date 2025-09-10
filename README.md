🚀 Controle de Gastos com Spring Boot e HTMX
Um gerenciador financeiro simples construído com Spring Boot, Thymeleaf e HTMX, projetado para uma experiência de usuário fluida e reativa, sem a complexidade de frameworks JavaScript.

📋 Pré-requisitos
Antes de começar, garanta que você tenha as seguintes ferramentas instaladas em sua máquina:

Git: Para clonar o repositório.

JDK 17 ou superior: O projeto está configurado para usar o Java 17.

Maven: Para gerenciamento de dependências.

IntelliJ IDEA: Uma IDE para facilitar o desenvolvimento.

▶️ Como Rodar a Aplicação Localmente
Siga os passos abaixo para executar o projeto em seu ambiente de desenvolvimento.

1. Clonar o Repositório
Abra seu terminal e clone o projeto do GitHub.

Bash

git clone https://github.com/VitoriaAlvim7/controle-de-gastos.git
cd controle-de-gastos
2. Abrir no IntelliJ IDEA
Inicie o IntelliJ IDEA.

Selecione "Open" e navegue até a pasta controle-de-gastos que você acabou de clonar.

A IDE irá detectar que é um projeto Maven e fará o download automático de todas as dependências listadas no arquivo pom.xml. Aguarde a conclusão desse processo.

3. Executar o Projeto
No painel de projeto à esquerda, navegue até src/main/java/br/com/controledegastos/.

Encontre a classe ControleDeGastosApplication.java.

Clique com o botão direito sobre o arquivo e selecione "Run 'ControleDeGastosApplication.main()'".

O servidor embarcado será iniciado e você verá no console uma mensagem indicando que a aplicação está rodando, geralmente na porta 8080.

4. Acessar a Aplicação
Após a inicialização, você pode acessar os seguintes endereços no seu navegador:

Página Principal:
http://localhost:8080

Console do Banco de Dados H2 (para desenvolvimento):
http://localhost:8080/h2-console

JDBC URL: jdbc:h2:mem:testdb

User Name: sa

Password: (deixe em branco)

Pronto! A aplicação está em execução no seu ambiente local e pronta para ser utilizada e modificada.

🛠️ Tecnologias Utilizadas
Backend: Spring Boot, Spring Data JPA, Spring Web

Frontend: Thymeleaf, HTMX

Banco de Dados:

Desenvolvimento: H2 Database (em memória)

Produção: PostgreSQL

Build Tool: Maven

Linguagem: Java 17
