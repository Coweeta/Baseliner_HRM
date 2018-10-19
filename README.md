# Baseliner_HRM
Prototype version of Baseliner software adapted for heat ratio method sensors

Program creates a GUI for correcting zero-flow offsets for processed HRM sapflow data (raw data needs to be converted from temperature measurements to velocities)

data columns must be in the following order
column: contents
1: site indicator variable (numerical value, not used in processing
2: year
3: day year
4: time (hhmm) format, needs to be continuous with no gaps
5: vpd (kPa)
6: par or radiation (arbitrary units)
7-...: converted HRM velocities (arbitrary units)
