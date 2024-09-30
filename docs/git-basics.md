# Git Basics - Noções Básicas do Git

In this guide, you will learn the fundamental Git commands to get started with version control.

## 1. Installing Git

To use Git, you first need to install it. Follow the instructions for your operating system:

- [Install Git on Windows](https://git-scm.com/downloads/win)
- [Install Git on Linux](https://git-scm.com/downloads/linux)
- [Install Git on macOS](https://git-scm.com/downloads/mac)

## 2. Configuring Git

Before using Git, set your user information:

``` bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

## 3. Initializing a Repository

To start tracking a project, navigate to your project folder and run:

``` bash
git init
```

This will create a ```.git``` folder where Git stores all version history.

## 4. Checking Repository Status

To check which files have been modified or staged for commit, use:

``` bash
git status
```

## 5. Staging Files

Before committing changes, you need to add files to the staging area:

``` bash
git add <file>
```

to add all changes in the directory:

```bash
git add .
```

## 6. Committing Changes

Once files are staged, save your changes with a commit:

``` bash
git commit -m "Describe the changes you made"
```

## 7. Viewing Commit History

To view the history of commits in your project, run:

``` bash
git log
```

## Cloning a Repository

To clone an existing repository from GitHub:

``` bash
git clone <repository-url>
```

## 9. Pushing Changes

To send your commits to a remote repository (e.g., GitHub):

``` bash
git push -u origin main

```

## 10. Pulling Changes

To pull the latest changes from a remote repository:

``` bash
git pull origin main
```

These are the basic commands you will use to manage your projects with Git.

- *PT-BR*

Neste guia, você aprenderá os comandos fundamentais do Git para começar a usar controle de versão.

## 1. Instalando o Git

Para usar o Git, você precisa instalá-lo. Siga as instruções para o seu sistema operacional:

- [Instalar Git no Windows](https://git-scm.com/downloads/win)
- [Instalar Git no Linux](https://git-scm.com/downloads/linux)
- [Instalar Git no macOS](https://git-scm.com/downloads/mac)

## 2. Configurando o Git

Antes de usar o Git, configure suas informações de usuário:

``` bash
git config --global user.name "Seu Nome"
git config --global user.email "seu-email@exemplo.com"
```

## 3. Inicializando um Repositório

Para começar a versionar um projeto, navegue até a pasta do projeto e execute:

``` bash
git init
```

## 4. Verificando o Status do Repositório

Para verificar quais arquivos foram modificados ou estão prontos para commit, use:

``` bash
git status
```

## 5. Adicionando Arquivos ao Stage

Antes de fazer commit das alterações, você precisa adicionar os arquivos à área de stage:

``` bash
git add <arquivo>
```

Para adicionar todas as mudanças no diretório:

``` bash
git add .
```

## 6. Fazendo Commit das Alterações

Depois que os arquivos estiverem no stage, salve suas alterações com um commit:

``` bash
git commit -m "Descreva as alterações que você fez"
```

## 7. Visualizando o Histórico de Commits

Para visualizar o histórico de commits do seu projeto, execute:

``` bash
git log
```

## 8. Clonando um Repositório

Para clonar um repositório existente do GitHub:

``` bash
git clone <url-do-repositório>
```

## 9. Fazendo Push das Alterações

Para enviar seus commits para um repositório remoto (por exemplo, GitHub):

``` bash
git push -u origin main
```

## 10. Fazendo Pull das Alterações

Para puxar as últimas alterações de um repositório remoto:

``` bash
git pull origin main
```

Esses são os comandos básicos que você usará para gerenciar seus projetos com Git.
