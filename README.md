# ⬡ CAB CE

### Creative Advanced Builder — Code Editor

A modern, powerful, and lightweight code editor with **real PowerShell execution**, support for **30+ programming languages**, an integrated terminal, and a full extension marketplace.

[![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)](https://github.com/yourname/cab-ce/releases)
[![Platform](https://img.shields.io/badge/platform-Windows-0078D6.svg)](https://github.com/yourname/cab-ce)
[![License](https://img.shields.io/badge/license-PUM%201.0-orange.svg)](LICENSE)
[![Electron](https://img.shields.io/badge/Electron-28-47848F.svg)](https://electronjs.org)
[![Node](https://img.shields.io/badge/Node.js-18%2B-339933.svg)](https://nodejs.org)

</div>

---

## ✨ Features

- 🚀 **Real code execution** — Runs your code through actual PowerShell, not simulations
- 🌐 **30+ languages** — Python, JavaScript, C, C++, C#, Java, Rust, Go, Ruby, PHP, Swift, Kotlin, Dart, Lua, Julia, Pascal, and more
- 🎨 **Custom languages** — VisualZenta, Native, Pie, Z, K# with dedicated syntax highlighting
- 💻 **Integrated PowerShell terminal** — Type commands directly, see real output
- 🧩 **Extension marketplace** — Install compilers and runtimes via `winget` with a trust dialog
- 📁 **File explorer** — Open folders, browse trees, switch files without losing context
- 🔍 **Find & replace, formatting, multi-theme** support
- 💾 **Real file saving** — Uses the File System Access API to save anywhere on disk
- ⚡ **Zero configuration** — Just double-click the .exe and start coding

---

## 📸 Screenshot

![CAB CE Screenshot](https://github.com/TGCGaming/CAB-CE/blob/main/assets/CAB%20CE%20screenshot%20Java.png?raw=true)

---

## 🚀 Quick Start

### Option 1 — Download the .exe (recommended)

1. Go to the [Releases](../../releases) page
2. Download **CAB CE Setup 1.0.0.exe**
3. Run the installer → launch **CAB CE** from your Start Menu
4. Start coding immediately

### Option 2 — Run from source

```bash
# Clone the repo
git clone https://github.com/yourname/cab-ce.git
cd cab-ce

# Install dependencies
npm install

# Launch as desktop app
npm start
```

### Option 3 — Run as a web app (no Electron)

```bash
npm install
node server.js
```

Then open **http://localhost:3000** in your browser.

---

## 📖 How to Use

### Basic workflow

1. **Open the app** — Double-click the shortcut or run `npm start`
2. **Create or open a file** — Click `+ New` or `📂 Open` in the toolbar
3. **Choose a language** — Pick from the grid (Python, JavaScript, C, etc.)
4. **Write code** — CodeMirror handles syntax highlighting, autocomplete, and matching brackets
5. **Run with F5** — Output appears in the built-in terminal
6. **Save with Ctrl+S** — First save opens a dialog; every subsequent Ctrl+S saves directly

### Keyboard shortcuts

| Shortcut | Action |
|----------|--------|
| `Ctrl+N` | New file |
| `Ctrl+O` | Open file |
| `Ctrl+S` | Save file |
| `Ctrl+Shift+S` | Save As |
| `Ctrl+W` | Close current tab |
| `Ctrl+Z` | Undo |
| `Ctrl+Y` | Redo |
| `Ctrl+F` | Find & Replace |
| `Ctrl+B` | Toggle Explorer |
| `` Ctrl+` `` | Toggle Terminal |
| `F5` | Run current file |
| `Shift+F5` | Stop execution |
| `Esc` | Close extensions screen |

### The integrated terminal

The bottom panel is a **real PowerShell terminal**. Type anything:

```powershell
PS> dir
PS> cd C:\Projects
PS> python --version
PS> node -e "console.log(2+2)"
PS> git status
```

Every command runs on your actual system. This is not emulated.

---

## 🌐 Supported Languages

### Mainstream languages

| Language | Extension | Runtime Required |
|----------|-----------|------------------|
| Python | `.py` | `python` |
| JavaScript | `.js` | `node` |
| TypeScript | `.ts` | `node` |
| HTML | `.html` | Browser |
| CSS | `.css` | Browser |
| C | `.c` | `gcc` |
| C++ | `.cpp` | `g++` |
| C# | `.cs` | `dotnet` or `csc` |
| Java | `.java` | `javac` + `java` |
| Rust | `.rs` | `rustc` |
| Go | `.go` | `go` |
| Ruby | `.rb` | `ruby` |
| PHP | `.php` | `php` |
| Swift | `.swift` | `swift` |
| Kotlin | `.kt` | `kotlinc` |
| Dart | `.dart` | `dart` |
| Lua | `.lua` | `lua` |
| Julia | `.jl` | `julia` |
| Pascal | `.pas` | `fpc` |
| SQL | `.sql` | `sqlite3` |
| Bash | `.sh` | `bash` |
| Batch | `.bat` | `cmd` |
| PowerShell | `.ps1` | `powershell` |
| JSON / YAML / Markdown | `.json` `.yaml` `.md` | — |

### Custom languages

| Language | Extension | Description |
|----------|-----------|-------------|
| **VisualZenta** | `.vz` | Component-based UI framework |
| **Native** | `.native` | Bridge module system using `nc` compiler |
| **Pie** | `.pie` | Recipe-based programming |
| **Z** | `.z` | Zero-based zone language |
| **K#** | `.k` | Modern object-oriented language |

Each ships with a **Hello World template** ready to run.

---

## 🧩 Extensions Marketplace

Don't have Python installed? No problem.

1. Click the **🧩 Extensions** icon in the sidebar
2. Browse the tile grid — each extension shows publisher, rating, and download count
3. Click any tile to see the full description and feature list
4. Click **⬇ Get Extension**
5. A **trust dialog** asks you to confirm — click **Yes, I Trust It**
6. The compiler/runtime installs automatically via `winget`
7. Restart the terminal and start using it

### Available extensions

| Extension | winget Package |
|-----------|----------------|
| 🐍 Python | `Python.Python.3.12` |
| 📜 Node.js | `OpenJS.NodeJS.LTS` |
| ⚡ C/C++ Compiler | `BrechtSanders.WinLibs.POSIX.UCRT` |
| ☕ Java JDK | `EclipseAdoptium.Temurin.21.JDK` |
| 🔵 Go | `GoLang.Go` |
| 🦀 Rust | `Rustlang.Rustup` |
| 💎 Ruby | `RubyInstallerTeam.Ruby.3.3` |
| 🐘 PHP | `PHP.PHP.8.3` |
| 🔷 .NET SDK | `Microsoft.DotNet.SDK.8` |
| 🎯 Dart | `Dart.Dart` |
| 🌙 Lua | `DEVCOM.Lua` |
| 🔮 Julia | `JuliaLang.Julia` |
| 🟣 Kotlin | `JetBrains.Kotlin` |
| 🔀 Git | `Git.Git` |

---

## 🏗️ Architecture

```
CAB CE/
├── index.html      UI layout (CodeMirror editor, panels, modals)
├── style.css       All styling (dark theme, tiles, terminal)
├── app.js          Frontend logic (files, tabs, extensions, terminal)
├── server.js       Express backend (executes code, installs tools)
├── main.js         Electron entry point
└── package.json    Build config
```

### How it works

1. **Electron launches** → `main.js` starts the Express server in the background
2. **Native window opens** → loads `http://localhost:3000`
3. **User writes code** → CodeMirror handles editing in `index.html`
4. **User presses F5** → `app.js` sends code to `/api/execute`
5. **Server compiles & runs** → returns stdout/stderr to the terminal
6. **Extensions install** → `server.js` runs `winget` on your behalf

### Why a server?

Browsers can't execute PowerShell directly for security reasons. The Express server runs locally on your machine and acts as a bridge — Electron bundles it inside the app so you never see it as a separate process.

---

## 🛠️ Building from Source

### Prerequisites

- **Node.js 18+** — [Download](https://nodejs.org)
- **Windows 10/11** (for the .exe build)
- **~500 MB free disk space** (Electron is big)

### Build steps

```bash
# 1. Install dependencies
npm install

# 2. Test the app locally
npm start

# 3. Build the .exe files
npm run build-all
```

Result in `dist/`:
- `CAB CE Setup 1.0.0.exe` — installer
- `CAB CE 1.0.0.exe` — portable single file

### Build only one target

```bash
npm run build            # NSIS installer only
npm run build-portable   # Portable .exe only
```

---

## 🎨 Theming

Switch between built-in themes via the top-right dropdown:

- **Dracula** (default)
- **Monokai**
- **Material**
- **Nord**
- **Oceanic**

The whole UI recolors instantly — editor, panels, terminal, modals.

---

## 💡 Tips & Tricks

- **Multiple files at once** — Open as many tabs as you want
- **Folder view stays open** — Clicking a file in the tree doesn't lose your folder
- **Recent files** — Bottom bar shows your 15 most recent
- **Restore session** — Recent files persist across restarts via localStorage
- **Run in terminal** — Press F5 or type the run command directly

---

## ⚠️ Known Limitations

- **Windows only** — The current build targets Windows. macOS/Linux support would need PATH handling changes in `server.js`
- **Unsigned .exe** — Windows SmartScreen will warn on first launch. Click **More info → Run anyway**
- **Internet required on first launch** — CodeMirror and Font Awesome load from CDN
- **Extensions use winget** — Requires Windows 10 21H2+ with App Installer

---

## 🗺️ Roadmap

- [ ] Offline bundling (CodeMirror + Font Awesome locally)
- [ ] Code signing for the .exe
- [ ] macOS + Linux builds
- [ ] Built-in Git panel
- [ ] AI autocomplete integration
- [ ] Custom theme creator
- [ ] Multi-root workspaces

---

## 🤝 Contributing

Contributions are welcome! Here's how:

1. Fork the repo
2. Create a branch: `git checkout -b feature/my-feature`
3. Commit your changes: `git commit -m "Add my feature"`
4. Push: `git push origin feature/my-feature`
5. Open a Pull Request

---

## 📄 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 🙏 Credits

- **CodeMirror** — The editor core
- **Electron** — Desktop app framework
- **Express** — Backend server
- **Font Awesome** — Icons
- **Winget** — Package installation

---

**Made with ❤️ for developers who want a lightweight, powerful editor**

⭐ Star this repo if you find it useful!

</div>
