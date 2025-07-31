## Supported boards

Soc | Boards |
|:--|:--|
| Allwinner H2+ | Orange Pi Zero/R1 |
| Allwinner H3 | Orange Pi One/Lite/Pc/PcPlus/Plus/Plus2E/ZeroPlus2 | 
| Allwinner H5 | Orange Pi Pc2/Prime/ZeroPlus/ZeroPlus2| 
| Allwinner H6 | Orange Pi 3/3 LTS/Lite2/OnePlus| 
| Allwinner H616 | Orange Pi Zero2 | 
| Allwinner H618 | Orange Pi Zero3 (with secure boot support) |
| Rockchip RK3328 | Orange Pi R1Plus/R1Plus LTS| 
| Rockchip RK3399 | Orange Pi 4/4B | 

## Security Features

This build system now includes enhanced security features for Orange Pi Zero3:

- **Full Disk Encryption (LUKS2)**: Protects data when SD card is removed
- **Secure Boot Chain**: Verifies boot integrity and detects tampering  
- **Hardware Crypto Acceleration**: Uses ARM Cryptography Extensions
- **Tamper Detection**: Monitors for physical and logical security events

See [SECURITY.md](SECURITY.md) for detailed security documentation.

### Quick Secure Build

```bash
# Build secure image for Orange Pi Zero3
sudo ./build.sh secure

# Setup encryption on device  
sudo orangepi-secure-setup
``` 

## Download links

- 中文链接：     http://www.orangepi.cn
- English link：http://www.orangepi.org
