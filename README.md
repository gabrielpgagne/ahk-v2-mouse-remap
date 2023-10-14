# ahk-v2-mouse-remap

This repo is an extremely simple [ahk v2](https://www.autohotkey.com/docs/v2/index.htm) that remaps mice side buttons 1 (_Back_) and 2 (_Forward_) to Shift and Ctrl, respectively.

In my case, this is useful because I use a lot of Ctrl- and Shift- shortcuts, but on-board memory mode does not work properly if you set these keys. And on Linux, it seems that onboard memory is the only way to use the side buttons.

## Setting up

The following allows you to get set up and launch the script on Windows personal session startup.

- Make sure you have AHK **V2** installed, if not, refer to [Required software](required-software)
- Clone the repo somewhere on your PC
- `winkey-R` : enter `shell:startup` in the prompt
- Create a shortcut that links to `mouseRemap.ahk` in the `Start-up` folder that was opened

**Example shortcut**

- `Target` : `C:\Users\<your_username_here>\Documents\AutoHotkey\mouseRemap\mouseRemap.ahk`
- `Start in` : `C:\Users\<your_username_here>\Documents\AutoHotkey\mouseRemap`

## Required software

- AHK V2, available [here](https://www.autohotkey.com/)
