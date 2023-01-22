SBINDIR := /usr/sbin
BINDIR := /usr/bin
CASC := /root/cascade/target/debug/casc

all:
	$(CASC) myapp.cas

package: 
	$(CASC) myapp.cas --package

clean:
	rm -rf *.cil *policy* *contexts* 

