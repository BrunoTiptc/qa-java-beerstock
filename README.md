QA Java – Beer Stock API 🍺

Projeto de **QA em Java** desenvolvido com **Spring Boot**, focado em **testes unitários, TDD e validação de regras de negócio** em uma API REST de controle de estoque.

Este repositório demonstra, na prática, como um QA atua validando lógica, limites, exceções e fluxos críticos de uma aplicação backend.

---

## 🎯 Objetivo do Projeto

- Aplicar **testes unitários** em uma API REST existente
- Validar regras de negócio como:
  - Controle de estoque
  - Incremento e decremento de quantidade
  - Limites máximos e mínimos
  - Tratamento de exceções
- Praticar **TDD (Test Driven Development)**

---

## 🛠 Tecnologias Utilizadas

- Java 14+
- Spring Boot
- Maven
- JUnit 5
- Mockito
- Hamcrest
- Postman
- Git / GitHub

---

## 🧪 Tipos de Testes Implementados

- Testes unitários de serviços
- Validação de regras de negócio
- Testes de exceções customizadas
- Testes orientados a TDD

---

## ▶️ Como Executar o Projeto

### Rodar a aplicação:
```bash
mvn spring-boot:run
Executar os testes:
bash
Copiar código
mvn clean test
Endpoint principal:
bash
Copiar código
http://localhost:8080/api/v1/beers
📌 Contexto
Projeto desenvolvido como parte do Lab de QA Java da Digital Innovation One (DIO), com foco prático em testes e qualidade de software, simulando cenários reais de mercado.

🚀 Próximos Passos (Evolução)
Integração com pipeline CI (GitHub Actions)

Testes de API automatizados

Relatórios de cobertura

Evolução para QAOps
