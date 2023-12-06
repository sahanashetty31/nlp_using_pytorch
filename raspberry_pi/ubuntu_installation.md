## Steps to install Ubuntu on Raspberry pi 4 

1. Insert micro SD card into sd card slot of the Laptop (or using sd card reader)
2. Open Terminal in Ubuntu
3. Run the commands :
   * sudo snap install rpi-imager
   * rpi-imager
4. Once the application is opened
5. Choose OS - others- ubuntu 22.04.3 LTS(64 bit)
6. Storage - Internal SD Card Reader
7. Click on Next
8. The flashing of SD Card starts and then verification starts.
9. Once the verification is done, eject the SD Card from the slot
10. Next, Plug in the micro SD Card into Micro SD Card slot of Raspberry pi 4.
11. Connect the power supply , hdmi cable to the monitor and usb cables of mouse and keyboard to the respective ports of Raspberry pi 4.
12. Once everything is connected, the ubuntu os will start.
13. Complete the configuration setup.
14. Install the updates using the below commands
    * sudo apt-get update
    * sudo apt-get upgrade