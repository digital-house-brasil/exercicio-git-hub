![](./assets/hd-header.png)

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
    - git config --global user.email "Seu email"
      > Configura o email do usuário    
    ```
  - Passo 2: git add . para adicionar o arquivo
  - Passo 3: git commit -m "Mensagem" para salvar as alterações
  - Passo 4: git push origin main para enviar as alterações para o repositório remoto 

</details>

<details>
  <summary>Membro 2 - Clonando repositório </summary>

  - Passo 1: Acessar o repositório do membro 1
  - Passo 2: Escolher a opção `ssh` e copiar o link do repositório
  - Passo 3: Clonar o repositório no seu computador utilizando o comando abaixo:
    ```bash
    git clone <link do repositório>
    ```
  - Passo 4: Criar uma nova branch usando o comando abaixo:
    ```bash
    git checkout -b feature/comandos-basicos
    ``` 

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
  - Passo 4: 

</details>

<details>
  <summary>6. SSH</summary>  

  > Secure Shell é um protocolo de rede criptográfico para operação de serviços de rede de forma segura sobre uma rede insegura. O melhor exemplo de aplicação conhecido é para login remoto de utilizadores a sistemas de computadores.
  
  - Gerar chave pública e privada [link](https://docs.github.com/pt/authentication/connecting-to-github-with-ssh)

  ![](./assets/11.png)
  
</details>

-------------------------------
Referências
 - [Mini curso de Git](https://minicursogit.github.io/#/)
 - [GIT CHEAT SHEET](https://education.github.com/git-cheat-sheet-education.pdf)

###### tags: `Git` `GitHub` `SSH` `Repositórios`