### Git Commands
- git config --global user.name "shivajid"
- git config --global user.email "shivaji@aurius.io"
- git config --list
- git init
- git add .
- git commit -m "message"
- git log --oneline
- git checkout <branchname> <filename>
- git reset HEAD <filename> 
- git checkout -- <filename>
- git remote add origin <ssh orgiin repo>
- git push -u origin master

### SSH Setup
- ssh -vT git@github.com
- ssh-add -l -E sha256
- ssh-keygen -t ed25519 -C "shivaji@aurius.io"
- eval "$(ssh-agent -s)"
- open ~/.ssh/config
- touch ~/.ssh/config
- vi ~/.ssh/config
-  ssh-add -K ~/.ssh/id_ed25519
-  pbcopy < ~/.ssh/id_ed25519.pub
-  -- Add keys to the Git repo

