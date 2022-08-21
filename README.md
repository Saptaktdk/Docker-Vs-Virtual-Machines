
![](/Docker-vs-Virtual-Machine-Big.webp)


## Layers of Operating System 
Operating system has 2 layers: Kernel and Applications layer.

The kernel connects the applications and hardware.

## The Difference
Docker virtualises the application layer of the operating system. 
It uses the kernel of the host as it does not have it's own kernel.

On the other hand, a VM uses it's own application layer and kernel.
So, it virtualises complete operating system.

![](/Docker-and-Virtual-Machine-architecture.webp)

## Features
# Size: 
Size of docker is lesser than size of VMs as it only virtualises one layer.

# Speed:
Docker is faster than any VM.

# Compatibility:
VM of any OS can on any OS host. It's not the case in docker. For example, 
a linux based docker image may not run on a windows kernel for compatibility
issues.