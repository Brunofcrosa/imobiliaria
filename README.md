<div align="center">

# 🏠 Imobiliária — Sistema de Gestão

**Sistema web completo de gestão imobiliária desenvolvido com Django — Projeto Integrador.**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-5.x-092E20?logo=django&logoColor=white)](https://www.djangoproject.com/)
[![Bootstrap](https://img.shields.io/badge/Bootstrap-5.x-7952B3?logo=bootstrap&logoColor=white)](https://getbootstrap.com/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?logo=vercel&logoColor=white)](https://2025-cppig-101-bruno.vercel.app)

🔗 **[Acesse o sistema em produção](https://2025-cppig-101-bruno.vercel.app)**

</div>

---

## 📋 Sobre o Projeto

O **Sistema de Gestão Imobiliária** é uma aplicação web completa desenvolvida com Django 5, voltada ao gerenciamento de imóveis, clientes, proprietários, corretores e transações imobiliárias. Possui controle de visitas, upload de imagens e interface administrativa completa — implantado na Vercel.

---

## ✨ Funcionalidades

- 🏡 Cadastro e listagem de imóveis com fotos
- 👤 Gestão de clientes, proprietários e corretores
- 🤝 Controle de transações (compra, venda, aluguel)
- 📅 Agendamento e controle de visitas
- 🖼️ Upload e processamento de imagens com django-stdimage
- 📊 Interface administrativa completa (Django Admin)
- ☁️ Deploy em produção no Vercel com Gunicorn

---

## 🚀 Tecnologias

| Tecnologia | Versão | Uso |
|---|---|---|
| [Python](https://www.python.org/) | 3.x | Linguagem principal |
| [Django](https://www.djangoproject.com/) | 5.2 | Framework web |
| [Bootstrap](https://getbootstrap.com/) | 5.x | Framework CSS responsivo |
| [django-bootstrap5](https://django-bootstrap5.readthedocs.io/) | 25.1 | Integração Bootstrap com templates Django |
| [django-stdimage](https://github.com/codingjoe/django-stdimage) | 6.x | Processamento de imagens |
| [Pillow](https://pillow.readthedocs.io/) | 11.x | Manipulação de imagens |
| [SQLite](https://www.sqlite.org/) | — | Banco de dados |
| [Gunicorn](https://gunicorn.org/) | 23.x | Servidor WSGI para produção |

---

## 📁 Estrutura

```
imobiliaria/
├── imobiliaria/      # Configurações do projeto Django
├── home/             # App principal
├── imovel/           # App de imóveis
├── cliente/          # App de clientes
├── proprietarios/    # App de proprietários
├── corretores/       # App de corretores
├── transacao/        # App de transações
├── visita/           # App de visitas
├── pessoa/           # App base de pessoas
├── static/           # Arquivos estáticos
├── manage.py
├── requirements.txt
└── vercel.json
```

---

## ⚙️ Como Executar

```bash
# Criar e ativar ambiente virtual
python -m venv venv
venv\Scripts\activate  # Windows

# Instalar dependências
pip install -r requirements.txt

# Aplicar migrations
python manage.py migrate

# Criar superusuário
python manage.py createsuperuser

# Rodar servidor
python manage.py runserver
```

Acesse em `http://localhost:8000`

---

## 🔐 Acesso Demo

| Campo | Valor |
|---|---|
| Usuário | `bruno` |
| Senha | `bruno` |
