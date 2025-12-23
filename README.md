# 📝 Sistema de Cadastro de Usuários

Sistema full-stack para gerenciamento de usuários com operações CRUD completas.

![React](https://img.shields.io/badge/React-19.0-blue)
![Node](https://img.shields.io/badge/Node.js-18+-green)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-brightgreen)

## 🚀 Tecnologias

**Frontend:**
- React 19 + Vite
- Axios
- CSS3

**Backend:**
- Node.js + Express
- Prisma ORM
- MongoDB

## ⚙️ Instalação

### Backend
```bash
cd api
npm install
echo "DATABASE_URL='sua-connection-string-mongodb'" > .env
npx prisma generate
npx prisma db push
node server.js
```

### Frontend
```bash
cd cadastro-usuarios-react
npm install
npm run dev
```

Acesse: `http://localhost:5173`

## 📂 Estrutura

```
├── api/                    # Backend Node.js
│   ├── prisma/            # Schema do banco
│   └── server.js          # Servidor Express
│
└── cadastro-usuarios-react/   # Frontend React
    └── src/
        ├── pages/Home/    # Componente principal
        └── services/      # Configuração API
```

## 🎯 Funcionalidades

- ✅ Criar usuários
- ✅ Listar usuários
- ✅ Deletar usuários
- ✅ Interface responsiva

## 📸 Preview

Interface moderna com design roxo/gradiente, formulário de cadastro e listagem dinâmica de usuários.

## 👨‍💻 Autor

**Eduardo Brito**
- GitHub: [@edu1brito](https://github.com/edu1brito)
- LinkedIn: [Eduardo de Brito](https://www.linkedin.com/in/eduardo-de-brito-437347231/)

---

⭐ Deixe uma estrela se curtiu o projeto!
