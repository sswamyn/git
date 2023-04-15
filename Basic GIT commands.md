### Basic GIT commands 

#### Start.. 

> clone a repo 
```
git clone https://github.com/sswamyn/git.git 
```
> Start a fresh repo _do not forget to check the .gitconfig is accurate_
```
git init
```

#### Commands to manage local repo 
> Check the status [ if used often, maybe an alias; ```st='git status' ```] <br>
``` git status ```

> Find the changes to a tracked file <br>
``` git diff ```

> Added all files in the current directory <br>
``` git add . ```

> Commit local changes <br>
``` git commit -a ``` <br>
Or commit previously stages changes 
``` git commit ```

#### Getting to the history 
> List all commits (starting with the newest) <br>
``` git log ``` <br> OR to list for a specific file <br>
``` git log -p <file> ```

#### Branching commands 
> List all branchs <br>
``` git branch ```<br> 
To checkout a particular branch (not the HEAD) <br>
``` git checkout <branch Name> ```










