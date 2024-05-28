# Hercules macrofix

This patch to the Anubis Hercules module for DCS fixes the macro system. It adds a mapping of all the command_defs into a range starting at 8000 and listens for these actions. The change was inspiried by Summit60/DCS-Hercules-TheWay-patch-v1.01 however that patch lacks most of the available actions. This is implemented in a way to introduce as little change as possible to the Herc module so it appends the change to pre-existing files command_defs and Radios_control. 

## Installation

This fix only requires the Anubis Hercules Mod v 6.8.2. Unzip the files into your DCS Saved_Games directory, eg C:\Users\<user>\Saved Games\DCS.openbeta. If you have any changes to command_defs.lua or Radios_control.lua files, then applying this patch may interfere with your changes. You'll need to merge this manually. If you have a pristine install of Anubis Hercules 6.8.2 then you will be fine.

## Acknowledgements

Anubis Hercules Mod discord: DCS Super Herc Mod
Summit60 https://github.com/Summit60/DCS-Hercules-TheWay-patch-v1.01
