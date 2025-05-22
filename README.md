<h1 align="center">📌 Projeto FastAPI - API de Restaurantes</h1>

Este projeto é uma API desenvolvida em FastAPI que disponibiliza informações sobre restaurantes, permitindo consultas flexíveis e oferecendo uma documentação interativa automática.

<br>

## 🚀 Funcionalidades
✔ Endpoint de Restaurantes – Retorna uma lista de estabelecimentos cadastrados.
✔ Filtro por Nome – Permite buscar restaurantes específicos usando um parâmetro de consulta (query parameter).
✔ Documentação Automática – Integração com Swagger (/docs) e ReDoc (/redoc), facilitando testes e compreensão dos endpoints.

<br>

🔧 Instalação e Execução
Pré-requisitos
Python 3.7+

Pip (gerenciador de pacotes)

## 🛠️ Tecnologias  
![icons8-python-48](https://github.com/user-attachments/assets/10a921d7-b517-417a-9ddb-efcf5dbbfdac)![icons8-visual-studio-code-2019-48](https://github.com/user-attachments/assets/048733ff-4531-42cc-9453-b7ee55c8c208)![icons8-html-48](https://github.com/user-attachments/assets/a49a1706-cda6-4bc9-892a-954ead66fe38)![icons8-chrome-48](https://github.com/user-attachments/assets/c8b04265-e0a2-437f-a529-4de5c86eb0f9)



| Ferramenta          | Descrição                         |  
|---------------------|-----------------------------------|  
| `FastAPI`           | Framework para construção da API  |  
| `Uvicorn`           | Servidor ASGI                     |  
| `Pydantic`          | Validação de dados                |  

<br>

------------------------------------------------------------------

### Passos
#### 1. Clone o repositório:

  - git clone https://github.com/seu-usuario/nome-do-projeto.git

  - cd nome-do-projeto

------------------------------------------------------------------

#### 2. Crie e ative um ambiente virtual (opcional, mas recomendado):

  - python -m venv venv
  - source venv/bin/activate  # Linux/Mac
  - venv\Scripts\activate    # Windows

------------------------------------------------------------------

#### 3. Instale as dependências:

  - pip install fastapi uvicorn

------------------------------------------------------------------

#### 4. Execute a aplicação:

  - uvicorn main:app --reload

------------------------------------------------------------------

- (O servidor estará disponível em http://localhost:8000)

<br>

### 📄 Endpoints
🔍 Listar todos os restaurantes
GET /restaurantes

Exemplo de resposta:

json
[
    {"id": 1, "nome": "Restaurante A", "tipo": "Italiano"},
    {"id": 2, "nome": "Restaurante B", "tipo": "Japonês"}
]

<br>

### 🔎 Filtrar restaurantes por nome
GET /restaurantes?nome=Restaurante A
Parâmetro: nome (opcional)

Exemplo de resposta:

json
{"id": 1, "nome": "Restaurante A", "tipo": "Italiano"}

<br>

### 📚 Documentação Interativa
Acesse para testar os endpoints diretamente no navegador:

- Swagger UI: http://localhost:8000/docs

- ReDoc: http://localhost:8000/redoc

<br>

### 🤝 Contribuição
Contribuições são bem-vindas! Siga os passos:

1. Fork o projeto

2. Crie uma branch (git checkout -b feature/nova-funcionalidade)

3. Commit suas mudanças (git commit -m 'Adiciona nova funcionalidade')

4. Push para a branch (git push origin feature/nova-funcionalidade)

5. Abra um Pull Request

<br>

Desenvolvido por [Cleiton Teles] 👨‍💻
