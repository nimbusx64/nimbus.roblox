<p align="center">
  <h1 align="center">NIMBUS | ENTERPRISE</h1>
  <p align="center">
    High-performance utility suite for the Roblox engine.
    <br>
    <a href="https://github.com/nimbusx64/nimbus.roblox/issues">Report Bug</a>
    ·
    <a href="https://github.com/nimbusx64/nimbus.roblox/issues">Request Feature</a>
  </p>
</p>

---

## 🚀 Overview
**Nimbus** is a custom-engineered utility suite designed for Roblox, focusing on stability, performance, and a modern, enterprise-grade user interface. Built with C# and optimized for seamless interaction, Nimbus provides a professional environment for game modification and script execution.

## ✨ Core Features
*   **Enterprise-Grade UI:** Obsidian-slate aesthetic featuring GDI+ custom rasterization for a sleek, responsive feel.
*   **Dynamic Script Hub:** Real-time cloud synchronization directly from this repository. Scripts are categorized and cached locally for instant access.
*   **Panic Protocol:** Immediate process termination and memory sanitization for enhanced user safety.
*   **Optimized Injection:** Low-latency interaction with the Roblox rendering process via QuorumAPI.
*   **Intuitive Hierarchy:** File-system style browsing for script management.

## 🛠️ Technical Specifications
| Category | Specification |
| :--- | :--- |
| **Language** | C# / .NET 6.0+ |
| **UI Framework** | WinForms (Custom GDI+) |
| **API Integration** | QuorumAPI |
| **Data Protocol** | GitHub REST API v3 |
| **Storage** | Encrypted Local Cache |

## 📋 Quick Start
1. **Download:** Grab the latest binary from the [Releases](https://github.com/nimbusx64/nimbus.roblox/releases) page.
2. **Initialize:** Ensure all dependencies are present in the root execution directory.
3. **Execution:** Launch the application; Nimbus will automatically detect the Roblox process.
4. **Library:** Access the **Hub** module to pull the latest community scripts automatically.

## 🛡️ Security & Privacy
Nimbus operates with a "Safety-First" policy. 
*   **Process Isolation:** The injector runs in a sandboxed thread to ensure system stability.
*   **No Telemetry:** We do not collect personal data, IP addresses, or hardware IDs.
*   **Clean Exit:** The Panic Protocol ensures all hooks are released before the application closes.

## 🗺️ Developer Roadmap
- [x] Core Injector Architecture
- [x] Cloud-Sync Script Hub Implementation
- [ ] Multi-Process Support
- [ ] Script Encryption/Obfuscation Module
- [ ] User Settings & Config Persistence

## 📂 Repository Structure
```text
/nimbus.roblox
├── /hub            # Cloud-synced script library
│   ├── Category-Name.lua
│   └── support.txt
├── MainForm.cs     # Main dashboard interface
├── HubForm.cs      # Hierarchy-based browser
└── QuorumAPI.dll   # Core injection driver
