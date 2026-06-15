# Not-Access

# NOT ACCESS - Advanced Secure Vault

NOT ACCESS is a decentralized, offline Progressive Web Application (PWA) built to keep your sensitive credentials and secure notes protected. Operating with a zero-server architecture, all data stays strictly within your browser's local sandbox (IndexedDB), ensuring complete offline privacy.

## Key Features

*   **Zero-Server Architecture:** No APIs, cloud backends, or third-party telemetry. Your vault remains local to your device.
*   **Cryptographic Security:** Utilizes the native Web Crypto API for industry-standard **AES-256-GCM** encryption.
*   **PBKDF2 Key Derivation:** Master passwords and recovery keys are stretched over 250,000 iterations of SHA-256 for enhanced brute-force resistance.
*   **Progressive Web App (PWA):** Installs directly onto your device for standalone offline usage (such as on Airplane Mode).
*   **Vault Auditing & Security Dashboard:** Automatically tracks and logs local events (such as password changes or recovery triggers) into a locally encrypted audit log. Includes strength assessments and reuse checks.
*   **HMAC-SHA256 Signed Backups:** Enables exporting and importing securely encrypted backups with built-in integrity verification.

## Technology Stack

*   **Frontend:** Pure HTML5, CSS3 (Mobile-First responsive design), and vanilla JavaScript. No external dependencies or libraries.
*   **Database:** IndexedDB (local browser sandbox) for persistent offline storage.
*   **Cryptography:** Native Web Crypto API.

## Recommended Environment

This application is designed, tested, and optimized primarily for **Brave Browser** to maintain the highest standard of security, feature integrity, and platform stability.

##🤝 Contributing

**Contributions, feature requests, and bug reports are welcome.**

**If you'd like to improve CLIPO, feel free to fork the repository and submit a pull request.**

##📄 License

**This project is licensed under the MIT License.**

##❤️ Support

**If you find this project useful, consider giving it a ⭐ on GitHub and sharing it with others.**

##🌐 LIVE ON INTERNET 

https://not-access.netlify.app


# NOT ACCESS - Advanced Secure Vault (v3.0)