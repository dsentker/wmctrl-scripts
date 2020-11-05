# wmctrl-scripts

Move windows to a predefined location. Perfect for a setup with a wide monitor (3280x1080) and the laptop (1920x1080) on the right side.

## Usage

### Monitor Setup Schema:

```
    1920x1080  
      |
[   ][ ]
  ^   
  |   
  |
1920x1080
```

### win1
```
[X  ][ ]
```

### win2
```
[ XX][ ]
```

### win3
```
[   ][X]
```

### win4
```
[ X ][ ]
```

### Bind to Shortcuts
Go to system control center, Workspace -> Own Shortcuts and add  keyboard shortcuts for the scripts and a path to one of the shell script, e.g.
```
gnome-terminal -e "bash /home/dsentker/win1"
```


## TODO
If no window is focussed, the background is moving around. Thats pretty bad :(
