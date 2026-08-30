# Install Snipbird 1.2 Legacy

The current public download is Snipbird 1.2.0, the legacy MIT edition. It is
cryptographically signed for Snipbird updates but was released before Apple
Developer ID notarization was available for the project.

1. [Download Snipbird.dmg](https://github.com/MinutesBack/snipbird/releases/latest/download/Snipbird.dmg).
2. Open the disk image and drag Snipbird into Applications.
3. Open Snipbird from Applications.
4. If macOS blocks it, click Done, then open System Settings, select Privacy &
   Security, scroll down, select Open Anyway beside Snipbird, and confirm.

Snipbird appears as a bird in the menu bar. The first-run guide explains
privacy, shortcuts, launch at login, and update preferences.

Snipbird 1.3 will replace this download after Developer ID signing and Apple
notarization are complete.

## Uninstall

Quit Snipbird and move it from Applications to the Trash. Delete
`~/Library/Application Support/Snipbird` to remove local history and templates.
Use Keychain Access to remove the Snipbird secure-storage key.
