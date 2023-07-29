# fast_api


This repository should track the study of Fast API[https://fastapidozero.dunossauro.com/]

## Step 1 -  Configurando o ambiente de desenvolvimento
- Introdução ao ambiente de desenvolvimento (terminal, ferramentas, etc.)
- Instalação do FastAPI e suas dependências
- Configuração das ferramentas de desenvolvimento
- Execução do primeiro "Hello, World!" com FastAPI com testes!

###  Step 1.1 - Editor de Text:
VS Codium: Já estava escolhido.
###  Step 1.2 - Terminal: 
Terminator já tinha ouvido falar mas nunca usei.
- sudo apt-get install terminator

Terminator não permite como ssh remoto:  % terminator
You need to run terminator in an X environment. Make sure $DISPLAY is properly set
então optei pelo zsh: (sudo apt install zsh -y) [https://linuxhint.com/install-z-shell-zsh-ubuntu-22-04/]


Sat, 29 13:30

## Step 3 - A versão 3.11 do Python instalada.
 Utilizanfo Python 3.10.6, ptei por tentar seguir com essa versão.

## Step 4 - Poetry para gerenciar os pacotes
Decided to isntall with: 
"curl -sSL https://install.python-poetry.org | python3 -"

## Step 5 - Git
Default from Ubuntu Server

## Step 6 - Docker
Installed with sudo apt install docker

## OPCIONAL: O pipx pode te ajudar bastante nesses momentos de instalações
Ignorado
## OPCIONAL: O ignr para criar nosso gitignore
Ignorado
## OPCIONAL: O gh para criar o repositório e fazer alterações sem precisar acessar a página do github
Ignorado

Felt the need to install (tree)[http://mama.indstate.edu/users/ice/tree/] so better see folders.


# Tool Sets:

taskipy: Ferramenta para automatizar alguns comandos e simplificar o fluxo
ruff: Um linter, para dizer se não estamos fazendo nada esquisito no código
blue: Um formatador de código bastante amigável
isort: Uma ferramenta para ordenar os imports em ordem alfabética
pytest: Ferramenta para executar testes

poetry add --group dev pytest pytest-cov taskipy blue ruff httpx isort

Rodou tranquilo se for feito na pasta correta.