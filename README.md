# Nico8 CPU
### An 8bit computer built in Logisim that features
* All of the basic things like registers, r/w to RAM, jumps, moving data, ALU operations, etc.
* 16bit register pairs for mathematical operations
* Interrupts
* IO ports

# Documentation [here](https://docs.google.com/document/d/1zHQLODf5kYBa-Lo_Y2UcSC72ngJ54vJQ80xLCT8P8R8/edit?usp=sharing)

<img width="970" alt="Screen Shot 2024-06-21 at 9 59 56 AM" src="https://github.com/FISHARMNIC/CPU/assets/73864341/d0a4aa3b-3daa-406f-abcc-45b0cf61d57b">

# How to Run
* Download all `.circ` files
* Load CPU.circ into logisim
* Example programs (load into PROGRAM RAM):
  * `interrupt.bin` loads r2 with the joystick when there is an interrupt
  * `display_joy.bin` Puts the joystick data on the display when there is an interrupt
