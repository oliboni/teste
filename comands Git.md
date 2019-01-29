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

