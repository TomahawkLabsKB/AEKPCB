This is a work in progress.

This project intends to replace the orignal PCB of the Apple M3501 (Apple Extended Keyboard 2) utiizing a Pimoroni PGA2040, which is a compact RP2040 breakboard board that has 30 GPIO. The PGA2040 is no longer in production and not readily available for purchase. Some design changes on this PCB design include the removal of the screw hole for the OEM. This was done because this project will require a custom plate (work in progress) to accomidate the PGA2040 placement. A bootsel and reset button are integrated into the PCB to allow for easy flashing of the firmware.

Current known issues include: 
1. Num and Scroll Lock LEDs are not properly placed
2. JST XH connectors may not be the proper part and a different connector may work better
