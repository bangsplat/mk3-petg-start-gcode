# mk3-petg-start-gcode
Custom start g-code for the Prusa i3 MK3/S for PETG filament that mimics the behavior of the Prusa Mini/+

Intended for use with the Prusa i3 MK3/S+ printing PETG, but may well work with other filament types.

When starting a print, extruder temperature is set to 170 C. This heats things up but not so much that plastic will ooze. Then the bed level leveling process is executed and the extruder moves to the extrusion priming start position before heating the extruder to the target profile temperature.

In PrusaSlicer, click on the Printer Settings tab, choose Custom G-code on the left, and replace the Start G-code.
