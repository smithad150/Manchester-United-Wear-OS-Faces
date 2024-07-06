# Manchester-United-Wear-OS-Faces
A couple of watch faces I developed for Wear OS devices for the Manchester United supporters like myself! Note I am not a 
developer so there may be bugs and issues to fix! These were designed for circular faced watches - not sure how they 
look on square faced devices.

There are 3 faces: A Newton Heath themed Red Devil face, a current colour themed Red Devil Face, and a full logo themed face. 
I have added them to separate branches for ease of use

These need to be sideloaded via ADB as I do not have a Google Developer account since its costly for a fun hobby
If you do not know how to do this, there are a few key steps. 
I am not responsible for your device so please research your device thoroughly for this process
ADB/SDK Tools are for developers so doing things wrong can cause big issues that are time consuming or even impossible 
to fix - do so at your own risk

1. Enable developer options on watch (Varies by device but it is usually: Go to Settings > System/About > Version/Build
   and tap 7 times on the Build/Version number)
3. Enable ADB Debugging (Find a guide online for your device)
4. Enable Wireless Debugging (Find a guide online for your device)
5. Ensure ADB/SDK tools installed on your PC - many guides online for this
6. Run ADB in Terminal/CMD window where ADB/SDK Tools are stored
7. Pair devices (Find a guide online for your device)
8. Download the APK to the same folder as ADB/SDK tools
9. Connect to device using ADB - both the computer and watch must be on the same wifi
10. Run the following: adb install -g name_of_file.apk
11. Find your new watch face in the list of faces on device and setup the conplications as you see fit!
12. Tested & confirmed working on: Google Pixel Watch 2 LTE (Canada), Fossil Gen 6 44mm (Canada)
13. If you try it out and it works please let me know your device and I will update this list
    
Last Edit: 2024-07-06
