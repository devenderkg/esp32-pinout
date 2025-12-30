# ⚡ ESP32 Interactive GPIO Pinout Reference

A lightweight, interactive, and high-accuracy GPIO reference tool for the ESP32 (30-pin/38-pin DevKit). Built with vanilla HTML5, CSS3, and SVG for maximum performance and zero dependencies.

![License](https://img.shields.io/github/license/devenderkg/esp32-pinout)
![Platform](https://img.shields.io/badge/platform-Web-blue)

## 🚀 Features
- **Interactive SVG Board:** Click any pin to see detailed hardware characteristics.
- **Hardware Constraint Warnings:** Highlights internal Flash pins (6-11) and ADC2/Wi-Fi conflicts.
- **Signal Classification:** Color-coded badges for Power, Ground, RTC, Touch, and Analog signals.
- **Strapping Pin Detection:** Clearly identifies pins that affect boot behavior.
- **Zero Dependencies:** No frameworks, no libraries. Just one file.

## 🛠️ How to Use
1. Clone the repository: `git clone https://github.com/devenderkg/esp32-pinout.git`
2. Open `index.html` in any modern web browser.
3. (Optional) Host it via GitHub Pages for a live URL.

## 🗺️ Pin Mapping Accuracy
The data is mapped based on the ESP32 WROOM-32 datasheet. It includes:
- **Input-Only Pins:** GPIO 34, 35, 36, 39.
- **RTC GPIOs:** Pins functional during deep sleep.
- **DAC/ADC Channels:** Specific analog mappings.

## 🤝 Contributing
Contributions are welcome! If you find a typo in the pin notes or want to add support for the ESP32-S3 or C3:
1. Fork the project.
2. Create your feature branch.
3. Commit your changes.
4. Open a Pull Request.

## 👤 Author
- **Devender Gupta** - [@devenderkg](https://twitter.com/devenderkg)

## 📄 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
