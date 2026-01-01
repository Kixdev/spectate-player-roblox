# 👁️ Roblox Spectate Player System (Client-Side)

> **Educational Purposes Only - Open Source UI & Camera Control Reference**

---

## 📌 Overview

**Roblox Spectate Player System** is a **client-side spectating tool** that allows players (or developers) to safely spectate other players in-game using a **modern, draggable user interface**.

This system focuses on:
- Clean UI/UX design
- Safe camera control
- Smooth spectate transitions
- Educational scripting practices

❗ This system does **not** modify server data  
❗ No RemoteEvents or exploits are used  
❗ Fully client-side and streaming-safe  

---

## 🎯 Purpose

The purpose of this project is to provide:

- A reference implementation for **spectate mechanics**
- An example of **camera handling on the client**
- A reusable **player list & navigation UI**
- A safe alternative to unsafe or exploit-based spectate scripts

Designed for:
- Game developers
- Moderators / admins (visual only)
- Educational Roblox scripting
- UI & camera prototyping

---

## ✨ Features

### 🔹 Player Spectating
Allows the local player to spectate other players by attaching the camera to the target player’s humanoid.

- Smooth camera transition
- Automatic re-spectate on respawn
- Safe fallback when stopping spectate

---

### 🔹 Player List with Search
Displays a live list of all players in the server (excluding the local player).

- Username & display name support
- Real-time search filtering
- Click-to-spectate interaction

---

### 🔹 Navigation Controls
Quickly switch between players without reopening the list.

- Previous / Next player buttons
- Keyboard shortcuts support
- Maintains player order consistently

---

### 🔹 Modern Draggable UI
A clean, floating interface designed for usability and streaming safety.

- Draggable header
- Minimize / expand functionality
- Responsive layout
- Non-intrusive design

---

### 🔹 Status Indicator
Displays the currently spectated player in real time.
