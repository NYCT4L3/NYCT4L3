# Hi, I'm NYCT4L3 👋

Cybersecurity student focused on **offensive security and penetration testing**. I learn by building, and I run all my experiments in a confined, authorized lab environment.

## 🔧 Projects

### 🕵️ [Cross-Layer Fingerprint Impersonation Detector](https://github.com/NYCT4L3/cross-layer-fingerprint-impersonation-detector) *(in development)*
Detects clients that fake their identity on the network. Instead of trusting a single signal, it extracts **JA4 (TLS)**, **JA4T (TCP)** and **JA4H (HTTP)** fingerprints from the *same flow* and checks whether they agree with each other. For example, a connection that looks like Chrome on Windows at the TLS layer but behaves like a Linux Python client at the TCP and HTTP layers gets flagged.

- Flow-based analysis (an IP address is never treated as a device identity, so NAT and shared IPs are handled correctly)
- Certificate and packet-behavior checks
- Weighted consistency and risk scoring, with verdicts: `CONSISTENT` / `SUSPICIOUS` / `FLAGGED`
- Audit logging, ground-truth labeling, and evaluation (accuracy, precision, recall, F1, confusion matrix)
- Plain-language explanations of why a flow was flagged

### 🔐 [Secure Proof-of-Life + Digital Legacy System](https://github.com/NYCT4L3/secure-proof-of-life) *(in development)*
A security-focused application that confirms a user is still active through regular check-ins. If they stop responding, it moves through a grace period and trusted-contact warnings, then triggers a **Dead Man's Switch** that releases encrypted information to chosen recipients.

- Encrypted digital vault with controlled, conditional release
- Lost Device Mode and Emergency Mode
- MFA, device and session management, replay and spoofing protection
- Audit logs and compromise detection
- Includes a security-testing section that demonstrates attacks (IDOR, XSS, CSRF, replay and more) and their mitigations

### 📝 Cyber Scribe
A Python tool that turns spoken lab notes into structured Markdown journal entries (voice recording, then transcription, then organized notes), so my lab work and reasoning are always documented.

### 🚩 CTF Challenge Development
Developing challenges for my university's upcoming CTF.

## 📚 What I'm studying
Networking · Linux · Python · Web & application security · Network enumeration · Penetration testing · Windows & Active Directory · Cryptography · Cloud & containers

## 🎯 Goals
Build a career in offensive security, develop tools that support penetration testing, and keep growing through CTFs, both playing them and building them.

## 🧪 How I work
All experiments run in an isolated, authorized lab. I follow responsible, ethical practices.

## 📫 Connect
- LinkedIn: *(coming soon)*
