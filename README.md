#### Convert the assembly to binary
nasm boot.asm -f bin -o boot.bin

#### Load the os
qemu-system-x86_64 boot.bin

#### To view the binary content
`od -t x1 -A n boot.bin`
