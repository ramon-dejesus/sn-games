# 🕹️ SN-Games – ServiceNow Widget Pack

A scoped application offering responsive, interactive game widgets for the ServiceNow Service Portal. Built with AngularJS and fully customizable via widget options to match your brand or Service Portal theme.

Developed and maintained by **DE JESUS SERVICES, INC.**\
GitHub: [https://github.com/ramon-dejesus](https://github.com/ramon-dejesus)\
Contact: [ramon@dejesus.services](mailto\:ramon@dejesus.services)

---

## 📦 Available Releases

- ✅ **Release 1: Tic Tac Toe**
- ✅ **Release 2: Connect Four** ← *New!*

---

## 📖 Table of Contents

- ➤ [Prerequisites](#-prerequisites)
- ➤ [Build & Usage](#-build--usage)
- ➤ [Release Details](#-release-details)
- ➤ [Widget Options](#-widget-options)
- ➤ [Customization Notes](#-customization-notes)
- ➤ [Contributors](#-contributors)
- ➤ [Licensing](#-licensing)

---

## 🍴 Prerequisites

To run these scoped widgets, you’ll need:

- ServiceNow Xanadu+ instance (tested on Yokohama and Xanadu)
- Access to Studio & Service Portal
- Scoped app import permissions

---

## 🏗️ Build & Usage

1. **Download desired Release UpdateSet**

   - [Releases](https://github.com/ramon-dejesus/sn-games/releases)

2. **Import into ServiceNow**

   - Go to **System Applications > Studio**
   - File → Import from XML → select `update-set.xml`

3. **Deploy the Widget**

   - Go to **Service Portal > Pages**
   - Add the widget to a desired page
   - Configure widget options (branding, font, etc.)

---

## 🚀 Release Details

### 🔖 Release 2: Connect Four

📅 Release Date: 2025-04-10\
🎮 Game Included: **Connect Four**

#### ✅ Features

- 👯 Player vs Player support
- 🤖 Player vs CPU mode with smart AI (win > block > random)
- 💥 Win detection with animated highlights
- ♿️ 508-Compliant (ARIA roles, keyboard nav, screen reader labels)
- 🎨 Brandable via Widget Options
- 🌈 Accessible color contrast with clear labels ("Red" / "Black")
- 🌀 Visual spinner for CPU "thinking"
- 🧠 Robust logic with error handling and scoped architecture

🔗 [View all 2.0 issues](https://github.com/ramon-dejesus/sn-games/milestone/2?closed=1)

---

### 🔖 Release 1: Tic Tac Toe

📅 Release Date: 2025-04-02\
🎮 Game Included: **Tic Tac Toe**

- 👯 Player vs Player support
- 🤖 Player vs CPU mode with basic AI
- 🔄 Alternate start
- ♿️ 508-Compliant
- 🎨 Brandable
- 🧼 Fully scoped



🔗 [View all 1.0 issues](https://github.com/ramon-dejesus/sn-games/milestone/1?closed=1)

---

## 🧩 Widget Options

| Option Name            | Type     | Description                                    |
| ---------------------- | -------- | ---------------------------------------------- |
| `default_game_mode`    | `string` | Either `pvp` or `pvc` (defaults to `pvc`)      |
| `background_color_hex` | `string` | Optional background color hex (e.g. `#ffffff`) |
| `font_color_hex`       | `string` | Hex code for font color (e.g. `#000000`)       |
| `font_family`          | `string` | Font family used in the game display           |
| `logo_url`             | `string` | URL of logo displayed under the game           |
| `provider_url`         | `string` | Link when logo or provider is clicked          |
|                        |          |                                                |

---

## 🎨 Customization Notes

- All game widgets support branding, fonts, and colors through options.
- No-code configuration: widget options are respected dynamically.
- Fully scoped — no global variables or script includes.

---

## 📜 Contributors

👦 Ramon De Jesus\
Email: [ramon@dejesus.services](mailto\:ramon@dejesus.services)\
GitHub: [@ramon-dejesus](https://github.com/ramon-dejesus)\
Role: Architect, Developer, and Maintainer

---

## 📌 Looking Ahead

Planned future additions to SN-Games:

- 🐍  Snake

Want to contribute or suggest a game idea?\
✨ Fork it. Build it. PR it.

---

## 🔐 Licensing

This repository is released under a **dual license model**:

- 🆓 **Creative Commons Attribution 4.0 International (CC BY 4.0)**\
  For non-commercial and educational use with required attribution. See [`LICENSE`](../LICENSE).

- 💼 **Commercial License Required for Business Use**\
  Any commercial, enterprise, or revenue-generating usage requires a commercial license with agreed royalties or fees.\
  See [`COMMERCIAL_LICENSE.md`](../COMMERCIAL_LICENSE.md) or contact [ramon@dejesus.services](mailto\:ramon@dejesus.services) to obtain permission.

© 2025 DE JESUS SERVICES, INC. All rights reserved.
