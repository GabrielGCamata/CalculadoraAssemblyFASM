# CalculadoraAssemblyFASM
Calculadora de ponto flutuante feita em assembly FASM

para compilar basta:

nasm -f elf -l calcFinal.lst calcFinal.asm
gcc calcFinal.o -m32
./a out
