# privacy-policy
 1. Zero-Knowledge Architecture
VaultX relies on a strict "Zero-Knowledge" security model. This means that all your data (including photos, passwords, bank cards, and notes) is fully encrypted locally on your device before syncing to the cloud.
2. Encryption Standards
We utilize military-grade AES-256-GCM encryption. The master encryption key is derived directly from your password locally on your device. We never transmit your password or the raw key to our servers or to any third party.
3. Backup and Synchronization
If cloud sync is enabled (via Google Auth, Firebase, or Google Drive), VaultX will only upload the encrypted ciphertexts. Neither the developer, the cloud service provider, nor any third party has the technical capability to decrypt or read your files. Without the exact password, the files in the cloud are merely unreadable random data.
4. App Permissions and Data Collection
VaultX requests only specific permissions necessary to function correctly, and no data collected by these permissions is shared with third parties:
Storage and Media: To import photos and files, save them encrypted locally, and export backups.
Camera: Used exclusively for local operations such as smart scanning (OCR) for cards, or capturing photos that are immediately encrypted and not saved to the phone's gallery.
Biometrics: To allow fast unlocking. Authentication is performed entirely within your device's secure hardware (Secure Enclave/Chip).
Cloud Access (Optional): To securely sync encrypted sections to your linked cloud account.
5. Advanced Privacy Features
The application includes additional protective features such as: Auto-lock on inactivity, screen capture prevention (supported by the OS), and Stealth Mode (Calculator), which completely hides the app to protect your privacy in public places.
6. AutoFill Service
When the AutoFill service is enabled, the app acts as a secure intermediary to fill passwords in targeted apps and websites. No diagnostic data or passwords are sent to our servers during this process; field detection and matching are handled entirely locally within the operating system.
7. Data Deletion
Since you are the sole owner of the decryption keys, you can completely erase your data at any time via the "Danger Zone" in the app settings. This will permanently destroy both the local database and the encrypted database stored in the cloud.
