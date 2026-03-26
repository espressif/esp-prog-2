# ESP-Prog-2

ESP-Prog-2 is a development and debugging tool released by Espressif Systems. It supports functions such as automatic firmware downloading, serial communication, multiple debugging interfaces.

## About the Board

The ESP-Prog-2 is built around the ESP32-S3 module and provides a versatile solution for ESP32 development and debugging. Key features include:

- **Automatic firmware downloading**
- **Serial communication**
- **JTAG online debugging**
- **Dual voltage support** - Both 3.3V and 5V power supply options via jumper selection
- **USB-C connectivity** - Single cable connection to computer
- **Dual interfaces** - Separate ports for downloading and JTAG debugging

The board features both 2.54mm and 1.27mm pin spacing connectors for maximum compatibility with different target boards.

## About This Repository

This repository gathers information and resources about the ESP-Prog-2 development kit. It serves as a central hub for documentation, firmware updates, and usage guides.

## Documentation

For comprehensive documentation about the ESP-Prog-2, including:

- Hardware specifications
- Pin configurations  
- Setup instructions
- Usage examples

Please refer to the official Espressif documentation:
**[ESP-Prog-2 User Guide](https://docs.espressif.com/projects/esp-dev-kits/en/latest/other/esp-prog-2/user_guide.html)**

## Firmware

The ESP-Prog-2 uses the **[esp-usb-bridge](https://github.com/espressif/esp-usb-bridge)** project as its firmware foundation. This project provides:

- USB to UART bridge functionality
- JTAG debugging capabilities
- CMSIS-DAP support
- Mass storage device functionality for UF2 binary flashing

### Flashing the ESP-Prog-2

You can flash the ESP-Prog-2 firmware using ESP Launchpad for a convenient web-based flashing experience:

<a href="https://espressif.github.io/esp-launchpad/?flashConfigURL=https://espressif.github.io/esp-usb-bridge/launchpad.toml">
    <img alt="Try it with ESP Launchpad" src="https://espressif.github.io/esp-launchpad/assets/try_with_launchpad.png" width="250" height="70">
</a>

For detailed flashing instructions including alternative methods, please refer to:

**[ESP-Prog-2 Firmware Update Guide](https://github.com/espressif/esp-usb-bridge/wiki/ESP-Prog-2-firmware-update-guide)**

This guide covers multiple flashing approaches and step-by-step instructions for updating your ESP-Prog-2 firmware.

## Hardware Setup

1. Connect ESP-Prog-2 to your computer using a USB-C cable
2. Select appropriate voltage (3.3V or 5V) using the jumper pins
3. Connect to your target ESP32 board using the cables
4. Use tools or scripts for debugging, flashing or serial communication
