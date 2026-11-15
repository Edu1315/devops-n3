# Projeto DevOps - Aplicação Node.js

## 📖 Sobre o Projeto

Este projeto foi desenvolvido para a disciplina de **DevOps**, com o objetivo de aplicar conceitos de versionamento, integração contínua, entrega contínua e implantação contínua utilizando ferramentas e práticas modernas do mercado.

A aplicação principal será desenvolvida em **Node.js**, seguindo boas práticas de desenvolvimento, testes automatizados e automação de processos de build e deploy.

---

## 🚀 Objetivos

- Implementar um fluxo de desenvolvimento utilizando Git e GitHub.
- Utilizar estratégias de branching para organização do projeto.
- Automatizar processos de validação de código.
- Aplicar Continuous Integration (CI).
- Aplicar Continuous Delivery (CD).
- Aplicar Continuous Deployment para ambiente em nuvem.
- Implementar testes automatizados de unidade e interface.

---

## 🛠️ Tecnologias Utilizadas

### Desenvolvimento
- Node.js
- Express.js
- JavaScript

### Controle de Versão
- Git
- GitHub

### Qualidade de Código
- ESLint
- Prettier

### Testes
- Jest (Testes Unitários)
- Selenium WebDriver (Testes de Interface)

### DevOps e Automação
- GitHub Actions
- CI/CD Pipelines

### Infraestrutura
- Amazon EC2 (AWS)

---

## 🌳 Estratégia de Branches

O repositório segue uma estratégia baseada no Git Flow simplificado:

### Branch Principal

```text
main
```

Contém apenas versões estáveis e prontas para produção.

### Branch de Desenvolvimento

```text
develop
```

Utilizada para integração das funcionalidades antes de serem promovidas para a branch principal.

### Branches de Funcionalidade

```text
feature/nome-da-funcionalidade
```

Exemplos:

```text
feature/autenticacao
feature/cadastro-usuarios
feature/api-produtos
```

Cada nova funcionalidade deve ser desenvolvida em uma branch específica e posteriormente integrada à `develop`.

---

## 🔄 Pipeline de Continuous Integration e Continuous Delivery

O projeto possui um workflow automatizado responsável por:

### Etapas executadas

1. Checkout do código.
2. Instalação de dependências.
3. Análise estática de código.
4. Execução dos testes unitários.
5. Geração do relatório de cobertura.
6. Build da aplicação.
7. Preparação do artefato para entrega.

### Ferramentas

- GitHub Actions
- ESLint
- Jest

---

## 🚀 Pipeline de Continuous Deployment

Um segundo workflow é responsável pela implantação automática da aplicação em uma instância EC2 da AWS.

### Etapas executadas

1. Conexão segura com a instância EC2.
2. Atualização do código da aplicação.
3. Instalação das dependências.
4. Reinicialização do serviço.
5. Validação pós-deploy.

---

## ✅ Testes Automatizados

### Testes Unitários

Os testes unitários garantem o correto
