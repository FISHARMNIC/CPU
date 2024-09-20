# Nico8 CPU
### An 8bit computer built in Logisim that features
* All of the basic things like registers, r/w to RAM, jumps, moving data, ALU operations, etc.
* Mulitple memory references per instruction
* 16bit register pairs for mathematical operations
* Interrupts
* IO ports
* Segmentation

# Documentation [here](https://docs.google.com/document/d/1zHQLODf5kYBa-Lo_Y2UcSC72ngJ54vJQ80xLCT8P8R8/edit?usp=sharing)

![pic](https://github.com/user-attachments/assets/6fe64c12-ffa3-4dee-9efc-b6a63312b0ae)


# How to Run
* Download all `.circ` files
* Load CPU.circ into logisim
* Example programs (load into PROGRAM RAM):
  * `interrupt.bin` loads r2 with the joystick when there is an interrupt
  * `display_joy.bin` Puts the joystick data on the display when there is an interrupt
