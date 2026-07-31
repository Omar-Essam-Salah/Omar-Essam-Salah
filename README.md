<div align="center">

```text
 ██████╗ ███╗   ███╗ █████╗ ██████╗
██╔═══██╗████╗ ████║██╔══██╗██╔══██╗
██║   ██║██╔████╔██║███████║██████╔╝
██║   ██║██║╚██╔╝██║██╔══██║██╔══██╗
╚██████╔╝██║ ╚═╝ ██║██║  ██║██║  ██║
 ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝
```

no cloud, no accounts, just systems that run

# السَّلامُ عَلَيْكُم

IT Systems Administrator · security & hardware · offline-first apps, embedded systems, and on-device AI

</div>

---

I build things that work on their own. No cloud, no accounts, no one else's servers.

By day I'm an IT systems administrator. The rest of the time I'm soldering boards, writing firmware,
training vision models, and shipping apps, usually the whole stack myself. The rule is simple: if it can
run offline, private, and on hardware I control, that's how I build it.

Security runs through all of it, from hardening networks at work to assembling Flipper Zero kits at home.
And a good part of what I make I give away for free, as ṣadaqah jāriyah.

## Projects

### [Nur — Quran & Azkar](https://github.com/Omar-Essam-Salah/Nur-Quran-Azkar)
A free, ad-free Quran and Azkar app that works fully offline, now heading to Google Play. The full Uthmani
Quran with a byte-level integrity check, a paper Mushaf and a verse-by-verse reader, word-by-word tap
(meaning and audio for each word), many reciters with live highlighting, prayer times and adhan computed on
the device, Qibla, azkar with sources, a duʿāʾ library, hadith from nine Sunni collections, a memorization
companion, and a multi-language interface. The Quran text always stays in Arabic.

React · TypeScript · Vite · Tailwind · Capacitor

### [COOPER — offline AI presence](https://github.com/Omar-Essam-Salah/cooper-ai)
The ambitious one. An always-on AI companion that runs with no cloud at all: a local LLM with real-time
speech, spread across a few ESP32 nodes (mic array, display, power rails) talking to a GPU box over a local
bus. Published here as the concept and the engineering behind it, not the source.

Local LLM (Ollama / Qwen) · faster-whisper · Piper · Silero VAD · ESP32-S3 · UDP mesh

### [Handball AI — real-time tactical analysis](https://github.com/Omar-Essam-Salah/handball-ai-system)
Point a 4K camera at a handball match and it follows every player and the ball live, calls the events
(pass, shot, goal, save, fast break), and cuts a tactical replay and stats for each goal. Runs fully offline
on CUDA. Shown for the idea and the engineering; the code stays private.

Python · YOLOv8 · OpenCV · PyTorch · OSNet Re-ID · Kalman · FastAPI

### [esp32-retro-console](https://github.com/Omar-Essam-Salah/esp32-retro-console)
A handheld game console I built from the board up. Custom ESP32-S3 hardware and firmware that boots to an
SD-card ROM browser and runs NES, Game Boy, Master System and Mega Drive, with Wi-Fi upload straight to the card.

C++ · ESP32-S3 · PlatformIO · I2S audio · ST7789 · FreeRTOS

### [Security and hardware](https://github.com/Omar-Essam-Salah/embedded-security-suite)
I build wireless-security research tools on M5Stick and ESP32: customized Bruce firmware with a Flipper
Zero-inspired UI, WiFi and BLE auditing, NFC and RFID testing, and a BLE-authentication access control, for
authorized testing only. I also build and assemble Flipper Zero and RF gear. Same instinct as the day job:
learn how something breaks, then close the gap.

### Enterprise IT and local AI
At work I run and automate networks and servers, and I build local-AI setups that keep data in house,
offline RAG and self-hosted models with Ollama.

## More on GitHub
- [ble-gyro-mouse](https://github.com/Omar-Essam-Salah/ble-gyro-mouse) — a wireless ESP32 + MPU6050 air-mouse that pairs as a standard BLE HID, no drivers.
- [hardware-password-vault](https://github.com/Omar-Essam-Salah/hardware-password-vault) — an offline, hardware-encrypted password manager that resists remote software attacks.
- [dasai-mochi](https://github.com/Omar-Essam-Salah/dasai-mochi) — a compact interactive desk robot with expressive animation on a small TFT display.

## Tech

<div align="center">

**Mobile and Web**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![Capacitor](https://img.shields.io/badge/Capacitor-119EFF?style=flat-square&logo=capacitor&logoColor=white)

**Embedded and Hardware**

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white)

**Computer Vision and AI**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![YOLOv8](https://img.shields.io/badge/YOLOv8-111F68?style=flat-square&logo=ultralytics&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![Ollama](https://img.shields.io/badge/Ollama-000000?style=flat-square&logo=ollama&logoColor=white)

**Security and Hardware Hacking**

![Flipper Zero](https://img.shields.io/badge/Flipper%20Zero-FF8200?style=flat-square)
![M5Stick](https://img.shields.io/badge/M5Stick-E60012?style=flat-square)
![Sub-GHz RF](https://img.shields.io/badge/Sub--GHz%20RF-222222?style=flat-square)
![BLE](https://img.shields.io/badge/BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)
![RFID / NFC](https://img.shields.io/badge/RFID%20%2F%20NFC-222222?style=flat-square)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white)

**Systems and Infrastructure**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Windows Server](https://img.shields.io/badge/Windows%20Server-0078D4?style=flat-square&logo=windows&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

</div>

---

<div align="center">

Free · offline-first · no tracking.

</div>
