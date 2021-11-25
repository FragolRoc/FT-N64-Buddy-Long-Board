# FT-N64-Buddy-Long-Board
A breakout board that offers an alternative to soldering wire directly to vias. This board can also be used to repair burnt vias/pads.

# PCB Fabrication
<b>This PCB has not been fabricated or tested.</b> 

If you decide to make this board for yourself, let me know of any feedback. Enjoy!<br>

Board Thickness: 0.8mm<br>
Castellated Holes: Optional

# Installation
The simple N64 RGB mod only works on systems with the VDC-NUS/VDC-NUS A encoder. Consoles with a serial number that begins with "NS1" will likely have the correct encoder. However, if the console has been shell swapped there is a chance the main board will be the incorrect version. Always check to be sure!

The Long Board solders to R10, R9, R8, and R16 on the underside of the main board (see pictures). Some consoles have an intact sync circuit around R16. If your console has this circuit, it is recommended you remove the components in that area. Remove Q1, C109, R16, and R15.

The native sync circuit puts out improperly spec'd sync levels that may be damaging to modern TV's and scalers. The Long Board forces you to use the restored, and properly adjusted, sync signal from the RGB mod. The Long Board cannot be install properly if those components are not removed.

After the components are removed, line up the board and solder the castellated holes to the vias making sure not to bridge or short any of the connections. That's it, you're done! Install your favorite N64 RGB mod and attach wires to the proper pads. Have fun with your blurry mess of a console!
