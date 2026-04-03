# Privacy Policy — Pocket Account

**Last Updated:** April 2, 2026
**Developer:** Rahul Patel, R&DC Software Development
**Contact:** contact@rndcsoftware.com | +91 97277 49009
**Website:** https://www.rndcsoftware.com

---

## Overview

Pocket Account ("the App") is an offline-first personal accounting application. We are committed to protecting your privacy. This policy explains what data the App handles and how.

## Data Collection

**We do not collect any personal data.** The App operates entirely offline on your device. No data is sent to any external server, cloud service, or third party.

## Data Stored on Your Device

The App stores the following information locally on your device only:

- Party details (name, phone, email, GSTIN, PAN, address)
- Transaction records (payments, receipts, transfers)
- Payment account details (cash, bank accounts)
- App preferences (language, mPIN hash, biometric settings)

All data is stored in a local SQLite database within the App's private storage area.

## Data Encryption

- Your mPIN is protected using PBKDF2-HMAC-SHA256 with 100,000 iterations and a unique random salt
- Backup files are encrypted using AES-256-CBC with password-based key derivation
- The App does not store your backup password anywhere

## Permissions Used

| Permission | Purpose |
|------------|---------|
| Contacts (READ_CONTACTS) | Optional — only used when you choose to import parties from your phone contacts |
| Biometric (USE_BIOMETRIC) | Optional — used for fingerprint/face unlock if you enable it |

No permissions are required for the App's core functionality.

## Third-Party Services

The App does not use any third-party services including:
- No analytics or tracking (no Google Analytics, Firebase Analytics, etc.)
- No advertising SDKs
- No crash reporting services
- No cloud storage or sync services

## Data Sharing

We do not share your data with any third party. When you choose to share a PDF report or backup file, you control where it goes via Android's standard share mechanism.

## Data Deletion

You can delete all your data at any time:
- **Settings > Clear Data** — Remove specific data (payments, receipts, parties, or everything)
- **Uninstalling the App** removes all locally stored data permanently

## Children's Privacy

The App does not knowingly collect or store information from children under 13. The App is a general-purpose financial tool with no age-restricted content.

## Changes to This Policy

We may update this Privacy Policy from time to time. Changes will be reflected in the "Last Updated" date above. Continued use of the App constitutes acceptance of the updated policy.

## Contact

If you have questions about this Privacy Policy, contact us at:

- **Email:** contact@rndcsoftware.com
- **Phone:** +91 97277 49009
- **Website:** https://www.rndcsoftware.com

---

*\u00a9 2026 R&DC Software Development. All rights reserved.*
