# Repo for copypasta .gitignore to projects

copy and paste command in terminal 

via ssh
```
git fetch git@github.com:and-is-me/public_gitignore.git main:public_gitignore
git checkout public_gitignore -- .gitignore
git rm -r --cached .
git add .
git commit -m "grabbed .gitignore from public_gitignore repo"
git push
git remote remove public_gitignore
```

via https
```
git fetch https://github.com/and-is-me/public_gitignore.git main:public_gitignore
git checkout public_gitignore -- .gitignore
git rm -r --cached .
git add .
git commit -m "grabbed .gitignore from public_gitignore repo"
git push
git remote remove public_gitignore
```

