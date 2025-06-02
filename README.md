# Garena Delta Force Mobile (com.garena.game.df) - Game Data Dump

Welcome to the data dump repository for **Garena Delta Force Mobile**! This repository contains reverse engineering assets and data extracted from the game, intended for research, modding (if permitted by the game's EULA), or educational purposes.

## 📜 License

This work is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).

## 📝 Content Description

This repository contains reverse engineering assets for the Unreal Engine 4 mobile game:

* **Reverse Engineering Headers**:
  - `AIOHeader.hpp`: Combined C++ header with game structures
  - `Offsets.hpp`: Memory offsets for game functions and classes
* **Il2Cpp Metadata**:
  - `script.json`: Il2Cpp metadata in JSON format
* **Game Object Information**:
  - `Objects.txt`: List of game objects and their properties
* **Extraction Logs**:
  - `Logs.txt`: Tool output and extraction process records

* **Game Version**: `1.203.37102.1401`
* **Unreal Engine Version**: `4.x`
* **Tools Used**: `AndUEDumper by MJx0`

## 🛠️ How to Use

This data is provided "as is" for reverse engineering purposes:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/eikarna/deltaforce-dump.git
   cd deltaforce-dump
   ```

2. **For Reverse Engineering**:
   - Use `AIOHeader.hpp` and `Offsets.hpp` in your game mods/trainers
   - Open with C++ compatible editors (VS Code, Visual Studio, Rider)
   - Combine with memory editing tools (Game Guardian, Cheat Engine)

4. **For Game Objects Reference**:
   - Consult `Objects.txt` for game object hierarchies
   - Use `Logs.txt` to understand extraction context

## ⚠️ Warnings and Disclaimers

* **GAME COPYRIGHT**: All game assets, trademarks, and copyrights belong to Garena International. This repository contains only reverse-engineered data for educational purposes.
* **GAME EULA**: Comply with the game's End User License Agreement. Using this data for cheating or unfair advantage may violate terms of service.
* **NO WARRANTY**: Data accuracy not guaranteed. Game structures may change with updates.
* **USE RESPONSIBLY**: Intended for legal reverse engineering research only.

## ❤️ Credits and Attribution

Game data collected and organized by:  
[**Eikarna**](https://github.com/eikarna)

If you use this data, please attribute:  
`Data sourced from eikarna/deltaforce-dump`

## 🤝 Contributions

Contributions welcome! Please open an Issue or Pull Request for:
- Updated offsets for new game versions
- Corrections to header files
- Additional extracted game data
- Improved documentation
