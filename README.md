# MegaAV
Sega Genesis audio and video bypass, incorporating a new Mega Amp 3 design that restores mono audio, along with native composite and S-video generation.

Attribution: Credit where Credit's due

Timeline of events:
ACE9921 & Villhed94 developed the original Mega Amp 1.0. Inception for a mod board that combines the Mega Amp with an RGB video amplifier was Bob from RetroRGB's idea. Rene from db Electronics designed the first build. Tienfeng designed the second with a modified version of the original Mega Amp, which we're calling the Mega Amp 2.0. Jose Cruz helped with testing. That became the Triple bypass v2.

Zaxour forked the 3BPv2 to support Composite restore with the 3BPV2+ and is continuing development of a Quadruple Bypass that will support S-video.

For most of the 6 years between the Mega Amp 2.0 and 3.0, Ace was pretty much developing alone. Villahed94, eep386, and ACE9921 were throwing ideas around, but nobody except Ace was doing anything. I want to make it clear that the Maga Amp 3 is it's own standalone thing and that the Mega Audio is NOT to be confused with it. ACE is not associated with the MegaAV. 

RIP-Felix incepted the idea of restoring Mono Audio for RF compatibility. RGBeter incepted the idea of recreating Composite video using a modern encoder, taking the opportunity to fix the luma trap. At that point it was still a derivative work of the 3BPV2+. Villhed94 agreed to join the MegaAV team to finish and implement the Mega Audio for both inboard and MegaAV mod board installations. The three of us tested and refined finalized values, and implemented the designs together. Both RIP-Felix and RGBeter designed the MegaAV PCB. The only part of the circuit that has remained unchanged is the THS7374 RGB amplifier. 

So the Mega AV is actually 2 mods in one. The Mega Video developed by RIP-Felix, RGBeter, and Villahed94. Mega Audio was developed with help from Villihed94 and others along the way. Villahed, RGBeter and RIP-Felix dialed in PSG and FM resistor values to dial in MD fourier. That said I (RIP-Felix) want to thank and credit everyone involved in these mods regardless of how much of their contributions made it into the current version of Mega AV. It's been a collective effort and everyone should be credited for the hard work they've put in! Massive thanks to all of you!
 
NOTEs:
- Fujitsu ASICs, 315-5708-01 and 315-5660-01 needed an additional pulldown resistor. Instead of bridging jumper C, solder a 200Ohm 1% or lower tolerance resistor to it. May apply to Model 1 VA7 through Model 2 VA1.8. The Suffix -01 indicates it's a Fujitsu Chip. This DOES NOT apply to chips LACKING the suffix "-01".
- Adds a ZIF connector for a future ribbon cable design to greatly simplify installation

(instructions pending, same as 3bp install except composite and mono must also be isolated from the din, and the subcarrier line must be routed to the MegaAV)
### When routing the subcarrier line, make sure it's a shielded coaxial cable or twisted pair to prevent jailbars

Instructions pending:
## Model 1 Installation Guides
[Model 1 - VA1-VA6]
[Model 1 - VA7]
## Model 2 Installation Guides
[Model 2 - VA0-1.8]
[Model 2 - VA2]
[Model 2 - VA2.3] (needed)
[Model 2 - VA3]
[Model 2 - VA4]

## Model 3 Installation Guides
[Model 3 - VA1] (needed)
[Model 3 - VA2] (needed)

## Sega CDX
[CDX]

## Other
[Other forms of Genesis]
