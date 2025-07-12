# To-Do List Fullstack

Um projeto de To-Do List com autenticação de usuário, feito para portfólio.

## 🚀 Tecnologias usadas
- **Frontend:** HTML, CSS, JavaScript
- **Backend:** Python Flask
- **Banco:** SQLite (desenvolvimento) / PostgreSQL (produção)
- **Autenticação:** JWT + bcrypt

## ✨ Funcionalidades
✅ Cadastro e login de usuário  
✅ Senha criptografada com bcrypt  
✅ Sessão JWT para autenticação  
✅ CRUD completo das tarefas  
✅ Cada usuário vê apenas as próprias tarefas

## 🚧 Como rodar localmente

```bash
# Clone o repositório
git clone git@github.com:TonySmith02/todolist.git
cd todolist

# Crie ambiente virtual e instale dependências
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt

# Rodar o servidor Flask
flask run
