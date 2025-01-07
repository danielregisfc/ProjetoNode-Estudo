# Setup Node

Projeto de Demonstração de Inicialização e Configuração utilizando node.js

**Canal "O Bruno Germano"**
https://www.youtube.com/watch?v=UYwezJUhaps

Foi criado um diretório para o projeto
Nele criamos um arquivo README.md para demonstração apenas
Inicializamos o git com o comando
git init

## Definir a branch a ser utilizada (main) -b cria uma nova branch

git checkout -b main

## Adicionar o arquivo README no git

git add README.md

## Realizar nosso primeiro commit - O Commit irá registrar as alterações em um ou mais arquivos da sua branch

git commit -am "Primeira Atualização README.md"

## Criar uma branch só para desenvolvimento e mudar para ela
git checkout -b develop

## Ir para o github.com, logar e criar um repositório para nosso projeto

## Tornar branch main na branch principal
git branch -M main

## Adicionar nosso repositório remoto
git remote add origin https://github.com/danielregisfc/ProjetoNode-Estudo.git

## Enviar meus arquivos locais para o repositório remoto
git push -u origin main

## Voltar para a branch de desenvolvimento
git checkout -b develop

## Inicializar um projeto com node
npm init

## Responder as solicitaçoes feitas
package name: (projetonode)
version: (1.0.0)
description: Projeto de Demonstração
entry point: (index.js)
test command:
git repository: https://github.com/danielregisfc/ProjetoNode-Estudo.git
keywords: nodejs, express, demo
author: Daniel Régis <danielregisfc@gmail.com>
license: (ISC)


## Criar estrutura do projeto, pasta src, dentro dela pasta services, dentro dela sayHelloWorld.js. No diretório src criar os arquivos app.js e index.js
## Na raiz do projeto criar os arquivos docker-compose.yml, Dockerfile e package-lock.json
## verificar conteúdo dos arquivos no repositório  https://github.com/obg-lab/setup-nodejs

## Cria e inicializar os contêineres
docker-compose up --build

## Caso necessário instale o express antes
npm install express

