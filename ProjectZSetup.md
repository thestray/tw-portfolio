#Project Z - Set-up.



###Preconditions
You must use a rooted device running Android OS 5.0+ to test Project Zero.  
Check [this list](#) for a compatible device. 

Have Android USB drivers installed on you computer.  

[Go here](http://developer.android.com/sdk/win-usb.html) for more information on installing the USB drivers.

---
###Uninstall previous version of S-Voice
Uninstall Updates for any version of S-Voice currently on the device.
To do this:

1. Go to **Settings**
2. Choose **Application Manager**
3. Swipe left to **All**
4. Find **S-Voice** and single tap to open application information.
5. Tap **Clear Data**
6. Next, tap **Uninstall Updates**

Restart the device once these steps have been completed.

---
###Install Nuance debug utility
Install the Nuance debug utility so you can access the S-Voice development settings.

1. Download the latest version of the [Nuance Debug Utility](#)
2. Connect you phone to the device with a device USB cable.
3. Copy the Nuancedebug.apk from your computer to the device.
  1. Open Windows explorer.
  2. Browse to the where you downloaded the NuanceDebug.apk.
  3. Select and copy the NuanceDebug.apk.
  4. Browse to you connected device.
  5. Paste the NuanceDebug.apk into a folder of you choosing.  
     *Remember where you copied it*.
4. On your device open the **File Manager**.
5. Browse to where you saved NuanceDebug.apk.
6. Tap the file and follow the prompts to install.

You will now see a new icon for the Nuance Debug Utility.

---

###Install SVFsampler
>Because of a change in architecture, Project Z now requires the SVF application to be installed along with S-Voice. This application is owned by the client. We make use of a sample version that they have provided to us for testing and development purposes.
>Just make sure you have the most up-to-date version installed when you are testing.

1. Download the latest version of the [SVFsampler](#)
2. Connect you phone to the device with a device USB cable.
3. Copy the SVFsampler.apk from your computer to the device.
  1. Open Windows explorer.
  2. Browse to the where you downloaded the SVFsampler.apk.
  3. Select and copy the SVFsampler.apk.
  4. Browse to you connected device.
  5. Paste the SVFsampler.apk into a folder of you choosing.  
     *Remember where you copied it*.
4. On your device open the **File Manager**.
5. Browse to where you saved SVFsampler.apk.
6. Tap the file and follow the prompts to install.
7.  When the install has finished,  go to **Settings**.
8. Choose **Application Manager**.
9. Find **SVFsampler** and single tap to open application information.
10. Tap **Clear Data**.
11. Restart the device.

---
###Install S-Voice
Install the latest build for Project Z. This project is under Continuous Integration(CI) so there may be multiple builds a day. It is fine to use any build from the current day, unless there is an issue in an earlier build.

1. Download the latest Project Z version of the [S-Voice](#)
2. Connect you phone to the device with a device USB cable.
3. Copy the S-Voice.apk from your computer to the device.
  1. Open Windows explorer.
  2. Browse to the where you downloaded the S-Voice.apk.
  3. Select and copy the S-Voice.apk.
  4. Browse to you connected device.
  5. Paste the S-Voice.apk into a folder of you choosing.  
     *Remember where you copied it*.
4. On your device open the **File Manager**.
5. Browse to where you saved S-Voice.apk.
6. Tap the file and follow the prompts to install.
7.  ***Do not open the application***  when the install has finished.
8. Restart the device and complete the steps in **Set-up S-Voice for testing**.

---

###Set-up S-Voice for testing

####Set Language

####Update language Vocon version

####Set test server

####Update LMTT