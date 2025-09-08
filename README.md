# Yeeps-APK-Library
Yeeps apks that I have accumulated over time.
All these APKS where all pulled by jyomama28 or jyoeymama on GitHub!
If you have any questions please let me know! Send me an email at: jyomama28@gmail.com (You will recieve a response within 1-2 days unless im busy!)
WARNING: I AM NOT RESPONSIBLE FOR ANY DAMAGE DONE TO YOUR GAME, HEADSET, OR ACCOUNT! FELLOW HACKERS BEWARE! YOU CAN GET BANNED FOR HACKING!
(my game got corrupted from a failed hack attempt lol) If you are a modder and have made sucessfull mods from yeeps, Id love to get a video if you can, send the video to: jyomama28@gmail.com
Heres another thing, If you find a file named global-metadta.dat its encrypted. I tried to do another hack test which required the global-metadata.dat and another file named libil2cpp.so to compile my script to change my player color in c# but when I tried to compile the project into one .dll file it gave several errors. PLEASE NOTE THAT SOME FILES ARE ENCRYPTED TO PREVENT HACKERS. I am personally trying to decrypt them using several methods but beware the some files are indeed encrypted!

Incase anyone is curios about how my game looked when it got corrupted here you go! (my guess is that when I attempted to change the code of the APK, it must have flagged my account saying that I cant play because meta cant autenticate my account because i modified the APK.)

![corrupted](https://github.com/user-attachments/assets/a7513b46-136f-4de0-9207-3bca32388184)


<img width="1280" height="720" alt="Welcome To The Yeeps APK Library!" src="https://github.com/user-attachments/assets/1214f66a-3c74-4c65-ba08-c06e85f613b9" />



TABLE OF CONTENTS:

Tools For Modding/Ripping Assets

APK Description

Tutorial On How To Install Your Own Apks

TOOLS FOR MODDING/RIPPING ASSETS:

1. Asset Ripper. Asset Ripper can help you take apart all the files of the yeeps apks (or any apk or game!) Here is the link to Asset Ripper on GitHub: https://github.com/AssetRipper/AssetRipper
   
2. Asset Studio. Similiar to Asset Ripper, Asset Studio can help you take apart the files of yeeps or any other game! Here is the link to Asset Studio: https://github.com/Perfare/AssetStudio
   
3. QuestPatcher. QuestPatcher is a GUI-based mod installer for il2cpp Unity apps on Oculus Quest devices. Here is a link to QuestPatcher: https://github.com/Lauriethefish/QuestPatcher
   
4. dnSpy. dnSpy is a tool for inspecting and editing assemblies (DLLs) in .NET applications, including Unity games. It allows you to decompile, edit, and recompile assemblies. Here is the link to dnSpy: https://github.com/dnSpy/dnSpy

5. Unity Asset Bundle Extractor (UABE). UABE is a versatile tool for extracting, editing, and replacing assets within Unity asset bundles. Here is the link to UABE: https://github.com/SeriousCache/UABE

6. ILSpy. ILSpy is an open-source .NET assembly browser and decompiler. Here is the link to ILSpy: https://github.com/icsharpcode/ILSpy

7. NinjaRipper.NinjaRipper can extract 3D models and textures directly from a running game. Here is the link to NinjaRipper: https://github.com/riccochicco/ninjaripper

8. UnityEX. UnityEx can extract older unity assets with focus on Unity3D serialized files. Here is the link to UnityEX: https://github.com/sinai-dev/UnityExplorer

9. Harmony Library. Harmony Library is unfortuanetly not a GUI tool, but a runtime patching library for .NET/Unity games. Here is the link to Harmony Library: https://github.com/pardeike/Harmony

10. Il2CppDumper. Il2CppDumper is specifically for Unity games using IL2CPP. Here is the link to Il2CppDumper: https://github.com/Perfare/Il2CppDumper

11. Il2CppInspector. Il2CppInspector can inspect and analyze IL2CPP binaries. Here is the link to Il2CppInspector: https://github.com/djkaty/Il2CppInspector

12. QModManager. QModManager has the purpose of a core mod loader for VR games; supports patching and runtime injection of mods. Here is the link to QModManager: https://github.com/SubnauticaModding/QModManager

13. BepInEx. BepInEx is a general-purpose unity modding framework. Here is the link to BepInEx: https://github.com/BepInEx/BepInEx

14. MelonLoader. MelonLoader is a high-level Unity mod loader and runtime patcher. Here is the link to MelonLoader: https://github.com/LavaGang/MelonLoader

APK DESCRIPTION:

yeeps1.9update.zip is the yeeps apk for the 1.9 update

yeeps2.0update.zip is the yeeps apk for the 2.0 update

yeepsdesertupdate.zip is the yeeps apk for the desert update

(TO RECOMPILE THEM INTO AN APK JUST RENAME IT FROM example.zip TO example.apk)

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
