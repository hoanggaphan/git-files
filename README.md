# remove specific file from git cache
  git rm --cached filename

# remove all files from git cache
  git rm -r --cached .
  git add .
  git commit -m ".gitignore is now working"

# show url is connecting
  git remote -v

# set the new URL (for example, git@github.com:User/project-new.git)
  git remote set-url origin git@github.com:User/project-new.git
  
# Undo last commit
  git reset
  + --soft HEAD~1: back to staging
  + (default) --mixed HEAD~1: back to working tree
  + --hard HEAD~1: back to the beginning, working tree clean

# show log
  git log
  git log --oneline (-n3)
