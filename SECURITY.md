# Security Policy

## Reporting a vulnerability

If you discover a security issue in PanelVerse, please report it **privately** rather than opening a public issue:

- Open a **private** [GitHub security advisory](https://github.com/Hazemserry90/panelverse-releases/security/advisories/new), or
- Email **saulgoodman547@gmail.com** with a description, reproduction steps, and the affected version.

Please allow reasonable time for a fix before any public disclosure.

## Supported versions

| Version | Supported |
|---|---|
| `v1.9.15` (Latest Android) | ✅ |
| Older Android releases | ❌ |

## Verifying downloads

Every official release includes a `SHA256SUMS.txt` file. Always download PanelVerse only from [GitHub Releases](https://github.com/Hazemserry90/panelverse-releases/releases) and verify the SHA-256 checksum before installing.

## Key security & privacy protections

- **Account & Cloud Isolation:** Strict per-user database isolation, email verification gates, Play Integrity attestation, and self-service account deletion.
- **Hardened In-App Reader:** Strict HTTPS-only host allow-listing, TLS error blocking, Content Security Policy enforcement, disabled file/content access, and zero JavaScript-to-native bridges.
- **Privacy by Default:** No analytics or ad SDKs, opt-in in-app messaging, 16+ age gate (date of birth is never stored or transmitted), and offline legal documents.
- **Release Integrity:** Android v3 signed releases with runtime signing-certificate integrity verification and disabled backup extraction (`allowBackup="false"`).
