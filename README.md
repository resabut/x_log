# commands used
```
 mkdir logx_graph
 cd logx_graph/
 git init
 git branch -m "main"
 touch README.md
 git add README.md
 git commit -m "First commit. Add README"
 git branch
 git switch -c "A"
 git branch
 touch A1
 git add A1
 git commit -m "Add A1 in A"
 git switch main
 git switch -c "B"
 touch B1
 git add B1
 git commit -m "Add B1 to B"
 git merge A
 git switch A
 git merge 85bf9dd462f9cadc08c
 git switch main
 git merge 12b79fac1e6c29
 git merge 92a9c9f1794b00
 git log --graph --all
```

