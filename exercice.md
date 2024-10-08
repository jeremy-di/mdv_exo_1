```bash
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git init
Initialized empty Git repository in A:/xampp/htdocs/1_projets/mdv/mdv_exo_1/.git/
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git remote add origin https://github.com/jeremy-di/mdv_exo_1.git
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git status
On branch master
No commits yet

  (use "git add <file>..." to include in what will be committed)
        bsg75.md
        sg1.md

nothing added to commit but untracked files present (use "git add" to track)
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git add .
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git commit -m "Stargate et battlestar"
[master (root-commit) 0915bdd] Stargate et battlestar
 2 files changed, 8 insertions(+)
 create mode 100644 bsg75.md
 create mode 100644 sg1.md
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git push origin main
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/jeremy-di/mdv_exo_1.git'
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git status
On branch master
nothing to commit, working tree clean
error: src refspec main does not match any
error: failed to push some refs to 'https://github.com/jeremy-di/mdv_exo_1.git'
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git branch -M main
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git push origin main
Enumerating objects: 4, done.
Counting objects: 100% (4/4), done.
Delta compression using up to 8 threads
Compressing objects: 100% (4/4), done.
Writing objects: 100% (4/4), 380 bytes | 380.00 KiB/s, done.
Total 4 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
To https://github.com/jeremy-di/mdv_exo_1.git
 * [new branch]      main -> main
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git status
On branch main
nothing to commit, working tree clean
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git pull
remote: Enumerating objects: 4, done.
remote: Counting objects: 100% (4/4), done.
remote: Compressing objects: 100% (3/3), done.
remote: Total 3 (delta 0), reused 0 (delta 0), pack-reused 0 (from 0)
Unpacking objects: 100% (3/3), 1009 bytes | 126.00 KiB/s, done.
From https://github.com/jeremy-di/mdv_exo_1
   0915bdd..a5a0a9a  main       -> origin/main
There is no tracking information for the current branch.
Please specify which branch you want to merge with.
See git-pull(1) for details.

    git pull <remote> <branch>

If you wish to set tracking information for this branch you can do so with:

    git branch --set-upstream-to=origin/<branch> main

PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> git pull origin main
From https://github.com/jeremy-di/mdv_exo_1
 * branch            main       -> FETCH_HEAD
Updating 0915bdd..a5a0a9a
Fast-forward
 README.md | 1 +
 1 file changed, 1 insertion(+)
 create mode 100644 README.md
PS A:\xampp\htdocs\1_projets\mdv\mdv_exo_1> 
```
