# REU 2019

Some notes and resources

## Links

- [Git reference](https://jrebel.com/wp-content/uploads/2016/02/Git-Cheat-Sheet-pdf-v2.png)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Atom Editor](https://atom.io/)

## Git commands

```sh
# Clone (i.e. copy the repository).
git clone https://github.com/creinkin/REU2019

# If required, adding your username for commit purposes.
git config user.name "your username"

# If required, adding your email for commit purposes.
git config user.email "Your email"

# Adding all edited files.
git add .

# Adding a single file.
git add filename

# Commit "added files".
git commit -m "Commit message."

# Sync your code with github.com for any new changes.
git pull

# Publish your new code to github for the first time.
git push origin master

# Publish your code subsequent times.
git push
```

## vim commands to get by

### open new file or edit file.

```sh
vim path/to/file.extension
```

### Insert mode (i.e. edit file)

```text
i
```

### Commands in edit mode.

```text
Ctrl+U - Delete everything on the left of the cursor.
Ctrl+Shift+C - Copy selected text
Ctrl+Shift+V - Paste selected text
```

### Enter Command mode

```text
Esc then :
```

### Possible commands in 'command mode'.
```text
w - save file

wq - save file and exit

q - exit

q! - exit without saving

u - undo

/keyword - search the document for keyword (Use n or Shift+n to go to the next or previous word respectively).
```

***NOTE: When in doubt, press Esc***

---

## python virtual environments

- Used to create 'isolated Python environments'.
- Environments are contained in a folder.
- Environments can be created or discarded at any time without affecting your system.

### Create a new project folder and switch to it
```sh
mkdir project

cd project
```

### Create the virtual environment
```sh
python3 -m venv venv-name
```

# Activate your virtualenvironment
```sh
source venv-name/bin/activate
```

# When done
```sh
(venv-name)$ deactivate
```
