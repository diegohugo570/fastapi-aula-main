# 🚀 FastAPI – Projeto de Aula

Este repositório contém um **projeto prático utilizando FastAPI**, criado com o objetivo de **ensinar os fundamentos de APIs modernas em Python**, incluindo rotas, validação de dados, boas práticas e organização de código.

Ideal para **estudo, testes e evolução para aplicações reais**.

---

## 🧠 O que é o FastAPI?

O **FastAPI** é um framework moderno e rápido para criação de APIs em Python, oferecendo:

- ⚡ Alta performance
- 🧩 Tipagem forte com Python (Pydantic)
- 📄 Documentação automática (Swagger / Redoc)
- 🔒 Validação automática de dados

📚 Documentação oficial: https://fastapi.tiangolo.com/

---

## 🛠️ Tecnologias Utilizadas

- Python 3.9+
- FastAPI
- Uvicorn
- Pydantic
- Swagger UI / Redoc

---

## 📁 Estrutura do Projeto

```bash
fastapi-aula/
├── app/
│   ├── main.py
│   ├── routers/
│   ├── schemas/
│   ├── services/
│   └── __init__.py
├── requirements.txt
├── README.md
└── .gitignore
```

⚙️ Como Executar o Projeto

1️⃣ Clonar o repositório

```
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio

```

2️⃣ Criar ambiente virtual (opcional)

```
python -m venv venv

```

Ativar:

Windows

```

venv\Scripts\activate

```

Linux / Mac

```

source venv/bin/activate

```

3️⃣ Instalar dependências

```

pip install -r requirements.txt

```

4️⃣ Rodar o servidor

```
uvicorn app.main:app --reload

```

🌐 Acessos

API: http://127.0.0.1:8000

Swagger: http://127.0.0.1:8000/docs

Redoc: http://127.0.0.1:8000/redoc

---

🎯 Objetivos do Projeto

Introduzir o FastAPI

Criar APIs REST

Validar dados com Pydantic

Usar documentação automática

Aplicar boas práticas

---

🚧 Próximos Passos

Banco de dados (PostgreSQL / SQLite)

Autenticação JWT

Docker

Testes automatizados

Deploy em produção
