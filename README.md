# Windows-10-Unmountable-Boot-Fix - Guide

The "Unmountable Boot Volume" error message occurs due to a variety of reasons. It can be due to a damaged file system and cannot be mounted, or the basic input/output system (BIOS) settings are configured to force the faster UDMA modes. It can also occur if there is a problem in the system hard drive or in the partition where your Windows is installed. It doesn't necessarily mean that your hard disk is defective.

The Automatic Repair should only take you for about 15 minutes max.

Since you've mentioned that you can't reach your lock screen to be able to log in and proceed to troubleshoot your PC, let's create an installation media and perform some troubleshooting steps using that tool.

You can download the installation media tool from this link. Don't worry as the steps on how to download it can be found on the link.

After successfully downloading it, you can proceed to these troubleshooting methods. Make sure that you start your PC using the installation media.

**Method 1 - Perform a Chkdsk.**
1. Select the **Repair your computer** option found at the lower-left corner once you start your PC using the installation media.
2. Choose **Command Prompt**.
3. Type **chkdsk /r c:**, then press the **Enter** key from the keyboard. **Note:** Replace **c:** to the bootable drive letter you're using if it's other than c:.
4. Select **Y** for **Yes** if you were asked regarding checking the disk the next time the system restarts.
5. Reboot your PC. Let's keep our patience here as the chkdsk can take quiet some time.

**Method 2 - Repair Master Boot Record.**
1. Select the **Repair your computer** option found at the lower-left corner once you start your PC using the installation media.
2. Choose **Command Prompt**.
3. Type **bootrec /fixboot**, then press the Enter key from the keyboard.
4. Reboot your PC. Your patience is also needed here.

**Method 3 - Automatic Repair.**
1. Select the **Repair your computer** option found at the lower-left corner once you start your PC using the installation media.
2. Choose **Troubleshoot**, then **Advanced options**.
3. Select **Automatic repair**, then **Next**.

If these methods didn't work to repair your PC, then you seem to have a bad hard drive that might need a replacement. That being said, you can check it with your manufacturer if you reach this point.

We'll be waiting for your update.


Best.
