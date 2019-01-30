Criando um repositório
 - entra na pasta desejada e digita git init

 branch = versões diferentes do sistemas.
 branch principal é a master.

 COMMIT
 commit envia para o git as alterações.
 vem acompanhado de um comentário

 README.md informações descritivas

 git status, verifica se tem algum arquivo novo ou modificado!

 git add -A adiciona todos os arquivos
 git add nomeDoArquivo adiciona apenas aquele arquivo

Envia as modificações ao git
 git commit -m "Comentário"

 git branch mostra em qual branch estou
 
 git log mostra os commits
 cogido do commit, oque interessa são os 7 primeiros digitos

 3 formas de usar git reset
 
 git reset --soft a41984a volta o commit mas pode alterar os arquivos novamente
 
 git reset --mixed a41984a volta o commit precisando adicionar novamente os arquivos

 git reset --hard a41984a apaga o commit e se perde todos os arquivos


 Criando novo branch

  git branch nomeBranch

  muda de branch
  git checkout teste


git diff -  mostra oque foi alterado

git diff --name-only - mostra os arquivos que foram modificados

git diff nomeArqui - mostra oque foi alterado em tal arquivo

git checkout HEAD -- style.css - volta o arquivo ao original


Repositório remoto

Criar chave SSH: 
https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

associar repositório do PC para repositório do hub 
git remote add origin https://github.com/oliboni/teste.git

git remote - verifica se ja tem um precesso vinculado

envia os conteudos locais para o servidor remoto
git push -u origin master


git revert --no--edit a41984a	- volta o commit para o anterior

remover um branch remoto
 git push origin :teste

remoto um	branch local	
 git branch -D teste


trazendo do git remoto para o local "Atualizar o git local"
git pull origin master

 