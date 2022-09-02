---
layout: text
title: "modulo - about"
---


## OTP Wallet

### One-Time-Password Authentication

OTP Wallet eliminates the use of seed phrases and private keys by creating a new set of on-chain authentication mechanisms based on one-time password (OTP), a method that most users are already accustomed to in web2. The 6-digit OTP can be provided automatically by macOS and iOS (through FaceID / Fingerprints), or manually by apps such as Google Authenticator. The code controls the access to a wallet built on Modulo. A new code is generated every 30 seconds, and is required for every transaction. The security design also ensures the wallets are secure against replay, side-channel, and front-running attacks.

Because of this, the setup process of a wallet becomes frictionless, and transactions can be made much faster because the user no longer needs to type a password for authorization.

### Air-gapped Security

Most wallets require the private key to be loaded in-memory for every transaction. This creates enormous risks because the private key may be intercepted by hackers, and may control all assets in the wallet.

OTP Wallet removes this risk using air-gapped security. A setup secret is only needed during the creation of the wallet, and remains sealed off permanently. A transaction only requires an OTP generated at the time of the transaction. The OTPs are always generated offline and used in an air-gapped manner, regardless whether the user is manually typing them, or whether the operating system is filling it in automatically. A hacker who intercepts an OTP can only perform one transaction, and the damage can be controlled and minimized by another built-in feature of Modulo - the spending limits, which the user may set and adjust based on their needs.

This feature, along with several other layers of security, make wallets built on OTP Wallet resilient to attacks in unsafe environments.

### Keyless Recovery

OTP Wallet provides many ways for a user to recover assets which they no longer have access to. The wallet can be synchronized across multiple devices, and optionally and securely backed up in a cloud. If the user lost all devices that have the wallet, or somehow erased the wallets on these devices, the user may restore the wallet using only the authenticator codes.

If the user lost the authenticator (hence the access to the wallet), the user may recover all assets to a recovery wallet they configured ahead of time, such as their other wallets or their friends’ wallets. If the user forgets to configure any recovery wallet, the assets can still be recovered to a treasury account.

## Features

- ENS Domain Registration and Resolutions
- Full ERC-20 Token Support
- NFT Showcase and Transfer
- ERC-20 Atomic Swaps
- Red Packets (Native Assets and NFT Gifts)
- Built-in On-Chain Transaction Viewer
- Full Test Coverage
- Full dApp Integration APIs (Connect, Call, Transfer, Sign)
- Open Source and Continuous Audit

## SMS Wallet

More information coming soon. See [solutions](/products) and [resources](/resources) for more details.
