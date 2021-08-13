nasm boot.asm -f bin -o boot.bin

qemu-system-x86_64 boot.bin


# od -t x1 -A n boot.bin
