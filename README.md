# bootloader-by-me
bootloader created by me

## building
first clone with git clone https://github.com/Vicc2008/bootloader-by-me.git
install nasm for windows and qemu
execute this command: nasm -f bin boot1.asm -o boot1.bin
or for 2 execute this command: nasm -f bin boot2.asm -o boot2.bin

## testing
for 1 execute this command: qemu-system-x86_64 -fda boot1.bin
for 2 execute this command: qemu-system-x86_64 -fda boot2.bin
