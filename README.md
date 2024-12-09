# 🛒 E-commerce API com Flask

Uma API simples para gerenciamento de produtos e autenticação de usuários, desenvolvida com **Flask**. Este projeto utiliza o banco de dados **SQLite** e implementa autenticação baseada em sessões usando **Flask-Login**. 

## 🚀 Funcionalidades

- **Autenticação de usuários**:
  - Login e Logout.
  - Proteção de rotas com login obrigatório.
- **Gerenciamento de Produtos**:
  - Adicionar produtos.
  - Atualizar informações de produtos.
  - Deletar produtos.
  - Listar todos os produtos.
  - Exibir detalhes de um produto específico.
- **Banco de Dados**:
  - Modelos para **Usuários** e **Produtos** usando **SQLAlchemy**.
- **CORS**:
  - Configurado para permitir acesso de origens externas.
  
## 🛠️ Tecnologias Utilizadas

- **Python**: Linguagem principal.
- **Flask**: Framework web.
- **Flask-SQLAlchemy**: ORM para interação com o banco de dados.
- **SQLite**: Banco de dados leve para armazenar informações.
- **Flask-Login**: Gerenciamento de autenticação de usuários.
- **Flask-CORS**: Permite requisições de domínios diferentes.

## 📁 Estrutura do Projeto

```plaintext
📦 projeto
├── app.py          # Arquivo principal contendo as rotas e lógica.
├── ecommerce.db    # Banco de dados SQLite.
└── requirements.txt # Dependências do projeto.
