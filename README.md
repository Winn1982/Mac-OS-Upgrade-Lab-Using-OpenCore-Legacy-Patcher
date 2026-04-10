<img width= "800" height="800" alt="image" src="https://github.com/user-attachments/assets/0f016ad5-c17e-4477-af86-6dd82be0dcf0" />


# Mac-OS-Upgrade-Lab-Using-OpenCore-Legacy-Patcher
## Project Overview

*Excuse the quality of some of the pictures.

This project documents the end-to-end process of upgrading a Late 2011 Mac to macOS Sequoia using OpenCore Legacy Patcher (OCLP). 

The purpose of this lab is to demonstrate real-world IT skills including:

OS deployment on unsupported hardware
Troubleshooting boot and driver issues
Following technical documentation
Creating repeatable upgrade processes

This project is designed to showcase hands-on experience relevant to entry-level IT / Help Desk roles.

## Tools & Requirements
- OpenCore Legacy Patcher (latest version)
- 16GB+ USB flash drive
- Internet connection

## Important Disclaimer

This installation method is not officially supported by Apple.

Potential risks include:

Hardware features may not function properly
- System updates may break patches
- Stability issues depending on configuration
- Always back up your system before proceeding.

## System Specifications
- Device: Late 2011 MacBook Pro
- CPU: (Intel Core i5)
- RAM: (16GB)
- Storage: (500 GB HDD)
- Original Supported OS: macOS High Sierra
- Installed OS: macOS Sequoia (via OCLP)

<p align="center"><img width="500" height="500" alt="Screen Shot 2026-04-04 at 2 53 26 PM" src="https://github.com/user-attachments/assets/5bde6c41-69e1-488e-97e4-66d4ca1871ca" />

## Step-by-Step Process
# Step 1
- Download OpenCore Legacy Patcher
- Download OCLP from the official GitHub repository
- Launch the application

<p align="center"><img width="500" height="500" alt="image" src="https://github.com/user-attachments/assets/b3f4442a-f7d0-46e1-92e4-087bf2d71578" />

<p align="center"><img width="500" height="500" alt="Screen Shot 2026-04-04 at 3 22 00 PM" src="https://github.com/user-attachments/assets/9f40685d-abd2-4596-9c20-a6bb53439625" />

<p align="center"><img width="500" height="500" alt="Screen Shot 2026-04-04 at 3 23 56 PM" src="https://github.com/user-attachments/assets/ab7c3500-a3f2-48c3-9014-8241eb166447" />

# Step 2
- Create macOS Sequoia Installer
- Use OCLP to download macOS Sequoia
- Create a bootable USB installer

<p align="center"><img width="500" height="500" alt="Screen Shot 2026-04-04 at 4 25 40 PM" src="https://github.com/user-attachments/assets/3b62fc44-72e2-49ea-9004-65738ee4dcee" />


<p align="center"><img width="500" height="500" alt="Screen Shot 2026-04-04 at 3 27 15 PM" src="https://github.com/user-attachments/assets/1eefbc03-1f4c-475e-add8-e4da10744513" />

# Step 3
- Build OpenCore Configuration
- Build and install OpenCore to the USB drive

<p align="center"><img width="500" height="500" alt="Screen Shot 2026-04-04 at 3 26 13 PM" src="https://github.com/user-attachments/assets/c33a6352-7685-4bf5-9d49-78864a15fe3e" />

# Step 4 
- Boot into OpenCore
- Restart the Mac
- Hold Option (⌥) key
- Select the EFI Boot (OpenCore) option

![patcher pic 4](https://github.com/user-attachments/assets/0c1691dc-7af8-46ef-80d4-1df169af8a17)

![pic 7](https://github.com/user-attachments/assets/557f1dbf-411b-4722-ad9a-47559c8713fd)

# Step 5
- Install macOS Sequoia
- Open Disk Utility
- Erase the target drive (APFS recommended)
- Install macOS Sequoia

![pic 9](https://github.com/user-attachments/assets/f1d39372-7f98-434e-9879-36e0ea78794f)

![patcher pic 6](https://github.com/user-attachments/assets/5d1b22f4-2646-4522-82bc-51fa35290d5e)


![pic 8](https://github.com/user-attachments/assets/39f91bf4-1ee8-4862-b369-818b524320cb)

![pic 12](https://github.com/user-attachments/assets/efc0c050-70c3-4923-930a-ae802e31ac71)

<img width="404" height="259" alt="Screen Shot 2026-04-04 at 3 44 36 PM" src="https://github.com/user-attachments/assets/8bf5e106-9bf2-4cd6-b177-9a08356b9107" />

![patcher pic 5](https://github.com/user-attachments/assets/f55f4a49-c76b-4dd5-befb-020e2fe71c4e)

# Step 6
- Post-Install Root Patching
- Launch OCLP after installation
- Apply Post-Install Root Patches
- Reboot system

![pic 17](https://github.com/user-attachments/assets/fae38b86-befa-4a88-9742-3da6dedbd8ff)

![pic 14](https://github.com/user-attachments/assets/bb79912f-7849-494b-82a9-3e7f8e28b787)

## Results & Observations
Successful Outcomes:
- macOS Sequoia installed on unsupported hardware
- System boots consistently via OpenCore
- Core functionality operational:
- Wi-Fi
- Audio
- USB devices

⚠️ Known Issues
- Graphics acceleration may be limited
- AirDrop / Handoff may not work
- Occasional UI lag depending on GPU
