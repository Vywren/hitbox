## Background

This is a collection of STL files I used to create my 3D-printed hitbox enclosure. The finished product looks like this:

![hitbox1](https://github.com/user-attachments/assets/1437a974-2694-491f-bec4-5ed376b029a6)

Please note that this hitbox is in a southpaw configuration, which is reversed from the default layout. If you prefer a standard hitbox layout, you'll need to use the "orthodox hitbox" STL file for the base.

## Required Materials

- **9x 30mm Screw-On Pushbuttons**
- **6x 23mm Screw-On Pushbuttons**
- **6x M3 x 55mm Screws and M3 Nuts**
  - Preferably with a countersunk head to avoid scratching your hands while playing
- **Neutrik USB Passthrough**
- **USB A Male to USB C or Micro USB Cable** (depending on your microcontroller)
  - 6 inches or longer, but probably no more than a foot
- **USB A Male to USB B Male Cable**
  - Dictates how far away the user can sit

## How to Assemble

1. Slice and print the STL file for the base and top panel in your desired orientation ("Orthodox" for a standard hitbox, "Reworked 1-Piece" for the southpaw version). These files are identical except for orientation. Note that you cannot simply reverse the file in the slicer due to the Neutrik passthrough screw positioning.
   
2. Screw all pushbuttons onto the top panel.

3. Connect the pushbuttons to the microcontroller using the appropriate diagram found [HERE](https://gp2040-ce.info/controller-build/wiring) to determine which pins to use.

4. Install the Neutrik passthrough on the base.

5. Connect the Neutrik passthrough to the microcontroller using the short USB cable.

6. Mount the Microcontroller (optional), it doesn't really make much of a difference

7. Connect the passthrough to a computer using the long USB cable.

8. Flash the appropriate UF2 file from the GP2040 project onto the microcontroller found [HERE](https://gp2040-ce.info/downloads/).

9. Confirm that all buttons work consistently using a controller-enabled app or an online controller tester.

11. Print 6 feet and use a strong binding agent like epoxy resin to attach a bolt to each feet.

12. Bolt the box together using the 6 screws and feet.

13. Enjoy your new hitbox!

More updates and possible redesigns to come.
