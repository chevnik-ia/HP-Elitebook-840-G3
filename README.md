# HP-Elitebook-840-G3 Hackintosh


![](https://img.shields.io/badge/Working-yes-green)
![](https://img.shields.io/badge/Latest%20supported-Big%20Sur%20Public%20Beta%201-orange)
![](https://img.shields.io/github/issues-raw/GGorAA/Hackintosh-840?color=yellow)
![](https://img.shields.io/github/issues-pr/GGorAA/Hackintosh-840)

# Hackintosh 840

В этом репозитории находяться настройки для HP EliteBook 840 G3 Хакинтош. Возможно этот EFI совместим с другими ноутбуками из линейки EliteBook (не проверено.)

## Compatibility table

### If the macOS version is not included in this list, it means that that version is not supported

| macOS Codename | macOS Version      | Support | Planned support | Stability |
| -------------- | ------------------ | ------- | --------------- | --------- |
| Big Sur        | 11.0 Public Beta 1 | Yes     | Yes             | Stable    |
| Big Sur        | 11.1               | Yes     | Yes             | Stable    |
| Big Sur        | 11.2               | Yes     | Yes             | Stable    |
| Big Sur        | 11.2.3             | Yes     | Yes             | Stable    |
| Big Sur        | 11.4               | Yes     | Yes             | Stable    |


## Working components

| Component | Component model        | State                 |
| --------- | ---------------------- | --------------------- |
| Wifi      | Intel Wireless AC 7265 | Working               |
| Bluetooth | Intel Wireless AC 7265 | Working with wifi off |
| Graphics  | Intel HD Graphics 520  | Working               |
| Sound     | Bang&Olufsen           | Working               |
| Battery   | N\A(Stock)             | Working               |
| Trackpad  | Synaptics              | Working               |

## Known bugs

 - Apple TV/TV+ doesn't work
 - The "Charger connected" sound plays only in headphones

 If you want to contribute, feel free to create issues and pull requests!

 ## Installation
 
Mount the encrypted EFI partition and place the EFI folder there. Replace the Information in Config. plist/platformminfo with the OpenCore Configurator application. It is very important.
