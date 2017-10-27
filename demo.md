# LISA17 Demo

### File system
Let’s take a look at the filesystem: 
```
ls /
```

Other basic commands:
```
vim
touch
ssh
```

### Check our hardware
What CPU are we using? 
```
less /proc/cpuinfo
```

### Have some fun
Let’s run something fun: fortune (notice prompt to install)
Oh! Ok, let’s install fortune: 
```
sudo apt-get install fortune
```

Now lets try again: 
```
fortune
```

Let’s make this even more fun: 
```
sudo apt-get install cowsay
```

Let’s see what a bovine philosopher might say: 
```
fortune | cowsay
```

Shall we check the weather in Hobbiton? 
```
clear; curl -4 wttr.in/middle-earth
```

### Colors
```
cmatrix
```

Toilet is a good one...
```
toilet -f mono12 -F "hello lisa17!"
```

### x11 shit

```
sudo apt-get install x11-apps
echo 'export DISPLAY=:0' >> ~/.bashrc && . ~/.bashrc
sudo sed -i 's$<listen>.*</listen>$<listen>tcp:host=localhost,port=0</listen>$' /etc/dbus-1/session.conf
```

```
xeyes &
xclock &
xcalc &
sudo apt-get install xbill
PATH=$PATH:/usr/games
xbill &
```

### Fun
```
telnet towel.blinkenlights.nl
```
### gtk apps
```
sudo apt-get install gnome-calculator
gnome-calculator &
```

### blow shit up
sudo apt-get install xorg xubuntu-desktop
xfce4-session