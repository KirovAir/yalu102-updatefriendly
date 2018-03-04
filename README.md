# yalu102-updatefriendly
iOS jailbreak for 64-bit devices created by [qwertyoruiopz](https://twitter.com/qwertyoruiopz) and [marcograssi](marcograss).

This is a modified build to make OTA updating to 10.3.3 possible __without__ blobs.

**THIS WILL ONLY WORK ON AN IPHONE 5S on 10.0.0 -> 10.2!**

## How?
- Jailbreak using original yalu102 (or any other jailbreak)
- Hook your iPhone 5s to your charger if you have a shitty battery.
- Go to Settings -> Display & Brightness -> Set autolock to __Never__.
- Download and run Cydia Eraser. This might take a while and/or several tries. Try to reboot if it's not working.
- Your iPhone is now stock, all data is gone.
- Rejailbreak using __yalu102-updatefriendly__ from this repo. ([Download here](https://github.com/KirovAir/yalu102-updatefriendly/raw/master/yalu102-updatefriendly.ipa))
This will keep all update functionality from your device in tact.

- Download Filza from Cydia and edit __/System/Library/CoreServices/SystemVersion.plist__

- Set these values:

| Key | Value |
|---------|----------|
| ProductVersion  | 7.0.2 |
| ProductBuildVersion  | 11A501 |

- Save and reboot your device!
- Go to Settings -> General -> Software Update and 10.3.3 should appear.
- Update & enjoy 10.3.3!
