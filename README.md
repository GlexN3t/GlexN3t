<!-- ============================================================
     GlexN3t · GitHub profile README
     Edit the <REPLACE-ME> markers and the REDACTED table rows.
     Everything else is safe to keep as-is.
     ============================================================ -->

<div align="center">

```text
 ██████╗ ██╗     ██╗███████╗███╗   ██╗███████╗███████╗
██╔════╝ ██║     ██║██╔════╝████╗  ██║██╔════╝╚══███╔╝
██║  ███╗██║     ██║█████╗  ██╔██╗ ██║█████╗    ███╔╝
██║   ██║██║     ██║██╔══╝  ██║╚██╗██║██╔══╝   ███╔╝
╚██████╔╝███████╗██║███████╗██║ ╚████║███████╗███████╗
 ╚═════╝ ╚══════╝╚═╝╚══════╝╚═╝  ╚═══╝╚══════╝╚══════╝
```

<img src="https://readme-typing-svg.demolab.com/?font=JetBrains+Mono&weight=600&size=22&pause=1200&color=35D07F&center=true&vCenter=true&width=760&height=50&lines=Security+Researcher+%E2%80%94+Firmware+%C2%B7+IoT+%C2%B7+RF;Breaking+things+that+fly+%F0%9F%9B%B8;Defense+%26+embedded+systems;Responsible+disclosure+only" alt="typewriter banner" />

[![Focus](https://img.shields.io/badge/focus-firmware_%C2%B7_IoT_%C2%B7_RF_%C2%B7_UAS-35D07F?style=flat-square&labelColor=111823)](#)
[![Disclosure](https://img.shields.io/badge/disclosure-responsible-35D07F?style=flat-square&labelColor=111823)](#)
[![Status](https://img.shields.io/badge/status-learning_in_public-4db8ff?style=flat-square&labelColor=111823)](#)

</div>

---

## 🔎 About

Security researcher focused on the attack surface most people never look at:
**embedded firmware, IoT/RF stacks, and unmanned systems** — with a growing
interest in the **defense & aerospace** vendor space and their vulnerability
disclosure programs.

What I actually do:

- **Firmware analysis** — extraction, unpacking, static + dynamic reversing
- **IoT / radio protocols** — MAVLink, BLE, MQTT, LoRa; protocol fuzzing
- **Hardware interfaces** — UART / JTAG / SPI / I2C recon and abuse
- **Android** — APK reversing, Frida instrumentation, IPC abuse
- **Web / API** — auth logic, broken object-level authorization, exposed backends

> ⚠️ Everything here is done through **responsible disclosure** — public
> bug bounty platforms and vendor VDPs. No exceptions.

---


---

## 🚀 Projects

<!-- EDIT ME: keep this row synced with your pinned repos -->

[![SkyBridge](https://img.shields.io/badge/🛩️_SkyBridge-ESP32_MAVLink_telemetry_bridge-0b0f14?style=for-the-badge&labelColor=111823)](https://github.com/GlexN3t/skybridge)
[![CI](https://github.com/GlexN3t/skybridge/actions/workflows/ci.yml/badge.svg)](https://github.com/GlexN3t/skybridge/actions/workflows/ci.yml)

**[SkyBridge](https://github.com/GlexN3t/skybridge)** — a companion-computer
platform for drones: hand-rolled MAVLink v2 protocol stack in auditable C
(framing state machine, CRC-16/X-25, per-message CRC_EXTRA), a pure-Python
virtual drone for hardware-free development, cross-language conformance
tests, and a live browser ground station with an artificial-horizon HUD.
Three CI pipelines: host unit tests · Python↔C interop · ESP-IDF build.

> *Next up:* on-target WiFi/UDP link under QEMU emulation, then real flight
> hardware — and firmware security tooling built along the way.

---

## 🧰 Arsenal

| Domain | Tools |
|--------|-------|
| **Reversing** | Ghidra · radare2 · binwalk · strings/entropy triage |
| **Hardware** | UART · JTAG · SPI · I2C · logic analyzers |
| **RF / UAS** | SDR toolchain · MAVLink · drone link analysis |
| **Mobile** | Frida · Objection · apktool · MobSF · adb |
| **Web / API** | Caido · Burp Suite · custom fuzzers |
| **Firmware dev** | ESP-IDF · FreeRTOS · C/C++ · Python |

---

## 📊 GitHub stats

<!-- External widgets (github-readme-stats). Delete this block if you
     prefer a fully self-contained profile. -->

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=GlexN3t&show_icons=true&theme=radical&hide_border=true&bg_color=0,0b0f14,111823" alt="GitHub stats" height="165" />
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=GlexN3t&layout=compact&theme=radical&hide_border=true&bg_color=0,0b0f14,111823" alt="Top languages" height="165" />
</div>

---

## 📡 Contact

<!-- EDIT ME: use channels you're comfortable making public.
     Never paste a personal phone number or home address anywhere public. -->

- **Email:** `<REPLACE-ME or remove>`
- **Discord:** `<REPLACE-ME or remove>`
- **Bug bounty platforms:** `<e.g. YesWeHack / Bugcrowd / HackerOne — your call whether to list>`

PGP: `<optional fingerprint — nice touch for a security profile>`

---

<div align="center">

*"The most interesting bugs live where the datasheet ends."*

</div>
