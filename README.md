# Volume Steps+ 1.3.0 for Magisk 17.0++

 ## How to use:
- Open Therminal Emulator App in your phone
- Write command: su
- Write command: VoSte
- Follow instructions in Therminal loaded script
- For example edit Media Steps Value: Write su =>VoSte => a => number (your value) =>reboot => done

## Description:
### Raises the Volume Step counts to:
- In Call Volume:	10 (callsteps) 
- Media Volume:		25 (mediasteps)
- Set Safe Media Bypass to True 
- You can change all these values in Terminal by command: VoSte
- Terminal Comman is: VoSte

### After install will module add systemlessly these Values to the build.prop (but you can change it later) :
- ro.config.vc_call_vol_steps=10
- ro.config.media_vol_steps=25
- audio.safemedia.bypass=true

## Requirements:
- Magisk 17.0 or higer
- If module do not work for you try install - BusyBox Magisk Module

## Warning:
- Maybe Won't work on Samsung Stock ROMs!!

## Tested and working on:
- Xperia XZ Oreo Stock ROM - with Magisk 17.3
- Xperia Z5 Compact LineAgeOS 14.1 - with Magisk 18.0

# Changelog:
## Version 1.3.0
  - module code optimalization and fixes
  - support reboot from module
  - to select in menu you have multiple options for one function ect-1/a/A for media volume steps

## Version 1.2.0 - 1.2.5
  - bug fixes
  - compatibility for Magisk GitHub Repo

## Version 1.1.1 - 1.1.2
  - just few little fixes, nothing big
  - edit of module style
  - added selection: q - for Exit
  - fixed use instructions

## Version 1.0.0
  - Initial Release 1.0(0)