# Pull Requests in GitHub - Pull Requests no GitHub

Pull requests (PRs) are a critical feature in GitHub for reviewing, discussing, and merging code changes. This guide covers the process of creating, reviewing, and merging pull requests.

## Creating a Pull Request

To create a pull request:

1. Push your branch to GitHub using:

    ``` bash
    git push origin <branch-name>
    ```

2. Go to the repository on GitHub.
3. Click the “Pull Requests” tab.
4. Click the “New Pull Request” button.
5. Choose the branch you want to merge into the main branch.
6. Add a title and description explaining your changes.
7. Submit the pull request.

## 2. Reviewing a Pull Request

After a PR is created, team members or collaborators can review it:

1. Go to the "Pull Requests" tab in the repository.
2. Click on the pull request you want to review.
3. Leave comments on specific lines or general feedback.
4. Approve the changes or request modifications.

## 3. Responding to Feedback

When a PR receives feedback:

1. Address the comments by making additional commits.
2. Push these changes to the same branch associated with the PR.
3. The PR will automatically update with the new changes.

## 4. Merging a Pull Request

Once the PR is approved:

1. Go to the PR on GitHub.
2. Click the “Merge Pull Request” button.
3. Choose to merge or squash the commits (if necessary).
4. Confirm the merge.

## 5. Deleting the Branch After Merging

After successfully merging the PR, it’s common to delete the branch to keep the repository clean:

1. You will be prompted with an option to delete the branch on the PR page.
2. Click "Delete branch" to remove it.

## 6. Closing a Pull Request Without Merging

If you decide not to proceed with a PR:

1. Go to the PR on GitHub.
2. Click the "Close Pull Request" button to close it without merging.

Pull requests facilitate code review, collaboration, and continuous integration, ensuring higher-quality code before merging it into the main codebase.

- *PT-BR*

Os pull requests (PRs) são uma funcionalidade essencial do GitHub para revisar, discutir e mesclar alterações de código. Este guia cobre o processo de criação, revisão e mesclagem de pull requests.

## 1. Criando um Pull Request

Para criar um pull request:

1. Envie seu branch para o GitHub usando:

    ``` bash
    git push origin <nome-do-branch>
    ```

2. Acesse o repositório no GitHub.
3. Clique na aba “Pull Requests”.
4. Clique no botão “New Pull Request”.
5. Escolha o branch que deseja mesclar no branch main.
6. Adicione um título e uma descrição explicando suas alterações.
7. Submeta o pull request.

## 2. Revisando um Pull Request

Após a criação de um PR, membros da equipe ou colaboradores podem revisá-lo:

1. Acesse a aba "Pull Requests" no repositório.
2. Clique no pull request que deseja revisar.
3. Deixe comentários em linhas específicas ou um feedback geral.
4. Aprove as mudanças ou solicite modificações.

## 3. Respondendo ao Feedback

Quando um PR recebe feedback:

1. esolva os comentários fazendo commits adicionais.
2. Envie essas alterações para o mesmo branch associado ao PR.
3. O PR será automaticamente atualizado com as novas alterações.

## 4. Fazendo Merge de um Pull Request

Uma vez que o PR é aprovado:

1. Vá até o PR no GitHub.
2. Clique no botão “Merge Pull Request”.
3. Escolha mesclar ou "squash" os commits (se necessário).
4. Confirme o merge.

## 5. Deletando o Branch Após o Merge

Depois de mesclar o PR com sucesso, é comum deletar o branch para manter o repositório limpo:

1. Você será solicitado com a opção de deletar o branch na página do PR.
2. Clique em "Delete branch" para removê-lo.

## 6. Fechando um Pull Request Sem Mesclar

Se decidir não prosseguir com um PR:

1. Acesse o PR no GitHub.
2. Clique no botão "Close Pull Request" para fechá-lo sem fazer o merge.

Os pull requests facilitam a revisão de código, a colaboração e a integração contínua, garantindo um código de maior qualidade antes de ser mesclado ao código principal.
