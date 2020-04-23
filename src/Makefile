AS=asm -C 6800 -n -u

%.S19:	%.ASM
	$(AS) -l $*.lst -o $@ $^

.PHONY: clean

all: MIKBUG.S19 MINIBUG.S19

clean:
	-rm -f *.lst *.S19
