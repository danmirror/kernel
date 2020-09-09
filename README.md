# simple kernel
> simple kernel with makefile

### prepare
> $ sudo apt-get install build-essential linux-headers-$(uname -r)

### use
> $ make \n
> $ sudo insmod main.ko \n
> $ modinfo main.ko \n
> $ tail /var/log/kern.log \n
