<p align="center"><img src="https://i.ibb.co/pj0Pnj7/ADB-and-Fastboot-Plus-Plus.png" width="200"></a>
<h1 align="center"><b>ADBKit</b></h1>
<h4 align="center">Pure ADB (Android Debug Bridge) with Batch Script to easily open a CMD Window</h4>
<br />

<p align="center">
<a href="https://forum.xda-developers.com/t/tool-windows-adb-fastboot-march-2022.3944288/" alt="XDA Thread"><img src="https://img.shields.io/badge/XDA-Thread-orange.svg"></a>
<a href="" alt="Latest Release"><img src="https://img.shields.io/github/v/release/K3V1991/ADBKit?color=blueviolet&label=Latest%20Release"></a>
<a href="" alt="Downloads"><img src="https://img.shields.io/github/downloads/K3V1991/ADBKit/total?color=green&label=Downloads"></a>
<a href="https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=HW8B98TVDLKWA" alt="Donate-PayPal"><img src="https://img.shields.io/badge/Donate-PayPal-blue"></a>
<a href="https://github.com/K3V1991/Donate-Crypto" alt="Donate-Crypto"><img src="https://img.shields.io/badge/Donate-Crypto-yellow"></a>
</p>
<hr>
<br />
<br />

## NFO:
* Android Debug Bridge & Fastboot updated to latest v1.0.41 (Version 33.0.1-8253317, March 2022)

## Features:
* Pure ADB (Android Debug Bridge)
* Open CMD.bat to easily open a Command Prompt
* Only 5.87MB (compressed 2.73MB)

## Requirements:
* Windows OS
* USB Driver for your Device or Universal ADB Driver (Included in the Installer)

## Enable Developer Options & USB Debugging:
1. Install the USB Driver for your Phone or Universal Adb Driver
2. On your Phone, go to Settings > About Phone. Find the Build Number and tap on it 7 times to enable Developer Options
3. Now enter System > Developer Options and find "USB debugging" and enable it
4. Plug your Phone into the Computer and change it from "Charge only" to "File Transfer" Mode
5. On your Computer, browse to the Directory where you extracted the ADBKit Zip
6. Launch a Command Prompt with Open CMD.bat
7. Once you’re in the Command Prompt, enter the following Command:
```
adb devices
```
8. System is starting the ADB Daemon (If this is your first Time running ADB, you will see a Prompt on your Phone asking you to authorize a Connection with the Computer. Click OK.)
9. Succesful enabled USB Debugging

## Unable to connect to ADB:
1. AMD Bug - [XDA Thread](https://forum.xda-developers.com/t/fix-fastboot-issues-on-ryzen-based-pcs.4186321/)
2. Switch Device from "Charging" to "File Transfer" Mode
3. Install the latest Device Driver or Universal USB Driver
4. Try another USB Cable
5. Use another USB Port (USB 3.0 Port to USB 2.0)
6. Try to execute Fastboot Command without connecting your Phone, and once it says "waiting for device" plug in your USB Cable
7. Windows: Click "Change advanced power setting" on your chosen Plan and expand "USB Settings". Under "USB Settings" Section, expand "USB selective suspend setting" and change it to "Disabled" for On Battery and Plugged In
8. Try another PC

## Usage:
1. Download latest Release
2. Extract the Zip Archive
3. Double click on Open CMD.bat
4. You should see a Command Window open, now you can use ADB Commands
