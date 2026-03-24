# 🚀 Bot para Discord

Um bot simples para Discord, construído com Node.js e a biblioteca `discord.js`. Este projeto serve como estrutura de base com um manipulador (handler) de comandos (Slash Commands) pronto para ser estendido.

---

## 📸 Preview

*(Adicione imagens ou GIFs do seu bot em funcionamento aqui)*

---

## 🧠 Funcionalidades

* ✔️ Estrutura organizada com Command Handler
* ✔️ Suporte a Slash Commands nativo do Discord
* ✔️ Comando utilitário (`/ping`) de exemplo incluído

---

## 🛠️ Tecnologias utilizadas

* [Node.js](https://nodejs.org/)
* [Discord.js (v14.11)](https://discord.js.org/)
* [Dotenv](https://www.npmjs.com/package/dotenv)

---

## ⚙️ Como rodar o projeto

```bash
# Clonar o repositório
git clone https://github.com/JockaMt/bot-para-discord.git

# Entrar na pasta do projeto
cd bot-para-discord

# Instalar as dependências
npm install

# Configurar as variáveis de ambiente
# Crie um arquivo .env na raiz do projeto e adicione a seguinte linha:
# TOKEN=seu_token_aqui

# Rodar o bot
node index.js
```

---

## 📁 Estrutura de pastas (opcional)

```text
/
├── index.js          # Arquivo principal que inicializa o bot
├── package.json      # Configurações do projeto e dependências
├── /handler          # Lógica para registrar comandos slash
└── /commands         
    └── /Utils        # Categoria de comandos utilitários
        └── ping.js   # Arquivo com a lógica do comando /ping
```

---

## 🎯 Objetivo do projeto

Criar uma base testada e escalável para desenvolvimento de bots versáteis no Discord, focando em:

* Estudo prático da API do Discord (`v14`).
* Criação de um esqueleto fácil de expandir e criar novos comandos.

---

## 💡 Melhorias futuras

* [ ] Adicionar evento `interactionCreate` de forma modularizada
* [ ] Conectar banco de dados (MongoDB, PostgreSQL) para dados de usuários
* [ ] Implementar sistema de logs avançado 

---

## 📄 Licença

Este projeto está sob a licença ISC.
