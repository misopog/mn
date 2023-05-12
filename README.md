# mn - a dead simple note-taking script

### installation

```
# first install fzy 
# sudo pacman -Syu fzy for arch
sudo curl -sL "https://raw.githubusercontent.com/misopog/mn/main/mn" -o "/usr/local/bin/mn"
sudo chmod 777 /usr/local/bin/mn
mkdir ~/notes # can be configured editing the script
```

### usage

the usage is dead simple, to create a note type `mn new`, to edit the note type `mn edit`, to remove the note type `mn rm`, to create a category type `mn newcategory`, the notes are written in markdown which syntax is really *really* simple

### transferring your notes

as simple as copying your notes folder to another folder

### uninstall

```
sudo rm /usr/local/bin/mn
sudo rm -r ~/notes
```
