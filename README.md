# RuskUno — Arduino® alternative based on MindMotion MM32F0141C6P

**RuskUno** is an open-source development board designed as an Arduino-style alternative built around the MindMotion **MM32F0141C6P** (ARM Cortex-M0).  
This repo contains the KiCad hardware sources and initial documentation. An Arduino-style core / cores for this MCU is **in progress** and will be provided here when ready.

This repository contains:

- ✅ Full KiCad hardware source files
- 🚧 Arduino-compatible core (In Progress)
- 🔓 Open Source Hardware

---

# 📸 Development Board

## Top View
![RuskUno Top](images/board_top.jpg)

## Bottom View
![RuskUno Bottom](images/board_bottom.jpg)

---

# 🧠 Why RuskUno?

The goal of RuskUno is to provide:

- Higher performance than ATmega328P
- More Flash & RAM
- Modern 32-bit ARM architecture
- Open hardware design
- Future Arduino ecosystem compatibility
- Affordable alternative for students & developers

---

# ⚙️ Microcontroller Overview

## 🔹 MM32F0141C6P

- Core: ARM Cortex-M0 (32-bit)
- Max Clock: 72 MHz
- Flash: 64 KB
- SRAM: 8 KB
- Multiple UART / SPI / I2C
- 12-bit ADC
- Advanced Timers
- SWD Debug Support

---

# 🔄 Comparison: MM32F0141C6P vs ATmega328P

| Feature | MM32F0141C6P | ATmega328P |
|----------|---------------|--------------|
| Architecture | 32-bit ARM Cortex-M0 | 8-bit AVR |
| Max Frequency | 72 MHz | 20 MHz |
| Flash | 64 KB | 32 KB |
| SRAM | 8 KB | 2 KB |
| ADC | 12-bit | 10-bit |
| Debug | SWD | No native debugger |
| Performance | High | Moderate |
| Math Speed | Fast 32-bit | Slower 8-bit |

**Result:**  
RuskUno offers significantly better performance, memory headroom, and peripheral flexibility compared to traditional Arduino UNO.

---

# 🛠 Hardware Features

- Arduino-style pin header layout
- USB programming interface
- External crystal
- SWD debug header
- 3.3V logic
- Power via USB or VIN
- LDO regulator onboard
- Status LED
- Reset button

---

# 🧩 Arduino Core (In Progress)

The Arduino-compatible core is currently under development.

Planned features:
- Arduino pin mapping
- digitalWrite / digitalRead
- analogRead
- PWM
- Serial support
- SPI & I2C
- Timer support

Once stable, the core will be:
- Added in `/firmware`
- Packaged for Arduino IDE board manager

Stay tuned ⭐

---

# 🎯 Project Vision

RuskUno aims to:

- Provide a powerful yet affordable board for students
- Enable migration from 8-bit AVR to 32-bit ARM easily
- Offer fully open hardware
- Support embedded learners
- Build an ecosystem around MM32 microcontrollers

---


# 🤝 Contributing

Pull requests are welcome!

If you'd like to contribute:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Submit a PR

---

# 📌 Roadmap

- [x] Hardware Design Complete
- [x] Prototype Built
- [ ] Arduino Core Development
- [ ] Bootloader
- [ ] Documentation Expansion
- [ ] Example Projects

---

# 🌍 Open Hardware Commitment

RuskUno is 100% open-source.

KiCad files are provided.
Anyone can:
- Study
- Modify
- Manufacture
- Improve

---

# 👨‍💻 Author

Designed & Developed by  
**Rajbhar Divesh**

---

# 🔓 License

This project is licensed under the MIT License.
