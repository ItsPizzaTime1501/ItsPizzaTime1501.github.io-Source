## Custom themes guide


### What you need

* A console with Luma3ds installed
* Anemone3ds (note: you should already have anemone if you followed a good guide, if you somehow don't you can get it [here](https://github.com/astronautlevel2/Anemone3DS/releases/latest))

#### Finding a theme

1. Open [Themeplaza](https://themeplaza.art/themes) on your computer
2. Find a theme you like
3. Click on it
4. Use one of the following 2 methods to install the theme

#### Method 1: Adding Themes via QR code

1. Hover over the theme's picture with your cursor, a QR code should pop up
![Theme QR](/files/pic/theme_qr.png)<br />
2. In Anemone, press the right bumper (<img src="/files/button/3ds_button_r.png" alt="rbumper" width="20">) to open the camera
3. Scan the QR code
4. The theme should be added to the list

#### Method 2: Adding Themes Manually

1. Press the download button on the theme's page
2. Save the zip somewhere on your pc
3. Open your 3ds's SD card
4. Make a `Themes` folder on the SD root if it doesn't already exist
5. Copy the downloaded zip file to the `Themes` folder
![Theme Location](/files/pic/theme_location.png)

#### Installing the theme

1. Open Anemone (<img src="/files/pic/anemone.png" alt="anemone" width="20"/>) on your 3ds if it isn't already open
2. Select the theme  
![Theme List](/files/pic/theme_list.png)
3. Hold A + Dpad Up (<img src="/files/button/3ds_button_a.png" alt="abutton" width="20"> + <img src="/files/button/3ds_dpad_up.png" alt="dpadup" width="20">) and then release A to install the theme
4. Press Start to exit Anemone and return to your home menu
5. Congratulations, you now have a custom theme  

&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;![Custom Theme](/files/pic/custom_theme.png)
<br /><br />

### <span style="text-decoration: underline">Troubleshooting</span>


#### **Anemone says "Theme extdata does not exist!"**

* Fix: Set a default theme in the home menu settings

#### **I get a crash after installing a theme**

1. Navigate to the following folder on your SD card:  `/Nintendo 3DS/(32 Character ID)/(32 Character ID)/extdata/00000000/` 

2. Delete the corresponding folder for your region:  
USA: `000002cd`  
EUR: `000002ce`  
JPN: `000002cc`  

#### **Anemone Crashes**

* Fix: Try deleting `/3ds/Anemone3ds/Cache` on your SD
