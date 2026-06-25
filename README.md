# BDK-BTCMobick

A fork of [Bitcoin Development Kit](https://bitcoindevkit.org/) extended to support the **BTCMobick (BMB)** and **LaptopMining (LTM)** networks.

## Overview

This project provides a native wallet SDK core for BTCMobick-based networks.  
Currently available: **Android (Kotlin)**  
Planned: iOS (Swift)

## Version

**0.1.0**

## Based on

| Component | Version |
|-----------|---------|
| bdk-ffi | 3.1.0-alpha.0 |
| bdk_wallet | 3.0.0 |
| rust-bitcoin | 0.32.8 |

## What's included

- `rust-bitcoin/` — forked rust-bitcoin with `Network::Mobick` and `Network::LaptopMining` variants
- `bdk-ffi/` — UniFFI bindings with Android AAR output
- `bdk/` — BDK wallet core with patch applied
- `bip157/` — patched compact block filters

## Networks

| Network | Chain |
|---------|-------|
| BTCMobick | BMB |
| LaptopMining | LTM |

## Support This Project

If this SDK saved you time, consider buying me a coffee ☕

| Network | Address |
|---------|---------|
| BTCMobick (BMB) | `bc1q3aa08pnpj7qqzpw4pye2a7jyryxdzqc2lk32pl` |
| Wrapped BMB (WBMB) | `0xea66EA4787d0D8Ec7264651808e82F871aB30279` |
