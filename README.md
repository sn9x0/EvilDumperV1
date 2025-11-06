# EvilDumpFucker v1 – README

## Description
**EvilDumpFucker** is a powerful analysis tool for FiveM dumps.  
It scans `.lua` files for:

- `TriggerServerEvent` calls (event name + payload)
- Discord webhooks
- Coordinates (`vector3(...)`, `x, y, z`) with context (teleport, stash, garage, etc.)
- Export function (TXT to Desktop)

Additionally: **Webhook Tools** for testing, spamming, or deleting webhooks.

---

## Features

| Tab | Function |
|-----|----------|
| **Triggers** | All `TriggerServerEvent` calls (event name + file) |
| **Event Parser** | Parse input → extract name & payload + copy |
| **Webhooks** | All found webhook URLs with path |
| **Coords + Target** | Coordinates with likely target (e.g. Safe, Garage) |
| **Webhook Tools** | Test, Spam (with delay & random), Delete, Proxy support |

---

## Usage

1. **Scan Dump** → Select folder with `.lua` files
2. Wait → All data loads automatically
3. Browse, filter, export via tabs
4. Select webhook → Test, Spam, or Delete

---

## Export
- Click **Export**
- File saved to **Desktop**:

---

## Security Notes
- Use only on **private dumps**
- Do not share sensitive server data
- Webhook spam may cause **rate limits** or **bans**

---

## Technical Info
- Runs **without installation**
- **No CMD window** on startup
- Built as `.exe` with **PyInstaller**
- **100% local** – no cloud dependency

---

## Version
v1.0 – EntireCFW

> **EvilDumpFucker – Clean. Fast. Effective.**
