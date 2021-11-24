git clone https://github.com/smartiqaorg/geometric_lib
cd geometric_lib
git checkout develop
git checkout release
git log --pretty=oneline --all --graph
git checkout main
git merge develop --no-ff
git log --pretty=oneline --all --graph
git reset --hard d078c8d
git log --pretty=oneline --graph
git log --pretty=oneline --graph --all
git merge develop --ff
git log --pretty=oneline --graph --all
git checkout release
git rebase main --interactive
git status
git add -A
git rebase --continue
git log --pretty=oneline --graph --all
git status
git add -A
git rebase --continue
git log --pretty=oneline --all --graph
git checkout main
git log --pretty=oneline --all --graph
git remote remove origin
git remote add origin https://github.com/AzamatRT/geolib.git
git branch -M main
git push -u origin main

#info: please complete authentication in your browser...
#Enumerating objects: 27, done.
#Counting objects: 100% (27/27), done.
#Delta compression using up to 12 threads
#Compressing objects: 100% (19/19), done.
#Writing objects: 100% (27/27), 3.59 KiB | 3.59 MiB/s, done.
#Total 27 (delta 5), reused 19 (delta 4), pack-reused 0
#remote: Resolving deltas: 100% (5/5), done.
#To https://github.com/AzamatRT/geolib.git
# * [new branch]      main -> main
#Branch 'main' set up to track remote branch 'main' from 'origin'.