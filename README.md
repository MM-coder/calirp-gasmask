# FiveM Gask Mask Script v2.5
A FiveM gas mask script.

## Description
By wearing a gasmask (configurable in the config) you become immune to tear gas. 

## Commands
`/gasmask on` - puts on

`/gasmask off` - takes off

`/gasmask` - toggles

## Images
![Equipped](https://cdn.discordapp.com/attachments/695031619819536565/786382849699741716/gasmask1.PNG)

![Unequipped](https://cdn.discordapp.com/attachments/695031619819536565/786383093165850654/gasmask2.PNG)

## Videos
https://i.gyazo.com/74d939211e350472aeac709fb4e5feb5.mp4

https://i.gyazo.com/03e2d847fcadf741a61db0f5d4dd0a60.mp4

## Installation
* Drop the **fivemgasmask-master** folder in your resources directory
* Open the `config.lua` file in **fivemgasmask-master** and set things to your liking
* Add `start fivemgasmask-master` to your **server.cfg**
* Restart server

## Changes in Fork:
* Removed ACE permissions, as anyone should be able to be protected from gas
* Renamed client.lua to cl_gasmask.lua
* Replaced __resource.lua with fxmanifest in accordance with Cfx.re guidance
* Some formatting changes in cl_gasmask.lua

## Improvements in v2.5
* Using ace_perms now. (Find older versions [here](https://github.com/JellyJamm/fivemgasmask/releases))
* Inputting a command is no longer required. If you are wearing the config mask, the script activates.
* Optional hud display

## Improvements in v2
* Added config
* If using a ped, equips an actual gas mask (configurable in the config.lua)
* Given the option to toggle the gasmask opposed to using on and off 

## Recommended Script
https://docs.badger.store/fivem-discord-scripts/discordaceperms

*Ties Ace Perms to Roles in a Discord Server*

## Contributions
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[GNU GPL 3.0](https://github.com/JellyJamm/fivemgasmask/blob/main/LICENSE)
