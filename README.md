<div align="center">
  <h1>NIMBUS | ENTERPRISE</h1>
  <p><b>High-performance utility suite for the Roblox engine.</b></p>
  
  <p>
    <a href="https://github.com/nimbusx64/nimbus.roblox/issues">Report Bug</a> •
    <a href="https://github.com/nimbusx64/nimbus.roblox/issues">Request Feature</a>
  </p>
  
  <img src="https://img.shields.io/badge/status-active-purple?style=flat-square" alt="Status">
  <img src="https://img.shields.io/badge/license-MIT-blue?style=flat-square" alt="License">
</div>

---

## 🚀 Overview
**Nimbus** is a custom-engineered utility suite designed for Roblox, focusing on stability, performance, and a modern, enterprise-grade user interface. Built with C# and optimized for seamless interaction, Nimbus provides a professional environment for game modification and script execution.

> **Our Philosophy:** We prioritize performance and safety. Nimbus is built to be a low-overhead tool that respects your system resources.

---

## 🔓 Community & Open Source
**Transparency is our policy.**
All scripts hosted within the Nimbus Hub are **100% open-source**. We believe in the power of community-driven development.
*   **Audit Everything:** You have full visibility into every line of code that executes.
*   **Contribution:** Want to improve a script or add a new category? Submit a pull request to our repository.
*   **Trust:** No obfuscated "black box" code. What you see is what you get.

---

## ✨ Core Features
*   **Enterprise-Grade UI:** Obsidian-slate aesthetic featuring GDI+ custom rasterization for a sleek, responsive feel.
*   **Dynamic Script Hub:** Real-time cloud synchronization. Scripts are categorized and cached locally for instant access.
*   **Panic Protocol:** Immediate process termination and memory sanitization for enhanced user safety.
*   **Optimized Injection:** Low-latency interaction with the Roblox rendering process via QuorumAPI.
*   **Intuitive Hierarchy:** Clean, file-system style browsing for professional script management.

---

## 🛠️ Technical Specifications

| Category | Specification |
| :--- | :--- |
| **Language** | C# / .NET 6.0+ |
| **UI Framework** | WinForms (Custom GDI+) |
| **API Integration** | QuorumAPI |
| **Data Protocol** | GitHub REST API v3 |
| **Storage** | Encrypted Local Cache |

---

## 📋 Quick Start
1. **Download:** Grab the latest binary from the [Releases](https://github.com/nimbusx64/nimbus.roblox/releases) page.
2. **Initialize:** Ensure all dependencies are present in the root execution directory.
3. **Execution:** Launch the application; Nimbus will automatically detect the Roblox process.
4. **Library:** Access the **Hub** module to pull the latest community scripts automatically.

---

## 🛡️ Security & Privacy
Nimbus operates with a "Safety-First" policy. 
*   **Process Isolation:** The injector runs in a sandboxed thread to ensure system stability.
*   **Zero Telemetry:** We do not collect personal data, IP addresses, or hardware IDs.
*   **Clean Exit:** Our Panic Protocol ensures all hooks are released before the application closes.

---

## 🗺️ Developer Roadmap

### 🟢 Phase 1: Foundation & Stability (Completed)
- [x] Core Injector Architecture
- [x] Cloud-Sync Script Hub Implementation
- [x] Obsidian/Slate UI Framework
- [x] GDI+ Custom Rasterization

### 🟡 Phase 2: Performance & Optimization (In Progress)
- [ ] **Multi-Process Management:** Allow Nimbus to attach to multiple instances of the game engine simultaneously.
- [ ] **Panic Protocol v2:** Advanced memory sanitization to prevent process flagging.
- [ ] **Hot-Reloading:** Ability to reload scripts from the Hub without restarting the injection process.
- [ ] **Resource Profiler:** Live monitoring of script CPU/Memory consumption to identify "heavy" scripts.

### 🔵 Phase 3: Advanced UI & Scripting Tools
- [ ] **Built-in Script Editor:** Integrated IDE within Nimbus featuring syntax highlighting and error checking.
- [ ] **IntelliSense Integration:** Autocomplete support for common Roblox engine functions.
- [ ] **Config Persistence:** Save user-defined settings, UI layout preferences, and keybinds to local `settings.json`.
- [ ] **Script Metadata:** Add "Author," "Version," and "Description" fields to hub items for better organization.

### 🟣 Phase 4: Enterprise Connectivity & Security
- [ ] **Discord Rich Presence:** Real-time status integration showing script activity to friends.
- [ ] **Cloud Profiles:** Sync user-specific script shortcuts and favorites to the cloud via OAuth.
- [ ] **Auto-Updater Module:** Seamless delivery of hotfixes and engine compatibility patches.
- [ ] **Obfuscated Injection:** Advanced binary protection to ensure the integrity of the injector during runtime.
- [ ] **Log Analytics:** Automated report generation for crash logs, helping us improve stability faster.

### ⚪ Phase 5: Community & Ecosystem
- [ ] **Public API Documentation:** Allow third-party developers to integrate their own modules into Nimbus.
- [ ] **Community Plugin System:** Support for user-created UI themes and external utility plugins.

---

## 📂 Repository Structure
```text
/nimbus.roblox
├── /hub              # Cloud-synced script library
│   ├── /Combat       # Organized Category
│   │   └── Script.lua
│   └── support.txt   # Documentation
├── MainForm.cs       # Main dashboard interface
├── HubForm.cs        # Hierarchy-based browser
└── QuorumAPI.dll     # Core injection driver
