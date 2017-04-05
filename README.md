# driverlib
A little python library for working with Windows drivers.   

Main usage - initialize the Driver class with the driver path and name.   
Driver.load() to load it.   
Driver.unload() to unload it.   
Driver.start() to start it.   
Driver.stop() to stop it.   
Driver.open_device() to get a handle to it.   
Driver.send_ioctl(ioctl, inbuf, inbufsiz, outbuf, outbufsiz) to send an ioctl to it.   