# how-to-update-drivers-for-windows
To update drivers on Windows using the terminal, follow these steps:

Press the Windows key + R on your keyboard to open the Run dialog box.
Type "devmgmt.msc" in the Run dialog box and press Enter to open the Device Manager.
In the Device Manager, expand the category of the device that you want to update the driver for. For example, if you want to update the driver for your graphics card, expand the "Display Adapters" category.
Right-click on the device that you want to update the driver for and select "Update Driver" from the context menu.
In the Update Driver window, select "Search automatically for updated driver software". This will cause Windows to search online for the latest available driver for the device.
If Windows finds an updated driver, it will automatically download and install it. Once the driver has been installed, restart your computer to complete the process.
If you prefer to use the command line, you can also update drivers using the "pnputil" command. To do this, follow these steps:

Open the Command Prompt by pressing the Windows key + R on your keyboard, typing "cmd" in the Run dialog box, and pressing Enter.
In the Command Prompt, type "pnputil -e" and press Enter. This will display a list of all the drivers that are currently installed on your computer.
To update a specific driver, type "pnputil -i -a [path to driver INF file]" and press Enter. Replace "[path to driver INF file]" with the full path to the INF file for the driver that you want to install.
Once the driver has been installed, restart your computer to complete the process.
Remember to always check the website of the manufacturer of your device for the latest available driver updates. This will ensure that you are getting the best possible performance and stability from your hardware.
