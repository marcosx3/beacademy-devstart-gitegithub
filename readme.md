
# Git Github

 Projeto elaborado como exercicio sobre a aula de Git&Github do programa DevStar. Uma parceiria entre a BeAcademy e a PayLivre.
## Configuração

As configurações do GIT são armazenadas no arquivo:  ```.gitconfig``` localizado dentro do diretório do usuário do Sistema Operacional.

#### Setar usuário
    git config --global user.name "Marcos oliveira"

#### Setar email
    git config --global user.email "marcos@hotmail.com"

#### Listar configurações
    git config --list

## Principais Comandos

#### Criar novo Repositorio
    git init

#### Verificar estado dos arquivos/diretórios
    git status

#### Comitar arquivo/diretório
    git commit meu_arquivo.txt 

#### Comitar informando mensagem
    git commit meuarquivo.txt -m "minha mensagem"

#### Remover arquivo/diretório
    git rm meu_arquivo.txt 

#### Comitar arquivo/diretório
    git commit meu_arquivo.txt 

#### Visualiza histórico
    git log 

## Repositorio Remoto

#### Vincular repositório local com um repositório remoto
    git remote add origin git@github.com:xxx/curso-git.git 

### Enviando para o repositório remoto
#### **O primeiro push de um repositório deve conter o nome do repositório remoto e o branch.**
    git push -u origin master 

#### **Os demais pushes não precisam dessa informação.**
     git push 
## **Atualiza o repositório local de acordo com o repositório remoto**
#### Atualizar os arquivos no Branch atual:
        git pull
#### Buscar as alterações, mas não aplica-las no branch atual:
    git fetch
#### Clonar um repositório remoto já existente
    git clone git@github.com:xxx/curso-git.git

### Branches
##### O **master** é o branch principal do GIT.

#### Criando um novo branch
    git branch bug-123
#### Trocando para um branch existente
     git checkout bug-123
#### Criar um novo branch e trocar
     git checkout -b bug-456
#### Listando Branches
     git branch
#### Listar branches que já foram fundidos (merged) com o master
     git branch --merged

## Rebasing
#### Fazendo o rebase entre um o branch bug-123 e o master.
    git checkout experiment
    git rebase master

## Autor

- [@marcosx3](https://github.com/marcosx3)

