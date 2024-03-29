# Project Z - Set-up.
Project Z is the current branch used in the series of upcoming devices the client is releasing this quarter. Because of a change in project architecture, previous install procedures (manual and automated) no longer work. Please follow the instructions outlined below to install Project Z.

### Preconditions
You need to use a rooted device running Android OS 5.0+ to test Project Z. Check [this list](#) for an available compatible device. 

Have Android USB drivers installed on your computer.  
[Go here](http://developer.android.com/sdk/win-usb.html) for more information on installing the USB drivers.

---
### Uninstall previous version of S-Voice
Uninstall updates for any version of S-Voice currently on the device.
To do this:

1. Go to **Settings**
2. Choose **Application Manager**
3. Swipe left across to **All**
4. Find **S-Voice** and single tap to open application information.
5. Tap **Clear Data**
6. Next, tap **Uninstall Updates**

Restart the device once you complete these steps.

---
### Install the Nuance debug utility
Install the Nuance debug utility so you can access the Project Z development settings.

1. Download the latest version of the [Nuance Debug Utility](#)
2. Connect you computer to the device with a device USB cable.
3. Copy the Nuancedebug.apk from your computer to the device.
  1. Open Windows explorer.
  2. Browse to the where you downloaded the NuanceDebug.apk.
  3. Select and copy the NuanceDebug.apk.
  4. Browse to your connected device.
  5. Paste the NuanceDebug.apk into a folder of you choosing.  
     *Remember where you copied it*.
4. On your device open the **File Manager**.
5. Browse to where you saved NuanceDebug.apk.
6. Tap the file and follow the prompts to install.

You will now see a new icon for the Nuance Debug Utility.

---
### Install SVFsampler
>Because of a change in architecture, Project Z now requires the SVF application along with the Project Z application. The client owns application. We make use of a sample version that they have provided us for testing and development purposes.

>Just make sure you have the most up-to-date version installed when you are testing.

1. Download the latest version of the [SVFsampler](#)
2. Connect you computer to the device with a device USB cable.
3. Copy the SVFsampler.apk from your computer to the device.
  1. Open Windows explorer.
  2. Browse to the where you downloaded the SVFsampler.apk.
  3. Select and copy the SVFsampler.apk.
  4. Browse to your connected device.
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
### Install the Project Z application
This project is under Continuous Integration(CI) so there may be many builds a day. You can use any build from the current day.

1. Download the latest Project Z version of the [S-Voice - Project Z](#)
2. Connect you computer to the device with a device USB cable.
3. Copy the ProjectZ.apk from your computer to the device.
  1. Open Windows explorer.
  2. Browse to the where you downloaded the ProjectZ.apk.
  3. Select and copy the ProjectZ.apk.
  4. Browse to your connected device.
  5. Paste the ProjectZ.apk into a folder of you choosing.  
     *Remember where you copied it*.
4. On your device open the **File Manager**.
5. Browse to where you saved ProjectZ.apk.
6. Tap the file and follow the prompts to install.
7.  ***Do not open the application***  when the install has finished.
8. Restart the device and complete the steps in **Set-up Project Z for testing**.

---
### Set-up the Project Z application for testing
Before you attempt to run the Project Z application for testing, you will need to complete some final set-up steps.
#### Set Language and update language VOCON version
The first time you start the Project Z application it will prompt you to select a testing language.  
Follow these steps to make sure the VOCON version is the most recent:  

1. Find and tap the Project Z icon to start the application.
2. You will see a list of available languages with an *Update* section below. First, select the testing language from the *Update* section.
3. Now, select the testing language from the list of available languages at the top.

The Project Z application will now start in the language selected.

#### Set test server
You will also need to set-up your test servers.

1. Tap the **Nuance Debug** application.
2. Select **Set default servers** from the options.
3. Choose your testing server from the drop down.
4. Tap **Apply** to set the testing servers and exit the application.

#### Update LMTT
To be able to use test *Music*, *Applications*, and *Contacts* you will need to push an LMTT update from the device.   

To do this:

1. Tap the **Nuance Debug** application.
2. Select **Debug options**.
3. Choose **LMTT Update** from the menu of commands.
4. Select the **Update all** option.

You will need to wait several minutes for the update to process on the server side.
>If you have waited a few minutes and LMTT items are still not recognized. Check that you are using the most up-to-date SVFsampler application.
