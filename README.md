Hello, this is Tony!

-------------------------------------
#Git commands I used for Activity5:

>git checkout -b rebase
#Create an empty file c1.txt
>git add .
>git commit -m "Create c1.txt"

#Create an empty file c2.txt
>git add .
>git commit -m "Create c2.txt"
>git push -u origin rebase

>git checkout develop
#Create an empty file c3.txt
>git add .
>git commit -m "Create c3.txt"

#Create an empty file c4.txt
>git add .
>git commit -m "Create c4.txt"

>git rebase rebase
>git rebase -i HEAD~4 #This is to reorder the git log history(top->down) from c4,c3,c2,c1 to c1,c2,c3,c4
>git push

