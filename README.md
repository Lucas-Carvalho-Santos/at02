# 🔐 API de Autenticação e Autorização com JWT (Spring Boot 3)

Este projeto é uma API RESTful desenvolvida com **Spring Boot 3** que fornece autenticação e autorização baseadas em **JWT (JSON Web Tokens)**. A API permite o login de usuários, geração de tokens, proteção de recursos com base em roles e documentação interativa com Swagger.

> ✅ Ideal para cenários de autenticação centralizada em arquiteturas com microsserviços ou APIs seguras.

---

## 📋 Funcionalidades

- Autenticação via login (usuário/senha)
- Geração de token JWT assinado internamente
- Validação interna de tokens
- Autorização baseada em roles (`USER`, `ADMIN`)
- Endpoints protegidos com `@PreAuthorize`
- Testes automatizados com JUnit + MockMvc
- Testes de carga com JMeter
- Documentação interativa com Swagger
- Banco de dados em memória (H2)
- Monitoramento com Spring Boot Actuator
- Preparado para deploy via Docker + Render/Railway

---

## 🚀 Tecnologias e Dependências

- Java 17+
- Spring Boot 3.x
- Spring Security
- OAuth2 Resource Server
- Spring Data JPA
- H2 Database
- Lombok
- Springdoc OpenAPI (Swagger UI)
- JUnit 5 + Mockito
- Apache JMeter
- Spring Boot Actuator
- Docker

---

## ⚙️ Como Executar Localmente

### 1. Clone o repositório

```bash
git clone https://github.com/seu-usuario/auth-jwt-api.git
cd auth-jwt-api


🔐 Usuários Criados Automaticamente
Username	Senha	Role
admin	123456	ADMIN
user	password	USER

⚠️ Senhas são armazenadas com BCrypt.
