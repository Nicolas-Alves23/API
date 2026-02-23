# 🚀 API de Gerenciamento de Usuários

> Aplicação Full Stack para gerenciamento completo de usuários (CRUD)  
> Desenvolvida com React no Front-end e Laravel no Back-end.

---

## 📌 Sobre o Projeto

Este projeto consiste em uma API RESTful integrada a uma aplicação React para realizar o gerenciamento completo de usuários.

O sistema permite cadastrar, listar, editar e excluir usuários com as seguintes informações:

- 👤 Nome
- 📧 Email
- 🎂 Data de Nascimento

Projeto desenvolvido com fins de aprendizado e prática de integração entre front-end e back-end.

---

## 🛠️ Funcionalidades

- ✅ Cadastro de usuário
- ✅ Listagem de usuários
- ✅ Atualização de usuário
- ✅ Exclusão de usuário
- ✅ Validação de dados
- ✅ Integração completa via API REST

---

## 🧰 Tecnologias Utilizadas

### 🎨 Front-end
- React
- Axios
- Bootstrap / CSS
- Hooks (useState, useEffect)

### ⚙️ Back-end
- Laravel
- Eloquent ORM
- API RESTful
- Migrations
- Arquitetura MVC

### 🗄️ Banco de Dados
- Sqlite 

---

## 📂 Estrutura do Projeto

```
API/
│
├── eduteka-course-apirest-backend/app/         # API Laravel
│   ├── app/
│   ├── routes/
│   ├── database/
│   └── ...
│
└── eduteka-course-apirest-frontend/       # Aplicação React
    ├── src/
    ├── components/
    ├── services/
    └── ...
```

---

## ⚙️ Como Executar o Projeto

### 🔹 Back-end (Laravel)

```bash
cd eduteka-course-apirest-backend/app/ 
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate
php artisan serve
```

---

### 🔹 Front-end (React)

```bash
cd eduteka-course-apirest-frontend/  
npm install
npm start
```

---

## 🔗 Endpoints da API

| Método | Endpoi     | Descrição              |
|--------|------------|------------------------|
| GET    | /users     | Listar usuários        |
| POST   | /users     | Criar novo usuário     |
| PUT    | /users/{id}| Atualizar usuário      |
| DELETE | /users/{id}| Excluir usuário        |

---

## 👨‍💻 Nicolas Vilela Barros da Costa Alves 

Projeto desenvolvido para fins de estudo e prática em desenvolvimento web.
