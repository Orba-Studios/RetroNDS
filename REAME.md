# RetroNDS - Web Emulation System

RetroNDS is a lightweight, single-file browser-based emulator shell styled after classic dual-screen handheld Nintendo systems. Instead of simply launching desktop shortcuts or external applications, it integrates with **EmulatorJS** (powered by WebAssembly/Libretro cores) to **actually execute and emulate** retro game ROMs straight inside your web browser.

---

## 🎮 Supported Systems & Cores
* **Nintendo Entertainment System (NES)** (`nes`)
* **Super Nintendo Entertainment System (SNES)** (`snes`)
* **Game Boy** (`gb`)
* **Game Boy Color** (`gbc`)
* **Game Boy Advance** (`gba`)
* **Nintendo DS** (`nds`)

---

## 🚀 Getting Started & Local Installation

You can run this project locally or host it instantly using **GitHub Pages**.

1. Clone or download this repository to your local machine:
   ```bash
   git clone https://github.com/your-username/retro-nds-emulator.git
   ```
2. Navigate into the folder and open `index.html` directly in any modern browser (Chrome, Firefox, Edge, Safari).

---

## 🌐 Deploying to GitHub Pages

To host your emulator online for free:
1. Upload `index.html` and this `README.md` to your GitHub repository.
2. Go to your repository **Settings** tab.
3. Click on **Pages** in the left sidebar.
4. Under **Build and deployment**, select the `main` (or `master`) branch as the source and click **Save**.
5. Your emulator will be live at `https://<your-username>.github.io/<repository-name>/`!

---

## 💻 How to Use
1. Choose your target console system from the dropdown menu on the physical control interface.
2. Click **Choose File** / browse to select a compatible ROM file (`.nes`, `.sfc`, `.gba`, `.nds`, etc.) or a `.zip` archive from your computer.
3. Click **LOAD GAME** to initialize the WebAssembly emulation core inside the top screen frame.

---

## 📜 License
This project is open-source and available under the [MIT License](LICENSE).
