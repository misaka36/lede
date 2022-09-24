all: nvram

nvram:
	$(CC) $(CFLAGS) -Ofast -pipe -o $@ cli.c crc.c nvram.c $(LDFLAGS)

clean:
	rm -f nvram
