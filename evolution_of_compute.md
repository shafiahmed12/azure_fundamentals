# Evolution of Computing

## Dedicated Servers

- A physical server wholly utilized by a single customer
- You have to guess your capacity, You will over pay for an un-utilized server
- Upgrading beyond your capacity will be slow and expensive
- you are limited by your OS
- Multiple apps can result in conflicts in resource sharing
- You have a *guarantee of security, privacy and full utility of underlying resources*

## Virtual Machines

- You can run multiple virtual machines on one machine
- Hypervisor is the software layer that lets you the VMs
- A physical server shared by multiple customers
- You pay for a fraction of a server as it is shared
- you will overpay for an underutilized VM
- you are limited by your Guest Operating System

## Containers

- VM running multiple containers
- Docker Deamon is the software layer that lets you run multiple containers.
- You can maximize the utility of the available capacity which is more cost effective
- Your container shares the same underlying OS so containers are more efficient
than multiple VMs
- Multiple apps can run side by side without being limited to the same OS
requirement and will not cause conflicts during resource sharing

## Functions

- A managed VM running managed containers
- Known as *Serverless compute*
- you upload a piece of code choose the amount of memory and duration
- Only responsible for the code and data, nothing else.
- Very cost-effective, only pay for the time code is running, VMs only run when
there is code to be executed.
- Cold start is a side effect of this setup.