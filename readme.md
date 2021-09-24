## Git basis command

git status --> check the current status 
touch readme.md 
git add .  --> stage readme.md 
git commit --> commit changes on master / creates master branch 
git branch devbranch --> create branch devbranch , with current state of master 
git checkout devbranch --> change to devbrach 

checkout to master and make some changes and commit and switch back to devbranch 
git merge master --> syncs changes made to master to devbranch 

#Below 2 steps are like creating PR 
git checkout master 
git merge devbranch 

#Add remote 
git remote add origin https://github.com/prashant887/gitCommandsLearn.git --> here origin means name given to remote repo url 

 git push origin master --> add master branch details to remote 

git checkout devbranch and git merge master 

modfify file 

git push origin devbranch
