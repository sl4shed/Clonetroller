# Clonetroller ([Makerworld](https://makerworld.com/en/models/1570441-clone-hero-guitar#profileId-1651626))
An open source, 3d printable guitar hero controller

# Assembly
3D print:
 - 5 frets
 - 1 fret plate
 - 1 rail
 - 1 neck plate
 - 1 body plate
 - 1 strum bar holder
 - 1 strum bar
 - 1 body
 - 1 neck

Buy:
 - 1 Raspberry Pi Pico 2
 - 7 Cherry MX switches
 - 40-ish M3x10 screws
 - 4 M2x10 screws
 - 2 meters of ethernet cable (to strip and obtain the wires from)

### step 1
Prepare 6 strands of wire that are about as long as the neck + body,
Place 5 Cherry MX style switches into the neck plate, solder one common ground wire to each one of them and solder one unique wire for every switch.
Optionally, crimp a connector at the end of the 6 cables.

### step 2
Prepare 3 strands of wire that are about as long as the body.
Place 2 Cherry MX switches into the strum bar holder, solder one common ground going around/below the strum bar and one unique wire for every switch.

### step 3:
find a GPIO input pin on the raspberry pi for each unique wire connected to the switches. For the ground wires use the square-shaped pins,
solder the wires to the raspberry pi (if you crimped a male connector to the neck switch wires, also crimp a female connector to the 6 wires going into the microcontroller)

### step 4:
Place the neck plate into the neck, put the wires through the hole at the end of the neck and screw in the neck plate

### step 5:
Connect the neck to the body using the rail - insert the rail into the neck and then slide the neck + rail into the body rail slot.
Screw in the 4 screws to secure the rail

### step 6:
Place the strum bar into the strum bar holder.
Place the strum bar holder above the 4 screw slots in the body and screw it in from the bottom.

### step 7:
place the neck plate on top of the neck and screw it in.

### step 8:
plug in the controller to your pc while holding down the BOOTSEL button on the Raspberry Pi Pico. Use [santroller](https://santroller.com/) to program the controller the way that you want it.

### step 9
place the body plate on top of the body and screw it in.

### great success, enjoy your controller!

