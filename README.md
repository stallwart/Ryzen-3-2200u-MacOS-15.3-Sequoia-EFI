# Ryzen 3 2200U Hackintosh EFI for macOS Sequoia

This repository contains the EFI files needed to run macOS Sequoia on systems with AMD Ryzen 3 2200U processor.

## 💻 Hardware Specifications

- **CPU:** AMD Ryzen 3 2200U
- **iGPU:** AMD Radeon Vega 3
- **Recommended macOS Version:** Sequoia (14.x)

## ✅ What Works
- CPU Power Management
- Graphics Acceleration
- USB Ports
- Audio
- Battery Management
- Keyboard & Touchpad
- Wi-Fi (with compatible card)
- Bluetooth (with compatible card)
- Sleep/Wake

## ❌ What Doesn't Work
- Built-in AMD Radeon Vega 3 Hardware Acceleration (Software rendering only)
- Apple Services (iMessage, FaceTime, etc.)
- DRM Content (Apple TV+, Netflix in Safari)

## 📝 Installation Guide

1. Create a bootable macOS Sequoia USB installer
2. Copy the EFI folder to your USB's EFI partition
3. Boot from USB and install macOS
4. After installation, copy the EFI to your system's EFI partition

## ⚙️ BIOS Settings

- Disable Secure Boot
- Disable Fast Boot
- SATA Mode: AHCI
- Enable EHCI/XHCI Hand-off
- Disable Serial/COM Port

## 🛠️ Post-Install

1. Install all necessary kexts
2. Generate new SMBIOS
3. Apply necessary patches for AMD processor
4. Fix sleep issues if any

## ⚠️ Disclaimer

- Use at your own risk
- I am not responsible for any damage to your hardware
- This EFI is specifically configured for Ryzen 3 2200U
- Always backup your data before installation

## 🔄 Updates

- Check this repository regularly for updates
- Follow the releases section for stable versions

## 🤝 Contributing

Feel free to:
- Open issues
- Submit pull requests
- Share your improvements
- Report bugs

## 📜 License

This project is licensed under the MIT License - see the file for details.

## 💝 Support

If this EFI helped you, please consider:
- Giving this repository a star ⭐
- Sharing it with others who might need it
- Contributing to make it better

## 📞 Contact

For support or questions:
- Open an issue in this repository
---
**Note:** This EFI is maintained by the community. Please ensure you understand the risks of Hackintosh before proceeding.
