# o_scope

O-SCOPE: https://mandrecut.github.io/o_scope/

RP2040: https://github.com/mandrecut/o_scope/blob/main/rp2040/firmware.uf2

RP2350: https://github.com/mandrecut/o_scope/blob/main/rp2350/firmware.uf2

Paper: https://arxiv.org/abs/2610.18906

The firmware.uf2 can be flashed on the RP2 board as following: 

- Disconnect the RP2 from the micro-USB.

- Press and hold the BOOTSEL button.

- Plug the board into the USB of the host computer and release the button.

- The computer will mount the RP2 as a mass storage drive.

- Drag and drop the \verb|firmware.uf2| file onto that drive. 

- The RP2 board will reboot automatically with the firmware active each time is plugged into an USB port.
