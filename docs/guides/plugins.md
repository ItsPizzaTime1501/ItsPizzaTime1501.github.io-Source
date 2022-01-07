## Luma3ds Plugin Loader Guide

This guide will teach you how to install and use two custom luma forks with different plugin types


If you're trying to use the ACNL plugin follow the steps listed in the [AC Modding Discord Server](https://discord.gg/EZSxqRr)

### Requirements

* A console with boot9strap installed
* A plugin file you want to use (`.3gx` or `.plg`), if you don't have any you can find them by doing a quick google search, here's a list of some good ones:

Pokemon Ultra Sun and Ultra Moon: [ultraSuMoFramework](https://gbatemp.net/threads/release-ultrasumoframework-ntr-plugin-for-ultra-sumo.489098/)

Pokemon Sun and Moon: [sumoCheatMenu](https://github.com/AnalogMan151/sumoCheatMenu/releases)

Mario Kart 7: [Mario Kart 7 Online NTR Plugin](https://github.com/DarkFlare69/MK7-Online-NTR-Plugin-v3/raw/master/MarioKart7.3gx)

The Legend of Zelda: Ocarina of Time 3D: [Zelda-Ocarina-Of-Time-3D-Plugin](https://github.com/Nanquitas/Zelda-Ocarina-Of-Time-3D-Plugin)

Assorted Games: [CTRPF Plugins 3.0](/files/plugins/CTRPF-Plugins-master.zip)

### Installing plugin type `.plg`
<!---
1. Download the `boot.firm` from [here](http://badda.de/lumamod/Luma3DS_v9.1-7-gbd15f_mod.7z) and place it on your SD root, make sure you overwrite the current one.
2. Rename your `.plg` file to `plugin.plg`
3. Make a folder called `plugins` if it doesn't already exist inside the `luma` folder on your SD card
4. Inside of the `plugins` folder make a folder named the titleid of the game you want to use the plugin file for (If you don't know the game titleid you can find a list [here](http://3dsdb.com) or [here](https://hax0kartik.github.io/3dsdb/))
5. Place the `plugin.plg` file inside the folder you just created <br/>
![plg location](/files/pic/plg_location.png)<br/>
(in this example `00040000001B5100` is Pokemon Ultra Moon's titleid)

6. Insert your SD card into your 3ds and boot it up, if you get a luma config screen select `Show NAND or user string in System Settings` and press start
7. Once you're in the home menu, open the rosalina menu (L + Dpad Down + Select by default) and select `Enable Plugin Loader`
8. Press B to exit the rosalina menu
9. When you launch the game you setup a plugin for your screen should flash green during the Nintendo 3ds splash
10. The standard for cheat menus is the select button, if pressing select doesn't work consider reading the readme of the plugin you're using
--->
Currently there are no up-to-date forks of Luma3ds that have `.plg` file support. Your only option is to use [BootNTR Selector](https://github.com/Nanquitas/BootNTR/releases) which requires you to have the [`.3gx` loader fork](https://github.com/Nanquitas/Luma3DS/releases/latest) of Luma3ds installed. To find out how to install the `.3gx` loader fork you can follow the instructions below. [Here](https://3ds.eiphax.tech/ntrplugins) is a guide on using BootNTR Selector.

### Installing plugin type `.3gx`

1. Download the `boot.firm` from [here](https://github.com/Nanquitas/Luma3DS/releases/latest) and place it on your SD root, make sure you overwrite the current one.
2. Make a folder called `plugins` if it doesn't already exist in the `luma` folder on your SD
3. Inside of the `plugins` folder make a folder named the titleid of the game you want to use the plugin file for (If you don't know the game titleid you can find a list [here](http://3dsdb.com) or [here](https://hax0kartik.github.io/3dsdb/))
4. Place your `.3gx` file in the folder you just created, here is an example that could be helpful:
![3gx location](/files/pic/3gx_location.png) <br/> (in this example `0004000000030800` is Mario Kart 7's titleid)
5. Insert your SD into your 3ds and boot it up, if you get a luma config screen select `Show NAND or user string in System Settings` and press start
6. Once you're in the home menu, open the rosalina menu (L + Dpad Down + Select by default) and enable the plugin loader
7. Press B to exit rosalina
8. Open the game you installed a plugin for, your screen should flash green or blue during the Nintendo 3ds splash
9. The standard for cheat menus is the select button, if pressing select doesn't work consider reading the readme of the plugin you're using

<!---
### (Optional) How to switch between `3gx` and `plg` loader luma easily

1. Download both `boot.firm`'s ([Luma 3gx Loader](https://github.com/Nanquitas/Luma3DS/releases/latest) | [Luma plg loader](http://badda.de/lumamod/Luma3DS_v9.1-7-gbd15f_mod.7z))
2. Rename both `boot.firm`'s to something else like `Luma3ds_3gx_loader.firm` for the `3gx` loader and `Luma3ds_plg_loader.firm` for the `plg` loader
3. Download and install [PayloadSpinner3ds](https://github.com/SaturnSH2x2/PayloadSpinner3DS/releases/latest) on your 3ds. Here is a QR you can scan with FBI (FBI -> Remote Install -> Scan QR Code)  
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![PayloadSpinner3ds QR](/files/pic/payload_spinner_3ds_qr.png)
4. Once it's done installing, exit to your home menu and open the app once. It should say `No payloads were found. Refer to README`, just press A to exit
5. Place both firm files in `/3ds/data/PayloadSpinner3DS/payloads` on your SD
![PayloadSpinner3ds payload location](/files/pic/payload_spinner_3ds_payload_location.png)<br/>
  Now when you would like to switch just launch PayloadSpinner3DS and select the luma version you would like to use
-->

### <span style="text-decoration: underline">Troubleshooting</span>

#### **Game crashes when using a plugin**

Fix: Don't use that plugin

#### **Screen doesn't flash and plugin doesn't load**

Fix: Check if you got the right titleid, if you're sure you did try a different plugin