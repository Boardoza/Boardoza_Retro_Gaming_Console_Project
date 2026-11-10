
# Boardoza Retro Gaming Console Handheld Gaming Project

The **Boardoza Retro Gaming Console Project** is an ESP32-based handheld gaming device designed to recreate the experience of classic video game consoles through modern embedded hardware. The system is powered by an **Espressif ESP32-S3 microcontroller with 16 MB Flash and 8 MB PSRAM**, supporting retro gaming platforms including NES, SNES, and Game Boy. Its integrated **2.8-inch TFT display**, directional pad, analog joystick, action buttons, and dedicated Start and Select buttons provide a traditional gaming experience in a portable design.

The system uses an ESP32-S3 controller with **Wi-Fi connectivity** and a **MicroSD card interface** for game storage. ROM files can be loaded directly onto the MicroSD card or transferred wirelessly over Wi-Fi, with games organized into dedicated directories for each supported console. The software provides customizable button mappings, adjustable screen brightness, display aspect-ratio settings, and a multilingual interface supporting five languages. The project is suitable for STEM education, retro gaming demonstrations, and embedded systems development.

<h2 align="center">Retro Gaming Console</h2>

<p align="center">
  <img src="./assets/Retro Gaming Console.gif" width="400">
</p>

---

## Key Features

- **Multi-Console Game Emulation:** Supports classic gaming platforms including NES, SNES, and Game Boy, allowing users to access multiple retro console libraries through a single handheld device.
- **Dual Game Transfer Options:** Enables ROM files to be loaded directly from a MicroSD card or transferred wirelessly over Wi-Fi, eliminating the need to remove the storage card when adding new games.
- **Customizable Gaming Controls:** Features a directional pad, analog joystick, action buttons, and dedicated Start and Select keys, with configurable button mappings for different games and player preferences.
- **Adjustable Display Configuration:** Integrates a 2.8-inch TFT display with adjustable brightness and aspect-ratio settings for different viewing preferences.
- **Multi-Language User Interface:** Provides a menu system supporting five languages for navigating games and device settings.
- **Integrated Game Management System:** Organizes ROM files into console-specific directories and provides a streamlined game selection interface.

---

## System Architecture

The Retro Gaming Console system combines an ESP32-S3 controller, a 2.8-inch TFT LCD display, and physical control buttons to create a portable gaming device for classic console emulation.

| Component | Model |
|---|---|
| Microcontroller | [Boardoza ESP32-S3-MINI-DEV](https://www.ozdisan.com/ureticiler/boardoza) |
| Display | [TFT LCD Module 2.8 Inch](https://www.ozdisan.com/p/arduino-sensorleri-ve-modulleri-613/ozd-arduino-tft-lcd-module-2-8-inch-980334?tab=productDetails) |
| Buttons | [L-KLS7-P8.0X8.0-0](https://www.ozdisan.com/p/push-button-sivicler-488/kls-electronic-l-kls7-p8-0x8-0-0-633531?tab=productDetails) |

---

## Board Pinout

[Boardoza Retro Gaming Console Pinout Diagram](./assets/Retro%20Gaming%20Console%20Pinout%20Diagram.pdf)

---

## Step Files

[Boardoza Retro Gaming Console.step](./assets/Retro%20Gaming%20Console%20Step.step)

---

## Version History

- v1.0 – Initial release

---

## Support

- For questions or technical support, please contact **support@boardoza.com**

---

## License

This repository contains both hardware and software components:

### **Hardware Design**

[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]

All hardware design files are licensed under [Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

### **Software/Firmware**

[![BSD-3-Clause][bsd-shield]][bsd]

All software and firmware are licensed under [BSD 3-Clause License][bsd].

[bsd]: https://opensource.org/licenses/BSD-3-Clause
[bsd-shield]: https://img.shields.io/badge/License-BSD%203--Clause-blue.svg
