# ESP32-C3 Web Flasher & Project

A lightweight, browser-based firmware flasher interface for the ESP32-C3 microcontroller utilizing the Web Serial API.

## Project Overview
This repository contains the source code and files necessary to flash binaries directly to an ESP32-C3 via a modern web browser without needing local installations or command-line tools.

## Files Included
* **`index.html`**: The web-based user interface and flasher script leveraging `esptool-js`.
* **`.ino`**: The core Arduino/C++ source code for the microcontroller.
* **Firmware Binaries (`.bin`)**: Compiled binary files ready for deployment.

## How to Use
1. Connect your ESP32-C3 to your computer via a data-capable USB cable.
2. Open the hosted web interface in a Web Serial-compatible browser (such as Google Chrome or Microsoft Edge).
3. Click **Connect**, select the correct COM port, and flash your `.bin` file directly to the board.
