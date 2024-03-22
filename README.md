<h2 align="center">GTK_icon Themes</h2>
A list of curated icon themes which make your Gnome Desktop look amazing!
<br>

 <h4>Apt based Distros</h4>
 
``` bash
sudo apt install gnome-tweaks
```
<h4>Pacman Based Distros</h4>

``` bash
sudo pacman -S gnome-tweaks
```

# Installation
Start by creating the directories where the icon themes will be stored.
``` bash
cd ~/
mkdir .icons && cd .icons
```
Proceed to clone the github repo to the current directory.
``` bash
git clone https://github.com/rohansharma-developer/GTK_icons.git
```
Copy all the contents of the folder to `.themes`
``` bash
cp -r ./GTK_icons/* ./
```
# Usage
Open `gnome-tweaks` from your app menu. Choose any theme of your choice. Enjoy!

