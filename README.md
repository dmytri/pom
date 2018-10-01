# POM

simple i3 friendly bash pomodro

## example .i3blocks

[pom]
color=#FF1122
command=/path/to/pom show
interval=once
signal=10
separator=true

## example .config/i3/config

bindsym $mod+period exec --no-startup-id /path/to/pom
bindsym $mod+Shift+period exec --no-startup-id /path/to/pom pause

# DEPENDENCIES

zenity

