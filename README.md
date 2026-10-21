# Vision Tactile downloads

Static software delivery pages for [Vision Tactile](https://github.com/yanglei18/VisionTactile-Dataset).

This repository hosts only browser UI, public integrity manifests, and AES-256-GCM encrypted installation packages. Equipment-specific plaintext archives, device configuration, access links, and decryption keys must never be committed here.

The equipment owner receives a complete link separately. Its fragment is processed locally by the browser; no account, password entry, GitHub token, or server-side decryption is needed. Anyone holding that complete link can obtain the corresponding package. This is equipment delivery, not a universal Tracker identity package.

Version directories are immutable. Build tools and operating instructions live in `tools/release/build_download_site.py` and `docs/download-hosting.md` in the source repository. Published links are version-specific; updates receive a new directory and a new private link. Public copies of ciphertext may remain accessible even after deletion, so do not promise revocation of an already shared package.

No analytics, advertisements, payment processing, or third-party browser scripts are used.
