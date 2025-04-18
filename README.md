# FastApi1

Projeto de API utilizando o framework FastAPI, com integração de banco de dados e conteinerização via Docker.

## 📦 Estrutura do Projeto

- `main.py`: Arquivo principal que inicia a aplicação FastAPI.
- `configurations.py`: Configurações da aplicação, como parâmetros de conexão e variáveis de ambiente.
- `database/`: Diretório contendo a configuração e os modelos do banco de dados.
- `requirements.txt`: Lista de dependências do projeto.
- `Dockerfile`: Script para criação da imagem Docker da aplicação.
- `docker-compose.yaml`: Orquestração dos containers Docker.
- `venv/`: Ambiente virtual Python (gerado localmente).

## 🚀 Como Executar

### Pré-requisitos

- [Docker](https://www.docker.com/)
- [Docker Compose](https://docs.docker.com/compose/)

### Passos

1. Clone o repositório:

   ```bash
   git clone https://github.com/CoutinhoGuilherme/FastApi1.git
   cd FastApi1

Construa e inicie os containers:

bash
Copiar
Editar
docker-compose up --build
Acesse a aplicação:

API: http://localhost:8000

Documentação Swagger: http://localhost:8000/docs

## 📡 Endpoints da API

Método	Descrição  
GET	/	Obtém os produtos  
POST	/produtos	Adiciona um novo produto  
PUT	/produtos	Retorna todos os produtos  
DELETE /produto/{id} 
## 🔧 Exemplo de JSON para POST /produtos  
json
Copiar
Editar
{
  "id": 1,
  "nome": "Notebook",
  "preco": 3500.0
}  

## 🛠 Tecnologias Utilizadas
FastAPI

Docker

Docker Compose

Python

