![](./hd-header.png)

## Front-End | Git e GitHub - Exercicio em dupla



<details>
  <summary>Integrante 1 - Criar repositório</summary>
  
  - Passo 1: Acessar seu GitHub
  - Passo 2: Criar um repositório público com o seguinte nome "exercicio-git-hub"
  - Passo 3: Selecionar a opção `ssh` e copiar o link do repositório 
  - Passo 3: Clonar o repositório no seu computador utilizando o comando abaixo:
    ```bash
    git clone <link do repositório>
    ```
    
</details>

<details>
  <summary>Integrante 1 - Criando arquivo </summary>
  
  - Passo 1: Criar um arquivo `README.md` e colocar o seguinte conteúdo:
    ```markdown
    # Git e GitHub - Exercicios   

    ## Dupla:
    - Nome do integrante 1: [GitHub](https://github.com/<usuario>)
    - Nome do integrante 2: [GitHub](https://github.com/<usuario>)

    ### Confingurações do Git
    - git help
      > Lista de comandos do Git
    - git config --list
      > Lista de configurações do Git
    - git config --global user.name "Nome do usuário"
      > Configura o nome do usuário
    - git config --global user.email "SeuRealizando
    ```
  - Passo 2: `git add .` para adicionar o arquivo
  - Passo 3: `git commit -m "adicionado comandos para configuracao do git"` para salvar as alterações
  - Passo 4: `git push origin main` para enviar as alterações para o repositório 
  remoto  
</details>

<details>
  <summary>Integrante 2 - Alterando arquivo README.md</summary>

  - Passo 1: Acessando o repositório do integrante 1
  - Passo 2: Realizando o clone do repositório do integrante 1
  - Passo 3: Criar uma nova branch com o comando abaixo:
    ```bash
    git checkout -b feature/comandos-basicos
    ```
    > o Comando `git checkout -b` cria uma nova branch
  - Passo 4: Adicione esse conteudo no `README.md`, colocando abaixo do existente.
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

  - Passo 5: `git add .` para adicionar o arquivo
  - Passo 6: `git commit -m "Adicionado comandos basicos do git"` para salvar as alterações
  - Passo 7: `git push origin feature/comandos-basicos` para enviar as alterações para o repositório 
  remoto
</details>

<details>
  <summary>Integrante 2 - Realizando Pull request</summary>
  
  > O Pull request é uma solicitação de mudanças para um repositório principal que é administrada pelo Integrante 1. O Integrante 1 é capaz de validar as alterações e realizar o `merge` do repositório principal.

  > Merge é o processo de unir duas ou mais branches, ou seja, juntar duas ou mais branches em uma única branch.

  - Passo 1: Acessar o repositório do Integrante 1
  - Passo 2: Vai selecionar a opção Pull Request
  - Passo 3: Depois clicar em `New pull request`, botão verde.
  - Passo 4: `base` e `head` são os repositórios que serão unidos.
    - base é o repositório principal, do Integrante 1
    - head é a branch do Integrante 2
  - Passo 5: Clicar em `Create pull request`
  - Passo 6: Adicionar um titulo e uma mensagem para o pull request
  - Passo 7: Clicar em `Create pull request` novamente
</details>

<details>
  <summary>Integrante 1 - Aceitando o Pull request</summary>
  
  > Antes de aceitar o pull request, o Integrante 1 deve validar as alterações.

  > Essa validação é chamada de Code Review.

  - Code Review: 
    > É processo de validar as alterações feitas pelo Integrante 2. Podendo colocar comentários e aprovar ou rejeitar as alterações.

  - Passo 1: Acessar o repositório do Integrante 1
  - Passo 2: Vai selecionar a opção Pull Request
  - Passo 3: Selecionar o `Pull request` aberto pelo Integrante 2.
  - Passo 4: Realizar o Code Review
    - Adicionar comentários, caso necessário
    - Selecionar a opção `Approve` ou `Reject`      
</details>

<details>
  <summary>Integrante 1 - Atualizando a branch local</summary>
  
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
  <summary>Integrante 2 - Atualizando a branch local</summary>
  
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

<details>
  <summary>Realizando Fork</summary>
  
  - O fork:
    > É um repositório que é criado a partir de um outro repositório.

  - Passo 1: Acessar o repositório `https://github.com/digital-house-brasil/debugger`
    > Clique aqui: [Repositório](https://github.com/digital-house-brasil/debugger)
  - Passo 2: Clicar em `Fork`
  - Passo 3: Clicar em `Create fork`
  - Passo 4: Clonar o repositório
    ```bash
    git clone <link-do-repositorio>
    ```
  - Passo 5: Editar o título `Como debugar seu código` para `Debugar seu código`
  - Passo 6: Subir as alterações
  - Passo 7: Realizar o PR
</details>

###### tags: `Git` `GitHub` `Repositórios`