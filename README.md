# cara make git
git pull https://github.com/*username*/*repository*.git master
git init
git add .
git commit -m "update"
git remote -v
git remote add origin https://username:password@github.com/username/repository.git
git push origin master
git ftp init --user username --passwd password ftp://domain.com/public_html/folder
git ftp push --user username --passwd password ftp://domain.com/public_html/folder

git status
git branch
git remote set-url origin https://username:password@github.com/username/repository.git
