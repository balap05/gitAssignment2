Assignment 2
git init
git branch develop
git branch feature1
git branch feature2
git checkout develop
git stash -u
git checkout feature1
git add .
git commit
git checkout develop
git stash pop
git add .
git commit


Assignment 3
git init
git branch develop
git branch f1
git branch f2
git checkout develop
git add .
git commit -m "develop"
git push origin develop
git checkout f1
git add .
git commit -m "f1"
git push origin f1
git checkout f2
git add .
git commit -m "f2"
git push origin f2
git checkout f2
git branch --delete f2
git branch -a 

git init
  251  git add .
  252  git commit -m "initial commit"
  253  git branch public1
  254  git branch public2
  255  git branch private
  256  git checkout public1
  257  git add .
  258  git status
  259  git commit -m "public1"
  260  git checkout master
  261  git merge public1
  262  git merge public2
  263  git checkout private1
  264  git pull
  265  git checkout private
  266  git status
  267  git add .
  268  git commit - m "edit master"
  269  git commit -m "edit master"
  270  git checkout public1
  271  git status
  272  git merge private
  273  git checkout public2
  274  git merge private
  275  git checkout master
  276  git checkout private
  277  git add .
  278  git commit -m "commit"
  279  git checkout master
  280  git checkout private
  281  git status
  282  git merge master
  283  git status
  284  git status
  285  git add .
  286  git commit -m "final commit"


