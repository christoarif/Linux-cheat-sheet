PyCharm do not have shortcut to open the app from current working directory like in vscode (vscode . will directly open the project in the code editor). 

However in the terminal we can do:
   ```bash
   open -b com.jetbrains.pycharm <file>
```
Therefore we can use alias and add it to  ~/.zshrc or ~/.bash_rc

  ```bash
alias pycharm='open -b com.jetbrains.pycharm'
```	

Now everytime we run 

```bash
pycharm .
```

It will open the cwd in pycharm! 

