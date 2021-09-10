
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


Colaborador 2
Daniel

Aluno@ESN914D1233548 MINGW32 /e/Vscode/Atividade_presencialUC7 (main)
$ git add .

Aluno@ESN914D1233548 MINGW32 /e/Vscode/Atividade_presencialUC7 (main)
$ git push origin main
fatal: O código de status de resposta não indica êxito: 401 (Unauthorized).
remote: Support for password authentication was removed on August 13, 2021. Please use a personal access token instead.
remote: Please see https://github.blog/2020-12-15-token-authentication-requirements-for-git-operations/ for more information.
fatal: Authentication failed for 'https://github.com/LadelloComunista/Atividade_presencialUC7.git/'

Aluno@ESN914D1233548 MINGW32 /e/Vscode/Atividade_presencialUC7 (main)
$ git push origin main
Everything up-to-date

Aluno@ESN914D1233548 MINGW32 /e/Vscode/Atividade_presencialUC7 (main)
$ git status
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
        new file:   contatos.html


Aluno@ESN914D1233548 MINGW32 /e/Vscode/Atividade_presencialUC7 (main)
$ git commit -m "adicionando contatos"
[main 0ed8898] adicionando contatos
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 contatos.html

Aluno@ESN914D1233548 MINGW32 /e/Vscode/Atividade_presencialUC7 (main)
$ git push origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 6 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (2/2), 295 bytes | 295.00 KiB/s, done.
Total 2 (delta 0), reused 0 (delta 0), pack-reused 0
To https://github.com/LadelloComunista/Atividade_presencialUC7.git
   b155d27..0ed8898  main -> main

