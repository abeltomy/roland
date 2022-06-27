*********************************************************
   Roland 2.5D DRIVER for Windows(R) 8 64-bit
*********************************************************

We do recommend you to read through this document first for your better understanding of Roland 2.5D DRIVER. This "Readme" file provides some important information to install Roland 2.5D DRIVER.

Explanation here is assuming that you are already familiar with operations on Windows. The further information about operation on Windows, please refer the user's manual from Microsoft Corp.

If you are reading this file with Notepad, check 'WordWrap' in Edit menu so that you can read more easily.


< Table of Contents >

1. In the beginning 
2. Installing the Driver
3. Uninstalling the Driver
4. Important Notes


* "Windows(R)" is registered trademark or trademark of Microsoft(R) Corporation in the United States and/or other countries.
* "TrueType" is a trademark of Apple Computer, Inc.
Other company and product names appearing herein are trademarks or registered trademarks of their respective holders.

Copyright (C) 2012, 2013 Roland DG Corporation


R2-130110


----------------------------------------

< 1. In the beginning >

This driver provides you the capability to make 2.5D engraving with Roland CAMM-2 series machines, CAMM-3 series machines, MODELA Pro and MODELA through your Windows application software.

* What is 2.5D?
CAMM-2, CAMM-3, MODELA Pro and MODELA can work on X and Y axes like as plotter. And, two manners are available to work on Z axis.

The one is just to work with a certain cutting depth giving the tool-up and tool-down positions (in height) to the machine. With this manner, CAMM-2, CAMM-3, MODELA Pro and MODELA can work with 2D CAD and Graphics applications by reading pen up and down instructions for plotter.
The other is to have the same simultaneous control on Z axis as on X/Y axes to work with continuous coordinates. This manner allows to work with 3D CAD applications, but it is necessary for application softwares to have the capability to generate the proper output data for Z axis.

We call the former manner '2.5D'.


----------------------------------------

< 2. Installing the Driver >

*	Log on as a user with administrator rights.
*	If an older version of the driver is installed, uninstall it before you install the new one. For more information about how to remove the driver, refer to the next section, "Uninstalling the Driver."

1.	Switch off the power to the machine, then detach the connector cable between the machine and the computer.
2.	Turn on the computer. After Windows has started, turn on the machine. At this time, do not attach the connector cable to the computer and the machine yet.
3.	Click [Desktop].
4.	Start Windows Explorer, then open the drive or folder where the driver is located. (*)
5.	Double-click "SETUP64.EXE".
6.	The [User Account Control] appears, click [Allow].
7.	The Setup program for the driver starts.
8.	Click [Install] to choose it.
	Choose the machine and connection port you're using, then click [Start].
9.	After installation has finished, use the cable to make the connection between the computer and the machine.


----------------------------------------

< 3. Uninstalling the Driver >

1.	Switch off the power to the machine, then detach the connector cable between the machine and the computer.
2.	Start Windows.
3.	Click [Desktop].
4.	Move the mouse to the bottom right corner to display the Charm, then click [Settings].
5.	Click [ControlPanel], and then click [Uninstall a program].
6.	Click the driver for the machine to delete to select it, then click [Uninstall].
7.	A message prompting you to confirm deletion appears. Click [Yes].
8.	Click [Start]-[Desktop].
9.	Start Windows Explorer, then open the drive or folder where the driver is located. (*)
10.	Double-click "SETUP64.EXE".
11.	The [User Account Control] appears, click [Allow].
12.	The Setup program for the driver starts.
13.	Click [Uninstall] to choose it.
	Select the machine to delete, then click [Start].
14.	If it is necessary to restart your computer, a window prompting you to restart it appears. Click [Yes].
15.	After the computer has restarted, start [ControlPanel], then click [View devices and printers].
16.	Right-click the icon when the icon of the machine you want to delete exists, and then click Remove Device.


(*) When using the CD-ROM, specify the folder as shown below (assuming your CD-ROM drive is the D drive).

	D:\Drivers\25D\WIN8X64

If you're not using the CD-ROM, go to the Roland DG Corp. website (http://www.rolanddg.com/) and download the driver for the machine you want to delete, then specify the folder where you want to expand the downloaded file.


----------------------------------------

< 4. Important Notes >

- This driver does not support [Test Print].

- The output command set for this driver supports mode 1.
If the machine tool is a CAMM-2 or CAMM-3, which have a command mode, set the command mode to [Auto] or [Mode 1]. (For information on how to make the setting, refer to the user's manual for the machine tool.)

- If You're Using Dr. Engrave
The [Fill] setting for this driver has no effect if made, because the [Fill] setting is made in Dr. Engrave.

- If You're Using 3D Engrave, MODELA Player, MODELA Player 4 or SRP Player
Cutting parameters and the like are all made in the program, and have no effect if set using this driver.

- This driver does not support output any bitmap (raster) data. It is impossible to output texts or border lines etc. from such applications that output bitmap data, for example word processing softwares.
We recommend to use drawing softwares.

- When you will output True Type fonts, you should generate 'outlines' of texts to convert them into vector data. Please refer to the manual of your application software for this function. If your software does not have the function to generate outline, it is impossible to output True Type fonts.

- The depth (working distance along Z-axis) can be selected in the driver setting. The driver help explains how to configure your driver.


========================================================

If you have further questions or problem, please contact to your local vendor or Roland sales center.
