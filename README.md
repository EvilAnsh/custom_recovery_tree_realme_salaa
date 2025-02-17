# Device Tree for Realme 7 (salaa)
![Realme 7](https://fdn2.gsmarena.com/vv/pics/realme/realme-7-1.jpg)

|Basic               |Spec Sheet                                                    |
|--                  |--                                                            |
|CPU                 |Octa-core (6x2.0 GHz Cortex-A55 & 2x2.05 GHz Cortex-A76)      |
|Chipset             |MediaTek MT6785 Helio G95                                     |
|GPU                 |ARM Mali-G76 MC4                                              |
|Memory              |4/6GB RAM                                                     |
|Android Version     |12 (RUI3)                                                     |
|Storage             |64/128GB                                                      |

## Working Feature
- Vibration/Haptic 
- Flashing .img/zip
- ADB Sideload
- Terminal/Console
- External Storage (SD and OTG)

## Bugs and Issues
- Internal Storage (Encrypted, if lockscreen is enable.)
- Internal Storage (Decrypted, if lockscreen is disable.)
- MTP; might need to disable and enable mtp button to work.

## Notes
- If you see error like, especially when you are in Stock ROM: `Failed to mount /partition_name (Invalid Argument)`, please ignore it for now. It was due to erofs as file-system of this device (and most of recent Realme devices)
- Kernel Source: [Stormbreaker-Kernel-salaa](https://github.com/stormbreaker-project/kernel_realme_salaa)
       (...if you want to build recovery with Kernel Source.)


## Credits
- TeamWin Recovery Project (Source)
- SkyHawk Recovery Project (Source)
- PitchBlack Recovery Project (Source)
- OrangeFox Recovery Project (Source)
- SebaUbuntu for the generated device tree.
- To all of the tester who patiently test and send logs.
  - 一護 黒崎
  - AdamsProStudio
  - Ivan Avetisov

Telegram Community: https://t.me/realme7global
