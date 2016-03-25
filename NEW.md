# Setting up a new Mac

This is the process I went through after getting a new Mac. Here I do my best to document every little thing I did to get into a comfortable working state.

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
20. Remap quit for Google Chrome
  - System Preferences > Keyboard > Shortcuts > App Shortcuts
  - Add entry with menu title: "Quit Google Chrome" and pick desired shortcut (`cmd` + `option` + `q`
21. Install Bartender 2
  - Download here: https://www.macbartender.com/
  - Launch and configure settings
22. Install apps from app store
  - DaisyDisk, Wunderlist, Evernote, Dashlane
23. Make apps launch on startup
  - System Preferences > Users & Groups > Login Items
  - Alfred 2 (hide)
  - Bartender 2 (hide)
  - Microsoft Outlook
  - Divvy (hide)
  - RDM (hide)
  - Wunderlist
  - Utilities > Activity Monitor
24. Update desktop
  - Find a wallpaper you like: https://www.reddit.com/r/wallpaperdump/top/?sort=top&t=all
  - System Preferences > Desktop & Screen Saver
  - Select wallpaper
25. Hide desktop icons
  - Run this in your terminal: `defaults write com.apple.finder CreateDesktop -bool false`
  - This will not take affect until you restart
26. **Checkpoint: Restart your laptop to make sure things launch in a sane way, also verify there are no desktop icons**
27. Install homebrew
  - http://brew.sh/
28. Install mosh
  - Run in terminal: `brew install mosh`
29. Generate new ssh key and add to github
  - Run in terminal: `ssh-keygen`
  - Add to public key to github
  - Edit local ssh config to tell which github key to use
    - http://superuser.com/questions/232373/how-to-tell-git-which-private-key-to-use
30. Setup terminal aliases etc.
  - https://github.com/kyldvs/konfig
31. Add alias for devserver to `~/.ssh/config`
32. Verify ablitiy to connect to devserver through terminal
33. Verify ability to connect to devserver through atom (nuclide)
34. Setup nuclide settings
  - `cmd` + `shift` + `o` for file open
  - `atom-material-ui` ui theme
  - `monokai` syntax theme
35. Setup spaces
  - Three fingers swipe up
  - Top far right, click + twice in order to create a total of 3 spaces
  - Three fingers swipe left/right to move between them
36. Open atom on space 2
  - Long press atom icon in dock > options
  - Select "This Desktop"
37. Open iTerm on space 3
  - Long press iterm icon in dock > options
  - Select "This Desktop"

[Check out more about my workflow here!](workflow.md)
