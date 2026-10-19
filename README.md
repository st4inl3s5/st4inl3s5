# Yiğit Aydemir (`st4inl3s5`)

**Security Researcher & Systems Developer**  
Edirne, Turkey · [yigitaydemir.com](https://yigitaydemir.com) · [LinkedIn](https://www.linkedin.com/in/yi%C4%9Fit-aydemir-7b8367164/) · [Medium](https://medium.com/@st4inl3s5)

---

### Core Focus & Research

- **Offensive Systems & C2 Internals:** Engineering distributed command-and-control topologies, memory-only execution pipelines, and covert communication protocols from first principles.
- **Vulnerability Research & Disclosure:** Author of [CVE-2026-1617](https://www.cve.org/CVERecord?id=CVE-2026-1617) (critical SQL injection in enterprise software, responsibly disclosed via USOM).
- **Embedded & RF Telemetry:** Communications Officer at TRAKIHA UAV Team engineering high-throughput PtP RF telemetry pipelines, hardware bring-up, and power profiling on cellular IoT implants.
- **Operating System Internals:** Reverse engineering Windows x64 user/kernel structures, PE loader mechanics, direct syscall stubs, and memory evasion.

---

### Featured Systems & Architecture

#### [telekinetiC2](https://yigitaydemir.com/#telekinetic2) *(Private / Closed-Source)*
> *81,727 lines of C++17, Go, Kotlin, and React/TypeScript across 6 decoupled services and 4 implants.*
- **Burner Listener Topology:** Distributed architecture decoupling disposable public listener edge nodes from the core admin server via mutual TLS and custom binary wire protocols.
- **Implants & Evasion:** Multi-platform agents (Windows x64, Linux, Android) featuring custom PE loaders, memory-only execution, stack spoofing, and syscall unhooking.
- **Telemetry & Operator UI:** Real-time agent session orchestration, encrypted stage delivery, and multi-operator web console.

#### [Intelekinetic](https://yigitaydemir.com/#intelekinetic) *(Private / Hardware Research)*
> *Hardware-level power optimization and firmware telemetry on LilyGO T-SIM7600G-H (ESP32-WROVER + LTE).*
- **Hardware Bug Isolation:** Identified parasitic reverse-current leakage over the `USB_VBUS` line caused by ferrite bead `FB2` remaining energized during power-down.
- **Micro-Soldering Remediation:** Desoldered `FB2` under a microscope, dropping deep-sleep standby draw from **22–30 mA down to 0.5 mA** (98% reduction).
- **Benchmarking:** Validated through a 990-cycle automated wake/transmit/sleep discharge test bench.

#### [OS-Internals](https://github.com/st4inl3s5/OS-Internals) *(Public)*
> *Personal research notes, architectural breakdowns, and hands-on C/C++ labs on operating system internals.*
- In-depth coverage of Windows x64 architecture: Virtual Memory, PEB/TEB walking, PE format parser, loader internals, tokens & handles, direct syscall execution, and stack unwinding.

#### [KIZAGAN](https://github.com/st4inl3s5/kizagan) *(Public)*
> *Covert Command & Control system and implant toolkit with custom binary wire protocol and stealth execution.*

---

### Technical Arsenal

| Domain | Technologies & Tooling |
| :--- | :--- |
| **Languages** | C, C++17, Go, Python, Kotlin, TypeScript, Bash, x86_64 Assembly, SQL |
| **Reverse Engineering & RE** | Ghidra, Radare2 (`r2`), GDB, Frida, JADX, Blutter, Wireshark, Burp Suite |
| **Embedded & Systems** | ESP-IDF (C), Jetson Xavier NX, Pixhawk Cube, LilyGO T-SIM7600G-H, RF PtP Telemetry |
| **DevOps & Infrastructure** | Linux (Arch), Docker, Nginx, PostgreSQL, Redis, Cloudflare Tunnels, QEMU/KVM |

---

### Recent Technical Publications

- **[Sıfırdan C2 Framework’ü İnşa Etmek: Mimariye Derinlemesine Bakış](https://medium.com/@st4inl3s5/s%C4%B1f%C4%B1rdan-c2-framework%C3%BC-i%CC%87n%C5%9Fa-etmek-mimariye-derinlemesine-bak%C4%B1%C5%9F-107d1be27ad3)** — Deep architectural analysis of telekinetiC2, burner listener routing, and wire protocols.
- **[CVE-2026-1617: Kurumsal Yazılımda SQL Injection ve Sorumlu Açıklama](https://lnkd.in/p/dwTPDFJY)** — Vulnerability discovery and responsible disclosure coordinated with USOM.
- **[Intelekinetic: LilyGO T-SIM7600G-H FB2 Hardware Fix](https://lnkd.in/p/dgKvw5Mt)** — Hardware reverse-engineering and power profiling writeup.
- **[TryHackMe Walkthroughs & CTF Notes](https://medium.com/@st4inl3s5)** — Technical write-ups covering HTTP Request Smuggling, client-side exploitation, and server-side vulnerabilities.

---

### Verification & Contact

- **Website & Archive:** [https://yigitaydemir.com](https://yigitaydemir.com)
- **LinkedIn:** [yiğit-aydemir](https://www.linkedin.com/in/yi%C4%9Fit-aydemir-7b8367164/)
- **CVE Record:** [CVE-2026-1617](https://www.cve.org/CVERecord?id=CVE-2026-1617)
- **Email:** `yigitaydemir522@gmail.com`
