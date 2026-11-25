# BTONE Effects Collection for Reaper

Professional guitar effects plugins developed by **BTONE** (Bryan Durán Badilla), designed for Reaper and installable via **ReaPack**.

## 📦 Plugins Included

| Plugin | Type | Description |
|--------|------|-------------|
| **BTONE - Tronboard** | Multi-FX Pedalboard | Complete signal chain with 46 effects across 6 categories (Dynamics, Drive, Amps, Cabs, Modulation, Delay/Reverb) in 12 serial slots |
| **BTONE 73 DRIVE** | Overdrive/Preamp | Neve 1073-style preamp with transformer emulation, tilt EQ, soft clipping, Hi-Gain & Bright switches |

---

## 🚀 Installation via ReaPack (Recommended)

### 1. Add the Repository
1. Open **Reaper**
2. Go to **Extensions → ReaPack → Import a repository**
3. Paste this URL:
   ```
   https://github.com/btonedev-coder/BTONE/raw/main/index.xml
   ```
4. Click **OK**

### 2. Install Plugins
1. Open **Extensions → ReaPack → Browse packages**
2. Search for **"BTONE"**
3. Right-click each plugin → **Install**
4. Restart Reaper (or re-scan FX)

### 3. Use in Your Projects
- **FX Browser** → Search "BTONE"
- Drag to any track

---

## 📁 Manual Installation (Alternative)

If you prefer not to use ReaPack:

1. Download this repository as ZIP
2. Extract to your Reaper **Effects** folder:
   - **Windows**: `%APPDATA%\REAPER\Effects\`
   - **macOS**: `~/Library/Application Support/REAPER/Effects/`
   - **Linux**: `~/.config/REAPER/Effects/`
3. Restart Reaper or **Options → Preferences → Plug-ins → ReScan**

---

## 🎛️ Plugin Details

### BTONE - Tronboard
**Category:** Multi-FX / Amp Modeler  
**Slots:** 12 serial slots (6 pre, 6 post)  
**Effects:** 46 modules across 6 categories:
- **Dyn & Tuner:** Compressor, Gate, Auto-Wah, Cry Wah, Tuner, Octaver
- **Drive & Boost:** Booster, TS808, Klon, Blues Driver, Super OD, Distortion, Rat, Fuzz, Muff, **73 Drive**
- **Amplifiers:** 10 amp models (Fender, Bassman, Tweed, Vox, Plexi, JCM800, Orange, Mesa, 5150, JC-120)
- **Cabinets:** 5 cab sims (1x12, 2x12, 4x10, 4x12 GB, 4x12 V30)
- **EQ & Mod:** 5-band EQ, Parametric EQ, Chorus, Flanger, Phaser, Tremolo, Rotary
- **Delay & Rev:** Digital Delay, Analog Delay, Tape Echo, Space Echo, Hall/Plate/Spring/Shimmer Reverb

**Features:**
- Drag-to-reorder slots
- Per-slot bypass
- 10 user preset banks with rename
- Neon/TRON-style GUI with real-time meters
- Full parameter automation

### BTONE 73 DRIVE
**Category:** Overdrive / Preamp  
**Controls:**
- **INPUT** (-18 to +18 dB)
- **DRIVE** (0-100, exponential curve up to 42 dB + Hi-Gain boost)
- **TONE** (Tilt EQ at 850 Hz)
- **OUTPUT** (0-100)
- **XFORMER** (Transformer saturation 0-100)
- **SOFT CLIP** (Asymmetric soft clipping 0-100)
- **HI GAIN** (Toggle: +10 dB drive)
- **BRIGHT** (Toggle: 5.2 kHz presence boost)
- **BYPASS** (Footswitch with LED)

**Signal Chain:**
`Input Gain → Transformer (HP→Body→HF) → Preamp Saturation → DC Block → Tilt EQ → Bright Boost → Soft Clip → Output LP → Level`

---

## 🔧 Requirements
- **Reaper** v6.0+ (JSFX support)
- **ReaPack** (for auto-updates)

---

## 📄 License
Proprietary - Free for personal use. Contact for commercial licensing.

---

## 👨‍💻 Author
**BTONE** — Bryan Durán Badilla  
📧 bryandev1986@gmail.com | bduranb1986@gmail.com

---

## 🔄 Updates
When installed via ReaPack, updates appear automatically in **Extensions → ReaPack → Update packages**.

---
*Made with ❤️ for guitarists who demand professional tone in Reaper*