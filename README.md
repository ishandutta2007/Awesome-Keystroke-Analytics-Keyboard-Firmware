# Awesome-Keystroke-Analytics-Keyboard-Firmware

# Awesome-Keystroke-Analytics-Keyboard-Firmware

Top Keystroke Analytics Keyboard Firmware (Opensource) 🌟 Star if you like it! 🌟

A curated list of top keystroke analytics tools, mechanical keyboard firmwares, web-based keymap configurators, Hall-effect/analog keyboard utilities, and input telemetry trackers—featuring commercial SaaS/Hosted platforms alongside their open-source equivalents.

---

## Table of Contents

- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source Equivalents & Tools](#open-source-equivalents--tools)
  - [Keystroke Analytics, Heatmaps & Typing Telemetry](#keystroke-analytics-heatmaps--typing-telemetry)
  - [Open-Source Mechanical Keyboard Firmwares](#open-source-mechanical-keyboard-firmwares)
  - [Web & Desktop Keymap Configurators](#web--desktop-keymap-configurators)
  - [Key Remappers, Macro Engines & Input Layers](#key-remappers-macro-engines--input-layers)
  - [RGB Lighting & Hardware Synchronization](#rgb-lighting--hardware-synchronization)
- [Contributing](#contributing)

---

## SaaS/Hosted Platforms

Commercial, cloud-synced peripheral suites, proprietary web configurators, and manufacturer keyboard utilities.

* **[Wooting Wootility Web](https://wootility.io)** - Browser-based WebHID configurator for Wooting analog/Hall-effect keyboards featuring Rapid Trigger, actuation point tuning, and cloud profiles.
* **[Razer Synapse & Synapse Web](https://razer.com)** - Proprietary cloud-enabled hardware configuration suite for key remapping, macros, Chroma RGB, and keystroke heatmaps.
* **[SteelSeries GG (Engine)](https://steelseries.com)** - Commercial peripheral management suite offering custom actuation settings, macro editors, and Prism RGB lighting.
* **[Corsair iCUE](https://corsair.com)** - Proprietary desktop ecosystem for Corsair keyboards supporting key assignments, hardware playback, and RGB synchronization.
* **[Logitech G HUB](https://logitechg.com)** - Commercial peripheral software with cloud profile sharing, LIGHTSYNC RGB, and programmable G-key macros.
* **[Glorious CORE](https://gloriousgaming.com)** - Proprietary configuration software for GMMK mechanical keyboards covering keybindings, polling rate, and lighting effects.
* **[Epomaker Driver / Cloud Software](https://epomaker.com)** - Manufacturer-provided configuration tool for customizing layers, macros, and RGB profiles on Epomaker boards.
* **[Ducky RGB / Ducky Hub](https://duckychannel.com.tw)** - Proprietary software utility for controlling per-key RGB lighting and macro profiles on supported Ducky keyboards.
* **[QMK Configurator (Hosted Web Service)](https://qmk.fm)** - Official hosted web application for visually building keymaps and compiling QMK firmware binaries in the cloud.
* **[VIA Web (usevia.app)](https://usevia.app)** - Hosted WebHID web application for real-time keymap, macro, and lighting configuration without flashing firmware.

---

## Open-Source Equivalents & Tools

Free and open-source software (FOSS) keystroke analytics trackers, custom keyboard firmwares, self-hosted configurators, OS-level remappers, and RGB controllers.

### Keystroke Analytics, Heatmaps & Typing Telemetry

* **[Keybytes (notaroomba)](https://github.com)** - Open-source keystroke analytics and keyboard telemetry utility for tracking, analyzing, and visualizing typing habits.
* **[WhatPulse (Open-Source Alternatives: KMonad / Keystats / ActivityWatch)](https://github.com)** - Privacy-first, open-source automated time and input activity tracker running locally without cloud telemetry.
* **[KeyStats](https://github.com)** - Lightweight open-source macOS menu bar utility tracking daily keystrokes, mouse clicks, and keyboard usage statistics.
* **[KLogg / keyfreq (Emacs & Linux Input Stats)](https://github.com)** - Open-source keystroke frequency counter and command-usage analyzer for optimizing keyboard layouts and shortcuts.
* **[Monkeytype](https://github.com)** - Open-source, customizable typing test and keystroke speed/consistency analytics web application.
* **[Colemak / Ergo Layout Analyzers (Oxeylyzer)](https://github.com)** - Fast, open-source keyboard layout analyzer written in Rust evaluating finger travel, bigrams, and keystroke ergonomics.

### Open-Source Mechanical Keyboard Firmwares

* **[QMK Firmware (Quantum Mechanical Keyboard)](https://github.com)** - The gold-standard open-source keyboard firmware based on tmk_keyboard supporting thousands of custom mechanical keyboards.
* **[ZMK Firmware](https://github.com)** - Modern, open-source, wireless-first keyboard firmware built on the Zephyr RTOS with native Bluetooth Low Energy (BLE) and split-keyboard support.
* **[KMK Firmware](https://github.com)** - Beginner-friendly, hackable open-source keyboard firmware written in CircuitPython for RP2040 and microcontroller boards.
* **[RMK](https://github.com)** - Modern, async open-source mechanical keyboard firmware written in Rust built on Embassy with BLE and Vial support.
* **[Keyberon](https://github.com)** - Pure-Rust, bare-metal (`no_std`) open-source keyboard firmware crate for building ultra-responsive custom keyboards.
* **[BlueMicro_BLE](https://github.com)** - Open-source Arduino-based firmware tailored for nRF52 wireless split mechanical keyboards.

### Web & Desktop Keymap Configurators

* **[Vial & Vial-QMK](https://github.com)** - Complete open-source fork of VIA offering offline desktop/web GUI configuration, Tap Dance, Combos, and Key Overrides with zero proprietary JSON servers.
* **[Nick Brassel's ZMK Studio](https://github.com-studio)** - Open-source runtime keymap editor for ZMK keyboards enabling real-time wireless keymap adjustments over BLE and USB.
* **[Keymap Drawer](https://github.com)** - Open-source tool for parsing QMK and ZMK keymaps and generating clean, publication-grade SVG visual layout diagrams.
* **[QMK Configurator (Self-Hosted Open-Source)](https://github.com)** - Full open-source Vue.js frontend powering the QMK Configurator web app, deployable locally.

### Key Remappers, Macro Engines & Input Layers

* **[Kanata](https://github.com)** - Cross-platform open-source software key remapper written in Rust bringing QMK-like layers, home-row mods, and tap-hold features to any laptop or standard keyboard.
* **[KMonad](https://github.com)** - Advanced open-source keyboard manager providing multi-tap, layers, and QMK-style customization at the OS level across Linux, macOS, and Windows.
* **[keyd](https://github.com)** - Low-level, ultra-fast key remapping daemon for Linux operating directly on `evdev`/`uinput` for system-wide layers and chords.
* **[Karabiner-Elements](https://github.com)** - Powerful, open-source kernel-level keyboard customizer and remapper for macOS.
* **[Input Remapper](https://github.com)** - Easy-to-use open-source Linux GUI tool for remapping keys, macros, and buttons across keyboards, mice, and gamepads.

### RGB Lighting & Hardware Synchronization

* **[OpenRGB](https://github.com)** - Open-source RGB lighting control that doesn't depend on manufacturer software, replacing Razer Synapse, Corsair iCUE, Logitech G HUB, and SteelSeries GG.
* **[SignalRGB Open Alternatives / Artemis RGB](https://github.com)** - Open-source, modular RGB lighting synchronization platform with real-time game and audio reactive effects.

---

## Contributing

Contributions are welcome! Feel free to open a Pull Request to add more open-source keystroke analytics tools, keyboard firmwares, WebHID configurators, or OS-level remappers.

1. Fork the repository.
2. Add your project under the appropriate category with a concise description.
3. Submit a Pull Request.
