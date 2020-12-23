# upsplus
## UPS Plus is a new generation of UPS power management module.
It is an `improved` version of the original UPS prototype.
* It has been fixed the bug that UPS could not charge and automatically power off during work time. 
* It can not only perform good battery power management, but also provide stable voltage output and RTC functions. 
* At the same time,it support for FCP, AFC, SFCP fast charge protocol, support BC1.2 charging protocol, support battery terminal current/voltage monitoring and support two-way monitoring of charge and discharge.
* It can provide programmable PVD function. 
- Power Voltage Detector (PVD) can be used to detect if batteries voltage is below or above configured voltage. 
- Once this function has been enabled, it will monitoring your batteries voltage, and you can control whether or not shut down Raspberry Pi via simple bash script or python script. 
- This function will protect your batteries from damage caused by excessive discharge. 
* It can provide Adjustable data sampling Rate.
- This function allows you to adjust the data sampling rate so that you can get more detailed battery information and also it will consume some power.
- The data sampling information can communicate with the upper computer device through the I2C protocol. 
* UPS Plus supports the OTA firmware upgrade function. 
- Once there is a new firmware update, it is very convenient for you to upgrade firmware for UPS Plus. The firmware upgrade can be completed only by connecting to the Internet,and execute a python script. 
* Support battery temperature monitoring and power-down memory function.
* UPS Plus can be set to automatically start the Raspberry Pi after the external power comes on. 
- The programmable shutdown and forced restart function will provide you with a remote power-off restart management method. 
- That means you don’t need to go Unplug the power cable or press the power button to cut off the power again. 
- You can set the program to disconnect the power supply after a few seconds after the Raspberry Pi is shut down properly.
- And you can also reconnect the power supply after a forced power failure to achieve a remote power-off and restart operation. 
- Once it was setting up, you don't need to press power button to boot up your device which is very suitable for smart home application scenarios.
