# Sistema de Gerenciamento de Usuários

Um sistema baseado em Flask para gerenciar usuários com controle de roles, permissões e recuperação de senha.

## Recursos
- Controle de usuários e roles (admin, user, etc.).
- Sistema de autenticação e autorização.
- Recuperação de senha.

## Como Configurar
1. Clone o repositório:  
   git clone <url-do-repositorio>
2. Instale as dependências:  
   pip install -r requirements.txt
3. Configure o banco de dados no arquivo config.py.
4. Execute a aplicação:  
   flask run

## Endpoints Principais
- POST /login - Login de usuários.
- POST /register - Registro de novos usuários.
- POST /forgot-password - Recuperação de senha.
