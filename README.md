# 🎯 MarkerRacePlugin (By Alone Elxy)

This plugin adds a **"first-to-reach" marker race** mechanic to your Counter-Strike 2 server. Admins can place a marker on the map, and the first players to reach it within the defined limit will be declared winners. Others will be automatically eliminated.

## 📦 Requirements

- [CounterStrikeSharp (CSS)](https://github.com/roflmuffin/CounterStrikeSharp)

## ⚙️ Installation

1. Place the plugin DLL in:  
   `cs2/addons/counterstrikesharp/plugins/`
2. Restart the server or use hotreload.

## 💬 Commands

| Command | Description |
|--------|-------------|
| `!ilk <1-9>` / `css_ilk <1-9>` | Admin command to place a marker. First N players to reach it will win. |
| `!ilkiptal` / `css_ilkiptal` | Cancels the currently active marker. |

> ⚠️ Only admins with the `@css/generic` permission group can use these commands.

## 📸 Screenshot

> *(You can include a screenshot or a short GIF here to showcase the marker and beam effect.)*

## 🛠 Developer Info

- **Author:** Alone Elxy
- **Version:** 1.0.0
- **Module Name:** `Alone Elxy ILK 1`

## 📝 License

This plugin is open-source and free to use in non-commercial CS2 server projects. Please give proper credit to the author when using or modifying it.

---

🖤 If you find this plugin useful, please consider giving it a ⭐ on GitHub!
