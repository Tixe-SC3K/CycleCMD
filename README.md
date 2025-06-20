# how to use:
enter the commands into the first field as depicted below, the rest is explained in the page

```
(COMMAND SHORTCUT NAME HERE) | (ACTUAL COMMAND HERE)
Toggle noclip | noclip
```

# installing command pallets:
1. make your pallet and then generate and download it, give it a recognisible name
2. open your games files and find the cfg folder, for garrys mod this is in "GarrysMod/garrysmod/cfg/" and place it there, if there are multiple put it in all of them
3. open the game and load a map, then open the console and type ```exec``` followed by the name of the of your file, if you did it correctly it should let you autocomplete
4. use the buttons you configured to change modes and run commands
5 (optional). if you dont want to run the ```exec``` command every time you load in you can put the ```exec``` command in autoexec.cfg to run it automatically

# trivia
as far as i know im the first person who came up with this, made it and published it
the first version of this command pallet was a handwritten CFG file and quickly evolved into something more advanced, you can see this below:
```
alias makezombie "ent_create monster_zombie"
alias makesci "ent_create monster_scientist"
alias mode_1 "say CURRENT MODE: spawn zombie ;bind k makezombie; bind x mode_2"
alias mode_2 "say CURRENT MODE: spawn scientist; bind k makesci; bind x mode_3"
alias mode_3 "say CURRENT MODE: toggle noclip; bind k noclip; bind x mode_1"
bind x mode_1
```
this works in HL:S and HL:S DM
