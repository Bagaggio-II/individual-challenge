# 🚀 Desafio Técnico Individual – API de Produtos

## 🎯 Objetivo

Desenvolver uma **API RESTful com operações de CRUD (Create, Read, Update, Delete)** para gerenciar produtos de um sistema fictício. O desafio avalia sua capacidade de estruturar uma aplicação backend simples, com boas práticas de código, clareza e organização.

---

## 🧱 Requisitos Obrigatórios

1. **Entidade "Produto"** com os seguintes campos:
   - `id` (gerado automaticamente)
   - `nome` (string)
   - `descricao` (string)
   - `preco` (float ou decimal)
   - `quantidade` (inteiro)

2. Endpoints obrigatórios:
   - `GET /produtos`: listar todos os produtos
   - `GET /produtos/{id}`: buscar produto por ID
   - `POST /produtos`: criar novo produto
   - `PUT /produtos/{id}`: atualizar produto existente
   - `DELETE /produtos/{id}`: remover produto

3. A API pode ser construída em **Python (FastAPI ou Flask), Java (Spring Boot) ou Node.js (Express)**.

4. Armazenamento:
   - Banco de dados em memória (ex: lista em Python, Map em Java, array em Node.js) ou
   - Banco real simples (SQLite, MongoDB local, PostgreSQL etc.)

5. O projeto deve conter:
   - README com instruções de execução
   - Organização em pastas/módulos
   - Código comentado e legível

---

## ⏱️ Tempo Estimado

Você terá até **2 dias** para realizar o desafio.

Use o tempo com sabedoria: priorize um CRUD funcional e bem estruturado antes de pensar em melhorias extras.

---

## 📦 Formas de Entrega

O projeto deve ser publicado em um **repositório público no GitHub**.

Após a finalização, o link do repositório deve ser enviado para o e-mail informado durante o processo seletivo.

> Não é necessário realizar o deploy da aplicação, mas isso será considerado um diferencial positivo na avaliação.

---

## 🚀 Dicas e Extras (opcional)

- Adicionar campo de `categoria` para cada produto
- Criar testes básicos para os endpoints
- Usar Swagger/OpenAPI (FastAPI e Spring ajudam nisso)
- Deploy local com Docker
