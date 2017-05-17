# driverlib
A little python library for working with Windows drivers.   

Main usage - initialize the Driver class with the driver path and name, Driver(path, name).   
Driver.load() to load it.   
Driver.unload() to unload it.   
Driver.start() to start it.   
Driver.stop() to stop it.   
Driver.open_device() to get a handle to it.   
Driver.send_ioctl(ioctl, inbuf, inbufsiz, outbuf, outbufsiz) to send an ioctl to it.   


Command line usage:

``` 
You'll need to be running as admin...

usage: driverlib.py [-h]
                    [--load PE_PATH | --unload PE_PATH | --start PE_PATH | --stop PE_PATH]

A tool for loading/unloading/starting/stopping windows drivers

optional arguments:
  -h, --help        show this help message and exit
  --load PE_PATH    load driver
  --unload PE_PATH  unload driver
  --start PE_PATH   start driver
  --stop PE_PATH    stop driver
```

![]()