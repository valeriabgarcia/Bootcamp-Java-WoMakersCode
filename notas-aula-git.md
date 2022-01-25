# Módulo 1 : Conceitos iniciais

## Git
Sistema de controle de versão

## GitHub
Plataforma de hospedagem de código-fonte e arquivos com controle de versão utilizando o Git

## Instalando no Windows
https://git-scm.com/download/win

git --version

## Acessando o GitHub
https://github.com/

## Configurando a conta do GitHub no terminal
git config --global user.email "email"

## Versionamento
Processo de controle de versões

## Repositório
É a pasta onde armazenamos o nosso projeto

## Commit
Toda vez que você desejar salvar/registrar as alterações no seu projeto, você comita essa alterações

## Branch
São separações de código, sendo possível que varias pessoas atuem em um mesmo projeto independentemente.

A branch inicial de todo projeto é a branch master

Develop: ambiente para uso em tempo de desenvolvimento.

Homolog: após as alterações serem validadas em ambiente de desenvolvimento, o código vai para a branch/ambiente de homologação

Master: é a branch principal do nosso projeto, geralmente os códigos contidos nela são os que vão para produção.

## Merge
Realizamos o merge para juntar alterações de duas branchs

## Clone
Transferir o repositório que está no github para nossa máquina local

## Pull
Com o comando git pull podemos atualizar o nosso repositório local

## Push
Com o comando git push podemos enviar nossas alterações locais para o nosso repositório remoto

## Fork
Você terá uma cópia do repositório na sua conta do github

Depois de “forkar” um repositório, você pode fazer pull-requests para contribuir com o conteúdo no repositório principal

## Pull request
Após “forkar” o repositório de outra pessoa, podemos resolver issues dele e fazer pull requests enviando soluções para erros e adicionando novos conteúdos

-----------------------

# Módulo 2: Criando seu primeiro repositório e aprendendo os comandos mais utilizados

## Criando o diretório local do projeto

## Criando o repositório no github

## Conectando seu repositório local com um remoto no github

git init

git config --global user.email "valeriabeserragarcia@gmail.com"

git remote add origin https://github.com/valeriabgarcia/Bootcamp-Java-WoMakersCode-Git-Github.git 

git add .

git commit -m "comentarios"

git push -u origin master

## Clonando um repositório já existente

## Comandos mais utilizados: 

**git status**

**git add**

**git commit**

**git push**

**git pull**

--------------------

# Módulo 3 : Trabalhando com branchs

## Criando uma branch pelo terminal
git checkout -b nome-da-branch

## Verificando as branchs 
git branch

## Voltando para a branch master 
git checkout master

## Criando uma branch pelo github

## Enviando sua branch local para o seu repositório remoto
git push -u origin nome-da-branch


## Fazendo um merge local na branch master

git checkout master

git pull

git merge nome-da-branch

## Realizando push da branch para o github
git push


