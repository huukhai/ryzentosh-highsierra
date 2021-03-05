![Screenshot](/cover.png?raw=true)

**macOS HIgh Sierra**: 10.13.6 (17G11023) Dual Boot w/ **Windows 10**: 1909 64Bit

**OpenCore version**: 0.5.6  

## Specification
| **Component** | **Model** |
| ------------- | --------- |
| CPU | AMD Ryzen 5 3600 @ 3.6GHz |
| Motherboard | MSI B450 Pro VDH MAX |
| GPU | NVDIA GTX 1060 6Gb |
| RAM | 16GB Gskill RIPJAWS @ 3000MHz |
| OS Disk (SSD) | Fuhler 500GB |

### Software
1. gibMacOS: https://github.com/corpnewt/gibMacOS
2. SSDT Time: https://github.com/corpnewt/SSDTTime
3. GenSMBIOS: https://github.com/corpnewt/GenSMBIOS 
4. Kexts archive: [https://onedrive.live.com/?authkey=%21APj...](https://onedrive.live.com/?authkey=%21APjCyRpzoAKp4xs&id=FE4038DA929BFB23%21455036&cid=FE4038DA929BFB23)
5. Kext descriptions: https://kb.amd-osx.com/guides/MJ/kexts.html
6. ProperTree: https://github.com/corpnewt/ProperTree

## Installation
  1. Create directory "EFI" in your EFI partition (e.g. pendrive or hard drive)
  2. Clone this repo and paste directiories "BOOT" and "OC" onto created directory
  3. Download [**GenSMBIOS**](https://github.com/corpnewt/GenSMBIOS) to generate unique SMBIOS information. Run it and select 
  4. Open config.plist with [**ProperTree**](https://github.com/corpnewt/ProperTree) and go to PlatformInfo > Generic. Set MLB  (Board Serial), SystemSerialNumber (Serial) and SystemUUID (SmUUID) to generated values.
  5. Enjoy :)
