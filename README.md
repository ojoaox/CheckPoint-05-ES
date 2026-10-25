## 🚀 Instruções de Inicialização

### 1. Clonar o repositório

Caso ainda não tenha baixado o projeto, clone-o através do terminal:

```bash
git clone https://github.com/ojoaox/CheckPoint-05-ES.git
cd CheckPoint-05-ES
```

### 2. Instalar as dependências

Instale as dependências necessárias (Tailwind CSS e seu CLI):

```bash
npm install
```

### 3. Compilar o Tailwind CSS

Você pode rodar o Tailwind em modo de observação (*watch*) durante o desenvolvimento ou gerar a versão final minificada:

- **Modo Desenvolvimento (com auto-recompilação ao alterar classes):**
  ```bash
  npm run dev
  ```
  *Esse comando observa alterações no arquivo `css/styles.css` e no HTML, gerando o `css/output.css` em tempo real.*

- **Modo Produção (gerar CSS minificado):**
  ```bash
  npm run build
  ```

### 4. Executar a aplicação no navegador

Com o arquivo `css/output.css` gerado, você pode visualizar a aplicação de duas formas:

1. **Via VS Code com Live Server (Recomendado):**
   - Abra o projeto no VS Code.
   - Clique com o botão direito no arquivo `index.html`.
   - Selecione **"Open with Live Server"**.

2. **Abertura direta:**
   - Dê um duplo clique no arquivo `index.html` ou abra-o diretamente em qualquer navegador web.