comandi dell'es

 mkdir es1
    7  cd ./es1
    8  ls
    9  git init
   10  cd ./.git
   11  git add "primoFile"
   12  ls ..
   13  cd ..
   14  git add "primoFile"
   15  git init
   16  echo "repository es1 " > READ.me
   17  echo "repository es1 " > READ.md
   18  git add READ.md
   19  git commit -m "aggiunta file read.me"
   20  git config --global user.name "dylan"
   21  git config --global user.email "dylan.rivieccio@studentigalileilivorno.edu.it"
   22  git config --global user.email "dylan.rivieccio@studenti.galileilivorno.edu.it"
   23  git commit -m "aggiunta file read.me"
   24  ls
   25  git status
   26  echo "repository es1 " > READ.md
   27  git add READ.md
   28  echo "prima modifica" >> READ.md
   29  git add READ.md
   30  git commit -m
   31  git commit -m "prima modifica"
   32  git status
   33  git log --online
   34  git log --oneline
   35  git branch -M main
   36  git remote add origin https://github.com/dylanrivieccio-hue/esPreparazione-git.git
   37  git push -u origin main
   38  git remote -v
   39  git status
   40  git log --oneline
   41  git push
