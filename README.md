# Estudo Avançado de GitHub Actions com Aplicação React

## 📌 Objetivo do Repositório

Este repositório foi elaborado para servir como ambiente de aprendizado prático sobre GitHub Actions. Inicialmente contendo apenas workflows de estudo conceitual, mas será enriquecido com uma aplicação React básica para permitir experimentos mais realistas e complexos.

## 🔍 Workflows Implementados para Estudo

### Fundamentos Básicos

1. **hello-world.yml**  
   - Primeiro contato com a estrutura de workflows
   - Configuração básica de triggers (on)
   - Uso de steps e actions padrão
   - Saída simples no console usando `echo`

2. **env-vars.yml**  
   - Definição de variáveis em diferentes níveis:
     - Variáveis do Github
     - Variáveis customizadas
     - Variáveis do sistema
     - Variáveis ddo Runner

### Controle de Execução

1. **needs.yml**  
   - Estrutura de dependência entre jobs com `needs`
   - Cenários de execução:
     - Sequencial simples
     - Dependência múltipla

2. **condicional.yml**  
   - Expressões condicionais com `if`

### Features Interativas

1. **inputs.yml**  
   - Configuração de `workflow_dispatch`
   - Tipos de inputs suportados:
     - string
     - boolean
     - choice
     - environment
   - Validação de inputs
   - Uso de inputs em steps subsequentes

2. **job-matrix.yml**  
   - Estrutura de matrizes para execução paralela
   - Combinações de parâmetros:
     - Sistemas operacionais
     - Configurações customizadas

## 🚀 Roadmap de Evolução com Projeto React

### Integração Contínua (CI)

- [ ] **Configuração de Testes Automatizados**
  - Jest com React Testing Library
  - Cobertura de código
  - Relatórios de testes

- [ ] **Linting e Code Quality**
  - ESLint com configuração React
  - Prettier para formatação
  - SonarCloud integration

- [ ] **Build e Verificação**
  - Build de produção
  - Análise de bundle size
  - Verificação de dependências

### Entrega Contínua (CD)

- [ ] **Deploy Automatizado**
  - GitHub Pages
  - Surge.sh
  - Netlify

- [ ] **Versionamento Semântico**
  - Conventional Commits
  - Auto versionamento com tags
  - CHANGELOG automático

### Features Avançadas

- [ ] **Otimizações**
  - Cache de dependências
  - Execução diferencial (apenas o que mudou)
  - Builds paralelizadas

- [ ] **Segurança**
  - Scans de vulnerabilidades
  - Validação de secrets
  - Assinatura de commits

- [ ] **Notificações**
  - Slack
  - Email
  - Discord
