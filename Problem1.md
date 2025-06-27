# Adding additional drive to a Virtual machine

1. Open up Hyper-V and create or open an existing virtual machine
2. Go to the setting of the virtual machine![VM Settings](https://github.com/user-attachments/assets/6d3dfd6c-1f7f-4f9a-8689-e637cdfb0b87)

3. Under the hardware tab, go to SCSI Controller
4. Selece Hard Drive from the list and click Add
5. Select Virtual Hard Disk then click on New
6. In the first step you will choose VHDX becuae of the optimal space it gives you (keep in mind this only works for versions of Windows 8 and up)
7. Next step you will choose dynamic and expanding
8. Now you will choose a name for the Hard Drive and location on where it is saved, we will Call it Pc1Hd2 and save it to our Pc1 Vm Folder
9. In this last step we will choose the option to create a new virtual hard disk and choose the size of it, here we will just stick with 35gbs to match our initial Hard Drive
10. Click on finish and the apply and your new Hard Drive is ready to use on your Virtual Machine.
11. Repeat Steps 1 through 10 to add a 3rd Hard Drive to your Virtual Machine
12. Boot up you Virtual Machine and go to Disk Management to see if your hard drive shows up
13. When you open Disk Management it will prompt you to intialize your disks, CLick Ok
14. Now your two new Virtual Hard Drives are ready to use and be Partitioned for your Virual Machine.   
