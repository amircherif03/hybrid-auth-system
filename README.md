# Hybrid Authentication System — PPP 2025

> Academic Project (PPP) — INSAT Tunis 2025 | Embedded Systems & Security

## Overview
Two-factor physical access control system combining RFID card reading and
fingerprint biometric verification. Access logs stored securely in MySQL database.

## Tech Stack
| Layer | Technology |
|-------|-----------|
| Hardware | Arduino Uno, RFID RC522, fingerprint sensor |
| Language | C/C++ (Arduino) |
| Database | MySQL |
| Protocol | Serial communication |

## Features
- RFID card detection and UID verification
- Fingerprint biometric scan and matching
- Dual-factor: both required for access
- MySQL logging of all access attempts
- Relay-controlled door lock

## How it Works
[RFID Card] ──→ [Arduino]
↓
[Fingerprint] ──→ [Match both?] ──→ YES → [Unlock door] → [Log to MySQL]
NO  → [Deny + Alert]

## Status
✅ Completed — 2025
