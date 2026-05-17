# Galaxy A35 Disable Force Encryption
## Disable File Encryption (DFE) for s5e8835 (Exynos 1380)
This is a custom recovery-flashable script designed to disable file-based encryption (FBE v2) on Samsung device with the s5e8835 SoC. This fix "0 MB internal storage" issues, and removes /data encryption.

## Use with caution.
I haven't tested on Galaxy M33 5G. but it will probably work.

## Supported Device
- Samsung Galaxy A35 5G
- Samsung Galaxy M33 5G
## Installation
1. Boot into custom recovery
2. Copy SM-A356N_DFE.zip to your device. Recommended path is on '/tmp'
3. Install as zip
4. Format /data when prompted (required to fully disable encryption).
5. Reboot to system.

## Developer Notes
This script was written with the help of OpenAI, especially for the EROFS handling.
This modifies your vendor and super partitions, and it will nuke your /data too, so please back up your data.

## License
This project is licensed under the [MIT License](https://github.com/Lyinceer/SM-A556E_DFE/blob/main/LICENSE).

## Credits
- [blackeangel](https://github.com/blackeangel) for UKA utils.
- And to all Contributors in every repositories and scripts I used.
