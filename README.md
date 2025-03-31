<h1 align="center">Raspberry Pi Thin Client</h1>
<p align="center">Low-cost thin clients for Proxmox VMs</p>

## What do we need?
- A Raspberry Pi *(or any other linux machine, not tested)*
- Keyboard & Mouse
    - Setup can be done over SSH, but it's a thin client! You'll need that!
- 8GB+ Micro SD card
    - Raspberry Pi OS **LITE**.
        - NOT DESKTOP
- Gigabit Ethernet is **VERY MUCH RECOMMENDED**

## What's a thin client?
To put it simply, it's a very low-power computer that acts only to remote into another.  We can use Raspberry Pis as thin clients for virtual machines running on a Proxmox server.

### What OSes are supported?
Anything *(or at least I couldn't find anything that didn't work)*