# hhy

…or create a new repository on the command line

echo "# hhy" >> README.md

git init

git add README.md

git commit -m "first commit"

git branch -M master

git remote add origin https://github.com/haiyunsky/hhy.git

git push -u origin master
                
…or push an existing repository from the command line

git remote add origin https://github.com/haiyunsky/hhy.git

git branch -M master

git push -u origin master

…or import code from another repository

You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

------

git pull

-----------------

git branch mybranch

git checkout mybranch

echo "# test branch1" >> test_branch.txt

git push --set-upstream origin mybranch

git add .

git commit -m "add a branch and file"

git push

-------

git checkout master

git pull

git merge mybranch

git push


