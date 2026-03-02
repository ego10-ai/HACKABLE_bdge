# HACKABLE_bdge
---
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
  
- Inputs & Expansion:
  - 5 user navigation buttons (A, B, C, Up, Down).

  - Dedicated Reset and Bootsel buttons.

  - Ambient light sensor (PT19-21B) for automatic screen brightness adjustments.

  - Standard 4-pin Qwiic / STEMMA QT port (I2C) for easily plugging in external sensors.

# Schemetic
---
![click here](https://image-pro.easyeda.com/pullimages/6bea0def080f4f468d6660067533a47e.webp)

# BOM file 
---
![click here](https://github.com/ego10-ai/HACKABLE_bdge/blob/main/BOM_Board1_Schematic1_2026-02-28.xlsx)
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
