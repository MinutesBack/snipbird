# Snipbird privacy notice

Effective date: August 31, 2026

Snipbird is designed to process clipboard content on your Mac.

## Data stored locally

Snipbird may store copied text, links, images, file references, source-app
names, pins, favorites, templates, and preferences. Clipboard history and
captured images are encrypted with AES-256-GCM. The encryption key is stored in
the macOS Keychain on that Mac and is not configured to sync through iCloud.

Templates are stored as readable JSON in the Snipbird application-support
folder so that users can import, export, and share templates intentionally.

## Data Snipbird does not collect

Snipbird does not require an account and does not include advertising,
analytics, tracking pixels, or a MinutesBack clipboard-content service.
Clipboard content is not uploaded to MinutesBack.

Items that compatible password managers mark as confidential are skipped.
Users can also block selected applications from clipboard capture.

## Network access

The Mac App Store edition makes no network requests and receives updates through
the Mac App Store. The directly distributed edition uses Sparkle to check the
public MinutesBack release feed for signed updates. That update request may
expose ordinary connection information, such as an IP address and user agent,
to GitHub as the release host. Update archives must pass Snipbird's embedded
EdDSA signature check before installation.

## Support reports

If you report a problem through GitHub, you choose what information to submit.
Do not include clipboard contents, encryption keys, passwords, or other secrets
in a public issue.

## Removing your data

Quit Snipbird and remove `~/Library/Application Support/Snipbird` to delete its
stored history, captured images, templates, and local settings. The Snipbird
secure-storage key can be removed separately in Keychain Access.

Questions may be submitted through the official Snipbird support page:
https://minutesback.github.io/snipbird/support.html
