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
