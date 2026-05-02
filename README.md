# Hybrid Communications System

## Overview
This project demonstrates a fully integrated hybrid communications architecture combining:

- RF (DMR / Analog / Digital Voice)
- VoIP (SIP-based telephony)
- SDR (ADS-B, AIS, spectrum analysis)
- Cloud infrastructure (redundant VPS)
- Secure overlay networking (VPN mesh)

The system is designed for **resilience, interoperability, and real-world validation**.

---

## Key Capabilities
- RF ↔ VoIP bridging
- End-to-end voice routing (radio → cloud → PSTN)
- SDR data ingestion and monitoring
- WAN failover (Primary ↔ Secondary)
- Secure remote access via VPN overlay

---

## Architecture Highlights
- Segmented network design
- Multi-path redundancy
- Cloud failover (Region A / Region B)
- Device-level validation across all subsystems

---

## Validation Summary
- Voice communications: PASS
- RF bridging: PASS
- SDR decoding: PASS
- WAN failover: ~25 sec validated
- System status: **Stable & Reliable**

---

## Public Version Notice
This repository contains a **sanitized public version** of the system:

- No IP addresses
- No call signs
- No sensitive infrastructure details
- Providers and regions generalized

---

## Project Artifacts
- Architecture diagram
- Bill of materials (sanitized)
- Validation summary
- Executive overview

---

## Author
**Rich Daniels**  
Systems / Network Engineering

---

## License
This project is shared for portfolio and educational purposes.
