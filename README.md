# `XpertLambda`

**Cybersecurity Engineering Student - Security Researcher & Low-Level Tooling Developer**

Security engineer in training, focused on the layers most tooling skips: firmware, kernels, network protocols, and the hardened infrastructure that ties them together. I build offensive and defensive tools from scratch - mostly in **C, C++, and Python** - and design secure systems end to end, from CAN-bus attack labs to Kerberos-backed Unix estates.

---

## Focus Areas

- **Offensive Security & Tooling** - password/hash recovery engines, Windows auditing frameworks, exploitation workflows
- **Automotive & Embedded Security** - CAN-bus attack & defense, ECU firmware reverse engineering, message authentication (SecOC / UDS)
- **Secure Infrastructure & Detection** - Proxmox / OPNsense lab design, SIEM + IDS pipelines, Kerberos & PKI, Linux and kernel hardening
- **Systems & Network Programming** - a C standard library from scratch, low-level automation, custom application-layer protocols

---

## Technical Toolbox

| Domain | Technologies |
|---|---|
| **Languages** | C · C++ · x86/x64 Assembly · Python · Bash · PowerShell · SQL |
| **Security** | Metasploit · Hashcat · Wireshark · Snort · OSSEC · Prelude SIEM · SELinux · grsecurity / PaX |
| **Infrastructure** | Proxmox VE · KVM · Docker · Ansible · Vagrant · OPNsense · OpenVPN · Kerberos / PKI |
| **Systems** | Linux internals (Arch / CentOS / Gentoo) · Windows internals & API · Kernel modules · LUKS / Btrfs |

---

## Selected Projects

### Security Tooling & Offensive

**[SysRecon](https://github.com/XpertLambda/SysRecon)** - Windows security auditing framework (C++ / Win32) for SOC teams and pentesters: automated enumeration of security configuration, posture assessment, and generated compliance & hardening reports.

**[Crasher](https://github.com/XpertLambda/Crasher)** - High-performance, multi-threaded hash-recovery toolkit (C) supporting MD5 / SHA-1 / SHA-256 across brute-force, probabilistic, and dictionary attacks, with an optimized wordlist-generation engine.

### Automotive & Embedded Security

**[ICSim](https://github.com/XpertLambda/ICSim)** - Instrument-cluster / CAN-bus security lab: a vulnerable simulator paired with a hardened variant adding **SecOC** message authentication (AES-128-CMAC) and **UDS** service hardening, plus interactive frame-injection and SecurityAccess tooling.

**[ECU-Firmware-RE](https://github.com/XpertLambda/ECU-Firmware-RE)** - Reverse engineering of automotive ECU firmware: teardown, static analysis, and documentation of firmware internals and attack surface.

### Secure Infrastructure, Detection & Cloud

**[Cyber Security CTF Environment](https://github.com/XpertLambda/CTF)** *(ongoing)* - Full Capture-The-Flag platform on **Proxmox VE** with a custom Python orchestrator driving the Proxmox API, an **OPNsense** gateway/firewall, OpenVPN student access, and host-level `tap`-interface isolation that holds even against in-VM `root` - hosting 15+ isolated challenges on a Dockerized CTFd.

**Hardened Unix Infrastructure with Kerberos** *(academic)* - Enterprise Linux estate with a centralized **Kerberos** KDC, **NFSv4** with krb5p / krb5i, **SELinux** in MLS/MCS modes, a PaX/grsecurity-hardened Gentoo, and a custom Certificate Authority securing TLS services.

**Enterprise Intrusion Detection System** *(academic)* - Multi-layer detection stack unifying **Snort**, **OSSEC**, and **Prelude SIEM** with custom signatures and a real-time correlation engine for brute-force and lateral-movement detection.

**[ContainerPool](https://github.com/XpertLambda/ContainerPool)** *(academic)* - Self-hosted Platform-as-a-Service with pre-warmed container pools reaching sub-second provisioning; a multi-tenant **Flask** REST backend orchestrating Docker via **Ansible** and **Vagrant / KVM**.

### Systems & Network Programming

**[MiniGlibC](https://github.com/XpertLambda/MiniGlibC)** - A minimal C standard library built from scratch: custom memory allocator, string and I/O primitives, and shell-style utilities, with no external dependencies.

**[Auto-Archchroot](https://github.com/XpertLambda/Auto-Archchroot)** - Arch Linux recovery automation (Python) that detects bootloader and partition layout - including **LUKS** encryption and **Btrfs** subvolumes - and generates ready-to-run chroot repair scripts.

**[Multiplayer-AOE-Protocol](https://github.com/XpertLambda/Multiplayer-AOE-Protocol)** *(team lead)* - A custom low-latency, application-layer protocol bridging Python and C for synchronized real-time multiplayer strategy sessions.

**[AIge-Of-EmpAIres](https://github.com/XpertLambda/AIge-Of-EmpAIres)** *(team lead)* - Real-time strategy game with autonomous AI opponents driven by decision-tree planning for economy, construction, and tactical combat.

---

## Languages

French (B2) · English (B2) · Arabic (Native)

---

<sub>Open to collaboration on security research, tool development, and infrastructure hardening.</sub>
