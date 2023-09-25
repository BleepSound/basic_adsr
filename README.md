# Basic ADSR

Basic ADSR based on René Schmitz [Fastest envelope in the West](https://www.schmitzbits.de/adsr.html). 

Four pots, one input, one output (just what you need).

On switch to change the time constant of the ADSR. I chose some arbitrary values for the capacitors in my case, but if you want different values, you can adjust them to your needs. 

Just change the values of **C8** and **C9**, which can be either polarized electrolytic or unpolarized capacitors. Just make sure you get the orientation right on the polarized ones.

You'll find the schematic of this module below: 

![basic ADSR schematic](documentation/image/Basic-ADSR--schematic.svg)

Regular build, I use ceramic capacitors but you can use film/polyester.

:warning: When building modules, always do it in this order (from smallest component to highest):
- diodes
- resistors
- DIP chips
- capacitors (film/ceramic)
- Transistors
- Electrolytic capacitors

For the next part, always place them without soldering them on: 
- jacks, pots and switches that go thought the front panel

Once placed, put in place the front panel, then fasten all components to it. Once this is done, you can solder them. 

![3D basic ADSR(front)](documentation/image/MS20-VCF-3D_top.png)

![3D basic ADSR(back)](documentation/image/MS20-VCF-3D_bottom.png)

![3D basic ADSR(iso)](documentation/image/MS20-VCF-3D_top30deg.png)

[See bom](documentation/bom/Basic-ADSR_V1.0--iBoM.html)
