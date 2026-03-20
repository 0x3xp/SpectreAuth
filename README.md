# SpectreAuth // Identity Research Node
![Security Research](https://img.shields.io/badge/Focus-Offensive%20Security-red.svg)
![Python](https://img.shields.io/badge/Python-3.9+-blue.svg)

**SpectreAuth** is an advanced proof-of-concept framework developed to analyze vulnerabilities within the OAuth 2.0 authorization flow. It simulates a "Consent Phishing" attack, demonstrating how an attacker can achieve **Long-term Persistence** by exfiltrating Refresh Tokens.

---

## 📂 Repository Structure

```text
📂 SpectreAuth
├── 📁 screenshots/          # 9-Step Proof of Concept Gallery
│   ├── ss1_landing.png      # Initial Lure UI
│   ├── ss2_redirect.png     # Handshake Initiation
│   ├── ss3_auth_page.png    # Google Sign-in Overlay
│   ├── ss4_permissions.png  # Scopes & Offline Access Request
│   ├── ss5_callback.png     # Intercepting the Auth Code
│   ├── ss6_exfiltration.png # Successful Token Exchange
│   ├── ss7_persistence.png  # Storing Refresh Tokens
│   ├── ss8_api_call.png     # Accessing Private Profile Data
│   └── ss9_token_refresh.png# Persistence via Token Rotation
├── 📜 .gitignore            # Security: Prevents token leakage
├── 📜 SpectreAuth.py        # Main SpectreAuth Python Node
├── 📜 captured_identity.txt # Local log (Auto-generated)
├── 📜 README.md             # Documentation
└── 📜 requirements.txt      # Dependencies
