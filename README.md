# git-corso-21
Started with GIT

# Configuration 
git config

# Clone repository
git clone

# Init repository
git init

# Remote repo
git remote ( add, --set-url, rm ecc..)

# Push - pull
git push
git pull

# Commands base
git add ( index.html, . )  [ . = TUTTI ]
git commit -m "message"
git push

# Stash
git stash list
git stash save
git stash apply 
...

# Reset
git reset
git reset --soft
git reset --hard

# Revert
git revert

# Comando per spostarmi da una branch ad un'altra
git checkout nome_branch || git switch nome_branch

# Comando per creare una branch
git checkout -b nome_branch ( crea la branch, mi porta dentro essa )
git branch nome_branch ( crea la branch )

# Comando per eliminare una branch
git branch -D nome_branch ( locale )
git push --delete origin nome_branch ( remoto )

# Comando per modificare una branch
git branch -m nome_nuovo_branch
git branch -m nome_vecchio_branch nome_nuovo_branch

# Comando per mergiare una branch in un'altra
git merge nome_branch
git push -f

# Comando per eseguire il rebase
git rebase nome_branch
git rebase --continue || git rebase --abort
git push -f

# Comando per eseguire il cherry-pick
git cherry-pick ID_COMMIT
git push -f

# Tips
--set-upstream === -u


