# Learnproject
cd /Desktop/project1

cd index.html

touch Product10

touch test.txt

git init

git status

git branch

git add .

git commit -am "Production10"

git status

git log --oneline

vi index.html

git branch -m master product 

git checkout -b integration product

git checkout -b hotfix product

git branch -b feature_1 integration

git branch -b feature_2 integration

touch styles.css

vi index.html

vi styles.css

clear

git status

git checkout feature_1

git add .

git commit -m "edited& added index"

vi test.txt -- create a change 

git  commit -am '' edited test.txt''

git checkout integration

git merge integration ( said already up to date )

git rebase integration ( already up to date )

git checkout feature_2

vi test.txt

git add .


cd /Desktop/project1

cd index.html

touch Product10

touch test.txt

git init

git status

git branch

git add .

git commit -am "Production10"

git status

git log --oneline

vi index.html

git branch -m master product 

git checkout -b integration product

git checkout -b hotfix product

git branch -b feature_1 integration

git branch -b feature_2 integration

touch test.txt

touch styles.css

vi index.html

vi styles.css

clear

git status

git checkout feature_1

git add .

git commit

git commit -m "edited& added index"

vi test.txt -- create a change 

git  commit -am '' req2: added feature 2 to test file"

git checkout integration

git merge feature_2

git log --oneline

git status

git checkout hotfix

git merge integration

git checkout production

git merge hotfix ( goes into nano asking for a commit message)

git checkout feature_1 ( for a new commit)

vi styles.css ( to adjust the file)

git commit -am "req04:added head,body,head"

git checkout integration

git merge feature_1 ( editor required merge message )

git checkout hotfix

git merge integration

git checkout production

git merge hotfix

git push origin production ( prompted username & password)

git pull

vi index.html (req5:added change 900 to index.html)

git checkout integration

git merge hotfix

git checkout production

git merge hotfix

git status  ( Your branch is ahead of 'origin/product' by 2 commits)

git push origin production.
