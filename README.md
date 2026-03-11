# HACKABLE_bdge
---
<img width="1120" height="959" alt="v2 render back no bg" src="https://github.com/user-attachments/assets/bf4cc576-1543-4e3e-9498-b6adff5064cf" />


The HACKable badge is an inspired by GitHub Universe 2025 badge but a fully custom, programmable electronic badge built around the Raspberry Pi RP2350B microcontroller. It is designed for hardware enthusiasts, developers, and hackers who want a portable, battery-powered platform with built-in wireless capabilities and a screen.

I Will write a firmwere soon till then you can use [https://badger.github.io/] or You can write your own code, play games, and connect to Wi-Fi.

The board is designed to be compatible with standard MicroPython, using the same wireless architecture as official Raspberry Pi development boards.

---
## Hardware Specifications
- Microcontroller: Raspberry Pi RP2350B (QFN-80 package)
- Wireless: Murata Type 1YN (CYW43439) Wi-Fi and Bluetooth module
- U.FL connector for attaching an external 2.4GHz antenna.
- Memory: 16MB QSPI Flash and 8MB QSPI PSRAM
- Display: 24-pin FPC connector designed for standard SPI LCD panels (example like :- like the 2.4-inch or 2.8-inch ST7789 or ILI9341)
- Power System: * USB-C connector for power and data.
  - JST connector for a standard 3.7V LiPo battery.
  - Onboard battery charging and protection circuitry.
  - High-efficiency buck converter to provide stable 3.3V system power.
- Timekeeping: PCF85063A Real-Time Clock (RTC) with a dedicated 32.768kHz crystal.
- 
- Wireless & RF (V2 Upgrades)
  - Wi-Fi & Bluetooth: Murata Type 1YN (CYW43439) module with a U.FL connector for external 2.4GHz antennas.
  - Sub-GHz Radio: RFM69HCW transceiver module mapped to the hardware SPI bus, featuring a dedicated U.FL connector for 433MHz/915MHz antennas.
  - Infrared: TSOP38238 IR Receiver (with hardware noise filtering) for capturing signals, and an IR11-21C blaster driven by a BSS138 MOSFET for long-range transmission.
  
- Inputs & Expansion:
  - 5 user navigation buttons (A, B, C, Up, Down).

  - Dedicated Reset and Bootsel buttons.

  - Ambient light sensor (PT19-21B) for automatic screen brightness adjustments.

  - Standard 4-pin Qwiic / STEMMA QT port (I2C) for easily plugging in external sensors.
  - BadUSB Switch: A physical hardware slide switch dedicated to toggling HID payload injection modes.
  - Expansion Ports: * Standard 4-pin Qwiic / STEMMA QT port (I2C) for external sensors.
  - Standard v1.69bis SAO (Shitty Add-On) 2x3 header (I2C + 3.3V) for conference bling and custom add-on boards.

# Schemetic
---
## V1
---
![click here](https://image-pro.easyeda.com/pullimages/6bea0def080f4f468d6660067533a47e.webp)

## V2
---
![click here](https://image-pro.easyeda.com/pullimages/5a3d070292074ad3b3fed5c777fde6f1.webp)
# BOM file 
---
![click here](https://github.com/ego10-ai/HACKABLE_bdge/blob/main/BOM_Board1_Schematic1_2026-02-28.xlsx)

## Firmware Compatibility
---
The HACKable bdge is designed to run MonaOS, a custom build of MicroPython optimized for conference badges. You can flash the board by holding the BOOTSEL button, pressing the RESET button, and dragging a .uf2 firmware file onto the mass storage drive. Apps and scripts can be loaded simply by dropping Python files into the /system/apps directory over USB.

## Contributing
Contributions are welcome! Feel free to:

- Fork the repository
- Suggest improvements or modifications
- Report issues or bugs
- Submit pull requests

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Support
For questions or issues, please open an issue on the GitHub repository.
