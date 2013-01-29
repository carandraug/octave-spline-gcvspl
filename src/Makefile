MKOCTFILE ?= mkoctfile -Wall

all: gcvspl.oct

gcvspl.oct: gcvspl.cc gcvsplf.f
	$(MKOCTFILE) -v gcvspl.cc gcvsplf.f

clean:
	rm -f *.o octave-core core *.oct *~
