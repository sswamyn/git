##### Some handy alias for git

> Some common typos.. at least for me

```
alias ls='ls -alh'
alias cd..='cd ../'
alias cd...='cd ../..'
```

###### Git Specific 
```
ds='git diff --staged'
st='git status'
ci='git commit'
changes='git log -n -p --format-fuller'
undo='git clean -f -d'
unstage='git reset HEAD --'

lg="git log --graph --pretty=format:'%Cred%h%Creset -%C(yellow)%d%Creset %s %Cgreen(%cr) %C(bold blue)<%an>%Creset' --abbrev-commit"
	
```