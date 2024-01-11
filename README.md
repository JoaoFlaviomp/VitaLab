Sistema de Gerenciamento de Exames
Este é um sistema de gerenciamento de exames desenvolvido em Python, utilizando o framework Django para o backend, e HTML/CSS para o frontend.

Pré-requisitos
Certifique-se de ter as seguintes ferramentas instaladas em seu ambiente de desenvolvimento:

Python (versão 3.6 ou superior)
Django (instalado via pip)
Um navegador web moderno
Configuração do Ambiente
Clone o repositório para sua máquina local:
bash
Copy code
git clone https://github.com/seu-usuario/sistema-gerenciamento-exames.git
cd sistema-gerenciamento-exames
Crie e ative um ambiente virtual (opcional, mas recomendado):
bash
Copy code
python -m venv venv
source venv/bin/activate  # No Windows, use "venv\Scripts\activate"
Instale as dependências do projeto:
bash
Copy code
pip install -r requirements.txt
Configuração do Banco de Dados
Aplique as migrações para configurar o banco de dados:
bash
Copy code
python manage.py migrate
Crie um superusuário para acessar a área administrativa:
bash
Copy code
python manage.py createsuperuser
Siga as instruções para fornecer um nome de usuário, endereço de e-mail e senha.

Executando a Aplicação
Execute o seguinte comando para iniciar o servidor de desenvolvimento:

bash
Copy code
python manage.py runserver
Acesse a aplicação em seu navegador web em http://localhost:8000.

Acesso à Área Administrativa
Para acessar a área administrativa, vá para http://localhost:8000/admin e faça login com as credenciais do superusuário criado anteriormente.

Contribuição
Se você quiser contribuir para este projeto, por favor, abra uma issue ou envie um pull request.
