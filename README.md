# Changelog 3.1

Miscellaneous changes:
- Enable Smart battery
- Allow disable of Screenshot sound
- Enable 3 modes in Location QS tile
- Redesigned Settings UI to A11 look alike

Fixes that are done:
- Fix various required permission to default apps for better experience
- Fix battery stats getting resetted on reboot
- Various Lockscreen bottom shortcut fixes
- Fixed some issues to SystemUI tuner
- Fixed Lockscreen charging issues
- Fixed ripple animations on side mounted FP devices

Newly added things:
- Added Lawnchair as default launcher
- Added Increasing ring feature
- Added Octavi Lab
- Added Reset battery stats button
- Added Caffeine tile
- Added AOD tile
- Added USB tether tile
- Added Sync tile
- Added Sound tile
- Added Screenshot tile
- Added heads-up tile
- Added Data switch tile
- Added haptic feedback to QS tiles
- Added animations on QS tiles
- Added Interpolators to QS tiles
- Added advance power menu toggle
- Added Double tap 2 sleep on statusbar
- Added Double tap 2 sleep on lockscreen
- Added long press power to toggle torch
- Added volume rocker wake
- Added volume key music control
- Added option to orient volume buttons in landscape
- Added option to hide power menu on secured lockscreen
- Added Heads-up customisations
- Added less boring heads-up
- Added Smart QS pull 
- Added Statusbar clock/date customisations
- Added toggle to enable/disable running services in QS
- Added toggle for wake on plug
- Added Incall vibrations
- Added Traffic Indicator
- Added Hardware key customisation support
- Added Notification light customisations
- Added lockscreen visualiser
- Added brightness slider customisations
- Added battery bar 
- Added Carrier label customisations
- Added navigation Gestures customisation
- Added Double tap to wake on Doze
- Added battery light customisations
- Added navbar customisations
- Add Dash/Warp/VOOC/SuperDart charging support
- Added battery styles customisations
- Added smartspace
- Forward port CM settings

Note : There are much more changes than these are we don't remember so... Good luck finding them


---

---

---

---



# Changelog 3.0

* Welcome Android 12 (Initial release)
* Added Monet implementation from ProtonAOSP
* Redesigned Settings Homepage
* Added a user card on homepage
* Introduced Greeter (Insulter basically xD)
* Enabled 2 Button navigation bar
* Added 3 finger Screenshot
* Introduced PixelPropUtils 
* Enabled Themed icons 
* Added overlays so Google apps are following monet too (Update Google apps from play store after flash)
* Reduced screenshot dismiss delay time
* Enabled one hand mode by default (Swipe on navbar)
* Added min and Max refrest rate options
* Added Double tap 2 sleep in Octavi Launcher
* Enabled Mic and Camera toggle tiles
* Enabled A12 beta features (Ripple on charge and unlock)
* Added overlays to make Power menu more consistent with UI
* Something else that I might forgot

Note: Features will be added from next release with Octavi Lab addon. Till then no spam for it.


---

---

---

---


# Changelog for 2.9.1

* Merged October Security patch (r48)
* Fixed QS rows value stuck at default isssue
* Fixed icons overlapping in "Manage available keyboards" section
* Removed the media art blurred filter in QS 
* Fixed settings indent issue for color pickers
* Made greetings qoutes a bit nicer
* Misc changes that doesn't make sense adding here


---

---

---

---


# Changelog for 2.9

New Things added
- Merged r43 September security patch
- Added Statusbar beighness control gesture
- Added notch city from POSP (3 mode cutout handler)
- Added Media notification background for QS media player
- Added Cloudflare DNS as a private DNS provider
- Added a network permission group for Internet
- Added a special runtime permission for sensors
- Added seekbar or Statusbar padding (no more icon cropping)
- Added an option to record longer in Screenrecord (can record upto 15GB now)
- Added hotspot clients feature
- Added Memory view in Recents panel
- Added Kill app button in Recents panel

Fixes done with this update:
- Fixed CTS with September patch
- Improved AppLock
- Fixed the pattern issue with collapsing toolbar
- Removed OTA notification coz spamming as hell 
- Fix clock icon in few icon packs
- Fixed Theming options getting reset to default on reboot
- Improved FPS counter 
- Fixed Expection errors with Android S clocks
- Fixed Null pointer error in Volume Plugins
- Improved Android S clock
- Made animations a bit humane 
- Fixed touch area in Volume panel for caption and ringer button while in landscape mode
- Fixed FOD position if cutout is hidden
- Fixed search bar background appearance in toolbar in Octavi Dialer
- Fixed Call history crash in Octavi Dialer
- Fixed a crash when u tap on Manage conference in Octavi Dialer
- Fixed the inconsistent indents among preferences in Settings 
- Fixed the name being small in Settings homepage header

Redesigned stuff
- Redesigned Dark mode page in settings
- Redesigned AOSP Clock app

There might be some other changes I forgot to add. 

Note for Unofficial builder: 
`Before starting the build make sure to add your device data in settings . Take a look at https://github.com/Octavi-OS/Bringup/blob/11/Bringup.mkdn`


---

---

---

---


# Changelog:2.8

* Merged r40 August Security Patch
* Changed Lockscreen Font to Default
* Added custom font support to third party apps
* Introduced LiveDisplay
* Added LiveDisplay Tile
* Added ReadingMode Tile
* Added AntiFlicker Tile
* Added FaceUnlock Changing Method when Locked
* Added Legacy WFD Output video mode Settings
* Added Octavi*OS Logo in Statusbar
* Added FOD Animations
* Added Custom Fingerprint Icon Option
* Added Flipendo to Battery Saver QS Tile
* Improvements in ShapeShift VolumePanel
* Renamed OOS volume panel to Nezuko panel (coz they made this one)
* Fixed the Scrolling issues in Running services page
* Fixed the Buggy Virtual keyboard UI
* Fixed the overlap issue in footer for RTL languages
* Fixed About phone page scrolling issues for small screen size devices like Sanders
* Fixed About phone camera info text cutting when 4 or more camera infos are present
* Fixed the battery page text getting cut
* Fixed the Dialer app crashing while swapping sim
* Improvements to re*ticker crash on notification pop up
* Fixed the QS music area getting blank with Re*ticker on (Probably)
* Fixed media card in qs not behaving well with G*Visual mode
* Fixed dialer toolbar and switches issues in light theme
* Added Dark mode support in Contacts app
* Fixed an issues where in lower DPI Hello,User gets out of screen while toolbar is in Collapsing mode. Re wrote the collapsing logic
* Changed default wall

Redesigned stuff :
* Redesigned Lab UI to more minimal and clean look
* Redesigned Dialer speed dial cards to match OOS UI

`Note : As we said Dialer will be open-sourced now but seeing the community using patched apk much instead of stopping the chain of spreading. It's decided that only In-call UI and fixes will be OSS. Speed dial UI will be octavi only thing`


---

---

---

---


# Changelog: 2.7

* Merged July Security patch (r39)
* Updated Gapps to newest
* Fixed an issue in calling with both aosp dialer and Googler dialer in different devices 
* Fixed an issue Bluetooth in some devices
* Added OOS Volume plugin
* Added P404 Volume plugin
* Added Shapeshift OS Volume plugin
* Fixed Wifi display / Cast with old legacy devices (Source side)
* Fixed Battery page text getting cut in low DPI
* Fixed an issue where the toolbar gets white in Octavi clear theme
* Fix the crash when you try to change keyboard
* Fix the issue Settings FC sometimes randomly due to overlay 
* Fixed the crash that occurs when you open running services in Developer options
* Fixed the misalignments in setting texts 

` (Note: There are few misalignments still there. We are finding a way to fix that but they are dynamic and we can't find a way to track them because others like them from same category follows our implementation)`

* Fix an overlay issue in app info where the toolbar gets overlapped 
* Fix the Google card getting cut at bottom of the settings homepage
* Fixed battery percentage not showing inside or outside with toggle
* Fixed the charging animation not showing on lockscreen
* Fixed some icons getting black on lockscreen 
* Added preference for maximum screen refresh rate
* Added S style clock
* Added A12 DP3 clock
* Fixed a few logspam for better bug report
* Fixed Lockscreen showing Dual charging info 

` Now let's talk about Dialer UI, The whole UI is inspired from OOS. The following are the changes `
* Added empty page illustration from OOS
* Re*designed Incall UI layout like OOS
* Added OOS like BG alpha animation when call is picked
* Added OOS in call icons
* Re*designed Incoming call screen
* Revamped swipe options to "Swipe right to delete" & "Swipe left to Text" 

` For making this Dialer open source on github it will be publically available after August patch release. We still need to complete it with some small but nice stuff... And we are trying to do it. `


---

---

---

---


# Changelog: 2.6

Dated : 23/06/2021

*  Merged June Security patch
*  Nukes all icons and iconspaces to make the UI consistent (Thnx to DOT for implementation idea)
*  Added Collapsing toolbar from DOT OS
*  Made sound seekbar same as brightness slider
*  Adapted OctaviLab with New Toolbar
*  Added categories in various parts of Settings
*  Fix an issue where the wellbeing card text gets cut in lower dpi
*  Introduced About Team page
*  New dialer UI from nezuko
*  Added Swipe To Call Feature on AOSP Dialer
*  Added new app icons from posp
*  Added Runtime Audio Panel Location Toggle
*  Reverted to AOSP Volume Panel Style
*  Added MIUI Compact Volume Panel Plugin 
*  Added Swap Volume Buttons Options
*  Reverted Old PowerMenu Customizations
*  Added New Powermenu Advanced Toggle
*  Added PowerMenu Background Opacity Option 
*  Added Option for Ambient Instead of Lockscreen on Wake Gestures
*  Added Extended "L" Back swipe to trigger action/app/activities
*  Improved RGB Accenter Code [3.0]
*  Added Option to Show and Edit Ambient Icons on Lockscreen
*  Added Lockscreen Clock Widget Fonts
*  Added Lockscreen Date Fonts
*  LS OwnerInfo Font & Size Option
*  Added Lockscreen Clock/Date Styles
*  Added Q Style Text Clock
*  Added Sammy,Analog,Q Beta Pill, Bootleg Date, X Clock Styles
*  Added Translations for TextClock
*  Added Option to Disable Led after Full Charging
*  Make Quick Unlock Compaitable for Pin/Password
*  Added Option for Power button predd fp unlock toggle 
*  Added Octavi*Ambient Doze Options
*  Added Ambient Customizations
*  Moved permission dialog box to bottom


---

---

---

---


# Changelog: 2.5

* Fixed Crash on changing toggles values from Settings
* Fixed crashes got introduced in 2.4
* Fixed Crash on switching between gesture and navbars
* Removed useless scrollbar and Overglow on homepage
* Redesigned Storage Header from OOS
* Show Octavi Ascii logo while flashing
* Fix Settings UI getting fucked on dirty flash
* FIX ALT clock showing wrong Salute message
* Improvement in Alt clock
* Improvement in IDE clock
* Removed useless Gradient definition 
* Added Sync QS tile
* Fixed Color Statusbar icon toggle not working sometimes
* Allow system to use real security patch level property
* Increased 5GHz network signal tolerance
* Improved Back gesture machine learning model
* Added memory usage info in App info page
* Fixes to Blur radius in system 
* More sepolicy side fixes to make ROM amazing for both Builders and Users
* Added Sony's Volte icon
* Fix OctaviLab going on top when u switch categories
* Fix scrolling cache not working 
* Add back Doze/AOD in notification category
* Force set QS ROW count to 2 when media player is enabled 

Changes in OctaviLauncher :

* Removed extra space in Dock/Hotseat
* Added option to change icon size along with user customizablity through seekbar
* Delink Font size in launcher 
* Add misisng permissions 
* Improved Swipe down to notification gesture

`There are more changes that either we dont remember or is on too low level that it doesnt makes sense to add that in changelog

Note : There are no UI changes because from yesterday's Poll people chose and supported us to move to minimal UI. And all the UI changes will be there in future updates.`


---

---

---

---


# Changelog: 2.4

Dated : 07/05/2021

*  Merged May Security patch
*  Launcher3 : Icon pack sizes
*  Launcher3 : Removed bottom hotseat padding
*  Asus screenshot : Updated app.
*  Asus screenshot : Removed some Google components
*  Asus screenshot : Screenshot options use accents
*  Tapping QS battery opens battery settings
*  New machine learning back gestures for gamers
*  Fixes for custom clocks
*  Ambient music animation
*  Optional colored sb icons 
*  Options colored notification icons
*  Nuked fod background (not needed with icon picker)
*  Keep used screenrecord settings 
*  Optional QS media player as notification
*  Whitelist apps for persistent QS media player
*  Address some bugs on bt, biometric unlock and camera 
*  Allow non market apps installation by default
*  Added the ability to whitelist apps for persistent QS media player
*  Introduced a new type of icons in settings page to chose from  (MIUI)
*  Fixed name getting too big
*  Fixed qs clock fading away on dark bg 
*  Redesigned OctaviLab and Rearranged OctaviLab
*  Redesigned battery page meter
*  Added IDE Clock and java IDE Clock


Note : Octavi clock from last release and Octavi Lab from this release are publically available for unofficial builds.


---

---

---

---


# Changelog: 2.3

Dated : 24/04/2021

Source Changes:
* OxygenOS 11 QS Footer layout is now added in octavi for better accessibility 
* Added collapsebar in settings 
* Rebased vendor with new implementations for better integration 
* Reverted AndroidS MediaPlayer View to old A11 view 
* Added QS Style Tint Option with more options like OOS / Accent / Android S
* Added Navbar Styles Option
* Added Settings Icon option now you can give your settings a new look with this 
* Added OctaviOS LockScreen Clock (Thanks to Madness)
* Added Toggle To Disable FP Icon on Lockscreen and moved it under weather 
* Implemented GVisual Mod Navbar Color
* New Implementation of PerApp Network Isolation
* Add Support for global cleartext penalties
* Wifi Timeout Feature
* Bluetooth Timeout Feature
* Few FOD Fixes
* Added Few FOD Icons
* Added TouchGestures
* Add Option to instantly lock app on Closing
* Fixed the crash in using AppLock when you don't have FP/Face registered
* Improvements to AppLock code
* Added a call to hide ringer button if your device has Alert slider (OnePlus devices)
* Optimization to Appinfo page creation
* Fix bug on High contrast text
* Fix creation of brightness thumb on diff icon packs
* Imported entity headers from OOS 
* Fixed an issue where content goes behind toolbar and yet visible 
* Fixed Volume panel animations a bit
* Various improvements in sepolicy of source
* Added Option to Disable StatusBar on Lockscreen 
* Improved Vanilla Clock app to match Google clock UI
* Rebased Launcher3 From ShapeshiftOS 
* Added some translations in octavi lab


---

---

---

---


# Changelog: 2.2

* April Patch
* A hell lot of Translations (Thanx to those who contributed)
* Redesigned stock Calculator app (Use vanilla to get it) and its open source 
* Fixed the issue where some devices can't have playback, either it gets black screen or it freezes
* Fixed an issue where ANX crashes on some devices due to mediaplayer function error
* Introduced Android S media player QS slice from Project * 404
* Added Applock from AOSPA
* Added Android S like QS tinting from Project * 404
* Removed old QS tinting switch in favour of S style tinting 
* Added ReTicker from Descendants (Still WIP)
* Added Shapeshift LS clock
* Added Biometric Authentication in Applock
* Implemented new Face Unlock with support in Applock from PE
* Enabled IORAP by default
* Disabled Fullscreen keyboard in landscape mode (It was annoying)
* Removed some annoying warning / Confirmation dialog boxes
* A bit of more optimization that doesn't matter to add in changelog but gonna improve the user experience while using the ROM itself


---

---

---

---


# Changelog: 2.1

Dated : 05/03/2021

Source Changes:
* Merged March Security Patch
* Added MIUI Type Headers In Settings
* Added GVisual Mod
* Added Option for Gesture Bar Radius
* Added Sensor block package list configurable
* Added AboutUs App (Check in System)
* Added Smart Pixels
* Reimplemented FOD Commits  
* Added Few More FOD Icons
* Fixed PowerOff Torch Completely
* Fixed Bubble Crash Issue
* Added FPS Info Tile
* Added CPU Info Tile
* Fixed NetworkTraffic Indicator on Light Theme
* Updated DND,Aeroplane,Hotspot and few statusbar Icons
* Fixed Issues With VoWifi Icons
* Added Option for Gesture Bar Radius
* Fixed Crash on Receiving Notification on Ambient Display
* Improved Notification Header Toggle
* Added Option to Swipe up for Face Unlock
* Fixed Old Mobile Type Icon
* Added Long Press Header Date to access calendar
* Added Long Press Header clock to access Clock App
* Reverted Use App Icon instead of md2 icon on statusbar
* Added InCall Vibration Options


---

---

---

---


# Changelog: 2.0

Dated : 14/02/2021

Source Changes:
* Merged February 2021 security patch 
* Fixed That 24 Hours QS Clock Bug on Left Side
* Fixed PowerOff Torch
* Fixed Notification Not Clearing after Clicking on Delete
* Added OctaviLauncher
* Added GoogleDialer With Call Recording Support ( Only in Gapps Build)
* Added 2 New Brightness Slider Styles 
* Added New QS Clock Style (Pill Clock)
* Added Signature Spoofing Toggle
* Added Toggle To Hide Lockscreen Icon
* Added FaceUnlock Animation From Descendants
* Added Coloured Notification Icon on Statusbar from Descandants
* Added UserIcon In Center in Settings Homepage
* Added Option to Disable Notification Vibrations
* Added Option to Disable all headsup for Gaming Mode
* Option to make ringtone audio focus customizable
* Improved Ambient Pulse and Notification Pulse
* Ported AmbientNow Playing from Pixel
* Option to Change the Music Ticker Position
* New Implementation of Old Style Mobile Data Indicators
* Added LongScreenshot
* Added VibrationPattern From OOS
* Added Clipboard Toast Toggle
* Added Option to Hide Lockscreen Shortcut
* Implemented Alert Slider
