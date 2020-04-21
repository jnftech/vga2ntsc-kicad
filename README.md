# RetroTINK VGA2NTSC - KiCad Respin

This is a modified version of Mike Chi's VGA2NTSC v1.1.
The first goal was to convert the original Altium source files to KiCad - a free and open source tool - as not everyone has access to Altium. Secondly, most footprints have been swapped to make the board more DIY friendly - for example swapping 0402 components (difficult to solder by hand) with 0805 or larger.

![](Images/VGA2NTSCv11-jnftech-20200420%20top.svg)

### Goals:
Convert original Altium project to KiCad

Use 0805 footprints instead of smaller packages

Keep location of jacks and mounting holes in the same locations

Keep circuit identical to original schematics

Adjust vertical board size slightly to fit within 100x100mm size limit for cheap boards with many popular PCB fabs

Add a footprint for a DC barrel jack instead of USB power (either-or can be used in the same spot). Warning has been added to the board denoting 5V power only

Modified power distribution rail using bottom layer of board

Relocated clock section to minimize routing near other signals or underneath video amp

Minimized the use of vias for signal traces where possible.

### Tools used for conversion:
Altium2Kicad https://github.com/thesourcerer8/altium2kicad
Tracespace View (conversion of original Gerbers to SVG for reference and silkscreen adaptations - Alitum2Kicad doesn’t translate original fonts/graphics) https://tracespace.io/view/
KiCad 5.1.5 https://www.kicad-pcb.org/
Inkscape https://inkscape.org/

<img align="center" src="Images/smVGA2NTSCv11-jnftech-20200420%20Top.jpg">
<img align="center" src="Images/smVGA2NTSCv11-jnftech-20200420%20Side.jpg">
<img align="center" src="Images/smVGA2NTSCv11-jnftech-20200420%20Side%202.jpg">

This derivative work maintains the same source license as the original board.
https://www.retrotink.com/post/vga2ntsc-released

### “Mike Chi” License:
(From https://www.retrotink.com/post/vga2ntsc-released)

License
The materials are released under the terms below. I don't have time for pedantic nonsense or legal theory and like to keep things simple. I call this the 'Mike Chi' license.

*For each project, at my sole discretion, I may release whatever sources, to whatever level of abstraction, that I deem appropriate. Additional information/materials may be released on a scheduled determined at my sole discretion.

*You may modify, use or adapt any or all portions of the released material for any purpose you wish, including sale.

*The exception is that the files may not be used for commercial activities by entities, determined at my sole discretion, that have a history of violating intellectual property rights or licenses.

*If these materials were helpful and/or of use to you, I only ask that you provide some form of acknowledgment that you feel is fair.

*I'd also love to hear about how you're using it!

*If you re-distribute the material in a substantially unaltered form, please include this notice.

*NO WARRANTY EXPRESSED OR IMPLIED. WE TAKE ABSOLUTELY NO RESPONSIBILITY FOR WHAT MAY OCCUR FROM USAGE OF THE FILES.

*WE CANNOT AND WILL NOT OFFER ANY SUPPORT FOR THE USAGE OF THE FILES. IF YOU DO NOT AGREE WITH THESE TERMS THEN DO NOT USE ANY OF THE MATERIALS AND DON'T COMPLAIN.

https://www.retrotink.com/

