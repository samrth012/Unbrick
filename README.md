# Unbrick

Requirements - 

USB drivers - https://spflashtool.com/download/MediaTek_USB_VCOM_drivers.zip

Lib USB driver - https://bypassfrpfiles.com/2021/02/download-libusb-win32-driver/

Sultneg tool - https://sfile.mobi/7pcPraEckEW

Mi flash pro - https://miflashpro.com/

Latest fastboot stock rom - https://xiaomifirmwareupdater.com/miui/pissarro/


Process - 
Extract stock rom
Extract and open sultneg tool
Go to xiaomi page
Choose auto select model
Press disable spa auth and select execute 
Press and hold volume down button for sometime 
Then press and hold volume up and down together while plugging in the cable after the it says auth bypass successfull 

Open mi flash pro, no need to login 
Select Sp flash ( Not the v6 ) only sp flash 
Select the scatter file from {extracted rom folder}/images/MT6877_Android_Scatter.txt 
Uncheck the preloader partition
Select download and wait for it to flash 
Once the flash is done 
Press and hold power button and reboot device 
It will take you to recovery
Wipe data and reboot to system 

Congo! You have successfully unbricked your device!!!
