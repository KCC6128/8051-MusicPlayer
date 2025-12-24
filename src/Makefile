all: main.hex
main.ihx: main.c
	sdcc main.c
main.hex: main.ihx
	packihx main.ihx > main.hex
clean:
	del *.hex *.ihx *.lk *.lst *.map *.mem *.rel *.rst *.sym *.asm *.lib

