# portifolio
Meu portifolio

Comando para criar uma File/pasta
nano "Nome da pasta"

    1  ls
    2  cd Desktop/
    3  mkdir Exemplo
    4  cd Exemplo/
    5  ls -la
    6  git init
    7  rm -rf .git
    8  git init
    9  ls -la
   10  git status
   11  nano teste.md
   12  cat teste.md
   13  git status
   14  git add .
   15  git status
   16  git rm --cached teste.md
   17  git status
   18  git commit -m "meu primeiro commit"
   19  git add .
   20  git commit -m "meu primeiro commit"
   21  git checkout -b dev
   22  git status
   23  ls -la
   24  nano teste2.md
   25  ls -la
   26  git status
   27  git add .
   28  git commit -m "meu segundo commit"
   29  git checkout master
   30  git merge dev
   31  git branch -d dev
   32  git branch


git stash -u /ele vai quardar todos os arquivos criados/deletador
git stash pop /ele vai voltar todos aqueles arquivos 
