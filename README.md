# Workatmo Billing downloads

Installers for Workatmo Billing (GST billing for Indian small businesses), published under **Releases**:

- **Android**: `WorkatmoBilling-<version>-arm64.apk`
- **macOS**: `WorkatmoBilling-<version>.dmg`

The apps update themselves: they check `https://workatmo-billing-api.onrender.com/api/app/version` and download
from here (APK verified with SHA-256; Mac updates via Sparkle, EdDSA-signed). This repository holds binaries only;
the source code is private.
