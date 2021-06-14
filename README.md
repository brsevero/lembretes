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
~~~git
git init
~~~

### Commit
~~~git
git commit -m "Mensagem"
~~~

### Criação de um branch
~~~git
git checkout -b <nome_da_branch_nova>
~~~

### Escolha de branch
~~~git
git branch -M main
~~~

### Colocar uma referência para um repositório
~~~git
git remote add origin <link do repositório> 
~~~

### Puxar da nuvem - pull
~~~git
git pull origin main
~~~

### Empurar pra nuvem - push
~~~git
git push -u origin main
~~~

### Clonagem
~~~git
git clone <link do repositório>
~~~

## Django

### Criação do Projeto
~~~Django
django-admin startproject <nome_do_projeto>
~~~

### Criação de uma Aplicação
~~~Django
python manage.py startapp <nome_do_app>
~~~

### Migração do banco de dados
~~~Django
python manage.py makemigrations
python manage.py migrate
~~~

### Rodar o servidor local
~~~Django
python manage.py runserver
~~~

### Criação de Super Usuario - admin
~~~Django
python manage.py createsuperuser
~~~
