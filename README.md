# Ahmad Saad

**Cybersecurity Engineering Student | Security Researcher & Tool Developer**

Fourth-year Cybersecurity and Information Technology Engineering student at **INSA Centre Val de Loire**, specializing in secure system architecture, automation, and low-level security tooling. Currently seeking a **Cybersecurity Engineering internship** starting **April 2026**.

---

## Core Competencies

### Security Operations & Analysis
Penetration Testing • Intrusion Detection Systems (Snort, Prelude SIEM) • Host-based Intrusion Detection (OSSEC) • Network Traffic Analysis (Wireshark) • Exploitation Frameworks (Metasploit) • Password Cracking (Hashcat) • Memory Forensics • Security Event Correlation • Vulnerability Assessment

### Systems & Infrastructure
Kernel-based Virtual Machines (KVM) • Container Orchestration (Docker) • Enterprise Virtualization (Proxmox VE, VMware) • Infrastructure as Code (Ansible, Vagrant) • Linux System Hardening (Arch, CentOS, Gentoo) • Windows Internals • Mandatory Access Control (SELinux, grsecurity) • Public Key Infrastructure (PKI/CA)

### Network Engineering
Socket Programming • TCP/IP Stack Implementation • VLAN Segmentation • VPN/IPSec Configuration • Deep Packet Inspection • Custom Protocol Design • Network Security Architecture

### Development & Programming
**Systems Programming:** C/C++, x86/x64 Assembly  
**Automation & Scripting:** Python, Bash, PowerShell  
**Backend Development:** Flask REST APIs, SQL  
**Security Tooling:** Windows API, Linux Kernel Modules

### Authentication & Identity Management
Kerberos Key Distribution Center (KDC) • Network File System Security (NFSv4 with krb5p/krb5i) • Principal Management • Centralized Authentication Architecture

---

## Projects

### [Cyber Security CTF Environment](https://github.com/XpertLambda/CTF-Proxmox)
*Ongoing Development*

Full-scale Capture The Flag platform deployed on Proxmox infrastructure featuring 15+ security challenges across web exploitation, reverse engineering, and incident response.

**Key Achievements:**
- Engineered automated infrastructure provisioning pipeline using Ansible and Proxmox API
- Designed isolated container architecture ensuring challenge segregation and preventing cross-contamination
- Developed integrated scoring system with real-time monitoring dashboard
- Implemented network segmentation with granular firewall policies

**Stack:** Proxmox VE, Docker, Ansible, Network Architecture, Firewall Engineering

---

### Hardened Unix Infrastructure with Kerberos Authentication
*January 2026 • Academic Project*

Enterprise-grade secure Linux environment integrating centralized identity management and kernel-level defense mechanisms.

**Security Implementation:**
- **Identity Management:** Deployed Kerberos KDC on CentOS 9 for centralized authentication and principal management across distributed systems
- **Secure Storage:** Integrated NFSv4 with Kerberos encryption modes (krb5p for privacy, krb5i for integrity) ensuring authenticated and protected remote file access
- **Kernel Hardening:** Applied PaX and grsecurity patches on Hardened Gentoo providing ASLR enhancement, memory protection, and exploit mitigation
- **Access Control:** Configured SELinux in Multi-Level Security (MLS) and Multi-Category Security (MCS) modes for data segregation across clearance levels
- **PKI Architecture:** Established custom Certificate Authority securing Apache web servers with TLS/HTTPS

**Stack:** Kerberos, NFSv4, SELinux, grsecurity, PKI/CA, Apache, CentOS, Hardened Gentoo

---

### [Auto-Archchroot](https://github.com/XpertLambda/Auto-Archchroot)
*January 2025*

Intelligent automation framework for Arch Linux system recovery and chroot environment configuration.

**Features:**
- Automatic detection and analysis of system configurations including bootloader and partition schemes
- Native support for LUKS full-disk encryption and Btrfs subvolume architectures
- Generates executable recovery scripts for live environment troubleshooting and repair operations

**Stack:** Python, Bash, Linux Internals, Cryptography (LUKS), Filesystem Management (Btrfs)

---

### [ContainerPool](https://github.com/XpertLambda/ContainerPool)
*January 2026 • Academic Project*

Self-hosted Platform-as-a-Service featuring pre-initialized container pools with sub-second provisioning capabilities.

**Technical Features:**
- Multi-tenant user management system with secure file upload functionality
- Automated infrastructure orchestration leveraging Ansible and Vagrant/KVM integration
- RESTful API backend built with Flask managing Docker container lifecycle
- Achieved <1 second deployment time through intelligent container pre-warming

**Stack:** Docker, Flask, Ansible, Vagrant, KVM, Shell Scripting, REST API Design

---

### [SysRecon](https://github.com/XpertLambda/SysRecon)
*Under Active Development*

Comprehensive Windows security auditing framework designed for IT administrators, Security Operations Centers, and penetration testing teams.

**Capabilities:**
- Automated enumeration and analysis of Windows security configurations
- Security posture assessment with vulnerability identification
- Generates detailed compliance and hardening reports

**Stack:** C++, Windows API, Security Assessment Frameworks

---

### [Multiplayer-AOE-Protocol](https://github.com/XpertLambda/Multiplayer-AOE-Protocol)
*March 2025 • Academic Project*

Real-time strategy game inspired by Age of Empires II featuring custom multiplayer networking architecture.

**Technical Implementation:**
- Hybrid Python-C communication system optimized for low-latency real-time gameplay
- Custom application-layer protocol for synchronized multiplayer sessions
- Efficient state synchronization for resource management and unit coordination

**Stack:** Python, C, Socket Programming, Custom Network Protocols, Real-time Systems

---

### [AIge-Of-EmpAIres](https://github.com/XpertLambda/AIge-Of-EmpAIres)
*January 2025 • Academic Project*

Real-time strategy game featuring intelligent AI opponents powered by decision tree algorithms.

**AI Systems:**
- Advanced autonomous resource management and strategic planning algorithms
- Decision tree implementation enabling dynamic tactical combat behavior
- Autonomous unit training, structure construction, and battlefield coordination

**Stack:** Python, Artificial Intelligence, Decision Trees, Game Development

---

### [MiniGlibC](https://github.com/XpertLambda/MiniGlibC)
*October 2024*

Minimalistic C standard library implementation built from scratch without external dependencies.

**Implementation:**
- Custom memory management primitives (malloc, free, memory operations)
- String manipulation and file I/O operations
- Shell-like utility functions for system-level programming

**Stack:** C, Systems Programming, Low-level Development, Memory Management

---

### Enterprise Intrusion Detection System
*January 2024 • Academic Project*

Multi-layered defensive security architecture simulating enterprise-grade network protection.

**Architecture:**
- Deployed unified security monitoring with Prelude SIEM aggregating events from multiple detection engines
- Configured Snort for network-based intrusion detection with custom signature development
- Integrated OSSEC for host-based security monitoring and log analysis
- Developed custom detection rules for SSH brute-force attacks and lateral movement patterns
- Implemented real-time correlation engine for cross-layer threat detection

**Stack:** Prelude SIEM, Snort, OSSEC, iptables, Log Analysis, Network Traffic Analysis

---

### [Crasher](https://github.com/XpertLambda/Crasher)
*April 2023*

High-performance cryptographic toolkit for hash analysis and password recovery operations.

**Capabilities:**
- Multi-algorithm hash decryption supporting MD5, SHA-1, and SHA-256
- Multiple attack methodologies: ASCII brute-force, probabilistic generation, dictionary-based attacks
- Optimized wordlist generation engine for password cracking campaigns

**Stack:** C, Cryptographic Algorithms, Performance Optimization, Multi-threading

---

## Contact

**GitHub:** [github.com/XpertLambda](https://github.com/XpertLambda)  
**LinkedIn:** [linkedin.com/in/ahmad-msaad](https://www.linkedin.com/in/ahmad-msaad)  
**Email:** ahmad.saad@insa-cvl.fr  
**Discord:** thelambda

**Languages:** French (B2) • English (B2) • Arabic (Native)

---

*Open to collaboration on security research, tool development, and infrastructure hardening projects.*
