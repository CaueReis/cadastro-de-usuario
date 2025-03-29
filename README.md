# 🖥️ Sistema de Cadastro de Usuários (Full-Stack)

<div align="center">
  
![React](https://img.shields.io/badge/React-16.x-%2361DAFB)
![Node.js](https://img.shields.io/badge/Node.js-18.x-green)

</div>


<div align="center">
  <img src="https://github.com/user-attachments/assets/5ffb4c83-bc4f-4770-bdc2-8b80ce1a5cdf" alt="Preview do Projeto" width="80%">
  
  <img src="https://github.com/user-attachments/assets/5f3a99ee-e3a5-4d64-87fb-af2eeceea90c" alt="Preview do Projeto" width="80%">
</div>



## 🚀 Tecnologias

### Backend
- **Node.js** + **json-server** (API REST)
- **db.json**
### Frontend
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
DELETE /usuarios/:id Excluí usuário

# 🤝 Como Contribuir

Faça um fork do projeto

Crie uma branch (git checkout -b feature/nova-funcionalidade)

Commit suas mudanças (git commit -m 'Adiciona X')

Push para a branch (git push origin feature/nova-funcionalidade)

Abra um Pull Request
