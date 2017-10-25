# LISA17 Demo

### File system
Let’s take a look at the filesystem: 
```
ls /
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
