# Emulator debugging

As an alternative to running the compiled code on hardware, a suitable software emulator can mimic the CPU and limited peripherals.

This option may be a viable alternative to [Hardware Debugging](Hardware Debugging.md)

## Emulator (Software)

Various software emulator solutions exist, but qemu is presently supported.

## Required Dependencies

### Linux

Required dependencies can be installed on Ubuntu with:

	sudo apt-get install qemu-system-arm gdb

## Emulating

Emulation environment and a GDB debugger can be setup with:

	make qemu

