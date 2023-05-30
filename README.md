# Patch-Android
HOW I APPLY PATCH FOR ANDROID USING LUCKY PATCHER

This method requires a rooted phone

Ingredients:

-Magisk By @topjohnwu ( https://github.com/topjohnwu/Magisk
)

-MT Manager

-Lucky Patcher

-Lsposed Framework (For Android 11+)

-Smali Patcher Oleh @fOmey (Ini Untuk Menerpa Lokasi Mock & Penyedia Mock) Saya Menggunakannya Untuk Pekerjaan Saya Sebagai Driver Online.


Step By Step:


Install Magisk On Custom Recovery (Any Recovery, Including OrangeFox, Pitchblack, TeamWin)
After Installing Magisk, Install Smali Patcher ( https://forum.xda-developers.com/t/module-smali-patcher-7-4.3680053/ ) Make Smali Patcher By @f0mey Using PC And Apply Mock Location & Mock Provider, Turn On Developer Options Your Device Enable Usb Debugging, Plug Cable Into Your PC, Wait Until Completed, Once Completed, Move Smali.zip Module To Your Device Storage. (Don't Forget to Read the Thread on Xda)

Install the Smali Module that you have made to Magisk, Install Lucky Patcher & Lsposed Framework (For Android 11+), After that Reboot your device, After turning on, Open the Lucky Patcher Application, Enter the Toolbox Menu and Select Patch To Android. And Select This

- Signature Verification Status Always True √
- Disable .apk Signature Verification √

(Use the Magisk Module option to apply the patch)

After patching there will be a notification to reboot your device, and select reboot.

After that, check in the Magisk> Module application, whether there is a Lucky Patcher module or not

Open the MT Manager application, enter the root directory, open the /data/adb/modules folder, find the folder named Luckypatcher Copy and paste it into your storage directory.

And finally delete the Lucky Patcher & Smali Patcher Module in the Magisk application. (Reboot After Uninstall Module)

Open MT Manager again, enter the folder that you have copied and pasted named luckypatcher, enter system/framework (inside the luckyaptcher folder) select Services.jar and copy it to the system/framework root directory and paste it there. 

Check Patching In Lucky Patcher In the Toolbox Menu/Patch To Android Select Option (Run Test For Patch). If Lucky Patcher Declares Succes, Then You Successfully Apply Patches To Your Android

After That You Can Un-Root Your Device. To avoid detecting a rooted device (I did this to avoid detecting the online driver application).

Congratulations You can enable mock location without turning on developer options and apply patches in Lucky Patcher.

