![](./hd-header.png)

## Front-End | Git e GitHub - Exercicio em dupla

<details>
  <summary>Membro 1 - Criar repositório</summary>
  
  - Passo 1: Acessar seu GitHub
  - Passo 2: Criar um repositório público com o seguinte nome "exercicio-git-hub"
  - Passo 3: Selecionar a opção `ssh` e copiar o link do repositório 
  - Passo 3: Clonar o repositório no seu computador utilizando o comando abaixo:
    ```bash
    git clone <link do repositório>
    ```
    
</details>

<details>
  <summary>Membro 1 - Criando arquivo </summary>
  
  - Passo 1: Criar um arquivo `README.md` e colocar o seguinte conteúdo:
    ```markdown
    # Git e GitHub - Exercicios

    ### Confingurações do Git
    - git help
      > Lista de comandos do Git
    - git config --list
      > Lista de configurações do Git
    - git config --global user.name "Nome do usuário"
      > Configura o nome do usuário
    - git config --global user.email "SeuRealizando
  > OBS: O comando `git checkout -b` é usado para criar uma nova branch.
</details>

<details>
  <summary>Membro 2 - Alterando arquivo README.md</summary>

  - Passo 1: Adicione esse conteudo no `README.md`, colocando abaixo do existente.
    ```markdown
    ### Comandos básicos do Git
    - git init
      > Inicializa um repositório local
    - git clone <link-do-repositorio>
      > Clona um repositório remoto
    - git status
      > Mostra o status do repositório
    - git add .
      > Adiciona todos os arquivos do diretório atual ao repositório
    - git commit -m "Mensagem"
    > Salva as alterações no repositório
    - git push origin master  
    > Envia as alterações para o repositório remoto
    ```
  - Passo 2: `git add .` para adicionar o arquivo
  - Passo 3: `git commit -m "Adicionado comandos basicos do git"` para salvar as alterações
  - Passo 4: `git push origin feature/comandos-basicos` para enviar as alterações para o repositório 
  remoto
</details>

<details>
  <summary>Membro 2 - Realizando Pull request</summary>
  
  > O Pull request é uma solicitação de mudanças para um repositório principal que é administrada pelo membro 1. O membro 1 é capaz de validar as alterações e realizar o `merge` do repositório principal.

  > Merge é o processo de unir duas ou mais branches, ou seja, juntar duas ou mais branches em uma única branch.

  - Passo 1: Acessar o repositório do membro 1
  - Passo 2: Vai selecionar a opção Pull Request
  - Passo 3: Depois clicar em `New pull request`, botão verde.
  - Passo 4: `base` e `head` são os repositórios que serão unidos.
    - base é o repositório principal, do membro 1
    - head é a branch do membro 2
  - Passo 5: Clicar em `Create pull request`
  - Passo 6: Adicionar um titulo e uma mensagem para o pull request
  - Passo 7: Clicar em `Create pull request` novamente
</details>

<details>
  <summary>Membro 1 - Aceitando o Pull request</summary>
  
  > Antes de aceitar o pull request, o membro 1 deve validar as alterações.

  > Essa validação é chamada de Code Review.

  - Code Review: 
    > É processo de validar as alterações feitas pelo membro 2. Podendo colocar comentários e aprovar ou rejeitar as alterações.

  - Passo 1: Acessar o repositório do membro 1
  - Passo 2: Vai selecionar a opção Pull Request
  - Passo 3: Selecionar o `Pull request` aberto pelo membro 2.
  - Passo 4: Realizar o Code Review
    - Adicionar comentários, caso necessário
    - Selecionar a opção `Approve` ou `Reject`      
</details>

<details>
  <summary>Membro 1 - Atualizando a branch local</summary>
  
  - git pull
    > Atualiza as alterações do repositório remoto para o repositório local

  - Passo 1: Fazer o checkout para a branch principal `main`
  - Passo 2: Executar o comando git pull no terminal
    ```bash
    git pull    
    ```
  - Passo 3: Verificar se as alterações aparecenram no repositório local
</details>

<details>
  <summary>Membro 2 - Atualizando a branch local</summary>
  
  - git checkout
    > Faz o checkout da branch local para a branch remota
    ```bach
    # branch local é a main
    git checkout <branch-local>
    ```
  - Passo 1: Fazer o checkout para a branch principal `main`
    ```bash
    git checkout main
    ```
  - Passo 2: Executar o comando git pull
    ```bash
    git pull
    ```
  - Passo 3: Verificar se as alterações aparecenram no repositório local
</details>

###### tags: `Git` `GitHub` `Repositórios`