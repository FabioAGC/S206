# API Tests


## Como Executar o Projeto

1. **Clone o repositório:**

   ```bash
   git clone https://github.com/FabioAGC/S206
   ```

2. **Instale as dependências:**

   ```bash
   npm install
   ```

   Em seguida, instale o `newman`:

   Instalar newman:

   ```bash
   npm i newman
   ```

   Instalar html-extra reporter:

   ```bash
   npm i newman-reporter-htmlextra
   ```

3. **Execute os testes e gere o relatório:**
   ```bash
   newman run colecao-postman.json -r htmlextra
   ```
