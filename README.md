# bd_livraria_VaiNaWeb

Este projeto é uma API simples para cadastro de livros utilizando Flask como micro framework web e SQLite como banco de dados nativo do Python. A API permite cadastrar e listar livros de uma base de dados.

## Como Usar

1. Clone o repositório para sua máquina local:
   ```bash
   git clone https://github.com/seu-usuario/nome-do-repositorio.git

cd nome-do-repositorio
pip install -r requirements.txt

2. Após instalar as dependências, execute o servidor Flask:

python app.py
O servidor estará disponível em http://127.0.0.1:5000/
Você pode acessar a API pelo navegador ou ferramentas como Postman

Endpoints da API:
1. POST /doar
Descrição: Cadastra um novo livro no banco de dados.
Exemplo de Payload:

{
  "titulo": "O Horror em Amityville",
  "autor": "Jay Anson",
  "categoria": "Terror",
  "imagem_url": "https://exemplo.com/amityville.jpg"
}
2. GET /livros
Descrição: Lista todos os livros cadastrados no banco de dados.
Resposta Exemplo:

{
    "titulo": "O Horror em Amityville",
    "autor": "Jay Anson",
    "categoria": "Terror",
    "imagem_url": "https://exemplo.com/amityville.jpg"
},

Tecnologias Utilizadas
Flask: Micro framework web para a criação da API.
SQLite: Banco de dados utilizado para armazenar as informações dos livros.

Autor
Eduardo-Alg

### Explicações sobre o que inclui neste README:
- **Nome do Projeto**: bd_livraria_VaiNaWeb.
- **Como Usar**: Passos para clonar o repositório, instalar dependências e rodar a API.
- **Endpoints da API**: Detalha as rotas disponíveis para o uso (Adicionar livros e listagem).
- **Tecnologias Utilizadas**: 1. Python, 2. Flask, 3. SQlite, 4. postman.
- **Autor**: Eduardo-Alg.

Essa estrutura oferece uma boa visão geral do que o projeto faz e como utilizá-lo! 🚀
