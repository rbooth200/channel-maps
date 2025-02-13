# channel-maps
A simple code for computing channels maps for line emission from thin surfaces in discs.


A note about high inclinations
------------------------------

When imaging discs at high inclinations, each line of sight can pass through the disc surface multiple times. The code then switches to a method of projecting a model disc before accounting for shadowing to avoid the need to ray-trace.

Everything can be foound in the Jupyter Notebook, `LineEmissionModel.ipynb`.
