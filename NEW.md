# From scratch

This is the process I went through after getting a new Mac. This is installation and configuration of the mac.

1. Setup Chrome
  - Open and log in to Chrome
  - Let extensions and configuration sync
2. Allow installing third party packages
  - System Preferences > Security & Privacy
  - Select and save "Allow apps downloaded from anywhere"
3. Only require password 5 seconds after lock
  - System Preferences > Security & Privacy
  - Select and save "Require password 5 seconds after sleep or screen saver begins"
4. Install RDM __(controls resolution of screen)__
  - https://github.com/avibrazil/RDM
5. Launch RDM and change resolution to desired setting
6. Launch and sign in to Mac App Store
7. Install Divvy __(window manager for mac)__
8. Enable accessability for Divvy
  - System Preferences > Security & Privacy > Privacy > Accessibility
  - Add/Enable Divvy
9. Launch Divvy and add desired shortcuts
  - Make sure to enable screen cycling when repeatedly hitting a shortcut
10. Hide Dock
  - System Preferences > Dock
  - Update desired settings: Left, Automatically hide and show the Dock
11. Configure Spaces
  - System Preferences > Mission Control
  - Disable "When switching to an application, switch to a Space with open windows for the application"
  - Disable "Automatically rearrange Spaces based on most recent use
  - Enable "Displays hav eseparate Spaces"
12. Consistent graphics (automatic switching sometimes causes bugs in Chromium apps)
  - System Preferences > Energy Saver
  - Disable "Automatic graphics switching"
13. Make F1, F2, etc. the default.
  - System Preferences > Keyboard
  - Enable "Use all F1, F2, etc. keys as standard function keys"
14. Disable autocorrect, it sucks.
  - System Preferences > Keyboard > Text
  - Disable "Correct spelling automatically"
15. Allow tabbing through all controls
  - System preferences > Keyboard > Shortcuts
  - Enable "All controles" in "Full Keyboard Access: ..."
16. Install Alfred __(a much better spotlight)__
  - Download here: https://www.alfredapp.com/
17. Launch Alfred
18. Disable spotlight
  - System Preferences > Keyboard > Shortcuts > Spotlight
  - Disable all spotlight shortcuts
19. Configure Alfred settings
  - Launch with `cmd` + `space`, and other settings
  - Activate Powerpack if you have it
  
TODO: Make things launch on startup (RDM, Divvy, Activity Monitor, Outlook, Wunderlist)

TODO: Multiple screens and swiping between spaces
  
