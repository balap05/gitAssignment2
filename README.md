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
