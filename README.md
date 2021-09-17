Hello, this is Tony!

-------------------------------------
#Git commands I used for Activity5:

git checkout -b rebase
#Create an empty file c1.txt
git add .
git commit -m "Create c1.txt"

#Create an empty file c2.txt
git add .
git commit -m "Create c2.txt"

git checkout develop
#Create an empty file c3.txt
git add .
git commit -m "Create c3.txt"

#Create an empty file c4.txt
git add .
git commit -m "Create c4.txt"
git push

git checkout rebase
git rebase develop
git push -u origin rebase

