# How to Evil Portal firmware in Electronic Cats Marauder Flipper Add-On

1. Go to the [ESPWEBTOOL](https://esp.huhn.me/).

<p align="center">
	<img src="https://github.com/ElectronicCats/flipper-shields/assets/107638696/6893b5b0-5500-4891-af80-388cd1dd3b32" width=80%>
</p>

2. Attach the Marauder/ Marauder Spoof Add-On to the Flipper. 

3. Plug the USB cable into the USB-C port on the Add-On, enter the ESP32-S3 module in bootloader mode.
<p align="center">
	<img src="https://github.com/ElectronicCats/flipper-shields/assets/107638696/01a3a579-4aad-4cbe-b7d8-7e76d97bad2f" width=80%>
</p>

4. Click connect on ESPWEBTOOL. A pop-up menu will appear, select the correct board and port.

5. Use the following table to select the appropriate files and place them at the corresponding addresses.

|            |  Flipper Zero Multi Board S3 | 
| ---------- | -------------------------------- |
|Bootloader|[0x0]()|
|Partitions|[0x8000]()|
|Boot App|[0xE000]()|
|Firmware|[0x10000]()|


6. Click on _PROGRAM_. A confirmation pop-up window will appear, click on _CONTINUE_.

7. The update will start immediately. **Do not disconnect the USB cable or detach the Add-On from the flipper while updating**.

8. Once the update has been finalized, press the reset button.

Now you can unplug the USB cable and you are ready!