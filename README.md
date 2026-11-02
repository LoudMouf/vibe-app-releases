# Vibe App Downloads

Public Android APK distribution for LoudMouf's personal apps. Source repositories remain private. Packaged web app HTML/JavaScript is necessarily extractable from APKs.

## Download

Use [Releases](https://github.com/LoudMouf/vibe-app-releases/releases) for signed APKs and SHA-256 checksums. Android 10 or newer is required. Android asks you to approve installation and may require allowing installs from your browser or Vibe App Store.

- **LL97 Model**: building-energy scenarios and LL97 screening. Not a compliance determination or filing.
- **NJ Energy Explorer**: building audit workflows and preliminary eligibility screening. Utility approval is separate.
- **HTL Calculator**: browser calculator, customer intake and 3D system. Does not include the Python/Streamlit lab runner. Not engineering design or safety approval.
- **Mushroom Fieldbook**: local grow/batch/harvest records. JSON backups exclude original photo bytes.
- **WeFit**: local meals, exercise and progress tracking. Optional AI integrations are not configured.

These apps store records locally. Export backups before changing devices. Updates retain the same package identity/signing certificate; do not uninstall to update, because uninstalling deletes local app data.

## Verification

Each catalog entry pins the APK SHA-256, Android package name, version and signing-certificate fingerprint. The Android store verifies these before requesting installation. Installation success is read back from Android rather than assumed after a download.

Signing certificate SHA-256:
`a8326086198e10ceb033356ae6903b85c54f1feb97df0187ae59cf4ee5865b12`

The signing private key is not published. This is a personal distribution channel, not Google Play or Apple's App Store. Only catalog-listed releases are supported.
