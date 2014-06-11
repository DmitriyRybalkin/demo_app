# Ruby on Rails Tutorial: demo application
This is the demo application for
[*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/)
by [Michael Hartl](http://michaelhartl.com/).

# Step by step instruction to commmit to git:

$ git checkout -b modify-README

$ git branch

$ git mv README.rdoc README.md

$ subl README.md

$ git status

$ git commit -a -m "Improve the README file"

$ git checkout master

merge branch with master
$ git merge modify-README

delete branch
$ git branch -d modify-README

# For illustration only; don't do this unless you mess up a branch
$
 git checkout -b topic-branch
$
 <really screw up the branch>
$
 git add .
$
 git commit -a -m "Major screw up"
$
 git checkout master
$
 git branch -D topic-branch

commit to GitHub
$ git push
