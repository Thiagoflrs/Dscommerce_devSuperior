# 🛒 DSCommerce API

Projeto desenvolvido durante o curso da DevSuperior, ministrado pelo professor Nélio Alves, com foco na construção de uma API REST completa utilizando o ecossistema Spring.

---

## 🚀 Sobre o projeto

O **DSCommerce** é uma API de e-commerce que simula operações reais de um sistema de vendas online, incluindo:

* Cadastro de usuários
* Catálogo de produtos
* Gerenciamento de pedidos
* Controle de acesso com autenticação e autorização

O projeto foi desenvolvido com foco em boas práticas de arquitetura, separação de camadas e segurança.

---

## 🧠 Tecnologias utilizadas

* **Java 21**
* **Spring Boot**
* **Spring Web**
* **Spring Data JPA / Hibernate**
* **Spring Security**
* **OAuth2 Authorization Server**
* **JWT (JSON Web Token)**
* **H2 Database (banco em memória)**
* **Bean Validation**
* **Maven**

---

## 🏗️ Estrutura do projeto

O projeto segue uma arquitetura em camadas:

```
📦 dscommerce
 ┣ 📂 config         # Configurações (Security, JWT, OAuth)
 ┣ 📂 controllers    # Endpoints da API
 ┣ 📂 dto            # Objetos de transferência de dados
 ┣ 📂 entities       # Entidades JPA
 ┣ 📂 projections    # Projeções para consultas customizadas
 ┣ 📂 repositories   # Interfaces JPA
 ┗ 📂 services       # Regras de negócio
```

---

## 🔐 Segurança

A aplicação utiliza:

* **Spring Security**
* **OAuth2**
* **JWT**

Funcionalidades implementadas:

* Autenticação via token
* Controle de acesso por perfil (roles)
* Proteção de endpoints
* Configuração de CORS

---

## 🗄️ Banco de dados

* Banco utilizado: **H2 (em memória)**
* Ideal para testes e desenvolvimento
* Console disponível para visualização dos dados

---

## 📌 Funcionalidades principais

* CRUD de produtos
* Listagem paginada
* Cadastro e autenticação de usuários
* Criação de pedidos
* Associação entre usuário, pedido e itens
* Validações de dados
* Tratamento de exceções

---

## 🧪 Testes

O projeto possui suporte a testes com:

* Spring Boot Test
* Spring Security Test

---

## 📚 Aprendizados

Durante o desenvolvimento deste projeto, foram consolidados conhecimentos em:

* Arquitetura em camadas
* API REST
* JPA e persistência de dados
* Segurança com Spring Security
* Autenticação com JWT
* OAuth2
* Boas práticas de desenvolvimento backend

---

## 🏁 Conclusão

O **DSCommerce** é um projeto completo que simula um cenário real de mercado, permitindo a aplicação prática de conceitos essenciais para o desenvolvimento backend moderno com Java e Spring.

A utilização de tecnologias como **Spring Boot, JPA, JWT e OAuth2** reforça a construção de APIs seguras, escaláveis e organizadas. Além disso, o uso de boas práticas como separação de responsabilidades e validação de dados contribui para a qualidade e manutenção do código.

Esse projeto representa um avanço significativo na minha formação como desenvolvedor Full Stack, consolidando conhecimentos fundamentais para atuação profissional no mercado.
