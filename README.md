# gba-kernel
implementation of a simple gameboy advance kernel in assembly for learning purposes.

# Requirements

* Some C/ARM Assembly knowledge
* A GameBoy Advance Emulator such as [Visual Boy Advance](http://www.emulator-zone.com/doc.php/gba/vboyadvance.html)
* [Devkit Pro toolchain](https://devkitpro.org/)

# Compilation
```javascript
arm-elf-gcc -mthumb-interwork -specs=gba.specs kernel.S
arm-elf-objcopy -O binary kernel.out kernel.gba
```
