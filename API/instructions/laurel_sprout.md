# Dirty Flash / Update
- Download ROM and Recovery to your computer
- Reboot the device to bootloader (Fastboot Mode) [Skip if already using PixelOS recovery]
- Flash the recovery by running "fastboot flash recovery <path/to/recovery.img>" in terminal [Skip if already using PixelOS recovery]
- Reboot to recovery by running "fastboot reboot recovery" in terminal
- On your phone [which is in recovery mode], Apply update > Apply from ADB
- Flash the ROM through ADB sideload by running "adb sideload <path/to/rom.zip>" in terminal
- Reboot and voila!
