# gould-k20

**The probe is currently untested**

This is my project to create a reproduction state mode probe for the Gould K20 logic analyzer and document the unit.

I did not get any probes with the unit, so I had to create my own one from scratch. 
The probe contains logic to route the three clock inputs to any combination of the three clocks on the analyzer. They can also be inverted and ORred together. All this is configured from the unit itself in the menu pictured in menu.jpg, and sent to a pair of shift registers in the probe. 

The probe connects to the main unit with a 34-pin ribbon cable. I use a PC floppy cable from which I removed the twist. 

The probe should work just like the original state mode probe, but I cannot be sure as I don't know anything about the original one.
The machine also came with an 8-channel timing mode probe. From what I understand, it had a configurable clock generator inside and thus would be quite difficult to recreate. 

The directory "logicanalyzer" contains the KiCad project for the probe. 
The directort "pictures" contains detailed pictures of the unit.
