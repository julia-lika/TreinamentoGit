O Windows PowerShell
Copyright (C) Microsoft Corporation. Todos os direitos reservados.

Instale o PowerShell mais recente para obter novos recursos e aprimoramentos! https://aka.ms/PSWindows

PS C:\Users\Inteli> cd C:\Projetos\Inteli\TreinamentoGit\
PS C:\Projetos\Inteli\TreinamentoGit> git init
Reinitialized existing Git repository in C:/Projetos/Inteli/TreinamentoGit/.git/
PS C:\Projetos\Inteli\TreinamentoGit> echo "Olá mundo!" >> .\index.txt
PS C:\Projetos\Inteli\TreinamentoGit> explorer .]
PS C:\Projetos\Inteli\TreinamentoGit> explorer .
PS C:\Projetos\Inteli\TreinamentoGit> cat .\index.txt
"Ol  mundo!"
"Ol  mundo!"
Olá mundo!


PS C:\Projetos\Inteli\TreinamentoGit> git status
On branch master

No commits yet

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        index.txt

nothing added to commit but untracked files present (use "git add" to track)
PS C:\Projetos\Inteli\TreinamentoGit> git add .\index.txt
PS C:\Projetos\Inteli\TreinamentoGit> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.txt

PS C:\Projetos\Inteli\TreinamentoGit> echo "Olá mundo!" >> .\index.txt
PS C:\Projetos\Inteli\TreinamentoGit> echo "Teste" >> text
PS C:\Projetos\Inteli\TreinamentoGit> cat text
Teste
PS C:\Projetos\Inteli\TreinamentoGit> git status
On branch master

No commits yet

Changes to be committed:
  (use "git rm --cached <file>..." to unstage)
        new file:   index.txt

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text

PS C:\Projetos\Inteli\TreinamentoGit> git commit -m ":lipstick: feat: adicionando arquivo txt ao projeto"
[master (root-commit) b4aae31] :lipstick: feat: adicionando arquivo txt ao projeto
 1 file changed, 0 insertions(+), 0 deletions(-)
 create mode 100644 index.txt
PS C:\Projetos\Inteli\TreinamentoGit> git status
On branch master
Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git restore <file>..." to discard changes in working directory)
        modified:   index.txt

Untracked files:
  (use "git add <file>..." to include in what will be committed)
        text

no changes added to commit (use "git add" and/or "git commit -a")
PS C:\Projetos\Inteli\TreinamentoGit> git remote add origin https://github.com/julia-lika/TreinamentoGit.git
PS C:\Projetos\Inteli\TreinamentoGit> git branch -M main
PS C:\Projetos\Inteli\TreinamentoGit> git push -u origin main
Enumerating objects: 3, done.
Counting objects: 100% (3/3), done.
Delta compression using up to 12 threads
Compressing objects: 100% (2/2), done.
Writing objects: 100% (3/3), 301 bytes | 301.00 KiB/s, done.
Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/julia-lika/TreinamentoGit.git
 * [new branch]      main -> main
branch 'main' set up to track 'origin/main'.
PS C:\Projetos\Inteli\TreinamentoGit>
