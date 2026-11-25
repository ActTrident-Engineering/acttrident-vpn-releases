# ActTrident VPN for Windows: releases

Installers and signed update files for **ActTrident VPN** by ACTTRIDENT LTD. No source code lives here.

- **Download (newest stable):** [ActTrident-VPN-Setup.exe](https://github.com/ActTrident-Engineering/acttrident-vpn-releases/releases/latest/download/ActTrident-VPN-Setup.exe)
- **Beta versions** are marked *Pre-release* on the [releases page](https://github.com/ActTrident-Engineering/acttrident-vpn-releases/releases).
- Windows 10/11, 64-bit. The installer also installs WireGuard for Windows if it is missing.
- Free to use during the beta: install, open, connect. No sign-up.

## Updates

Installed copies update themselves. In the app, **Settings › About** shows the version and lets you choose the
**Stable** or **Beta** channel. The release tagged `channels` holds the files the app checks (`stable.json`,
`beta.json`).

Every update file is signed with ACTTRIDENT's update key (Ed25519). The app only installs an update when:
- the signature verifies;
- the file is for this app and channel;
- the version is newer;
- the installer matches the signed size and SHA-512.

Anything else is ignored. The public key is pinned in the app; it is also here, so you can check a file yourself:

```
/67ZnyD9p835Lo72LpcNtnZ5CbHmZJjWZqQbZv6r99E=
```
