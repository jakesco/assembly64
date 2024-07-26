binary: example.o
	ld -g -o binary example.o

example.o: example.asm
	yasm -g dwarf2 -f elf64 example.asm -l example.lst

clean:
	rm *.o *.lst binary

