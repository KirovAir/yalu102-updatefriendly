# yalu102-updatefriendly

![Yalu logo](https://github.com/kpwn/yalu102/blob/master/yalu102/Assets.xcassets/AppIcon.appiconset/AppIcon60x60@3x.png?raw=true)

This is a modified build to make updating to 10.3.3 possible.
iOS jailbreak for 64-bit devices created by [qwertyoruiopz](https://twitter.com/qwertyoruiopz) and [marcograssi](marcograss).

## This is only usable to update your iPhone 5s from 10.0.0 ~ iOS 10.2 to 10.3.3!
1. Jailbreak using original yalu102 (or extra_recipe what you prefer)
2. Hook your iPhone 5s to your charger if you have a shitty battery.
3. Go to Settings -> Display & Brightness -> Set autolock to __Never__.
4. Download and run Cydia Eraser. This might take a while and/or several tries. Try to reboot if it's not working.
5. Your iPhone is now stock, all data is gone.
6. Rejailbreak using __yalu102-updatefriendly__ from this repo. [DOWNLOAD HERE](https://github.com/KirovAir/yalu102-updatefriendly/raw/master/yalu102-updatefriendly.ipa) This will keep all update functionality from your device in tact.
7. Download Filza from Cydia and edit __/System/Library/CoreServices/SystemVersion.plist__
Set these values:
| Device | Version |
|---------|----------|
| ProductVersion  | 7.0.2 |
| ProductBuildVersion  | 11A501 |

8. Save and reboot!
9. Go to Settings -> General -> Software Update and 10.3.3 should appear.
10. Update & enjoy 10.3.3!
