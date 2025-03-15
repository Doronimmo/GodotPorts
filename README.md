## Notes

### **Godot Games**

Godot games usually have a .pck file which contains the main data to make the games work (I you can't find it that is not a problem, its probably embeded in the exe). As the games are not meant to run natively on ARM devices supported by portmaster, it uses frt/westonpack to help translate the data into information which can be read by arm devices. Based on the current limitations of RockNix LibMali, it cannot run godot 4.x ports. 

**Note:** the following instructions assumes you already have Portmaster installed on your device. 
It is also a lot more convenient to SSH your files via WIFI to your device rather than physically transferring the data via an SD card reader.

### **How to port Godot games to Portmaster**
1. Download Godot RE Tools from https://github.com/GDRETools/gdsdecomp
2. Legally obtain your Godot game files from Steam or GOG or Itch.io OR try the many wonderful free ones available from websites such as https://itch.io/
3. Locate the .pck or .exe file inside the game files and open it using the Godot RE Tools and determine the Godot version to see which runtime can help to translate the game information appropriately.
4. You can find the game version at the top of the window or under Version

