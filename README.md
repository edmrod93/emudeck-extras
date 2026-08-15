# 🎮 EmuDeck Extras

A collection of extra files for **EmuDeck**, including a BIOS pack and AppImages for emulators or applications that are no longer included with EmuDeck.

> **SteamOS / Steam Deck focused**

---

## 📦 Releases

### 🧩 Removed AppImages

Replacement **AppImage files** for emulators or applications that are no longer included or easily available through EmuDeck.

### 📥 Downloads

**[➡️ Browse AppImages Release](https://github.com/edmrod93/emudeck-extras/releases#release-appimages)**
Download individual AppImages from the release assets.

**[⬇️ Download All AppImages (.zip)](https://github.com/edmrod93/emudeck-extras/archive/refs/tags/appimages.zip)**
Download the entire AppImages release as a ZIP archive.

### Installation

1. Download the AppImage you need from the **AppImages release**.
2. Switch to **Desktop Mode**.
3. Place the `.AppImage` file inside:

```text
/home/deck/Applications/
```

4. Make sure the AppImage is **executable**.
5. Do **not** extract the AppImage itself.
6. Launch **EmuDeck**.
7. **Reset the corresponding emulator** so EmuDeck recreates its configuration using the replacement AppImage.

---

### 💾 BIOS Pack

A pre-organized **BIOS pack** designed to be placed directly into your EmuDeck BIOS directory.

### 📥 Downloads

**[➡️ Browse BIOS Release](https://github.com/edmrod93/emudeck-extras/releases#release-BIOS)**
Download individual BIOS files and archives from the release assets.

**[⬇️ Download Complete BIOS Pack (.zip)](https://github.com/edmrod93/emudeck-extras/archive/refs/tags/BIOS.zip)**
Download the entire BIOS release as a ZIP archive.

### Installation

1. Download the **BIOS pack**.
2. Extract the downloaded archive.
3. Locate your EmuDeck BIOS folder:

```text
Emulation/bios/
```

4. Back up your existing BIOS folder if needed.
5. Copy the downloaded BIOS files into `Emulation/bios/`.
6. Choose **Replace / Overwrite** when prompted.
7. Open **EmuDeck** and use the **BIOS Checker** to verify your files.

> **Important:** Do not accidentally create an extra nested BIOS folder.

Incorrect:

```text
Emulation/bios/bios/
```

Correct:

```text
Emulation/bios/
```

---

## 📂 Quick Reference

| Package      | Location                   | Download                                                                                                                                                                          |
| ------------ | -------------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 🧩 AppImages | `/home/deck/Applications/` | **[Release](https://github.com/edmrod93/emudeck-extras/releases#release-appimages)** · **[Full ZIP](https://github.com/edmrod93/emudeck-extras/archive/refs/tags/appimages.zip)** |
| 💾 BIOS      | `Emulation/bios/`          | **[Release](https://github.com/edmrod93/emudeck-extras/releases#release-BIOS)** · **[Full ZIP](https://github.com/edmrod93/emudeck-extras/archive/refs/tags/BIOS.zip)**           |

---

## ⚠️ Disclaimer

This repository is intended to provide additional files for **EmuDeck setups** where certain components are no longer bundled or readily available.

BIOS files may be copyrighted. Only use BIOS files that you are **legally permitted to use**, such as dumps made from hardware you own.

This project is not affiliated with or endorsed by **EmuDeck**.
