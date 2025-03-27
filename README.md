# Workshop Spring Boot 4 JPA

## Visão Geral

Bem-vindo ao **Workshop Spring Boot 4 JPA**! Este projeto demonstra como utilizar tecnologias modernas do ecossistema Java para construir uma aplicação robusta e escalável. Ele foca na gestão de produtos, pedidos e pagamentos, aproveitando ferramentas e tecnologias avançadas para criar uma solução completa.

## Tecnologias Utilizadas

- **Java 17**: Versão moderna para desenvolvimento eficiente.
- **Maven**: Gerenciamento de dependências e automação de build.
- **Spring Boot 4**: Framework para aplicações Spring autônomas e preparadas para produção.
- **H2 Database**: Banco de dados leve para desenvolvimento e testes.
- **PostgreSQL**: Banco de dados relacional open-source para produção.
- **Apache Tomcat**: Contêiner para deploy de aplicações Java.
- **Postman**: Cliente API para testar e interagir com os endpoints.

## Funcionalidades

- **Gerenciamento de Produtos**: Operações CRUD para produtos.
- **Gestão de Pedidos**: Criação, recuperação, atualização e exclusão de pedidos.
- **Processamento de Pagamentos**: Pagamentos associados a pedidos.

## Como Começar

### Pré-requisitos

- **Java 17** instalado.
- **Maven** configurado no ambiente.

### Instalação

1. Clone o repositório:

   ```bash
   git clone https://github.com/LucaolDev/workshop-springboot4-jpa.git
   ```

2. cd workshop-springboot4-jpa

   ```bash
   cd workshop-springboot4-jpa
   ```

3. Construa o projeto com o Maven:

   ```bash
   mvn clean install
   ```

4. Execute a aplicação:

   ```bash
   mvn spring-boot:run
   ```

### Configuração

Edite o arquivo application.properties em src/main/resources para ajustar as configurações do banco de dados e outras propriedades da aplicação.

### Testando a API

Utilize o **Postman** ou outra ferramenta similar para interagir com os endpoints da API. O URL base para testes locais é: http://localhost:8080

### Endpoints Disponíveis

**Produtos**:<br/>
**GET** /api/products: Listar todos os produtos.

**POST** /api/products: Criar um novo produto.

**Pedidos**:<br/>
**GET** /api/orders: Listar todos os pedidos.

**POST** /api/orders: Criar um novo pedido.

**Pagamentos**:<br/>
**POST** /api/payments: Processar o pagamento de um pedido.
