AS=asm -v -n -C 6800

%.S19:	%.ASM
	$(AS) -l $*.LST -o $@ $^

.PHONY: clean distclean

all: MIKBUG.S19 MINIBUG.S19

clean:
	-rm -f *.LST
distclean: clean
	-rm -f *.S19
