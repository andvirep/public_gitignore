# Repo for copypasta .gitignore in projects

copy and paste command in terminal 

via ssh
```
git fetch git@gitlab.com:and_me_group_submodules/public_gitignore.git main:public_gitignore
git checkout public_gitignore -- .gitignore
git commit -m "grabbed .gitignore from public_gitignore repo"
git push
```

via https
```
git fetch https://gitlab.com/and_me_group_submodules/public_gitignore.git
git checkout public_gitignore -- .gitignore
git commit -m "grabbed .gitignore from public_gitignore repo"
git push
```

