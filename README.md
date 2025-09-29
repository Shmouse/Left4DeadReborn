# 🔧 Left 4 Dead Reborn – External Enhancements Pack

This repository contains **essential modifications** that cannot be distributed via the Steam Workshop due to platform limitations. These enhancements are designed to work **alongside the official [Left 4 Dead Reborn collection](https://steamcommunity.com/sharedfiles/filedetails/?id=2845732576)** and unlock advanced gameplay logic, configuration control, and realism effects.

> ⚠️ **SourceMod and ReShade is required** for installing this pack.  
> Install SourceMod from the official site: [https://www.sourcemod.net/downloads.php](SourceMod.net)  
> Install ReShade from the official site: [https://reshade.me/](ReShade.me)

---

## 🧩 Features Enabled by This Pack

When installed alongside the modpack, this repository activates:

- 👁️ **Left 4 Dead Reborn ReShade**
  - **Three** Custom ReShade Presets (with effects folder)
    - 🏝️ Reborn
    - 📸 Reborn Cam
    - 🌓 Reborn Cam w/ NightVision

- ✅ **Custom configuration file setups** for all VScript-based mods in the collection  
  *(Integrated into the balancing addon; pending full validation)*

- ✅ **Custom configuration files for all SourceMod plugins**  
  *(Ensures consistent logic and behavior across all gameplay scenarios)*

- 🔁 **Struggle out of incapacitation & self-revive mod**  
  - Modified version of *StruggleLeft4Dead* for solo play  
  - Includes a tailored config file for balance and realism

- 🤖 **Bot support for struggle/self-revive**  
  - Bots can now recover themselves using the same logic

- ☠️ **Permanent death logic for players and bots**  
  - Enforced via SourceMod scripting  
  - No respawns once a survivor dies

- 👻 **Dead players can take control of alive bots**  
  - Keeps gameplay flowing even after death

- 🔦 **L4D2 Realism Flashlight mod with custom config**  
  - Flashlight intensity decreases with battery
  - Flashlight glitching increases with the draining battery
  - Shoving recharges the battery  
  - Adds immersive tension and tactical depth

---

## 📦 Installation Instructions

1. **Download this repository as a ZIP** from GitHub.
2. **Extract the contents** of the ZIP file to your L4D2 root directory 
- C:\Program Files (x86)\Steam\steamapps\common\Left 4 Dead 2\
- The folder structure mirrors the L4D2 root for seamless integration.
3. **Install ReShade Shaders** by running the ReShade installer as normal but three times against all three config files, installing the "Normal" one last to make it the default.
4. **Start the game** and ensure ReShade (HOME key) and SourceMod are active and working as intended ("sm plugins list" in the console **in-game**).

---

## 🛠 Troubleshooting & Notes

- Ensure SourceMod is correctly installed before launching the game.
- If configs don’t load, verify file paths and plugin activation.

---

## 🧠 Why This Exists

Steam Workshop restrictions prevent certain script types, plugin logic, and config files from being distributed directly, I also don't want to flood the workshop description with any more junk. This pack ensures that all gameplay enhancements envisioned in the Reborn collection are fully realized.

---

## 💬 Feedback & Contributions

If you encounter issues or want to contribute improvements do feel free to voice your opinion. These systems are modular by design—let’s evolve it together.


