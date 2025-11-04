## Creating new Repository

Creating new repository on the command line:

git init \
gitt add README.md or git add . \
git commit -m "message" -m "description" \
git remote add origin 'ssh link' \
git push origin master

### Branching

Create new branch: \
git checkout -b [name of the branch]

Switch between branches: \
git checkout [name of the branch]

Check existing branches: \
git branch

If I now change stuff here, it doesn't appear on the other branches, like the master branch. \
Push it to github using: \
git push -u origin feature-readme-instructions \
Then you can merge them on github.
