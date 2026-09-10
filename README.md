# DRAMmer
Simpe Arduino Mega 2560 shield for testing retro DRAMs, up to 20 pins, including 4116


## 4116 Power.
Only the 4116 needs -5 V and +12 V.
The +12 V needs about 35 mA when active, the -5 V is just the substrate bias at a few hundered μA at most.
For +12 V a MT3608 boost converter module or circuit would be good enough.
For -5 V a ICL7660, or a more modern IC, like the MAX860 can be used (the latter also has an /SHDN "enable" input).