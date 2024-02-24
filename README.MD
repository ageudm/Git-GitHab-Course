CURSO DE GIT & GITHUB
=======================

GIT: Sistema de vercinamento de código
GITHUB: Serviço de hospedagem de código


CONFIGURAÇÃO
==============

git config --global user.name "Seu Nome"
git config --global user.email "seuemail@dominio.com"
git config --global core.editor "code --wait"



COMANDOS BÁSICOS
===============

git init inicializa um repositório
git status verifica o status do repositório
git add . adiciona todos os arquivos
git add <nome do arquivo> adiciona um arquivo específico
git commit -m "first commit" salva as alterações ou versoes


SUBIR PROJETO PARA O GITHUB
===========================

git remote add origin <url> adiciona o repositório remoto
git push -u origin master envia as alterações para o repositório remoto

BAIXAR PROJECTO NO GITHUB
===========================
git clone <url> clona um repositório remoto para a máquina local
git pull atualiza o repositório local com as alterações do repositório remoto


GERENCIAMENTO DE REPOSITÓRIO
=============================
git reset --soft <hash> volta para o commit
git reset --mixed <hash> volta para o commit e desfaz o commit
git reset --hard <hash> volta para o commit e desfaz o commit e as alterações
rm -rf .git remove o repositório

GERENCIAMENTO DE BRANCHS
=========================

git log mostra o histórico de commits
git checkout -b <nome> cria uma nova branch e muda para ela
git branch lista as branchs
git checkout <nome> muda para a branch
git merge <nome> junta a branch com a branch atual
git branch -D <nome> deleta a branch
