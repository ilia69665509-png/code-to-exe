 ⚙️ Multi-Lang to EXE Compiler

A modern, dark-themed GUI tool that turns source code into standalone Windows `.exe` files — supporting **Python, C#/.NET, Node.js, and Go** in a single app.
<img width="698" height="670" alt="2026-08-23_23-24-05" src="https://github.com/user-attachments/assets/d2a1791b-9514-44bf-b775-ad76e9a6989b" />
<img width="698" height="672" alt="2026-08-23_23-24-01" src="https://github.com/user-attachments/assets/11cc09af-2640-44f7-9d8b-7d344d5b0d36" />

---

## ✨ Features

- 🌐 **Multi-language support** — pick your language first, get the right build pipeline automatically
- 🎨 **Modern dark UI** — no ugly command-line windows, just clean cards and live logs
- 📦 **One-click builds** — no need to memorize compiler flags or CLI arguments
- 🖥️ **Live build log** — watch the compilation happen in real time, styled like a terminal
- 🎯 **Custom icons** — set your own `.ico` for Python and C# builds
- ⚡ **Zero telemetry** — everything runs 100% locally on your machine, nothing is ever uploaded

## 🖼️ Supported Languages

| Language | Engine | Output |
|---|---|---|
| 🐍 Python | PyInstaller | Standalone `.exe`, bundles the interpreter |
| 🔷 C# / .NET | `dotnet publish` | Self-contained, single-file `.exe` |
| 🟢 Node.js | `pkg` | Bundles Node runtime into `.exe` |
| 🐹 Go | `go build` | Native compilation, no wrapper needed |

## 🚀 Getting Started

### Prerequisites

You only need to install the toolchain for the language(s) you plan to use:

```bash
# Python
pip install pyinstaller

# C# / .NET
# Install the .NET SDK: https://dotnet.microsoft.com/download

# Node.js
npm install -g pkg

# Go
# Install Go: https://go.dev/dl/
```

The app itself only needs Python 3.8+ with `tkinter` (included by default on Windows).

### Run

```bash
python py2exe_compiler.py
```

### Usage

1. Pick your source language from the home screen
2. Browse to your project file
3. (Optional) Set a custom `.ico` icon
4. Configure build options (onefile, windowed mode, etc.)
5. Click **Build .exe** and watch the live log
6. Find your finished executable in the output folder (`dist` / `bin` / `Release`, depending on the language)

## 🛠️ Built With

- Python & `tkinter` — GUI framework
- PyInstaller / dotnet / pkg / go build — underlying compilers

## 🤝 Contributing

Pull requests are welcome! Feel free to open an issue for bugs, feature requests, or additional language support (Rust, C/C++, etc.).

## ☕ Support

If this tool saved you time, consider [buying me a coffee](#) — it helps keep the project maintained and new languages coming.

## 📄 License

MIT License — free to use, modify, and distribute.
