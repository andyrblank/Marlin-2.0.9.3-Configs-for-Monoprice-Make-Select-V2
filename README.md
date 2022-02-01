# Marlin 2.x Configuration files for the Monoprice Maker Select V2

## Special Instructions
When compiling this firmware the only error I encountered was around u8glib missing. I resolved this in the arduino (1.8.7) IDE by going to "tools -> manage libraries" and installing U8glib by Oliver Version 1.19.1

## Based On
https://github.com/MarlinFirmware/Configurations/tree/release-2.0.9.3/config/examples/Wanhao/Duplicator%20i3%202.1
And
https://reprap.org/forum/read.php?415,809741
And
https://github.com/andyrblank/Marlin-Maker-Select-V2
## Warnings
This is a work in progress. Use at your own risk.

Lightly tested only on a heavily modified Maker Select V2.

I accept no responsibility for the modifications posted here. This configuration compiles and works for my Monoprice Maker Select V2 on the original Melzi board but I have likely not tested all scenarios and modifying your firmware will void your warranty and can potentially damage your printer.
## Additional Info
Before installing this firmware I burned a bootloader on my melzi board using an Arduino Uno clone (found here: http://a.co/d/iCYILT7) and the instructions from a Youtube video here: https://youtu.be/ejpSniiJejI until about the 6:45 mark. The rest of the instructions on that video are around updating the Repetier firmware which I couldn't get the latest versions to fit on the small Melzi board so I switched to Marlin and here we are.