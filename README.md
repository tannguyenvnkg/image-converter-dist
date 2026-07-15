# Image Converter — Downloads

Batch image converter for macOS and Windows. Convert · Compress.

**[⬇ Download the latest version](https://github.com/tannguyenvnkg/image-converter-dist/releases/latest)**

This repository hosts the installers only. Each release includes builds for both platforms,
and the app updates itself automatically once installed.

| Platform | File | Notes |
|---|---|---|
| macOS (Apple Silicon + Intel) | `.dmg` | Universal — one file, works on both |
| Windows | `.exe` (installer) or `.msi` | 64-bit |

---

## Installing on macOS

The app is not yet signed with an Apple certificate, so macOS asks you to confirm it once —
the first time you open it, and never again.

1. Open the `.dmg` and drag **Image Converter** into **Applications**.
2. Open it from Applications. macOS shows a warning and refuses to launch — this is expected.
3. Go to  → **System Settings** → **Privacy & Security**.
4. Scroll to the bottom. Next to *"Image Converter was blocked…"*, click **Open Anyway**.
5. Confirm **Open Anyway**, then enter your password or use Touch ID.

The app opens normally from then on, and updates install without any of this.

## Installing on Windows

1. Run the `.exe` installer.
2. Windows shows a blue **"Windows protected your PC"** box.
3. Click **More info**, then **Run anyway**.

No admin password needed. Updates install without the prompt.

---

## Why the warnings?

Both operating systems warn about software from developers who haven't paid for a code-signing
certificate (Apple charges $99/year). The warnings say nothing about whether the app is safe —
only that the developer hasn't paid for the certificate. The prompts appear **once, on first
install**. Automatic updates are cryptographically signed and verified by the app itself, and
never show these prompts.

## Support

Found a bug or something not working right?
[Open an issue](https://github.com/tannguyenvnkg/image-converter-dist/issues).

---

Crafted by Tan Nguyen.
