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
virtualenv <nome_da_pasta>
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

## GIT

### Iniciar
~~~git
git init
~~~

### Commit
~~~git
git commit -m "Mensagem"
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