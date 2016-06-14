## Configuration

Global configuration stored under ~/.gitconfig. Local configuration stored under .git/config. Can edit with a text editor.
``bash
 git config --global user.name "Tyson Whitehead" 
 git config --global user.email "twhitehead@gmail.com" 

```bash
 git config --global color.ui auto 
```
```bash
 git config --global core.edit vim
```
## Initialization
Creates the .git directory. To undo `rm-r .git`
```bash
mkdir $folder
cd $folder
git init
```

