## Configuration

Global configuration stored under ~/.gitconfig. Local configuration stored under .git/config. Can edit with a text editor.
``bash
 git config --global user.name "Erika Munoz" 
 git config --global user.email "e.munoz.torres@gmail.com" 
    
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

First view the status to see where things are at

```bash
git status
```

Add the changes you want in the next version (the `-p` option asks you change by change and is not required to just add everything)

```bash
git add -p $file
```

If you want to remove a file

```bash
git rm $file
```

# Save the next version

To save the next version run

```bash
git commit
```

For a log message, describe why you made the change, not what change you made as the computer can tell you the latter but not the former. Make the first line a brief oneline overview.
# Viewing changes

You can view all the log messages going back to the start with (the `--graph` options draws a pretty graph and `--oneline` just displays the first line of each message)

```bash
git log
```
