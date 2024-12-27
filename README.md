# Projeto TWTodos

## Descrição
O **TWTodos** é um projeto desenvolvido como parte de um curso da TreinaWeb, com o objetivo de criar uma aplicação web de gerenciamento de tarefas utilizando **Python**, **Django** e **PostgreSQL**. O projeto implementa funcionalidades como criar, editar e excluir tarefas, com uma interface simples e responsiva.

## Tecnologias Utilizadas

- **Python**
- **Django 5.1.4**
- **PostgreSQL**
- **Bootstrap 5**

## Dependências

As dependências do projeto são gerenciadas via `pip` e estão listadas no arquivo `requirements.txt`:

- `asgiref==3.8.1`
- `crispy-bootstrap5==2024.10`
- `dj-database-url==2.3.0`
- `Django==5.1.4`
- `django-crispy-forms==2.3`
- `psycopg2-binary==2.9.10`
- `python-decouple==3.8`
- `sqlparse==0.5.3`
- `typing_extensions==4.12.2`

## Funcionalidades

- **CRUD de Tarefas**:
  - Criar novas tarefas.
  - Editar tarefas existentes.
  - Excluir tarefas.
  - Listar todas as tarefas cadastradas.

- **Interface Responsiva**:
  - Construída com Bootstrap 5.
  - Uso de `django-crispy-forms` para estilizar formulários.

- **Configuração Segura**:
  - Utilização de variáveis de ambiente com `python-decouple`.

## Requisitos do Sistema

- **Python 3.8 ou superior**
- **PostgreSQL 12 ou superior**
- **Pipenv ou Pip**

## Como Executar o Projeto

1. **Clone o Repositório**
   ```bash
   git clone (https://github.com/LeoFonseca98/TWTodos_django.git)
   cd twtodos
   ```

2. **Crie e Ative um Ambiente Virtual**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # Linux/Mac
   .venv\Scripts\activate    # Windows
   ```

3. **Instale as Dependências**
   ```bash
   pip install -r requirements.txt
   ```

4. **Configure o Arquivo `.env`**
   Crie um arquivo `.env` na raiz do projeto com as seguintes configurações:
   ```plaintext
   SECRET_KEY=sua-chave-secreta
   DEBUG=True
   DB_NAME=seu-banco-de-dados
   DB_USER=seu-usuario
   DB_PASSWORD=sua-senha
   DB_HOST=localhost
   DB_PORT=5432
   ```

5. **Aplique as Migrações do Banco de Dados**
   ```bash
   python manage.py migrate
   ```

6. **Inicie o Servidor de Desenvolvimento**
   ```bash
   python manage.py runserver
   ```

7. **Acesse a Aplicação**
   Abra o navegador e acesse: [http://localhost:8000](http://localhost:8000)






