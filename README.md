# 🦉 OPortX

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-0a0c10?style=flat-square"/>
  <img src="https://img.shields.io/badge/Category-OScan-blue?style=flat-square"/>
  <img src="https://img.shields.io/badge/License-MIT-green?style=flat-square"/>
  <img src="https://img.shields.io/badge/Part%20of-OwlSec%20Toolkit-7b5ea7?style=flat-square"/>
  <img src="https://img.shields.io/badge/Version-1.0.0-cyan?style=flat-square"/>
</p>

> **OPortX** — Port Scanner

---

> ⚠️ **AUTHORISED USE ONLY** — Use only on systems you own or have explicit written permission to test. Unauthorised use is illegal.

---

## 📌 Overview

OPortX is a threaded TCP connect port scanner. It scans single ports, ranges or common-port presets, performs host discovery across a range, and can grab service banners. Results can be exported as TXT, CSV or JSON.

---

## ✨ Features

- Threaded TCP connect scanning of single ports, ranges or lists
- Common-ports preset for quick one-shot scans
- Host discovery across a CIDR or range
- Service fingerprinting via a well-known port map and banners
- Banner grabbing with safe timeouts
- Open/closed/filtered summary with TXT/CSV/JSON export

---

## ⚙️ Requirements

- **Linux**
- **No Python installation needed** — runs as a standalone executable

---

## 🚀 Usage

```bash
./OPortX -t 192.168.1.1 -p common
./OPortX -t example.com -p 1-1024 -b
./OPortX -t 10.0.0.5 -p 22,80,443 --json
./OPortX --help
```

---

## 📦 Part of OwlSec Toolkit

This tool is part of the **OwlSec** suite — a collection of 300+ security and privacy tools.

🔗 [owlsec.org](https://owlsec.org)

---

## ©️ License

MIT License — © Khaled S. Haddad

*Tools are distributed as pre-built executables. Source code is proprietary.*
