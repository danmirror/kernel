# simple kernel
> simple kernel with makefile

### prepare
> $ sudo apt-get install build-essential linux-headers-$(uname -r)

### use
> $ make
> $ sudo insmod main.ko
> $ modinfo main.ko
> $ tail /var/log/kern.log
