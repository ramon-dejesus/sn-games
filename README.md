# 🕹️ SN-Games – ServiceNow Widget Pack

&#x20;

A scoped application offering responsive, interactive game widgets for the ServiceNow Service Portal.\
Built with AngularJS and fully customizable via widget options to match your brand or Service Portal theme.

Developed and maintained by **DE JESUS SERVICES, INC.**\
GitHub: [https://github.com/ramon-dejesus](https://github.com/ramon-dejesus)\
Contact: [ramon@dejesus.services](mailto\:ramon@dejesus.services)

---

## 📦 Release 1: Tic Tac Toe Widget

This initial release features a fully functional **Tic Tac Toe** game:

- 👯 PvP (Player vs Player) Mode
- 🤖 PvC (Player vs CPU) Mode
- ♻️ Reset Button
- 🎨 Branding via Widget Options
- 🌐 Scoped for clean deployments

> Future releases will expand this repository with more classic and custom games, all designed for seamless integration into the Service Portal.

---

## 📖 Table of Contents

- ➤ [Prerequisites](#-prerequisites)
- ➤ [Folder Structure](#-folder-structure)
- ➤ [Build & Usage](#-build--usage)
- ➤ [Release 1 Details](#-release-1-details)
- ➤ [Customization Notes](#-customization-notes)
- ➤ [Licensing](#-licensing)
- ➤ [Contributors](#-contributors)

---

## 🍴 Prerequisites

To run this scoped widget, you’ll need:

- ServiceNow Paris+ instance (tested on Yokohama and Xanadu)
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
│   │   └── WidgetOptionSchema.json
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
   - Configure widget options (branding, mode toggle, etc.)

---

## 🚀 Release 1 Details

🔖 Release Name: `v1.0.0`\
📅 Release Date: YYYY-MM-DD\
🎮 Game Included: **Tic Tac Toe**

✅ **Release 1 Epics & Features**:

- ✔️ Scoped deployment under `x_sn_games` namespace
- ✔️ Widget options for:
  - `primaryColor`
  - `fontFamily`
  - `logoUrl`
  - `enablePvcMode` (true/false)
- ✔️ Player vs Player and Player vs CPU game logic
- ✔️ Reset functionality
- ✔️ AngularJS-driven UI with fallback to Service Portal theme if branding not defined

📌 See `/docs/epics.md` for Agile breakdown of all Release 1 tasks.

---

## 🎨 Customization Notes

- **No branding? No problem.** The widget uses classes like `bg-primary`, `text-color`, etc. for seamless fallback styling.
- You can update widget options without editing the widget code—just configure in the instance.

---

## 🔐 Licensing

This repository is released under a **dual license model**:

- 🆓 **Creative Commons Attribution 4.0 International (CC BY 4.0)**\
  For non-commercial and educational use with required attribution. See [`LICENSE.md`](../main/LICENSE.md).

- 💼 **Commercial License Required for Business Use**\
  Any commercial, enterprise, or revenue-generating usage requires a commercial license with agreed royalties or fees.\
  See [`COMMERCIAL_LICENSE.md`](../main/COMMERCIAL_LICENSE.md) or contact [ramon@dejesus.services](mailto\:ramon@dejesus.services) to obtain permission.

© 2025 DE JESUS SERVICES, INC. All rights reserved.

---

## 📜 Contributors

👦 Ramon De Jesus\
    Email: [ramon@dejesus.services](mailto\:ramon@dejesus.services)\
    GitHub: [@ramon-dejesus](https://github.com/ramon-dejesus)\
    Role: Architect and SN Developer

---

## 📌 Looking ahead...

We plan to include more classic games like:

- 🎲 Connect Four
- ♠️ Memory Match

Want to contribute or suggest a game idea?\
✨ Fork it. Build it. PR it.
