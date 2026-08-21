# SMProxy App

**A fast and simple VPN client for VLESS, Reality, VMess, Trojan, Shadowsocks and WireGuard — on every device you own.**

### 🌐 Website — **https://smproxy.com**

SMProxy App is a client, the way a mail app is a client. It ships **no servers of its own** and has no built-in connection: you import a configuration from your own provider — by subscription link, QR code or manually — pick a server and connect in one tap. Connections are handled by the **Xray** core.

No subscriptions to buy, no in-app purchases, no accounts.

## Protocols

**VLESS** · **Reality** · **VMess** · **Trojan** · **Shadowsocks** · **WireGuard** — broad protocol support on a single Xray core.

## Features

- **All platforms** — iPhone, iPad, Mac, Apple TV, Android, Android TV, Windows and Linux, with a native interface on each
- **Easy import** — add configs by link, QR code or manually; subscriptions refresh automatically
- **Split routing** — send only what you choose through the tunnel, by domain, IP or CIDR (with geoip/geosite rules), and per-app on Android
- **No added overhead** — the app doesn't slow down the connection your server provides
- **Traffic statistics and per-server ping**, so you can pick the fastest node
- **Phone-to-TV pairing** — keyboard-free setup on the big screen
- **Light / dark themes**, English and Russian

## Privacy

- The app keeps **no logs** of your activity
- Your configurations **stay on your device**
- **No data shared** with third parties

## Download

| Platform | Download |
|----------|----------|
| iOS · iPadOS · macOS · Apple TV | [**App Store**](https://apps.apple.com/ru/app/smproxy/id6783880283) |
| Android · Android TV | [**Google Play**](https://play.google.com/store/apps/details?id=com.smartvpnru.app) |
| Android APK (sideload, incl. Android TV) | [SMProxy.apk](https://github.com/SMProxy/smproxy-binary/releases/latest/download/SMProxy.apk) |
| Windows 10 & 11 · x64 | [SMProxy-Setup.exe](https://github.com/SMProxy/smproxy-binary/releases/latest/download/SMProxy-Setup.exe) |
| Linux · Debian/Ubuntu | [.deb (x86_64)](https://github.com/SMProxy/smproxy-binary/releases/latest/download/SMProxy-amd64.deb) · [.deb (ARM64)](https://github.com/SMProxy/smproxy-binary/releases/latest/download/SMProxy-arm64.deb) |
| Linux · Fedora/RHEL | [.rpm (x86_64)](https://github.com/SMProxy/smproxy-binary/releases/latest/download/SMProxy-x86_64.rpm) · [.rpm (ARM64)](https://github.com/SMProxy/smproxy-binary/releases/latest/download/SMProxy-aarch64.rpm) |

Install on Linux from the terminal:

```bash
sudo dpkg -i ./SMProxy-amd64.deb    # Debian / Ubuntu, x86_64
sudo rpm -U ./SMProxy-x86_64.rpm    # Fedora / RHEL, x86_64
```

Every build lives on the [**Releases**](https://github.com/SMProxy/smproxy-binary/releases/latest) page, with checksums in `SHA256SUMS.txt` and current version numbers in `versions.json`.

## Getting started

1. Get a configuration from your provider (subscription link, QR code or config file).
2. Add it to the app — paste the link, scan the QR code or enter it manually.
3. Choose a server and connect.

Setup guides and FAQ: [smproxy.com](https://smproxy.com)

## Support the project

SMProxy App is free, has no ads and no in-app purchases. If it is useful to you, a donation helps keep development going. **USDT / USDC are preferred.**

| Network | Address |
|---------|---------|
| **USDT/USDC · TRC-20** (Tron) | `TAayuwHP1cz5VxsNmVTE2dtkEiPZnTjbeH` |
| **USDT/USDC · BEP-20** (BNB Smart Chain) | `0xa0C15221e3BA172CEC1D97a63a0bFCD6f81f19A2` |
| **USDT/USDC · ERC-20** (Ethereum) | `0xC408F74434A382BaB2b80f236997CfbA017e230A` |
| **USDT/USDC · Solana** | `D9kB6YrsPcrW1FrgqyuttaZRw3RHNeS5Dj28CqnsmRWh` |
| **BTC** (SegWit) | `bc1qjvlc30t8unn9k9dan284c0y0602a05ks3snwa8` |
| **LTC** (SegWit) | `ltc1qxg8qngw253885m0tm2w8luszmsag5yesh3k804` |

⚠️ Always send on the matching network — funds sent to the wrong network cannot be recovered.

## Support

- Website — [smproxy.com](https://smproxy.com)
- Issues with a build — [open an issue](https://github.com/SMProxy/smproxy-binary/issues)

---

© RB Media FZC LLC · [smproxy.com](https://smproxy.com)
