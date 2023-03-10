## Flashing Process

First, unplug your lulu PCB from the computer.

On the back of your PCB you will notice a sliding switch around where the controller would sit on the other side. This switch has two states, Default and Boot. When you open your PCB, the switch should be in the default position. The switch’s default position is outlined with silkscreen.

In order to put the PCB into boot mode, you must (while the PCB is unplugged) put the switch into Boot mode. When the switch is in Boot mode you will notice the silkscreen outline indicating it’s Default position.

Check the diagrams below to see these two states, Default and Boot.


[picture showing switch on the downward position, as relative to button directly to the left of it]

With the PCB in Boot mode, you can plug it back into your computer.

After a few moments, your PCB should appear as a Drive on your computer named "RPI-RP2.” After you locate this drive, before doing anything else, put your PCB back into Default mode. The drive will NOT disappear.

With the Drive "RPI-RP2" located on your computer AND the Switch reset to it’s Default position you can drag and drop the Uf2 files onto the drive (onto the PCB). When it is done transferring the file, your PCB will reboot. Because you put the switch back to it’s Default position, when the board restarts it will no longer be in Boot mode and will be good to go.

If you’ve successfully transferred the Uf2 file, you should see the LEDs turn back on, and a new ‘LULU’ drive mount to your computer. If the transfer fails for any reason, simply repeat the steps, starting back from the beginning with the PCB unplugged from your computer.