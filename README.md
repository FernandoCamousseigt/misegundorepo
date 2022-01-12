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

then:
git push origin main   (or git push -u origin main)

git log





