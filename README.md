```
git remote add oh-my-zsh git@github.com:robbyrussell/oh-my-zsh.git
git fetch oh-my-zsh
git subtree add --prefix=oh-my-zsh/ oh-my-zsh master
git subtree pull --prefix=oh-my-zsh/ --squash oh-my-zsh master
```
