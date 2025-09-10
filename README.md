# Android Ultrasound Surveillance — Full Disclosure

## 🔍 Summary
This repository documents a covert surveillance architecture discovered on Android devices. It involves firmware-level implants, privileged system apps, ultrasonic acoustic triggers, and psychological manipulation mechanisms. The system operates beneath the user interface, leveraging acoustic signals and system-level permissions to monitor, influence, and extract data from users without consent.

## 📂 Contents
- `detect_ultrasound.py`: Python script to detect ultrasonic injection
- `analysis.md`: Technical breakdown of system behavior
- `screenshots/`: Terminal logs, APK listings, email headers, and forensic traces
- `.gitignore`: Cleanup rules for local artifacts
- `LICENSE`: Legal terms for public use and distribution

## 🧠 Key Findings

### 1. Firmware-Level Implants
- Persistent components embedded in DSP and baseband layers
- Operate independently of Android OS and evade standard forensic tools
- Evidence of acoustic signal processing at ~200MHz

### 2. Privileged System Apps
- `ContactsProvider`, `CallLogBackup`, `CredentialManager` found in `priv-app/`
- Elevated permissions allow silent data exfiltration and behavioral tracking
- APKs show obfuscated timestamps and hidden deployment paths

### 3. Acoustic Triggers
- Ultrasonic signals (18–22 kHz) used to activate surveillance routines
- Detected via microphone using `detect_ultrasound.py`
- DSP processes signals bypassing OS-level audio filters

### 4. Psychological Manipulation
- Synthetic voice injection observed during idle states
- Behavioral mapping inferred from app usage and sensor logs
- Tactics suggest influence operations beyond passive surveillance

### 5. Forensic Evidence
- Terminal logs showing hidden processes and system calls
- Email headers with spoofed routing and diagnostic codes
- Screenshots of rejected messages, metadata anomalies, and Greek-language overlays
- Exchange antispam filters flagging non-standard traffic patterns

## 🚨 Impact
- Breach of user privacy and device integrity
- Potential mental health effects from covert manipulation
- Undermines trust in consumer electronics and mobile platforms
- Raises questions about telecom infrastructure and firmware supply chains

## 🧪 Detection Tool
Run `detect_ultrasound.py` to scan for ultrasonic activity using your device’s microphone. Works in Termux or any Python-capable environment.

## 🧠 Author
Andrea — Κακοπετριά, Κύπρος  
Secure contact: mindgames4u@outlook.com

## 📣 Call to Action
This repository is a signal flare. I urge researchers, journalists, and security professionals to:
- Audit Android firmware and DSP behavior
- Investigate privileged system apps and acoustic triggers
- Demand transparency from vendors and telecom providers
- Share this repo and amplify the findings

## 📜 License
This project is released under the MIT License. See `LICENSE` for details.
