# Zero
<div align="center">
  
<img src="Zero.png" width="80" alt="Zero Logo">

# Zero
**The Minimalist Android Threat Scanner & Debloat Utility**

<!-- Functionality Badges (Modern Sharp Edges) -->
![Security Auditing](https://img.shields.io/badge/Security_Auditing-10B981?style=flat-square)
![Stalkerware Detection](https://img.shields.io/badge/Stalkerware_Detection-047857?style=flat-square)
![Safe Debloating](https://img.shields.io/badge/Safe_Debloating-064E3B?style=flat-square)

<!-- Tech Stack Badges (Classic Rounded Edges) -->
![Electron](https://img.shields.io/badge/Electron-47848F?logo=electron&logoColor=white&style=flat)
![React](https://img.shields.io/badge/React-20232A?logo=react&logoColor=61DAFB&style=flat)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?logo=tailwind-css&logoColor=white&style=flat)
![Platform](https://img.shields.io/badge/Platform-Windows-0078D6?logo=windows&logoColor=white&style=flat)
</div>

> **The Origin Story:** I needed a reliable application to keep my Android devices safe. While searching for one, I had a realization: instead of spending two hours hunting, downloading, and testing random pre-existing apps to find a good fit, I could just build exactly what I needed in the same amount of time. I treated this like a true product build—mapping requirements, designing the brand identity from scratch, and swapping out my initial Python prototype for a fluid Electron/React interface. Guided by Google's Antigravity, I built Zero from start to finish in exactly two hours. 

Zero is a zero-trust Windows application designed to put Android privacy back in your hands. Without requiring root access or USB cables, Zero audits your device permissions, unmasks hidden stalkerware, and safely eradicates carrier bloatware through a fluid, modern interface.

---

## ✨ Key Features

### 🛜 Frictionless Connection
- **Wireless Auto-Discovery:** Utilizes mDNS to automatically detect Android devices broadcasting on your local Wi-Fi. 
- **Zero Cables Required:** Connect directly via Android's native Wireless Debugging feature, or fall back to a standard USB wired connection if preferred.
- **Dynamic Port Pruning:** Automatically handles Android 11+ port randomization, flushing stale connections to prevent timeout errors.

### 🛡️ Vulnerability & Threat Auditing
- **Deep System Scan:** Analyzes thousands of background packages in seconds to expose critical risks.
- **Stalkerware Detection:** Hunts down hidden trackers, dangerous permission clusters, and background telemetry processes running without your knowledge.
- **Smart Scoring Engine:** Calculates a true "Security Score" that penalizes your device for actual threats (malware, outdated security patches) while intelligently ignoring cosmetic annoyances.

### 🧹 Safe Device Debloating
- **OEM & Carrier Cleanup:** Securely strips away heavy, un-installable bloatware pushed by phone manufacturers and carriers.
- **Full Path Visibility:** Detailed table rendering shows the exact absolute path (e.g., `/data/app/.../base.apk`) of every identified threat so you know exactly where a package resides before you remove it.

---

## 🚀 Getting Started (No Installation Required)

Zero is packaged as a ready-to-use, standalone Windows executable. 

1. Navigate to the **[Releases](../../releases)** section on the right side of this repository.
2. Download the latest `Zero.exe` file.
3. Double-click the file to run the application instantly.
4. Ensure "Wireless Debugging" or "USB Debugging" is enabled in your Android phone's Developer Options.

---

## 🛠️ Under the Hood
For developers curious about the stack, Zero is a prime example of migrating from legacy Python UIs to modern web technologies for desktop:
- **Electron & Node.js:** Handles the core application window and heavy ADB (Android Debug Bridge) shell commands.
- **Asynchronous IPC:** Utilizes custom `ipcMain` and `ipcRenderer` threading to offload heavy scanning to background processes, ensuring the UI never freezes.
- **React:** Powers the component-based, fluid user interface.
- **Tailwind CSS:** Replaces rigid, boxy legacy UI wrappers with a sleek, frameless, and highly responsive "zero-trust" dark aesthetic.

---

## 🤝 Support & Connect

This project proved to me that the barrier to creating custom, high-quality software has vanished. If Zero helped secure your device, or if you're interested in product management, vibe coding, and agile delivery, I'd love to hear from you! 

Drop a thanks, report an issue, or connect with me on LinkedIn: 
**[Harish Reddy](https://www.linkedin.com/in/hareesh-reddy/)**
