### How to install conky on Khadas Vim2 ###

__open a terminal...__

```shell
$ sudo apt-get install conky-all -y
$ sudo apt-get install git -y
$ cd~/
$ git clone https://github.com/wSmithyeah/KhadasVim2conky.git
```

*** setup up autostart for it ***
+ use the menu
system<br/>
preferences<br/>
personal<br/>
startup applications<br/>
 
**add the following command line item to the list**

```shell
conky --font=/home/khadas/.config/conky/Arial.ttf --config /home/khadas/.config/conky/ConkyNew --pause=5
```

<img src="screenshot.png">

