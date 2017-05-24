KERNELDIR:=/lib/modules/$(shell uname -r)/build
PWD=$(shell pwd)

obj-m=ptable.o

all:
	$(MAKE) -C $(KERNELDIR) M=$(PWD)

clean:
	$(MAKE) -C $(KERNELDIR) M=$(PWD) clean
