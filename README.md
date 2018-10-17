# gitMastery
Tips and pointers in the right direction, courtesy of the internet


## Remove tracked files after creating/updating .gitignore
git rm -r --cached .
git add -A
git commit -am 'Removing ignored files'

