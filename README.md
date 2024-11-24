# .config
I use this to share config around.

# Installation
Because your `.config` likely already has content in it, init an empty repo in your own `.config` and add this as a remote
```
cd $HOME/.config
git init .
git remote add https://github.com/ehharvey/.config
git pull origin main
git branch --set-upstream-to=origin/main
echo 'Done :)'
```
