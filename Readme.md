
Colaborador 1: Gustavo Assis Coladello

git c
Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7
$ git config --global user.name "Gustavo Assis"

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7
$ git config --global user.email "gustavo.coladello@gmail.com"

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7
$ git init
Initialized empty Git repository in C:/Users/Aluno/Desktop/Atividade_presencialUC7/.git/

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (master)
$ git add .

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (master)
$ git commit -m "Criando index.txt"
[master (root-commit) c32fb55] Criando index.txt
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.txt

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (master)
$ git remote add origin https://github.com/LadelloComunista/Atividade_presencialUC7.git

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (master)
$ git branch -M main

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Writing objects: 100% (3/3), 223 bytes | 223.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LadelloComunista/Atividade_presencialUC7.git
 * [new branch]      main -> main
Branch 'main' set up to track remote branch 'main' from 'origin'.

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git remote add origin https://github.com/LadelloComunista/Atividade_presencialUC7.git
error: remote origin already exists.

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git add .

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git commit -m "Criando Readme"
[main 824c83f] Criando Readme
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 Readme.md

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 258 bytes | 258.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LadelloComunista/Atividade_presencialUC7.git
   c32fb55..824c83f  main -> main

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git add .

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git commit -m "Configurando index.txt"
[main b155d27] Configurando index.txt
 1 file changed, 3 insertions(+)

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$ git push origin main
Enumerating objects: 5, done.
Counting objects: 100% (5/5), done.
Delta compression using up to 6 threads
Compressing objects: 100% (3/3), done.
Writing objects: 100% (3/3), 377 bytes | 188.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LadelloComunista/Atividade_presencialUC7.git
   824c83f..b155d27  main -> main

Aluno@ESN914D1233551 MINGW32 ~/Desktop/Atividade_presencialUC7 (main)
$
