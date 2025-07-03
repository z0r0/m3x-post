# m3x-post
M3X Post processor for use in freecad.

# Updates

- Replace all instances of "linuxcnc" with "m3x"
- change mist coolant on command from M7 to M8
- Add speed range set instruction to tool change steps 
    TODO: (is there a way to add error checking on this?)
- add commands to pre- and post-ambles that appeared in EPS generated file
- Add {gcode += linenumber() + "%\n"} lines to put in start and end "%"
- Change "CORNER_MAX" to reflect actual work envelope
- Add coolant off (M9) to tool change spindle stop line
- Add move to G59 tool change position sequence to tool change

# TODO


