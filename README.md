# Hackintosh HP Prodesk 600 G1 TWR / MacPro 7.1 / Sequoia 15.0.1

<img src="https://dbi.ma/wp-content/uploads/2020/08/5.jpg" width=50% height=50%>

Successfully installed macOS Sequoia 15.0.1 (24A348) on my HP Prodesk 600 G1 with Opencore 1.0.2.

## Specs:

| Component  | Model |
| ------------- | ------------- |
| CPU  | Intel® Core™ i3-4160 Processor @ 3.60 GHz  |
| Architecture  | Haswell  |
| Graphics  | Intel® HD Graphics 4400 / RX 570 4GB  |
| RAM  | 16GB DDR3 1600MHz  |
| Storage  | Crucial 250GB SSD  |
| Audio  | Realtek ALC221 - layout 11  |
| Wifi / BT  | Fenvi T919  |


## Current status:

Working:

- Audio
- Graphics with RX 570 (native)
- WiFi / Bluetooth Fenvi T919 (native) Airdrop, Handoff etc
- USB

Bios setup:

- Reset bios by defaults
- Storage = SATA Emulation > AHCI
- Integreted Video = Disabled (For Ventura 13, Sonoma 14, Sequoia 15)



## IMPORTANT

Please generate a new SMBIOS (MacPro 7.1) as I deleted my serials... with https://github.com/corpnewt/GenSMBIOS
Since I don't have this PC anymore, they will be no upgrade for it.
