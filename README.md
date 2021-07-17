Changelog:
# 2.7
- Merged July Security patch (r39)
- Updated Gapps to newest
- Fixed an issue in calling with both aosp dialer and Googler dialer in different devices 
- Fixed an issue Bluetooth in some devices
- Added OOS Volume plugin
- Added P404 Volume plugin
- Added Shapeshift OS Volume plugin
- Fixed Wifi display / Cast with old legacy devices (Source side)
- Fixed Battery page text getting cut in low DPI
- Fixed an issue where the toolbar gets white in Octavi clear theme
- Fix the crash when you try to change keyboard
- Fix the issue Settings FC sometimes randomly due to overlay 
- Fixed the crash that occurs when you open running services in Developer options
- Fixed the misalignments in setting texts 

` (Note: There are few misalignments still there. We are finding a way to fix that but they are dynamic and we can't find a way to track them because others like them from same category follows our implementation)`

- Fix an overlay issue in app info where the toolbar gets overlapped 
- Fix the Google card getting cut at bottom of the settings homepage
- Fixed battery percentage not showing inside or outside with toggle
- Fixed the charging animation not showing on lockscreen
- Fixed some icons getting black on lockscreen 
- Added preference for maximum screen refresh rate
- Added S style clock
- Added A12 DP3 clock
- Fixed a few logspam for better bug report
- Fixed Lockscreen showing Dual charging info 

` Now let's talk about Dialer UI, The whole UI is inspired from OOS. The following are the changes `
- Added empty page illustration from OOS
- Re-designed Incall UI layout like OOS
- Added OOS like BG alpha animation when call is picked
- Added OOS in call icons
- Re-designed Incoming call screen
- Revamped swipe options to "Swipe right to delete" & "Swipe left to Text" 

` For making this Dialer open source on github it will be publically available after August patch release. We still need to complete it with some small but nice stuff... And we are trying to do it. `
