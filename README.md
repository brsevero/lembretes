# lembretes Importantes

~~~markdown
marcação de deixar o código cru em alguma linguagem
~~~~

Em C, por exemplo:

~~~C
#include <stdio.h>
int main()
{
    print("Hello World");
    return 0;
}
~~~

## Máquinas Virtuais em Python

### Criação: Rodar no terminal
~~~shell
python -m venv <nome_da_pasta>
~~~

### Ativação
~~~shell
source <nome_da_virtualenv>/bin/activate (Linux/macOS)
<nome_da_virtualenv>\Scripts\activate (Windows)
~~~

### Desativação
~~~shell
deactivate
~~~

### Instalação de pacotes
Utilizar o pip normalmente

### Instalação de dependências
~~~shell
pip install -r requirements.txt
~~~

### Criação de Lista de dependências
~~~shell
pip freeze > requirements.txt
~~~


## GIT

### Iniciar
~~~Shell
git init
~~~

### Commit
~~~Shell
git commit -m "Mensagem"
~~~

### Criação de um branch
~~~Shell
git checkout -b <nome_da_branch_nova>
~~~

### Clonar uma brach específica
~~~shell
git clone -b <branch> <repositório_remoto>
~~~

### Visualizar todas as branches
~~~shell
git branch -a
~~~

### Escolha de branch
~~~Shell
git branch -M main
~~~

### Colocar uma referência para um repositório
~~~Shell
git remote add origin <link_do_repositório> 
~~~

### Puxar da nuvem - pull
~~~Shell
git pull origin main
~~~

### Empurar pra nuvem - push
~~~Shell
git push -u origin main
~~~

### Clonagem
~~~Shell
git clone <link_do_repositório>
~~~

### Configuração Inicial
~~~Shell
git config --global user.name "Fulano de Tal"
~~~

~~~Shell
git config --global user.email fulanodetal@exemplo.br
~~~

## Django

### Criação do Projeto
~~~Python
django-admin startproject <nome_do_projeto>
~~~

### Criação de uma Aplicação
~~~Python
python manage.py startapp <nome_do_app>
~~~

### Migração do banco de dados
~~~Python
python manage.py makemigrations
~~~

~~~Python
python manage.py migrate
~~~

### Rodar o servidor local
~~~Python
python manage.py runserver
~~~

### Criação de Super Usuario - admin
~~~Python
python manage.py createsuperuser
~~~

## Docker

### Ativar docker linux
~~~shell
sudo systemctl start docker
~~~

### Desativar docker linux
~~~shell
sudo systemctl stop docker
~~~

### Status Docker
~~~shell
sudo systemctl status docker
~~~

### Executar um conteiner interativo
~~~shell
docker exec -it [projeto] bash
~~~
### executar um conteiner
~~~shell
sudo docker-compose up -d
~~~
