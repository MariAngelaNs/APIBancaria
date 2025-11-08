💳 Desafio DIO: API Bancária Assíncrona com FastAPI

Projeto desenvolvido por Mariangela como parte do desafio "API Bancária Assíncrona com FastAPI" da Digital Innovation One (DIO)
.
Este projeto faz parte do programa de formação em desenvolvimento backend moderno com Python e FastAPI, reforçando boas práticas de API REST, autenticação JWT e programação assíncrona.

🚀 Sobre o Projeto

O objetivo deste desafio é projetar e implementar uma API RESTful assíncrona capaz de gerenciar operações bancárias — como depósitos e saques — associadas a contas correntes.

A proposta é proporcionar uma experiência prática no desenvolvimento de aplicações backend modernas e eficientes, com foco em segurança, performance e clareza arquitetural.

⚙️ Funcionalidades Implementadas

Cadastro de Transações:
Permite registrar operações bancárias (depósitos e saques) associadas a contas correntes.

Exibição de Extrato:
Endpoint para visualizar o histórico completo de transações de uma conta.

Autenticação JWT:
Protege os endpoints sensíveis, garantindo que apenas usuários autenticados possam realizar operações.

🧠 Conceitos Aplicados

FastAPI: Framework rápido e intuitivo para criação de APIs modernas com Python.

Programação Assíncrona: Uso de async/await para lidar com I/O de forma eficiente.

Modelagem de Dados: Estruturação de entidades para representar contas e transações.

Validação: Bloqueio de depósitos e saques inválidos (como valores negativos ou saldo insuficiente).

Segurança: Implementação de autenticação baseada em JWT (JSON Web Token).

Documentação OpenAPI: API documentada automaticamente, acessível via Swagger UI e ReDoc.

🧩 Requisitos Técnicos

Python 3.10+

FastAPI

Uvicorn

Pydantic

JWT (via PyJWT)

Banco de dados (ex: SQLite, PostgreSQL ou outro de sua escolha)

▶️ Como Executar o Projeto

Clone o repositório:

git clone https://github.com/mariangela/api-bancaria-fastapi.git
cd api-bancaria-fastapi


Crie e ative um ambiente virtual:

python -m venv venv
source venv/bin/activate  # ou venv\Scripts\activate no Windows


Instale as dependências:

pip install -r requirements.txt


Execute o servidor:

uvicorn src.main:app --reload


Acesse a documentação interativa da API:

Swagger UI → http://localhost:8000/docs

Redoc → http://localhost:8000/redoc

✨ Aprendizados e Reflexões

“Este projeto foi uma excelente oportunidade para consolidar meus conhecimentos em FastAPI, entender o poder da programação assíncrona e aprofundar o uso de JWT na autenticação de APIs seguras.”
— Mariangela 💡

📚 Créditos

Desenvolvido por Mariangela
📘 Desafio proposto pela Digital Innovation One (DIO)

👩‍💻 Formação: Python Backend Developer
