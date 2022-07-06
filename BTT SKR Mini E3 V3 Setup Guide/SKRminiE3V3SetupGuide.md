>**BTT SKR Mini E3 V3 Setup gude **

# index 

* index

# Notes about wiring 
Although our intention is to keep the BTT SKR Mini E3 V3 Setup Guide as simple and easy to follow as possible. However there may be an odd cable or connector that needs to be rewired. But worry not. As more often than not, it is a simple case of pushing the metal retaining pins down with a tool or pin. Followed by pulling out the cable. Then with the cable removed, lift the pushed down pin backup with a fingernail. Simply reposition the cables as needed and push back in.
Whether you need to rewire or not is dependent on each printer and its components.

# Power Supply Jumpers (power source options)
By default the BTT SKR Mini E3 V3 is set to be powered via the Power Supply Unit. But if you wish to power the board via USB for means of testing. Then place a jumper over the SW_USB header pins (Between the RESET button and USB port). BUT don’t forget to remove it after.
A point of note, powering the SKR Mini E3 V3 via USB is not a replacement method of powering the board. Instead, it is a means to test the board and firmware settings before installing the mainboard.

[IMAGE POWER JUMPER...]

# Power Connections
[image P_COnenction_pinout]

When upgrading any mainboard on a 3D printer, the wiring sequence of the cables may differ from the original mainboard. Consequentially, the polarity of the wiring must always be checked and double-checked.
But what do I mean by polarity? Moreover, the + (red) cable goes to the positive connections (+) and the – (black) wire goes to the negative or ground connection (-).
If handling the electrics worries you. Then fear not, follow along step by step, and you will be fine.

> DC IN 

[IMAGE_DC-IN]

Firstly the BTT SKR Mini E3 V3 needs power from the Power Supply Unit (PSU) to function. Firstly take a red Positive (V+) cable from the PSU and insert it into the left-hand side of the DCIN connector. Then take a black Negative (V-) wire from the PSU and insert it into the right-hand side of the DCIN connector.

[IMAGE_DC-IN_PInout]

# Heated Bed
[IMAGE HB]

Importantly the wire orientation/polarity for the heated bed is different from the DCIN connection. Moreover, the Red Positive (+) cable inserts on the right-hand side of the HB connector, while the Black Negative (-) cable inserts into the left-hand side.
Some will argue polarity doesn’t matter on heated beds. Yet on many beds, it is critical. Especially those heated beds with LED’s attached on the underside, as these indicate the power is being received and flicker when controlled by PID tuning. Consequentially most heated beds have positive and negative traces and contacts marked on them.

[IMAGE_HB-PINOUT]

# Heating Element (Hotend)

[Image-HotEnd]

For the most part, heating elements on 3D printers are not polarity sensitive and are insertable either way around. But if the cables have markings on them, check the manufactures documentation for references to polarity.