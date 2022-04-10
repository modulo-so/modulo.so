# Modulo

Advanced infrastructure for building secure, frictionless, programmable crypto wallets

## Overview

Modulo (modulo.so) provides the open source, modular infrastructure for developers to build customizable smart-contract crypto wallet and payment apps that are secure, frictionless, and programmable, leveraging Modulo’s technical innovations in one-time-password authentication, air-gapped security, and keyless recovery. Modulo supports EVM compatible blockchains, and has operated in production under Layer 1 blockchains such as Harmony since Q4 2021. 

Modulo is founded by the developers who created 1wallet (github.com/polymorpher/one-wallet, 1wallet core and web edition). Modulo operates independently, and focuses on business-facing solutions and services, cross-chain infrastructure expansion, real-life use-case exploration, and the research and development of scaling and privacy technologies for the infrastructure, such as zero-knowledge proof.

## Highlights

### One-Time-Password Authentication

Modulo eliminates the use of seed phrases and private keys by creating a new set of on-chain authentication mechanisms based on one-time password (OTP), a method that most users are already accustomed to in web2. The 6-digit OTP can be provided automatically by macOS and iOS (through FaceID / Fingerprints), or manually by apps such as Google Authenticator. The code controls the access to a wallet built on Modulo. A new code is generated every 30 seconds, and is required for every transaction. The security design also ensured the wallets are secure against replays, side channel, and front running attacks. 

Because of this, the setup process of a wallet becomes frictionless, and transactions can be made much faster because the user no longer needs to type a password for authorization.  

### Air-gapped Security

Most wallets require the private key to be loaded in-memory for every transaction. This creates enormous risks because the private key may be intercepted by hackers, and may control all assets in the wallet. 

Modulo removes this risk using air-gapped security. A setup secret is only needed during the creation of the wallet, and remains sealed off permanently. A transaction only requires an OTP generated at the time of the transaction. The OTPs are always generated offline and used in an air-gapped manner, regardless whether the user is manually typing them, or whether the operating system is filling it in automatically. A hacker who intercepts an OTP can only perform one transaction, and the damage can be controlled and minimized by another built-in feature of Modulo - the spending limits, which the user may set and adjust based on their needs.

This feature, along with several other layers of security, make wallets built on Modulo resilient to attacks in unsafe environments.

### Keyless Recovery

Modulo provides many ways for a user to recover assets which they no longer have access to. The wallet can be synchronized across multiple devices, and optionally and securely backed up in a cloud. If the user lost all devices that have the wallet, or somehow erased the wallets on these devices, the user may restore the wallet using only the authenticator codes. 

If the user lost the authenticator (hence the access to the wallet), the user may recover all assets to a recovery wallet they configured ahead of time, such as their other wallets or their friends’ wallets. If the user forgets to configure any recovery wallet, the assets can still be recovered to a treasury account.

### Features

- ENS Domain Registration and Resolutions
- Full ERC-20 Token Support
- NFT Showcase and Transfer
- ERC-20 Atomic Swaps
- Gifts and Red Packets (including Native Assets and NFTs)
- Built-in On-Chain Transaction Viewer
- Full Test Coverage
- Full dApp Integration APIs (Connect, Call, Transfer, Sign)
- Open Source and Continuous Audits

### Resources

Source Code: [GitHub](https://github.com/polymorpher/one-wallet) (1wallet core and web edition)

Presentations: [Slides](https://docs.google.com/presentation/d/1lmpWZyT8Mk6yey6FJWEdpeMo6vWdY7Vy2NUMArQHTGw), [Notes](https://docs.google.com/document/d/1MyJGH87ujlBVzwLMBNzJmdw4JH-UzhRUQTNw3t6AaWM/edit#)

Documentations: [Wiki](https://github.com/polymorpher/one-wallet/wiki), [dApp Integration Guide](https://github.com/polymorpher/one-wallet/wiki/App-Integration)

Bugs and Discussions:  [GitHub Issues](https://github.com/polymorpher/one-wallet/issues)

### Pricing

Please contact us for a custom quote.

### Contact

[hello@modulo.so](mailto:hello@modulo.so)

Twitter: [@modulo_so](https://twitter.com/modulo_so)

Telegram: [@modulo_so](https://t.me/modulo_so)

