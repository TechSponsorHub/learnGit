# Branching and Merging in Git - Branching e Merging no Git

Branches allow you to work on different features or fixes separately from the main codebase. In this guide, you will learn how to create branches, switch between them, and merge changes.

## 1. Creating a Branck

To create a new branch:

``` bash
git checkout -b <branch-name>
```

This command creates a new branch and switches to it.

## 2. Viewing Branches

To list all branches in your repository:

``` bash
git branch
```

The current branch will be highlighted with an asterisk (*).

## 3. Switching Between Branches

To switch to another branch:

``` bash
git checkout <branch-name>
```

## 4. Merging Branches

When you're ready to bring changes from one branch into another (typically the main branch):

### 1. First, switch to the branch where you want to apply the changes

``` bash
git checkout main
```

### 2. Merge the other branch into *main*

``` bash
git merge <branch-name>
```

## 5. Resolving Merge Conflicts

If Git cannot automatically merge the changes, you'll need to resolve conflicts manually:

### 1. Open the conflicting files and review the changes

### 2. Choose which changes to keep, then stage the resolved files

``` bash
git add <file>
```

### 3. Once all conflicts are resolved, commit the merge

``` bash
git commit -m "Resolve merge conflicts"
```

## 6. Deleting a Branch

Once you've successfully merged a branch, you can delete it:

``` bash
git branch -d <branch-name>
```

If the branch hasn't been merged yet and you still want to delete it, use:

``` bash
git branch -D <branch-name>
```

Branching and merging allow you to isolate work and integrate it efficiently into the main project, enhancing collaboration.

- *PT-BR*

Branches permitem que você trabalhe em diferentes funcionalidades ou correções separadamente do código principal. Neste guia, você aprenderá a criar branches, alternar entre eles e mesclar mudanças.

## 1. Criando um Branch

Para criar um novo branch:

``` bash
git checkout -b <nome-do-branch>
```

Esse comando cria um novo branch e muda para ele.

## 2. Visualizando Branches

Para listar todos os branches no seu repositório:

``` bash
git branch
```

O branch atual será destacado com um asterisco (*).

## 3. Alternando Entre Branches

Para alternar para outro branch:

``` bash
git checkout <nome-do-branch>
```

## 4. Fazendo Merge de Branches

Quando estiver pronto para trazer as mudanças de um branch para outro (geralmente o branch main):

### 1. Primeiro, alterne para o branch onde deseja aplicar as mudanças

``` bash
git checkout main
```

### 2. Mescle o outro branch no *main*

``` bash
git merge <nome-do-branch>
```

## 5. Resolvendo Conflitos de Merge

Se o Git não conseguir mesclar as mudanças automaticamente, você precisará resolver os conflitos manualmente:

### 1. Abra os arquivos conflitantes e revise as mudanças

### 2. Escolha quais mudanças manter e depois adicione os arquivos resolvidos ao stage

``` bash
git add <arquivo>
```

### 3. Quando todos os conflitos forem resolvidos, faça o commit do merge

``` bash
git commit -m "Resolve conflitos de merge"
```

## 6. Deletando um Branch

Após mesclar um branch com sucesso, você pode deletá-lo:

``` bash
git branch -d <nome-do-branch>
```

Se o branch ainda não foi mesclado e você deseja deletá-lo mesmo assim, use:

``` bash
git branch -D <nome-do-branch>
```

Branching e merging permitem isolar o trabalho e integrá-lo de forma eficiente ao projeto principal, facilitando a colaboração.
