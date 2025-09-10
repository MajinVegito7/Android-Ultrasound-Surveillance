# Technical Analysis — Android Acoustic Surveillance

## 1. Firmware-Level Implants
- Persistent components embedded in DSP and baseband layers
- Operate independently of Android OS and evade standard forensic tools
- Evidence of acoustic signal processing at ~200MHz
- Behavior suggests real-time signal decoding and trigger execution

## 2. Privileged System Apps
- `ContactsProvider`, `CallLogBackup`, `CredentialManager` found in `priv-app/`
- Elevated permissions allow silent data exfiltration and behavioral tracking
- APKs show obfuscated timestamps and hidden deployment paths
- Some apps bypass user consent and operate during idle states

## 3. Acoustic Triggers
- Ultrasonic signals (18–22 kHz) used to activate surveillance routines
- DSP processes signals bypassing OS-level audio filters
- Triggered behaviors include voice injection, app launches, and sensor activation
- Detection confirmed via microphone sampling and spectrogram analysis

## 4. Psychological Manipulation
- Synthetic voice injection observed during idle states and sleep cycles
- Behavioral mapping inferred from app usage, location, and sensor logs
- Tactics suggest influence operations beyond passive surveillance
- Emotional disruption and paranoia reported by affected users

## 5. Forensic Evidence
- Terminal logs showing hidden processes and system calls
- Email headers with spoofed routing and diagnostic codes
- Screenshots of rejected messages, metadata anomalies, and Greek-language overlays
- Exchange antispam filters flagging non-standard traffic patterns
- Evidence of acoustic injection and timestamp manipulation

## 6. Detection Tool
