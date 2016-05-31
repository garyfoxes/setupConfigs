# setupConfigs

# ADB COMMANDS
emulator -avd Android4 -dns-server 8.8.8.8
adb install < path_to_apk_file> (installs apk to device or emulator)

adb shell pm list packages(gets all package names on your device)
adb shell pm path com.whatsapp(gets the path of the apk on the device)
adb pull /data/app/com.whatsapp-21.apk C:\Users(copies apk to your laptop at a specified destination)

adb kill-server
adb start-server
