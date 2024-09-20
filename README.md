# AAI-NOITE-73698-NICOLLAS
AAI NOITE UNIFECAF 73698 NICOLLAS WENDEL DE OLIVEIRA VIANA

<h3>React Native & GitHub</h3>

**1. Comandos para criar um projeto React Native do zero e subir no GitHub:**

// Criando o projeto (o "npm install" já executa automaticamente). A pasta do projeto também.
- npx create-expo-app@latest nome-do-projeto

// Acessando a pasta do projeto.
- cd nome-da-pasta

// Se for editar o código, abrir a IDE na pasta do projeto (para o VS Code, o comando é o abaixo).
- code .

// Rodando o projeto.
- npm run start

// Após aparecer o QR code no terminal, apertar "W" (o navegador irá abrir). Após isso, inspecionar a tela e por na visualização de celular.

**Subindo no GitHub:**

// Necessário criar um repositório e pegar o link dele.

// Após criar o repositório, voltar ao CMD ou ir na pasta do projeto pelo explorador de arquivos e abrir o Git Bash.

// Com o link em mãos e o Git Bash ou CMD aberto, realizar os comandos abaixo.

// Cria um novo repositório do Git.
- git init

// Troca a branch para a principal (main).
- git branch -M main

// Adiciona os arquivos para a área de transferência, antes de irem para o repositório remoto no GitHub.
- git add .

// Grava uma mensagem nos arquivos. Essa mensagem é referente ao que foi alterado no código.
- git commit -m "mensagem do commit"

// Indica o link do repositório remoto, o qual irá receber os arquivos que estão na área de transferência.
- git remote add origin https://github.com/seu-usuario/nome-do-repositorio.git

// Faz o "upload" dos arquivos do projeto para o repositório remoto. Após isso, o código já fica disponível no GitHub.
- git push -u origin main

**2. Como clonar o projeto da nossa aula e rodá-lo:**

// Abrir o terminal e digitar o seguinte comando:
- git clone https://github.com/GuilhermeCamargo744/aula-fecaf-noite-dog-ever-match

// Entrar na pasta (após digitar "aula-fecaf" e dar um TAB, o nome virá automaticamente).
- cd aula-fecaf-noite-dog-ever-match

// Pegar as alterações do repositório remoto (GitHub) e baixá-las no local.
- git pull

// Realizar a troca de branch para a da aula em questão.
- git checkout nome-da-branch-da-aula

// Após isso, abrir o VS Code e verificar se a branch está correta (canto inferior esquerdo da tela).
- code .

// Voltar no terminal e rodar o projeto.
- npm run start
