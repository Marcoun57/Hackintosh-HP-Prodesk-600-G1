# Hackintosh HP Prodesk 600 G1 TWR / Sequoia 15.0.1 / OpenCore 1.0.2

<img src="https://github.com/Marcoun57/Hackintosh-HP-Prodesk-600-G1/blob/main/Prodesk%20picture.jpg" width=50% height=50%>

Successfully installed macOS Sequoia 15.0.1 (24A348) on my HP Prodesk 600 G1 with Opencore 1.0.2.

## Specs:

| Component  | Model |
| ------------- | ------------- |
| CPU  | Intel® Core™ i3-4160 Processor @ 3.60 GHz  |
| Architecture  | Haswell  |
| Graphics  | Intel® HD Graphics 4400 / RX 570 4GB  |
| RAM  | 16GB DDR3 1600MHz  |
| Storage  | Crucial 500GB SSD  |
| Audio  | Realtek ALC221 - layout 11  |
| Wifi / BT  | Fenvi T919  |


## Current status:

### Working:

- Audio
- Graphics with RX 570 (native)
- WiFi / Bluetooth Fenvi T919 (native) Airdrop, Handoff etc
- USB

### Bios setup:

1. Reset bios by defaults
2. Storage = SATA Emulation > AHCI
3. Integreted Video = Disabled (For Ventura 13, Sonoma 14, Sequoia 15)



## IMPORTANT

Please generate a new SMBIOS, I use MacPro 7.1, as I deleted my serials... with https://github.com/corpnewt/GenSMBIOS

Since I don't have this PC anymore, they will be no upgrade for it.
