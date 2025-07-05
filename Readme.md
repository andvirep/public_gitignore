

# Репозиторий для копипасты .gitignore между проектами

просто скопируй команду в терминале с положением к корне проекта
```
git fetch git@gitlab.com:and_me_group_submodules/public_gitignore.git main:public_gitignore
git checkout public_gitignore -- .gitignore
git commit -m "grabbed .gitignore from git@gitlab.com:and_me_group_submodules/public_gitignore.git"
git push
```