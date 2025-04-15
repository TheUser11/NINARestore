# NINARestore
NINARestore is an iOS (App Store installed) AIM patcher for NINA for iOS/iPadOS 15.2 - 16.7 RC (20H18) and 18.0(.1). It will replace the default aim_servers.plist file with a modded one to connect to NINA. This is primarily for users who don't wish to be locked to a seven day limit for sideloading (this requires the app to be installed from the App Store, under purchase history. if you never purchased the app when it was availible, welp.). NINARestore makes use of backups via [CVE-2024-44252](https://support.apple.com/en-us/121563#:~:text=Mina%2C%20Ismail%20Amzdak-,MobileBackup,-Available%20for%3A%20iPhone) in order to replace the file in the AIM app. Based on [TrollRestore](https://github.com/JJTech0130/TrollRestore) (if your device supports trollstore, i recommend just using that.)

# Usage
To run the script, clone this repository and run the following commands:
```sh
pip install -r requirements.txt
python3 trollstore.py
```

# Post-installation
Just open the AIM app and sign in with your NINA credentials! Easy!

# Notes
It should theoretically support iOS 14 and iOS 15.0 - 15.1.1, but during our testing, we experienced issues restoring the backup to an iOS 14 device, and later also found the same issues with devices on iOS 15.0 - 15.1.1. Therefore, using NINARestore on a device below iOS 15 has been disabled for the time being.

todo: remove trollstore branding

# Known Working Devices
 - iPad 10 on 18.0.1
 - iPad Air 2 on 15.8.4