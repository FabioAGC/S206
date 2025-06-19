
# Testes Automatizados com Cypress - SauceDemo

Este projeto contém 3 casos de teste automatizados com a ferramenta [Cypress](https://www.cypress.io/) para o site [saucedemo.com](https://www.saucedemo.com), incluindo um caso de teste negativo, conforme especificado no exercício.

## Pré-requisitos

- Node.js (recomendado: versão 18+)
- npm (ou yarn)
- Git (opcional)

## Passos para rodar o projeto

### 1. Clone ou baixe o repositório

Se estiver usando Git:

```bash
git clone <URL_DO_REPOSITORIO>
cd cypress-test-saucedemo
```


### 2. Instale as dependências

```bash
npm install cypress mochawesome
```

### 3. Execute os testes

```bash
npx cypress run
```

### 4. Acesse o relatório gerado (mochawesome)

Após a execução dos testes, abra o arquivo HTML que será gerado em:

```
cypress/reports/mochawesome.html
```