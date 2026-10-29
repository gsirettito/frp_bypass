# frp_bypass by samfw

<a href="https://samfw.com/blog/samfwtool"><img src="https://samfw.com/assets/img/logo_spin.gif"/></a>

# SamFW Tool Features

A Windows-based utility for managing and unlocking Samsung, Xiaomi, LG, and other Android devices via ADB, MTP, Download Mode, EDL, and more.

## Main Functions

- **Remove FRP with one click:** Bypass the Google account lock (Factory Reset Protection) in a single step.
- **Change CSC with one click:** Switch the region/consumer software customization code.
- **Remove FRP for new security patch (Aug 2022 and later):** Supports devices with recent security updates.
- **Remove FRP paid method:** Paid service option for unlocking FRP on all models and versions.
- **Read info, Factory reset, Reset FRP:** Basic diagnostic and reset operations.

## Features by Brand / Connection Mode

### Samsung

- **MTP Mode:**
  - Read device information (Android version, FRP status, IMEI2, security patch level) [reference:0][reference:1].
  - Factory Reset (2 methods).
  - Enable secret code for Verizon phones (e.g., `*#06#`, `*#0*#`) [reference:2].
  - Disable Knox.
  - Open browser (YouTube, Google Maps, Samsung Browser) [reference:3].

- **ADB Mode:**
  - Remove FRP (2 methods).
  - Read full device information.
  - Change CSC (includes list of supported CSC codes).
  - Disable/Enable OTA updates.
  - Application management: install APK/xAPK, install as Dual Messenger, remove bloatware [reference:4].
  - Battery information (OneUI 8+, charge cycles) [reference:5].
  - Set language, hide developer options, open network settings [reference:6][reference:7].

- **Download / Odin Mode:**
  - Odin flashing (auto-detect files, auto-extract firmware) [reference:8].
  - Read information in Download Mode [reference:9].
  - Reboot to Download Mode, Recovery Mode, or Normal Mode.
  - Exit Download Mode / Fix soft-brick [reference:10].

- **Test Mode (`*#0*#`):**
  - Remove FRP for new security patches [reference:11].
  - Disable Factory Mode [reference:12].
  - Change CSC.

- **EDL (9008):**
  - Read info, Factory Reset, Reset FRP [reference:13].
  - Partition manager (Read/Write/Erase) [reference:14].

- **Exynos FRP Unlock:**
  - Supports Exynos chipsets: 850, 880, 980, 990, 1080, 1280, 1330, 1380, 1480, 1580, 1680, 2100, 2200, 2400, 2500, 2600, W920, W930, W1000 [reference:15].

### Xiaomi

- **ADB:** Bypass Mi Cloud (Android 8.1), enable Diag [reference:16].
- **Sideload:** Factory Reset, Remove FRP, Reset Mi Cloud, bypass Mi Cloud (Anti-relock) [reference:17].
- **EDL 9008:** Factory Reset, Reset FRP, Reset Mi Cloud.
- **Fastboot:** Remove FRP (only on unlocked devices) [reference:18].

### LG

- **MTP:** Factory Reset.
- **EDL (supports G7, G8, G8X, G8S, V30, V40, V50, V50S, Q6, G5, G6, V20, V35, V60):** Factory Reset, Remove FRP [reference:19].
- **LG UP:** Flash KDZ firmware [reference:20].

### Android (Generic)

- **ADB:**
  - Battery info (ASOH and BSOH) [reference:21].
  - Disable/Enable OTA updates.
  - Set language, Factory Reset, hide developer options, open network settings.
  - Application manager (delete, disable, clear data).
  - Install multiple APK/xAPK files [reference:22].
- **ROOT:** Remove screen lock (root required) [reference:23].

### Qualcomm

- **EDL 9008:** Partition manager (Read/Write/Erase), Reset FRP, Factory Reset, Erase userdata [reference:24].

### MediaTek

- **Functions:** Factory Reset, Format userdata, Remove FRP, Unlock/Relock bootloader, Bypass Auth [reference:25].

### Apple (iPhone/iPad)

- **Basic support:** Read information in Normal/Recovery/DFU mode, reboot to Recovery or Normal mode [reference:26].

## Other Utilities

- **Driver management:** Auto-install Samsung USB drivers and Visual C++ 2015 [reference:27].
- **Driver signature check:** Verify and disable/enable Windows driver signature enforcement [reference:28].
- **User interface:** Button descriptions on hover, automatic log saving, minimize to system tray [reference:29][reference:30].

---

*This list summarizes the documented capabilities of SamFW Tool. Note that some features are model, Android version, or security patch-specific. Use the tool at your own risk.*
