# Segunda-Feira IA 🤖 - Mentor Técnico Adaptativo

Este projeto é um assistente de inteligência artificial inspirado na **FRIDAY (Segunda-Feira)** do Tony Stark. Ele foi desenvolvido para atuar como um mentor técnico que ajusta a complexidade de suas respostas com base no nível de conhecimento do usuário, recuperado diretamente de um banco de dados relacional.

## 🚀 Funcionalidades
- **Sistema de Login:** Autenticação de usuários via MySQL.
- **Contexto Persistente:** A IA identifica o nível do usuário (Iniciante/Avançado) através do banco de dados.
- **Respostas Adaptativas:** Utiliza o modelo Llama 3 (via Groq API) para gerar explicações personalizadas.
- **Interface Web:** Desenvolvida em Flask com um design moderno e imersivo.

## 🛠️ Tecnologias Utilizadas
- **Linguagem:** Python 3.x
- **Framework Web:** Flask
- **Banco de Dados:** MySQL
- **IA:** Groq Cloud API (Llama 3.3 70B)
- **Frontend:** HTML5 e CSS3 (Design Responsivo)

## 📁 Estrutura do Projeto
```text
Portfolio-Matheus/
├── index.html (Portfólio Geral)
├── style.css
└── segunda-feira-ia/
    ├── app.py (Servidor Flask)
    ├── database.sql (Script do Banco)
    ├── requirements.txt (Dependências)
    └── templates/
        ├── login.html
        └── index.html
