# GIT E GITHUB
Guia para iniciantes
creditos: Rocketseat.

### INSTALAÇÃO
Instalação do git:
https://git-scm.com/

### GIT

Para inicializar o git é necessario usar:

git init

### CODIGOS GIT

git add < '.' (adiciona todos, sem aspas) ou (nomedoitem)> - O comando git add adiciona arquivos novos ou alterados em seu diretório de trabalho à área de teste do Git

git commit -m "msg" - server para para capturar o estado de um projeto naquele ponto no tempo

git log - mostra os as capturas feitas pelo commit, as mudanças

git show "codigo do git log" - mostra o commit feito e somente o git show mostra o ultimo ponto feito.

git status - mostra o estado do desenvolvimento no git

git branch - mostra todas nossas branch

git branch "nome" - Basicamente é como se fosse outra linha do tempo de seu codigo, tudo que esta na master sera copiado para essa "linha do tempo" e voce poderá fazer suas alterações nela sem afetar a master.

git branch -D "nome" - Apaga a branch criada.

git checkout "nome da branch" - isso te levará para branch que você criou, ou para voltar para master

git merge "nome da branch" - vai juntar a branch que voce esta mais a que você adicionou.

git remote add origin "URL" - e o nome do repositório Git onde você deseja hospedar seu código. Isso muda o destino de envio de origem para esse repositório Git.