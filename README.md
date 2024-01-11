# Sistema de Gerenciamento de Exames

Este é um sistema de gerenciamento de exames desenvolvido em Python, utilizando o framework Django para o backend, e HTML/CSS para o frontend.

## Pré-requisitos

Certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:
- Python (versão 3.6 ou superior)
- Django (instalado via pip)
- Um navegador web moderno

## Configuração do Ambiente

1. Clone o repositório para sua máquina local:

```bash
git clone https://github.com/JoaoFlaviomp/VitaLab.git
cd sistema-gerenciamento-exames
```

2. Crie e ative um ambiente virtual (opcional, mas recomendado):

   - No Linux:
     ```bash
     python -m venv venv
     source venv/bin/activate
     ```
   - No Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```

3. Instale as dependências do projeto:

```bash
pip install -r requirements.txt
```

## Configuração do Banco de Dados

1. Aplique as migrações para configurar o banco de dados:

```bash
python manage.py migrate
```

2. Crie um superusuário para acessar a área administrativa:

```bash
python manage.py createsuperuser
```

Siga as instruções para fornecer um nome de usuário, endereço de e-mail e senha.

## Executando a Aplicação

Execute o seguinte comando para iniciar o servidor de desenvolvimento:

```bash
python manage.py runserver
```

Acesse a aplicação em seu navegador web em [http://localhost:8000](http://localhost:8000).

## Acesso à Área Administrativa

Para acessar a área administrativa, vá para [http://localhost:8000/admin](http://localhost:8000/admin) e faça login com as credenciais do superusuário criado anteriormente.

## Contribuição

Se você quiser contribuir para este projeto, por favor, abra uma issue ou envie um pull request.
