#Personal project. Please do not apply on your system before understanding what each command does.
I personally run the script with debloat only and install any additional programs I need later

WARNING: Strongly recommended to setup a strong password before running this script.

# win10script
This is the Ultimate Windows 10 Script from a creation from multiple debloat scripts and gists from github. 

## Tweak Additions

- Dark Mode
- One Command to launch and run
- O&O Shutup10 CFG and Run
- Added Debloat Microsoft Store Apps

## Feel free to add your own modifications
I encourage people to fork this project and comment out things they don't like! Here is a list of normal things people change:
- Uninstalling OneDrive (This is on in my script)
- Installing Adobe, Chocolatey, Notepad++, MPC-HC, and 7-Zip



Comment any thing you don't want out... Example:

```
########## NOTE THE # SIGNS! These disable lines This example shows UACLow being set and Disabling SMB1
### Security Tweaks ###
	"SetUACLow",                  # "SetUACHigh",
	"DisableSMB1",                # "EnableSMB1",

########## NOW LETS SWAP THESE VALUES AND ENABLE SMB1 and Set UAC to HIGH
### Security Tweaks ###
	"SetUACHigh",
	"EnableSMB1",
```
