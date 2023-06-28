# PicoDAW
A portable music sequencer and sampler based on Raspberry Pi Pico.  

WORK IN PROGRESS. 

I am just now populating the board and attempting to bring it up. 

There's no software yet! Also, I'm hoping that the SDIO SD Card interface is fast enough to stream
some audio tracks, since the Pico only has around 264KB or RAM. :D  We'll see.

Let's have an animated GIF on this page like its 1995!!

![LCD bring-up](https://github.com/caiannello/PicoDAW/blob/main/hardware/lcd_bringup.jpg)

![top](https://github.com/caiannello/PicoDAW/blob/main/hardware/WIP_Top.jpg)
![bottom](https://github.com/caiannello/PicoDAW/blob/main/hardware/WIP_Bottom.jpg)

Velocity Sensitivity Note:

The keyswitches are quite clicky. They are HONYONE PB86 with integrated LED. Because the switches are SPDT Single-Pole-Double-Throw,
there is a possibility of timing the switch's break-before-make to get velocity information.  

That's why both throws on each switch are connected in the key matrix. 102 tiny little diodes.
During testing though, the clicky-ness of the keys causes this feature to not work very well. 

I tried anneling the switch's spring with heat, but that was a fail. 

Maybe someday I'll find some more suitable SPDT switches, but at least these ones look really cool!

![schematic](https://github.com/caiannello/PicoDAW/blob/main/hardware/pico_daw_schematic_v0.1.png)
![layout](https://github.com/caiannello/PicoDAW/blob/main/hardware/pico_daw_layout_v0.1.png)

Let's have an animated GIF on this page like its 1995!!

![blinky](https://github.com/caiannello/PicoDAW/blob/main/hardware/pico_daw_leds.gif)