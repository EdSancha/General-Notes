# General-Notes
General Notes, Shortcuts, etc

## System: 

* Fix Audio Problem in Mojave
  
  ```sudo killall coreaudiod```
  ```sudo launchctl unload /System/Library/LaunchDaemons/com.apple.audio.coreaudiod.plist && sudo launchctl load /System/Library/LaunchDaemons/com.apple.audio.coreaudiod.plist```
