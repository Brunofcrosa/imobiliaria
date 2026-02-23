<div align="center">

# 🏠 Imobiliária — Sistema de Gestão

**Sistema completo de gestão imobiliária desenvolvido com Django — Projeto Integrador.**

[![Python](https://img.shields.io/badge/Python-3.x-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Django](https://img.shields.io/badge/Django-4.x-092E20?logo=django&logoColor=white)](https://www.djangoproject.com/)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?logo=sqlite&logoColor=white)](https://www.sqlite.org/)
[![Vercel](https://img.shields.io/badge/Deploy-Vercel-000000?logo=vercel&logoColor=white)](https://2025-cppig-101-bruno.vercel.app)

🔗 **[Acesse o sistema ao vivo](https://2025-cppig-101-bruno.vercel.app)**

</div>

---

## 📋 Sobre o Projeto

O **Sistema Imobiliária** é uma aplicação web de gestão imobiliária desenvolvida com **Django** como Projeto Integrador do curso de Sistemas para Internet da **UFSM**. O sistema gerencia todo o ciclo imobiliário: desde o cadastro de imóveis e pessoas até transações e visitas agendadas.

---

## 🚀 Stack Tecnológica

| Camada | Tecnologia |
|---|---|
| Backend | Python 3 + Django |
| Banco de Dados | SQLite3 |
| Frontend | Django Templates + HTML/CSS |
| Deploy | Vercel |
| IDE | JetBrains (PyCharm) |

---

## 📁 Estrutura de Módulos

```
imobiliaria/
├── cliente/              # App de clientes
├── corretores/           # App de corretores
├── home/                 # Página inicial
├── imovel/               # App de imóveis
├── imobiliaria/          # Configurações do projeto (settings, urls)
├── pessoa/               # App de pessoas (base)
├── proprietarios/        # App de proprietários
├── transacao/            # App de transações (venda/aluguel)
├── visita/               # App de agendamento de visitas
├── static/               # Arquivos estáticos (CSS, JS, imagens)
├── manage.py
├── requirements.txt
├── vercel.json
└── db.sqlite3
```

---

## ✨ Funcionalidades

- 📰 **Imóveis**: Cadastro, listagem e filtragem de imóveis (venda/aluguel)
- 👥 **Clientes**: Gerenciamento completo de clientes
- 💼 **Corretores**: Controle de corretores e suas carteiras
- 🏢 **Proprietários**: Cadastro e gestão de proprietários
- 💰 **Transações**: Registro de vendas e alugueis
- 📊 **Diagrama de Classes**: Documentação estrutural incluída no repositório
- 🗓️ **Visitas**: Agendamento de visitas aos imóveis
- 🔐 **Autenticação**: Sistema de login e permissões Django

---

## ⚙️ Rodando Localmente

### Pré-requisitos

- Python `>= 3.10`
- pip

### Instalação

```bash
# Clone o repositório
git clone https://github.com/Brunofcrosa/imobiliaria.git
cd imobiliaria

# Crie e ative o ambiente virtual
python -m venv venv
source venv/bin/activate       # Linux/macOS
venv\Scripts\activate          # Windows

# Instale as dependências
pip install -r requirements.txt

# Execute as migrations
python manage.py migrate

# Crie um superusuário (opcional)
python manage.py createsuperuser

# Inicie o servidor
python manage.py runserver
```

Acesse [http://localhost:8000](http://localhost:8000)

---

## 🌐 Deploy

A aplicação está configurada para deploy na **Vercel** via `vercel.json`. Todo push na branch `master` pode acionar o pipeline.

```bash
# Deploy manual via Vercel CLI
vercel --prod
```

---

## 📚 Documentação

Os diagramas de classe do sistema estão disponíveis no repositório:

- [`Diagrama de classe antigo.pdf`](./Diagrama%20de%20classe%20antigo.pdf) — versão inicial
- [`Diagrama de classe novo.pdf`](./Diagrama%20de%20classe%20novo.pdf) — versão atual

---

## 📣 Melhorias Futuras

- [ ] Migrar banco para PostgreSQL em produção
- [ ] Implementar API REST com Django REST Framework
- [ ] Adicionar testes unitários e de integração
- [ ] Dashboard com métricas e relatórios
- [ ] Filtro avançado de imóveis (preço, localização, tipo)

---

## 🎓 Contexto Acadêmico

Projeto desenvolvido como **Projeto Integrador** do curso de Sistemas para Internet — **UFSM (Universidade Federal de Santa Maria)**.

---

## 👤 Autor

**Bruno Fetzer** — Desenvolvedor Full Stack

[![GitHub](https://img.shields.io/badge/GitHub-Brunofcrosa-181717?logo=github)](https://github.com/Brunofcrosa)
[![Portfolio](https://img.shields.io/badge/Portfolio-brunofcrosa-blue)](https://portfolio-brunofcrosas-projects.vercel.app)
