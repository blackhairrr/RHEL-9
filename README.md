# RHEL-9
System Disk expansion

![image](https://github.com/blackhairrr/RHEL-9/assets/37354986/2d89aa6d-127b-4659-80ce-9d23eb31343d)

1. Verify and check the free space for System disk
   #parted /dev/vda u s p free
    Model: Virtio Block Device (virtblk)
    Disk /dev/vda: 419430400s
    Sector size (logical/physical): 512B/512B
    Partition Table: msdos
    Disk Flags:
    
    Number  Start       End         Size        Type     File system  Flags
            2s          2047s       2046s                Free Space
     1      2048s       2099199s    2097152s    primary  xfs          boot
     2      2099200s    209715166s  207615967s  primary               lvm
            209715167s  419430399s  209715233s           Free Space
    
