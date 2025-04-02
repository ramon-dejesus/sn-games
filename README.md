<p align="center">
  <img src="./logo.png" alt="SN Games Logo" width="250">
</p>

# 🕹️ SN-Games – ServiceNow Widget Pack

A scoped application offering responsive, interactive game widgets for the ServiceNow Service Portal. Built with AngularJS and fully customizable via widget options to match your brand or Service Portal theme.

Developed and maintained by **DE JESUS SERVICES, INC.**  
GitHub: [https://github.com/ramon-dejesus](https://github.com/ramon-dejesus)  
Contact: [ramon@dejesus.services](mailto:ramon@dejesus.services)

---

## 📦 Release 1: Tic Tac Toe

This initial release features a fully functional **Tic Tac Toe** game:

- 👯 PvP (Player vs Player) Mode
- 🤖 PvC (Player vs CPU) Mode – win/block strategy
- 🔄 Alternating start between X and O
- ♿️ Fully 508-Compliant: keyboard accessible, screen-reader friendly
- 🎨 Customizable via Widget Options
- ♻️ Reset Button
- 🌐 Scoped for clean deployments

> Future releases will expand this repository with more classic and custom games, all designed for seamless integration into the Service Portal.

---

## 📖 Table of Contents

- ➤ [Prerequisites](#-prerequisites)
- ➤ [Folder Structure](#-folder-structure)
- ➤ [Build & Usage](#-build--usage)
- ➤ [Release 1 Details](#-release-1-details)
- ➤ [Widget Options](#-widget-options)
- ➤ [Customization Notes](#-customization-notes)
- ➤ [Contributors](#-contributors)
- ➤ [Licensing](#-licensing)

---

## 🍴 Prerequisites

To run this scoped widget, you’ll need:

- ServiceNow Paris+ instance (tested on Tokyo & Vancouver)
- Access to Studio & Service Portal
- AngularJS 1.x support (OOTB with Service Portal)
- Scoped app import permissions

---

## 🌵 Folder Structure

```
sn-games/
│
├── tictactoe/
│   ├── widget/
│   │   ├── TicTacToe.html
│   │   ├── TicTacToe.js
│   │   ├── TicTacToe.css
│   │   ├── TicTacToe.server.js
│   │   ├── WidgetOptionSchema.json
│   │   └── DemoData.json
│   ├── manifest.xml
│   └── README.md (this file)
│
├── scoped-app.xml              # Import into Studio
├── LICENSE
└── COMMERCIAL_LICENSE.md
```

---

## 🏗️ Build & Usage

1. **Clone this repo**
```bash
git clone https://github.com/ramon-dejesus/sn-games.git
```

2. **Import into ServiceNow Studio**
   - Go to **System Applications > Studio**
   - File → Import from XML → select `scoped-app.xml`

3. **Deploy the Widget**
   - Go to **Service Portal > Pages**
   - Add the `TicTacToe` widget to a desired page
   - Configure widget options (branding, font, etc.)

---

## 🚀 Release 1 Details

🔖 Release Name: `v1.0.0`  
📅 Release Date: 2025-04-02  
🎮 Game Included: **Tic Tac Toe**

✅ **Release 1 Epics & Features** ([View GitHub Issues](https://github.com/ramon-dejesus/sn-games/issues)):

- [✔️ Scoped deployment under `x_sn_games` namespace](https://github.com/ramon-dejesus/sn-games/issues/1)
- [✔️ Player vs Player and Player vs CPU logic](https://github.com/ramon-dejesus/sn-games/issues/2)
- [✔️ Turn-based flow with CPU logic and alternating turns](https://github.com/ramon-dejesus/sn-games/issues/3)
- [✔️ 508-compliance with keyboard & screen reader support](https://github.com/ramon-dejesus/sn-games/issues/4)
- [✔️ Reset button and game mode toggle](https://github.com/ramon-dejesus/sn-games/issues/5)
- [✔️ Custom branding via widget options](https://github.com/ramon-dejesus/sn-games/issues/6)

---

## 🧩 Widget Options

| Option Name            | Type     | Description                                                              |
|------------------------|----------|--------------------------------------------------------------------------|
| `default_game_mode`    | `string` | Either `pvp` or `pvc` (defaults to `pvp`)                                |
| `background_color_hex` | `string` | Optional background color hex (e.g. `#ffffff`)                          |
| `font_color_hex`       | `string` | Hex code for font color (e.g. `#000000`)                                |
| `font_family`          | `string` | Font family used in the game display                                    |
| `logo_url`             | `string` | URL of logo displayed under the game                                    |
| `provider_url`         | `string` | Link when logo or provider is clicked (defaults to GitHub)              |

---

## 🎨 Customization Notes

- All options are non-destructive. You can override them without editing code.
- Visual elements (reset button, turn indicator) adapt to theme colors.

## 📜 Contributors

👦 Ramon De Jesus  
    Email: [ramon@dejesus.services](mailto:ramon@dejesus.services)  
    GitHub: [@ramon-dejesus](https://github.com/ramon-dejesus)  
    Role: Architect, Developer, and Sole Contributor

---

## 📌 Looking ahead...

We plan to include more classic games like:

- 🎲 Connect Four
- ♠️ Memory Match

Want to contribute or suggest a game idea?  
✨ Fork it. Build it. PR it.

---

## 🔐 Licensing

This repository is released under a **dual license model**:

- 🆓 **Creative Commons Attribution 4.0 International (CC BY 4.0)**  
  For non-commercial and educational use with required attribution. See [`LICENSE`](../LICENSE).

- 💼 **Commercial License Required for Business Use**  
  Any commercial, enterprise, or revenue-generating usage requires a commercial license with agreed royalties or fees.  
  See [`COMMERCIAL_LICENSE.md`](../COMMERCIAL_LICENSE.md) or contact [ramon@dejesus.services](mailto:ramon@dejesus.services) to obtain permission.

© 2025 DE JESUS SERVICES, INC. All rights reserved.
