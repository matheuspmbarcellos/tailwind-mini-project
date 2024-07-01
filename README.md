# Mini Projeto com Tailwind CSS

Este é um projeto simples criado para demonstrar o uso básico do Tailwind CSS em um ambiente de desenvolvimento utilizando o WSL (Windows Subsystem for Linux).

## Configuração do Ambiente

Antes de começar, certifique-se de ter instalado o Node.js e o npm no seu ambiente de desenvolvimento. Você também precisará configurar o Tailwind CSS seguindo os passos abaixo:

1. **Instalação do Tailwind CSS:**
   - Clone este repositório:
     ```bash
     git clone https://github.com/seu-usuario/tailwind-mini-project.git
     cd tailwind-mini-project
     ```

   - Instale as dependências do projeto:
     ```bash
     npm install
     ```

   - Inicialize o Tailwind CSS e crie o arquivo de configuração:
     ```bash
     npx tailwindcss init
     ```

2. **Compilar o CSS:**
   - Para compilar o CSS do Tailwind, execute o seguinte comando:
     ```bash
     npm run build:css
     ```

   Isso criará um arquivo `dist/styles.css` com o CSS compilado.

3. **Executar o Projeto:**
   - Abra o arquivo `src/index.html` em um navegador para visualizar o projeto.

## Estrutura do Projeto
```
/tailwind-mini-project
├── dist
│ └── styles.css
├── node_modules
├── src
│ ├── index.html
│ └── styles.css
├── package.json
├── tailwind.config.js
└── README.md
```
