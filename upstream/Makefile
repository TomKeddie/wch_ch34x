KERNELDIR := /lib/modules/$(shell uname -r)/build
PWD :=$(shell pwd)
obj-m := ch348.o
default:
	$(MAKE) -C $(KERNELDIR)  M=$(PWD)  
clean:
	rm -rf *.mk .tmp_versions Module.symvers *.mod.c *.o *.ko .*.cmd Module.markers modules.order *.a *.mod
