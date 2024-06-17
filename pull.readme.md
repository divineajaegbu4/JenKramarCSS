 git pull origin main
 * branch            main       -> FETCH_HEAD
fatal: refusing to merge unrelated histories

causes:

solution:

git pull

* branch main -> FETCH_HEAD fatal: refusing to merge unrelated histories

causes:


solution:
git pull origin master --allow-unrelated-histories
git push -u origin main
