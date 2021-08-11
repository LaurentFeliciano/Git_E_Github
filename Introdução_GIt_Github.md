Olá! Este repositório foi criado com a intenção de armazenar meu conhecimento sobre git e Github de forma resumida.
Então vamos lá...

O que é Git e Github?

Git: 
    Sistema de versionamento de arquivos.

Github:
    Plataforma utilizada para hospedar seus arquivos e projetos.
    Outras opções: Gitlab, Bitbucket, Gitbucket, Gitea, Beanstalk, Launchpad, Sourceforge, Phabricator, Gogs, Apache Allura.

Repositório:
    Diretório,"pasta" onde se armazena os arquivos e Projetos.

    #Criando um repertório vazio:
    git init
    #Cria-se uma pasta ".git" dentro da pasta onde está sendo utilizada o git bash

    #É necessário identificar-se, por isso, utilize o comando abaixo para cadastrar seu nome e email:
    git config --global user.email "<seu email>"
    git config --global user.name "<seu nome>"

    #Caso queira identificar-se somente neste repositório, utilize:
    omit --global

Add:
    Insere o arquivo especificado na área de standing.

    #Inserindo um arquivo:
    git add <arquivo>

    #Inserindo todos os arquivos do repositório:
    git add .

    #Também é utilizada para atualizar o arquivo

Restore:
    Descarta as mudanças.

    #Descartando as mudanças:
    git restore <arquivo>

Branch:
    Ramificação, linha alternativa de desenvolvimento.
    
Main:
    Linha cronologia.

    #Define o nome da branch principal como "main":
    git branch -m "main"

Commit:
    Insere na branch ou main.

    #Fazendo um commit:
    git commit -m "<nome do commit>"

Merge:
    Faz a união, junção entre a branch e o main.

    #Unindo a main com o branch:
    git merge <nome da branch>

Remote:
    Conecta o repositório local com o repositório do Github.

    #Conectando o repositório local e o repositório do Github
    git remote add origin <link.git>

Push:
    "Empurra" o commit para o repositório do Github.

    #Enviando os commits para o repositório do Github:
    git push -u origin <branch>

    #Só se utiliza o -u na primeira vez

Pull:
    "Puxa" o repositório do Github para sua máquina, usado para atualizar o repositório.

    #Atualizando o repositório
    git pull

Pull request:
    Uma sugestão de atualização.

Clear:
    Limpa o histórico de comandos.

    #Limpando o histórico de comandos:
    clear

Init:
    Inicia um repositório git vazio.

    #Criando um repertório vazio:
    git init

Status:
    Mostra o status da branch.

    #Mostrando o status da branch:
    git status

Checkout:
    Sai da branch(ou main) atual para outra.

    #Comando:
    git checkout -b "<nome da branch>"

Clone:
    Clona o repositório do link inserido.

    #Clonando repositório:
    git clone <link.git>

cd:
    Entra na pasta inserida.

    #Comando:
    cd <nome do projeto>