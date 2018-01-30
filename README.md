# command history

```
10254  mkdir test2
10255  git mv *.* test2
10257  git commit -m "prepare for merge into test1"
10261  cd test1
10264  git remote add test2 ~/all_repos_merged/test2
10267  git remote -v
10268  git pull test2 master
10269  git pull --allow-unrelated-histories test2 master
10271  git lg
10272  git status
10274  git remote rm test2
10275  cd ..
10276  ls
10277  rm -rf test2
```
