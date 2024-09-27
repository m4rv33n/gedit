### [Gedit](https://wiki.gnome.org/Apps/Gedit)

#### Install

1. Download the raw file:

    wget https://raw.githubusercontent.com/dracula/gedit/master/dracula.xml

> If your version of Gedit is 46 or newer, use the following command instead:
>
>   wget https://raw.githubusercontent.com/dracula/gedit/master/dracula-46.xml -O dracula.xml

2. Move the file to gedit style's folder:

    mv dracula.xml $HOME/.local/share/gedit/styles/

3. Activate in Gedit's preferences dialog


If it doesn't show up in the dialog:
In some distributions it has to be moved to a different place

    cp $HOME/.local/share/gedit/styles/dracula.xml /usr/share/libgedit-gtksourceview-300/styles/

you'll need to to perform that action as root though (sudo)! 
