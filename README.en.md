# MT1389-Emulator

**Cross-platform DVD player emulator on the 8-bit MediaTek MT1389 processor**

DVD player emulator that recreates the functionality of the MediaTek MT1389 chip with support for a virtual remote control, shared folders, and video output via Pygame.
*The repository is under active development - your contributions are welcome!*

---

## 📌 Features
- **🎮 Virtual remote control** with mouse and keyboard support.
- **📂 Shared folders like SD/MMC** - mount local folders for access via the emulator's file browser.
- **🎥 Video output via Pygame** - cross-platform video and interface rendering.
- **🖥️ Windows, Linux, macOS** support.

## ⚙️ Installation and Run
*Note: The code is a work in progress. The instructions are valid for future versions.*

1. **Clone the repository**:
```bash
git clone https://github.com/CherryBerd/MT1389-Emulator.git
cd MT1389-Emulator
```

2. **Install dependencies**
```bash
pip install -r requirements.txt # While the file is empty or does not exist, you need to add Pygame and other libraries
```

3. **Run the emulator**
```bash
python src/main.py # The file will be added later
```

# 🛠️ How to help the project
We invite everyone who wants to:

* Write code for emulating the MT1389 processor.

* Implement video/audio decoding.

* Add GUI elements (remote control, file browser).

* Write tests and documentation.

# 🔄 Development stages
1. Fork the repository.

2. Create a branch:

```bash
git checkout -b feature/your-feature
```
Commit the changes and send a Pull Request.

# Project structure (planned)

```plaintext
MT1389-Emulator/
├── docs/                 # Documentation
├── src/                  # Source code
│ ├── core/               # CPU and hardware emulation
│ ├── gui/                # Interface (Pygame)
│ └── utils/              # Auxiliary scripts
├── tests/                # Tests
├── roms/                 # Firmwares in *.BIN format
├── requirements.txt      # (File missing!)
└── LICENSE               # MIT license (needs to be added!)
```

# 📜 License

The project will be distributed under the MIT license. There is currently no LICENSE file - adding it will be the first contribution to the repository!

**Join the development!**
Your code and ideas will help preserve the legacy of MT1389 for future generations.
