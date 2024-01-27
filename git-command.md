
1-ssh-keygen -t ed25519 -C "gillianramirez0@gmail.com"
2-Copy the public file to github.com ssh key setting by using ew key
3-eval $(ssh-agent)
4-ssh-add ~/.ssh/fileName
5-git clone git-repository-url
6-git status
7-git configure --global. user.name "GillianRamirez"
8-git configure --globa'. user.email "gillianramirez0@gmail.com"
9-git status
10-touch index.html (or create index.html using visual studio code)
11-Add some HTML to index.html or keep it empty
12-git status (Now index.html will show in red to messafe it's untracked)
13-git add index.html
14-git status (after gi add index.html it starts showing in green means it's tracked in git local storage area)
15-git commit -m "a message about your changes"
16-git push

git push command will push your local commit (tracked changes) to your github.com/repository
