# 🎬 FlixAPI

API RESTful desenvolvida para gerenciamento de um catálogo de plataforma de Filmes. O sistema gerencia filmes, atores, gêneros e avaliações de usuários, com autenticação segura e relacionamentos complexos de banco de dados.

## 🚀 Tecnologias Utilizadas

- **Linguagem:** Python 3.x
- **Framework Principal:** Django
- **API Toolkit:** Django REST Framework (DRF)
- **Autenticação:** JWT (JSON Web Token)
- **Banco de Dados:** SQLite (Desenvolvimento)
- **Versionamento:** Git

## ⚙️ Funcionalidades

- **Catálogo de Filmes:** CRUD completo de filmes com metadados (título, data de lançamento, resumo).
- **Gestão de Atores:** Cadastro de atores e vínculo com múltiplos filmes (Relacionamento Many-to-Many).
- **Categorização:** Organização por gêneros.
- **Sistema de Reviews:** Usuários autenticados podem avaliar e comentar filmes.
- **Autenticação e Permissões:**
  - Rotas públicas (Leitura do catálogo).
  - Rotas protegidas (Avaliações e inserção de dados).

## 🔧 Como rodar o projeto localmente

1. **Clone o repositório**
   ```bash
   git clone [https://github.com/guilhermeallen/flix_api.git](https://github.com/guilhermeallen/flix_api.git)
   cd flix_api
