# Отчет о проделанной работе

### Автор: Тухбатуллин Азамат Расимович
Ссылка на репозиторий с уроком на животных: 
[<ссылка на репозиторий>](https://github.com/AzamatRT/homework05)
#### Ход работы

* git clone https://github.com/smartiqaorg/geometric_lib
* cd geometric_lib
* git checkout develop
* git checkout release
* git log --pretty=oneline --all --graph
* git checkout main
* git merge develop --no-ff
* git log --pretty=oneline --all --graph
* git reset --hard d078c8d
* git log --pretty=oneline --graph
* git log --pretty=oneline --graph --all
* git merge develop --ff
* git log --pretty=oneline --graph --all
* git checkout release
* git rebase main --interactive
* git status
* git add -A
* git rebase --continue
* git log --pretty=oneline --graph --all
* git status
* git add -A
* git rebase --continue
* git log --pretty=oneline --all --graph
* git checkout main
* git log --pretty=oneline --all --graph
* git remote remove origin
* git remote add origin https://github.com/AzamatRT/geolib.git
* git branch -M main
* git push -u origin main
