# set Path variable to identify GH CLI
## Step 1
```
Get-ChildItem "C:\Program Files\GitHub CLI"
setx PATH "$env:PATH;C:\Program Files\GitHub CLI"
```
## Step 2
Restart Power Shell Terminal

```
gh --version 

```
