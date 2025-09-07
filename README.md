# Yeeps-APK-Library
Yeeps apks that I have accumulated over time.
All these APKS where all pulled by jyomama28 or jyoeymama on GitHub!
If you have any questions please let me know! Send me an email at: jyomama28@gmail.com (You will recieve a response within 1-2 days unless im busy!)
WARNING: I AM NOT RESPONSIBLE FOR ANY DAMAGE DONE TO YOUR GAME, HEADSET, OR ACCOUNT! FELLOW HACKERS BEWARE!
(my game got corrupted from a failed hack attempt)


<img width="1280" height="720" alt="Welcome To The Yeeps APK Library!" src="https://github.com/user-attachments/assets/1214f66a-3c74-4c65-ba08-c06e85f613b9" />



TABLE OF CONTENTS:
Tools For Modding/Ripping Assets
APK Description
Tutorial On How To Install Your Own Apks

TUTORIAL ON HOW TO INSTALL YOUR OWN APK:
first go into sidequest and go into the terminal, You can use the powershell terminal too! (MUST HAVE DEVELOPER MODE ON ACCOUNT ENABLED, YOU MUST HAVE A PC OR LAPTOP, YOU ALSO NEED A USB 3.0 CABLE!)

Go into powershell and type this to make sure your headset is connected to your PC:

(MAKE SURE YOU GO INTO YOUR HEADSET FIRST AND CLICK ALLOW)
```
adb list devices
```
Once the connection is successfull type the following command below:

```
adb shell pm list packages
```

(This will list all the packages or apps on your headset)

Then type the following below:

```
adb shell pm path com.TrassGames.Yeeps
```

you should get a string similar to this apk: package:/data/app/~~REDACTED==/com.TrassGames.Yeeps-REDACTED==/base.apk

Then once this is complete, Type the following command below (MAKE SURE TO REPLACE WITH YOUR STRING THAT YOU GOT, FOR EXAMPLE: package:/data/app/~~REDACTED==/com.TrassGames.Yeeps-REDACTED==/base.apk:

```
adb pull package:/data/app/~~REDACTED==/com.TrassGames.Yeeps-REDACTED==/base.apk
```
Then you should have the apk for yeeps on your computer! to look at the files of yeeps, I recommend using a tool like AssetRipper to look around the files! Make sure to change the file name from yourfilename.apk to yourfilename.zip, Thank you for looking at this repository and happy hacking! 
