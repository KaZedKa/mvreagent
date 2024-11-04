# mvreagent
Powershell Script to move the default Windows recovery partition at the beginning of the partition table. This is useful for VMs when you need to increase the disk size as it lets you just expand the OS partition.


This script requires a 1GB partition created before the Windows related partitions. This is done in the installer (and to my knowledge can't be done once it's installed) like this: 

![image](https://github.com/user-attachments/assets/6f98728d-6727-4429-9650-cb15df8fd511)

Once this is done, your partition setup should look like this: 
![image](https://github.com/user-attachments/assets/1583c5e9-b0fa-4b71-89d7-919677a5a681)

If that's the case, then the script will function.

Please take note of the disk number (if you have 1 disk it will be 0), the script will ask for it.

This is the end result: 

![image](https://github.com/user-attachments/assets/a2a0b03a-a908-4d54-9dbb-ef237ec8d1e4)
