# Hugo Moran's dotfiles
Personal dotfiles and useful commands/scripts. This repo is under construction since I'm still customizing my distro.

## Some useful commands
Sets the night light temperature in a Ubuntu distro running Gnome.

`gsettings set org.gnome.settings-daemon.plugins.color night-light-temperature 5500`

Finds the 10 most used words in your bash history (handy for creating useful aliases).

`sed -e 's/\s/\n/g' < ~/.bash_history | sort | uniq -c | sort -nr | head  -10`

Search a file in the system using regex.

`locate --regex '(vimrc)$'`
