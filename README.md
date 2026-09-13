# Better-Story-Timer

![Better Story Timer banner](banner.png)

# Better Story Timer — The Blood of Dawnwalker Mod

[![Latest Release](https://img.shields.io/github/v/release/IdentityCuckoo/Better-Story-Timer?style=flat-square&color=red&label=latest)](https://github.com/YOUR_USERNAME/Better-Story-Timer/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/IdentityCuckoo/Better-Story-Timer/total?style=flat-square&color=blue)](https://github.com/YOUR_USERNAME/Better-Story-Timer/releases)
[![License](https://img.shields.io/badge/license-MIT-yellow?style=flat-square)](LICENSE)
[![Game](https://img.shields.io/badge/game-The%20Blood%20of%20Dawnwalker-purple?style=flat-square)]()
[![Nexus Mods](https://img.shields.io/badge/Nexus%20Mods-profile-orange?style=flat-square)](https://www.nexusmods.com/profile/Caites)

**Remove the rush. Play the story at your own pace.**

A quality-of-life mod for **The Blood of Dawnwalker** that extends the main quest timer, increases time segments, and removes time costs from traits and skills.

> **Current version:** `1.0.5` — Compatible with game version 1.0.5.

---

## ⬇️ Download

All files are distributed **only through GitHub Releases**.

👉 **[Download the latest version](https://github.com/IdentityCuckoo/Better-Story-Timer/releases/latest)**

---

## ✨ Features

- **90-Day Main Quest Timer** — Extends the default deadline. Adjustable in `game.ini` (any reasonable integer).
- **16 or 32 Time Segments** — Doubles or quadruples the original 8 segments per day.
- **No Time Cost for Traits & Skills** — Spend points freely. All other costs remain untouched.

### Key Benefits
- Achievement safe — does not break achievements.
- Non-Steam compatible (GOG and others; path may differ).
- Safe mid-playthrough. Recommended to uninstall during epilogue.
- Read-only config protection.
- Lightweight, no performance impact. No dependencies (experimental version requires UE4SS).

---

## 🔧 Installation

> Detailed install instructions are included inside each release archive as `INSTALL.txt`. Below is the quick summary.

### 1. Pick your version

You need **ONE** timer version and **optionally** the traits version.

| Version | What it does |
|---------|--------------|
| 90 Days | Main quest extended to 90 days |
| 32 Segments | Daily segments increased from 8 to 32 |
| 90 Days + 16 Segments | Balanced setup |
| No Time Cost for Traits/Skills | Removes time cost from traits and skills |
| Configurable (Experimental) | UE4SS-based, fully configurable |

> **Recommended setup:** 90 Days + No Time Cost for Traits/Skills.

### 2. Install timer

1. Download the archive from [Releases](https://github.com/IdentityCuckoo/Better-Story-Timer/releases/latest).
2. Extract `Game.ini`.
3. Copy it to:
   ```
   %LOCALAPPDATA%\Dawnwalker\Saved\Config\Windows
   ```
4. Set the file to **read-only**.

### 3. Install optional traits version

1. Extract `.pak`, `.utoc`, `.ucas`.
2. Place them in:
   ```
   ...\steamapps\common\The Blood of Dawnwalker\Dawnwalker\Content\Paks\~mods
   ```
3. Create `~mods` if it doesn't exist.

### 4. Install experimental version (advanced)

1. Install **UE4SS** for The Blood of Dawnwalker.
2. Copy `BetterStoryTimerConfigurable` into:
   ```
   ...\Dawnwalker\Binaries\Win64\ue4ss\Mods
   ```

---

## ⚙️ Configuration

To change the number of days:

1. Uncheck **Read-only** on `Game.ini`.
2. Edit `StoryTimerDays` to any reasonable integer.
3. Save and set **Read-only** again.

Do not change `SegmentsPerDay` unless you understand every property in the file.

---

## 🗑️ Uninstallation

- Timer: delete `Game.ini` from `%LOCALAPPDATA%\Dawnwalker\Saved\Config\Windows`.
- Traits: delete `.pak` / `.utoc` / `.ucas` from `~mods`.
- Experimental: delete `BetterStoryTimerConfigurable` from `UE4SS/Mods`.

---

## 🤝 Compatibility

| Mod type | Compatible | Notes |
|----------|:----------:|-------|
| Texture / Graphics | ✅ | No conflicts |
| Other timer mods | ⚠️ | May conflict |
| Trait-editing mods | ❌ | Conflicts with optional traits (except Better Shadowstep) |
| UE4SS-based mods | ✅ | Experimental version only |
| Achievement enablers | ✅ | No issues |

---

## ❓ FAQ

**Will this break my achievements?** No.
**Can I install mid-playthrough?** Yes for timer. Install traits before allocating points.
**Does it work with GOG?** Yes, path may differ.
**Timer didn't change?** Make sure `Game.ini` is in the right folder and set to read-only.
**Can I use 90 days AND 32 segments?** Yes, but not recommended.

---

## 🎮 My Other Mods

Better Shadowstep · Combat Tweaks · Faster Leveling and More Traits · Better Carry Weight · Configurable Loot Quality · Focus Tweaks · Duelist with Directional Cues · Seamless UI Scaler and Colorblind Mode · Day Stalker Night Walker · Fast Travel To Any Marker · Better Enemy UI - HP and Level · No Level Scaling · Movement Tweaks · Slowmo And Pause

Full list: [Nexus Mods profile](https://www.nexusmods.com/profile/Caites)

---

## 🙏 Credits

- **Author:** Caites
- **Game:** The Blood of Dawnwalker by Rebel Wolves / Bandai Namco
- **Engine:** Unreal Engine 5
- **Tools:** UE4SS team
- **Community:** Nexus Mods Dawnwalker community

---

## 📜 License

MIT — see [LICENSE](LICENSE).

You may use, modify, and redistribute. Credit the original author.

---

## ⭐ Support

- ⭐ Star this repo
- 👍 Endorse on Nexus Mods
- 🐛 Report bugs via [Issues](https://github.com/IdentityCuckoo/Better-Story-Timer/issues)

---

**Keywords:** The Blood of Dawnwalker mod, Better Story Timer, Dawnwalker timer mod, 90 days mod, no time limit, trait time cost, Dawnwalker QoL, Rebel Wolves mod, UE5 mod, Nexus Mods Dawnwalker, UE4SS mod.
