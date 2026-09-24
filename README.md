# Sistema Escolar — Cadastro de Alunos

Cadastro de alunos com listagem, cadastro e exclusão, feito em React + Vite consumindo uma API simulada com json-server.

Projeto da disciplina de Programação para Internet — IFRN Campus Pau dos Ferros.

## Pré-requisitos

- [Node.js](https://nodejs.org/) instalado (você já deve ter, mas confira com `node -v` no terminal).

## Como baixar o projeto

1. Baixe o projeto pelo GitHub: **https://github.com/JefersonQueiroga/sistema-escolar**
   - Pelo navegador: entre no link, clique em **Code > Download ZIP** e extraia a pasta.
   - Ou, se tiver o Git instalado, rode no terminal (PowerShell):
     ```powershell
     git clone https://github.com/JefersonQueiroga/sistema-escolar.git
     ```
2. Abra a pasta do projeto no VS Code (ou no terminal, navegue até ela com `cd`).

## Como instalar as dependências

No terminal, dentro da pasta do projeto, rode:

```powershell
npm install
```

## Como rodar o projeto

Este projeto precisa de **dois terminais abertos ao mesmo tempo** — um para a API simulada e outro para a aplicação React.

**Terminal 1 — API simulada (json-server):**
```powershell
npx json-server --watch db.json --port 3000
```

**Terminal 2 — aplicação React (Vite):**
```powershell
npm run dev
```

Depois, abra no navegador o endereço mostrado no terminal (geralmente `http://localhost:5173`).

> Se aparecer uma mensagem de erro de conexão na tela, confira se o Terminal 1 (json-server) ainda está rodando.

## Screenshot

<img width="1775" height="424" alt="image" src="https://github.com/user-attachments/assets/6e0766b7-d3e2-46d2-b761-22a502cb9f3f" />
<img width="1354" height="486" alt="image" src="https://github.com/user-attachments/assets/8942877d-c0d3-4869-879e-0e82c619cdb8" />
<img width="1283" height="693" alt="image" src="https://github.com/user-attachments/assets/25bb2a81-06b3-4cd9-9cbc-6f249b0321bb" />
<img width="1216" height="606" alt="image" src="https://github.com/user-attachments/assets/878a42f5-1a4a-4ddf-9785-1ad5e0daff71" />
<img width="1277" height="709" alt="image" src="https://github.com/user-attachments/assets/4126c326-29da-49f1-9423-fe3590244715" />




