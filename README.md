# Root-10-or-G
100% Working trick to root 10 or G

Steps to root 10.or G:

Download ADB.
Download platform-tools.
Download Qualcomm drivers.
Download Magisk manager.

Go to settings in your phone.
Go to about phone.
Click on build number 7 times. You will get msg "You are now a developer".
Go back and select Developer options.
Developer option > oem unlocking > On & usb debugging > On.


Steps to downgrade to Android 7.1.2 from Oreo.
Go to Qualcomm > bin > QFIL > Run as Administrator on your pc.
Select Flat Build in QFIL. 
Start your phone in EDL mode by pressing Power + Vol Up + Vol Down all at a time. 
The screen will flash 10.or logo and then go blank. You have entered edl mode.
Choose browse and locate inside 10or_G_V1_0_70_RepairMyMobile > prog_emmc_firehose_8953_ddr.mbn
Choose load xml and locate inside 10or_G_V1_0_70_RepairMyMobile and select rawprogram0.xml and next patch0.xml.
Click on Download button.
This will install stock android 7.1.2 on your 10.or G device.

Next you need to unlock bootloader.
Use flash tool by DhirajMS_10orG_Bootloader_Unlock in edl mode.
Now boot your phone in fastboot mode by pressing Power + Vol Up and select reboot to bootloader.
Go to command prompt in your pc.
Locate to platform tools. Eg- cd ..\..\Users\Rajat\Downloads\platform-tools
use command : fastboot flashing unlock.
Confirm on mobile by selecting yes.
bootloader unlocked.

Next flash twrp in edl mode using FLASH_RECOVERY_TWRP_STANDARD>Vishalsmagic. Password is vishalsmagic

Next you need to root your phone.
Download Magisk manager in your phone via Wifi or via sd card.
Copy 10or_G_V1_0_70_RepairMyMobile > 10or_G_V1_0_70 > boot.img to sd card of your phone.
Connection to internet is compulsory for next step.
Select install in magisk manager and select patch. Locate boot.img and press Ok.
Copy the patched file back to 10or_G_V1_0_70_RepairMyMobile > 10or_G_V1_0_70 > here.
Flash your mobile in edl mode using QFIL with the new boot.img in 10or_G_V1_0_70_RepairMyMobile.
Install Magisk manager once again and reboot your phone.

Congratulations. Your 10.or G is now rooted.

But wait. Your IMEI number will show 0. Don't worry. You can get back IMEI using your pc.
Open folder imei > WriteDualIMEI(W+G_eMMC)
Connect your phone in adb mode.
Type your COM port. Eg - COM3. You can search your COM port in Device Manager of your computer. 
Type both the IMEI of your phone located on the box of your Tenor phone.
Hit Start.
Reboot your phone.

Hurray. You will get back your IMEI no. and network will start working again.

Disclaimer - The above trick is only for educational purposes. Do only as I instruct here. Moreover,
I am not resposible if you brick your phone. Do not misuse.

Note - At any point of time if you brick your phone:
Open your phone in edl mode and flash original 10or_G_V1_0_70 using QFIL as mentioned above.




