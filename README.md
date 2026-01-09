# UI-Utils CevAPI 2.4.0 - Minecraft 1.21.11

This repository is a **fork of UI-Utils** updated specifically to support **Minecraft 1.21.11**.

This fork was created and shared **with the blessings of MrBreakNFix**.

## What it is

UI-Utils adds extra in-GUI utilities for debugging and testing inventory/container interactions, including tools for controlling packet sending behavior and fabricating GUI-related packets.

## Key features

- In-GUI buttons + a text field when you open inventories/containers
- Close GUI without sending a close packet
- Client/server GUI de-sync tools
- Toggle sending GUI click packets on/off
- Delay packets and flush them later
- Save the current GUI for later access via keybind
- Packet fabrication tools:
  - `ClickSlotC2SPacket`
  - `ButtonClickC2SPacket`
- Copy GUI title JSON
- Chat/command box usable while inside a GUI
- Optional resource pack bypass/deny tools (server-dependent)

> Note: Some features may be unreliable on macOS (especially packet fabrication UI).

## Compatibility

- **Minecraft:** 1.21.11  
- **Loader:** Fabric  
- **Requires:** Fabric API

## Usage

Open any inventory/container in-game and you should see UI-Utils controls on the screen.  
(See the upstream documentation/screenshots for full feature explanations.)

## Commands

- `^toggleuiutils` — Enables/Disables UI-Utils GUI rendering.

## Building

Build instructions are provided on the UI-Utils website:  
https://ui-utils.com

## Credit

- Original project: UI-Utils (upstream authors)
- Fork maintenance/1.21.11 support: this repository
- Special thanks: **MrBreakNFix** for allowing this fork to be made/maintained

## Disclaimer

This project is intended for debugging/testing. Use responsibly and respect server rules and community guidelines.
