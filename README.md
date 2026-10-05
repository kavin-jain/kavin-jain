## Kavin Jain

**I build ESP32 hardware from the circuit up.** That means radios, robots and security tools, plus the software around them. I design the board, solder it, write the firmware and ship it. Udaipur, India.

[kavinjain.in](https://kavinjain.in) · [LinkedIn](https://www.linkedin.com/in/kavin-jain-b79a312b3/) · [hello@kavinjain.in](mailto:hello@kavinjain.in)

---

### Now building: [S3 Handheld](https://github.com/kavin-jain/s3-handheld)

<a href="https://github.com/kavin-jain/s3-handheld"><img src="https://raw.githubusercontent.com/kavin-jain/s3-handheld/main/docs/photos/hero.jpg" width="560" alt="S3 Handheld bench prototype: two CC1101 sub-GHz radios, two NRF24L01+ with antennas, 2.4-inch display and rotary encoder" /></a>

Flipper-class security handheld on an ESP32-S3, in progress since July 2026:

- **Radios:** 2× CC1101 sub-GHz, 2× NRF24L01+, PN532 NFC, IR, and the S3's own WiFi and BLE
- **Firmware:** an LVGL UI with 61 tools in 13 categories, plus 56 host unit tests
- **Docs:** a full BOM and wiring tables, so you can rebuild it

It has no jammers, by design. The firmware compiles and its logic is tested. Radio bring-up on the real device is in progress.

---

### Projects

| Project | What | Built | Status |
|---|---|---|---|
| [**MARK5**](https://github.com/kavin-jain/MARK5) | Quant research for NSE India: survivorship-free, tax-aware. The README opens with the negative result, because the stock-picking alpha is not yet statistically significant | Jan 2026 → now | Paper trading · [live dashboard](https://kavinjain.in/mark6) |
| [**Verified Pentest**](https://github.com/kavin-jain/verified-pentest) | Self-service pentest platform that only scans domains whose ownership is proven, and re-checks that proof at scan time. OWASP, TLS, DNS and port checks, plus a capped, read-only AI pass that links findings into attack chains | Jun 2026 | Code · 64 tests, CI passing |
| [**Jarvis**](https://github.com/kavin-jain/jarvis) | Local-first voice assistant for macOS. A double clap or wake word starts it, and a 3-tier router (regex → local Ollama → Gemini/Claude) sends cloud calls only when it has to. Controls the Mac, Spotify, an Android phone and an ESP32 desk lamp | Aug 2026 | Code · macOS only |
| [**PICKORA**](https://github.com/kavin-jain/pickora) | Café and pickleball court booking (Next.js, Firebase), with real-time slot locking and an admin dashboard | May 2026 | Live at [pickora.in](https://pickora.in) |
| [**Robo Soccer**](https://github.com/kavin-jain/robo-soccer) | Hand-built sheet-metal RC soccer bot. Twin-joystick tank steering over an NRF24L01 link | 2024 | Code + build notes |
| [**Swarm Intelligence**](https://github.com/kavin-jain/swarm-intelligence) | Decentralised ESP32 swarm over ESP-NOW, with no central controller | 2024 | Write-up + photo |
| [**Card Detection**](https://github.com/kavin-jain/yolo-card-detection) | Real-time playing-card detection with YOLOv8 (54 classes) | 2023 | Write-up + screenshot |

Not public yet: a 12-servo 3D-printed quadruped (FABRIK inverse kinematics on ESP32, 2025) and an ESP32 + NFC attendance system built for a Model UN conference.

**Toolbox:** ESP32 / ESP32-S3 · C++ · PlatformIO · LVGL · CC1101 / NRF24L01 / PN532 · PCB design & soldering · 3D printing · Python · pandas · TypeScript · Next.js · Firebase · YOLOv8 / OpenCV

---

### Also

- **Head of Operations** across 4 Model UN conferences, with delegate awards in 4 committees
- I run a daily feeding route for street animals in Udaipur

<sub><i>"Built from the circuit up."</i></sub>
