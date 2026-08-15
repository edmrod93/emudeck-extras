# 🎮 EmuDeck Extras

A collection of extra files for **EmuDeck**, including a BIOS pack and AppImages for emulators or applications that are no longer included with EmuDeck.

> **SteamOS focused**

---

## 📦 Releases

### 🧩 Removed AppImages

Replacement **AppImage files** for emulators or applications that are no longer included or easily available through EmuDeck.

**Installation:**

1. Download the AppImage you need from the **AppImages release**.
2. Switch to **Desktop Mode**.
3. Place the `.AppImage` file inside:

```text
/home/deck/Applications/
```

4. Make sure the AppImage is **executable**.
5. Do **not** extract the AppImage.
6. Open **EmuDeck**.
7. **Reset the corresponding emulator** so EmuDeck recreates its configuration using the replacement AppImage.

➡️ **Go to Releases → AppImages** to download the available files.

---

### 💾 BIOS Pack

A pre-organized **BIOS pack** designed to be placed directly into your EmuDeck BIOS directory.

**Installation:**

1. Download the BIOS pack from the **BIOS release**.
2. Extract the downloaded archive.
3. Locate your EmuDeck BIOS folder:

```text
Emulation/bios/
```

4. Back up your existing BIOS folder if needed.
5. Copy the downloaded files into `Emulation/bios/`.
6. Choose **Replace / Overwrite** when prompted.
7. Open EmuDeck and use the **BIOS Checker** to verify your files.

Make sure you do **not** accidentally create an extra nested folder such as:

```text
Emulation/bios/bios/
```

➡️ **Go to Releases → BIOS** to download the BIOS files.

---

## 📂 Quick Reference

```text
EmuDeck
│
├── BIOS
│   └── Emulation/bios/
│
└── AppImages
    └── /home/deck/Applications/
```

---

## ⚠️ Disclaimer

This repository is intended to provide additional files for **EmuDeck setups** where certain components are no longer bundled or readily available.

BIOS files may be copyrighted. Only use BIOS files that you are **legally permitted to use**, such as dumps made from hardware you own.

This project is not affiliated with or endorsed by **EmuDeck**.
