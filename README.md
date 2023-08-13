<h1 align="left">CB34S</h1>

CB34S is a 34 key column-staggered choc unibody keyboard that has wireless capabilities with the Nice!Nano and supports a Nice!View display.

***

## Picture

![CB34S picture final build](/Images/CB34S_Built.jpg)

***

## PCB

If you like to get a PCB to build your own CB34S you'll find the KiCad source files and a Gerber file [here](/PCB/).

![CB34S picture pcb](/Images/CB34S_PCB.jpg)
***

### BOM

For a complete build you'll additionally need the following components:
- 34x SMD diodes (SOD-123)
- 34x Kailh Choc Hotswap Sockets
- 34x Kailh Choc V1 Switches
- 1x Nice!Nano
- 2× Pair of female headers for the N!N
- (optional) 1x Nice!View
- (optional) 1x Lipo battery (301230)
- (optional) 1x Power switch (MSK 12C02)
- (optional) 1x Reset switch (B3U-1000P(M))

***

## FIRMWARE

CB34S runs on ZMK. To modify and compile your own keymap you can clone the dedicated [ZMK config repository](https://github.com/bubbleology/zmk-config-cb34s).

***

## CREDITS

I've been on the lookout for a unibody keyboard for quite sometime but haven't found one that has all the features I was looking for:
- Choc V1 spacing
- Hotswap support
- Wireless support with an on/off switch
- Face down MCU mounting
- 34 keys columnar stagger
- Only a slight angle but more space inbetween the halves

An established community member in the ergo mechanical keyboard scene by the name of [Mabroum](https://github.com/AlaaSaadAbdo) heard of my unsuccessful search and took it upon himself to create a board that fullfills all my criterias. He did it in such a record speed that it encouraged me to also try it myself and again delve into the wonderful but for me still daunting tool of [Ergogen](https://github.com/ergogen/ergogen) and KiCad. The board above is the result of that. 

I couldn't have done it without the help and inspiration of the lovely keyboard community so many thanks goes out to them. I would also like to thank some individuals that made it all possible

- [Mabroum](https://github.com/AlaaSaadAbdo) - for making me a board from scratch and encouraging me to make my own
- [Marco "Bob"](https://github.com/GroooveBob) - for correctly guessing my firmware error
- [Kilipan "Apfel"](https://github.com/kilipan) - for correctly confirming my firmware error 
- [FlatFootFox](https://twitter.com/flatfootfox) - for the wonderful introduction/guide to Ergogen
- [duckyb "Kyek"](https://github.com/duckyb) - for the footprints
***

## LICENSING
<picture align="left">
  <img alt="Creative Commons (4.0 International License)" src="https://licensebuttons.net/l/by-nc-sa/4.0/88x31.png">
</picture>

This work is licensed under a
Creative Commons (4.0 International License)
Attribution—Noncommercial—Share Alike

- ✖ | Sharing without ATTRIBUTION
- ✔ | Remix Culture allowed
- ✖ | Commercial Use
- ✖ | Free Cultural Works
- ✖ | Meets Open Definition 