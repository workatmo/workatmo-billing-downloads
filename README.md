# Workatmo Billing downloads

Installers for Workatmo Billing (GST billing for Indian small businesses), published under **Releases**:

- **Android**: `WorkatmoBilling-<version>-arm64.apk`
- **macOS**: `WorkatmoBilling-<version>.dmg`
- **Windows**: `WorkatmoBilling-Setup-<version>.exe`

Website and download page: https://billing.workatmo.in/download/

The apps update themselves: they check `https://billing-api.workatmo.in/api/app/version` and download
from here (APK verified with SHA-256; Mac updates via Sparkle, EdDSA-signed; Windows installer verified with SHA-256). This repository holds binaries only;
the source code is private.
