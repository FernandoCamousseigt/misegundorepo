# misegundorepo
probandogit.

Commands:
git init
git add .
git commit -m "adding index"
git log
git remote add origin WriteYourRepoURL.git
git branch -m main

if you try git pull origin main:  error:
* branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

quickly solution:
git pull origin main --allow-unrelated-histories

(or option2: git fetch without arguments (or git remote update), updating all your remote branches, then running git merge origin/<branch>, but using FETCH_HEAD internally instead to refer to whatever single ref was fetched, instead of needing to name things.)

then:
git push origin main   (or git push -u origin main)

git log





