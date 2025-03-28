# 🖥️ Sistema de Cadastro de Usuários (Full-Stack)

[![GitHub license](https://img.shields.io/github/license/CaueReis/cadastro-de-usuario)](https://github.com/CaueReis/cadastro-de-usuario/blob/main/LICENSE)
![React](https://img.shields.io/badge/React-18.x-%2361DAFB)
![Node.js](https://img.shields.io/badge/Node.js-18.x-green)

<div align="center">
  <img src="frontend/public/screenshot.png" alt="Preview do Projeto" width="80%">
</div>


## 🚀 Tecnologias

### Backend
- **Node.js** + **Express** (API REST)
- **Mongoose** (Para conexão com MongoDB)
- **JWT** (Autenticação - se aplicável)

### Frontend (a ser implementado/recuperado)
- React/Vue (pelas pastas `src/components/`)
- Axios (para consumo da API)

## 📂 Estrutura do Projeto

````bash
cadastro-de-usuario/
├── backend/
│ ├── server.js # Ponto de entrada da API
│ ├── models/ # Schemas do MongoDB
│ ├── routes/ # Rotas da API
│ └── package.json # Dependências
├── frontend/ # (Submódulo ou pasta do front)
└── README.md # Este arquivo
````

## ⚙️ Como Executar

### Pré-requisitos
- Node.js 18+
- MongoDB (local ou Atlas)

### Backend

````bash
cd backend
npm install
npm start
````

A API rodará em http://localhost:3000

### Frontend
````bash
cd frontend
npm install
npm run dev
````

# 🔍 Endpoints da API
Método	Rota	Descrição
<hr>
POST	/usuarios	Cria novo usuário
<hr>
GET	/usuarios	Lista todos usuários
<hr>
PUT	/usuarios/:id	Atualiza usuário
<hr>

# 🤝 Como Contribuir
Faça um fork do projeto

Crie uma branch (git checkout -b feature/nova-funcionalidade)

Commit suas mudanças (git commit -m 'Adiciona X')

Push para a branch (git push origin feature/nova-funcionalidade)

Abra um Pull Request