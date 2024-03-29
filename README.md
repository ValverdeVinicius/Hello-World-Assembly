Assembler: as asm.s -o asm.o
Compiler: gcc -o asm asm.o -nostdlib -no-pie
Runner: ./asm
