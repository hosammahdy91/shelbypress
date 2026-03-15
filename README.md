<div align="center">

```
███████╗██╗  ██╗███████╗██╗      ██████╗ ██╗   ██╗██████╗ ██████╗ ███████╗███████╗███████╗
██╔════╝██║  ██║██╔════╝██║     ██╔══██╗╚██╗ ██╔╝██╔══██╗██╔══██╗██╔════╝██╔════╝██╔════╝
███████╗███████║█████╗  ██║     ██████╔╝ ╚████╔╝ ██████╔╝██████╔╝█████╗  ███████╗███████╗
╚════██║██╔══██║██╔══╝  ██║     ██╔══██╗  ╚██╔╝  ██╔═══╝ ██╔══██╗██╔══╝  ╚════██║╚════██║
███████║██║  ██║███████╗███████╗██████╔╝   ██║   ██║     ██║  ██║███████╗███████║███████║
╚══════╝╚═╝  ╚═╝╚══════╝╚══════╝╚═════╝    ╚═╝   ╚═╝     ╚═╝  ╚═╝╚══════╝╚══════╝╚══════╝
```

### ⛓ Censorship-Resistant Publishing on Shelby Protocol × Aptos

<br/>

[![Shelby Protocol](https://img.shields.io/badge/Built_on-Shelby_Protocol-0066FF?style=for-the-badge&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjQiIGhlaWdodD0iMjQiIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PHBhdGggZD0iTTEyIDJMMiA3bDEwIDUgMTAtNS0xMC01ek0yIDE3bDEwIDUgMTAtNS0xMC01LTEwIDV6TTIgMTJsMTAgNSAxMC01LTEwLTUtMTAgNXoiLz48L3N2Zz4=)](https://shelby.xyz)
[![Aptos](https://img.shields.io/badge/Aptos-Blockchain-00C2FF?style=for-the-badge)](https://aptoslabs.com)
[![AIP-62](https://img.shields.io/badge/Wallet-AIP--62-22C55E?style=for-the-badge)](https://github.com/aptos-foundation/AIPs)
[![MIT License](https://img.shields.io/badge/License-MIT-F59E0B?style=for-the-badge)](LICENSE)
[![Early Access](https://img.shields.io/badge/Early_Access-Requested-EF4444?style=for-the-badge)](https://developers.shelby.xyz)

<br/>

> **"Your words, once committed, are as permanent as mathematics."**

<br/>

[🚀 Live Demo](https://shelbypress.vercel.app) &nbsp;·&nbsp; [📋 Roadmap](#-roadmap) &nbsp;·&nbsp; [🔌 SDK Preview](#-shelby-sdk-integration) &nbsp;·&nbsp; [🤝 Early Access](#-early-access)

</div>

---

## 🧩 What is ShelbyPress?

**ShelbyPress** is the first publishing platform built entirely on **Shelby Protocol's hot decentralized storage** and **Aptos blockchain**.

Unlike Medium, Substack, or any traditional platform — no company, government, or server operator can delete, alter, or censor content published on ShelbyPress.

Every article is:
- 📦 **Stored** as an encrypted Blob on Shelbynet
- 🔐 **Signed** by the author's Aptos wallet
- ⛓ **Registered** on Aptos blockchain as immutable proof
- ♾️ **Permanent** — distributed across nodes worldwide

---

## 🎯 The Problem We Solve

```
Today's internet:

  Writer ──► Platform ──► Reader
               │
               └──► Can DELETE, EDIT, SHADOW-BAN, CENSOR at any time

ShelbyPress:

  Writer ──► Shelbynet + Aptos ──► Reader
                    │
                    └──► PERMANENT. No one has the delete button.
```

---

## ✨ Core Features

| Feature | Description |
|---------|-------------|
| 🔗 **Wallet Login** | Connect any Aptos wallet via AIP-62 standard — Petra, Nightly, and more |
| ✍️ **On-chain Publishing** | Articles signed by your wallet and stored as Shelby Blobs |
| 📰 **Permanent Feed** | All published articles are immutable and always accessible |
| 🔍 **Full-text Search** | Instant search across titles, content, and tags |
| 🏷️ **Tag System** | Dynamic topic cloud for content discovery |
| 📱 **Responsive** | Optimized for desktop and mobile |
| ⚡ **Zero Dependencies** | Single HTML file — no frameworks, no build tools |

---

## 🏗️ Architecture

```
┌─────────────────────────────────────────────────────────┐
│                     Writer (Browser)                     │
│                  Aptos Wallet (AIP-62)                   │
└───────────────────────┬─────────────────────────────────┘
                        │ signMessage
                        ▼
┌─────────────────────────────────────────────────────────┐
│                  ShelbyPress Frontend                    │
│              (HTML + CSS + Vanilla JS)                   │
└──────────────┬──────────────────────┬───────────────────┘
               │                      │
               ▼                      ▼
┌──────────────────────┐  ┌──────────────────────────────┐
│   Shelby Protocol    │  │       Aptos Blockchain        │
│                      │  │                               │
│  upload(blob)        │  │  registerBlobReference(id)    │
│       │              │  │            │                  │
│       ▼              │  │            ▼                  │
│  Shelbynet Nodes     │  │   On-chain proof of           │
│  (distributed,       │  │   authorship + timestamp      │
│   permanent)         │  │   (immutable forever)         │
└──────────────────────┘  └──────────────────────────────┘
```

---

## 🚀 Why Shelby Protocol?

| | AWS S3 | IPFS | Filecoin | **Shelby** |
|---|---|---|---|---|
| Speed | ✅ Fast | ❌ Slow | ❌ Slow | ✅ **Fast** |
| Decentralized | ❌ | ✅ | ✅ | ✅ |
| Permanent | ❌ | ⚠️ | ✅ | ✅ |
| Censorship-proof | ❌ | ⚠️ | ✅ | ✅ |
| Hot storage | ✅ | ❌ | ❌ | ✅ |

Shelby is the **only protocol** that combines all five properties — making it the ideal foundation for a censorship-resistant publishing platform.

---

## 🗺️ Roadmap

### ✅ Phase 1 — Foundation (Done)
- [x] Full publishing UI with newspaper aesthetic
- [x] Aptos wallet connection via AIP-62 standard
- [x] Wallet-signed article publishing flow
- [x] Full-text search + tag system
- [x] Responsive design

### 🔄 Phase 2 — Shelby Integration (Awaiting Early Access)
- [ ] `@shelby-protocol/sdk` integration
- [ ] Real Blob upload to Shelbynet
- [ ] On-chain Blob reference via Aptos transaction
- [ ] Blob Explorer link for every article
- [ ] Content verification via Shelbynet audit

### 📋 Phase 3 — Platform Growth
- [ ] Wallet-based author profiles
- [ ] On-chain tipping (APT)
- [ ] Article collections and series
- [ ] DAO governance for platform policies
- [ ] Multi-language support

---

## 🔌 Shelby SDK Integration

Once Early Access is granted, the core publishing function becomes:

```javascript
import { ShelbyClient } from '@shelby-protocol/sdk';
import { AptosClient } from '@aptos-labs/ts-sdk';

async function publishArticle(article, wallet) {

  // 1. Connect to Shelbynet
  const shelby = new ShelbyClient({ network: 'shelbynet' });

  // 2. Encode article as Blob
  const blob = new Blob(
    [JSON.stringify(article)],
    { type: 'application/json' }
  );

  // 3. Upload to Shelbynet (hot decentralized storage)
  const { blobId, size } = await shelby.upload(blob, {
    duration: '1year',
    signer: wallet.address,
  });

  // 4. Sign with Aptos wallet (AIP-62)
  const signature = await wallet.signMessage({
    message: `ShelbyPress: ${article.title}`,
    nonce: blobId,
  });

  // 5. Register on Aptos blockchain
  const txHash = await shelby.registerOnChain(blobId, {
    wallet,
    metadata: { title: article.title, author: wallet.address }
  });

  return {
    blobId,
    txHash,
    url: `https://explorer.shelby.xyz/shelbynet/${blobId}`
  };
}
```

---

## ⚡ Quick Start

```bash
# Clone
git clone https://github.com/hosammahdy91/shelbypress.git
cd shelbypress

# Run (no build needed)
open index.html

# Or with a local server
npx serve .
```

Then open your browser, connect your Aptos wallet, and start publishing.

---

## 🤝 Early Access

ShelbyPress is purpose-built to demonstrate Shelby Protocol's potential as a **hot storage layer for censorship-resistant applications**.

We are applying for Early Access to:

- Integrate `@shelby-protocol/sdk` into production
- Deploy live Blob storage on Shelbynet
- Prove the use case at real scale

**👉 [developers.shelby.xyz](https://developers.shelby.xyz)**

---

## 📄 License

[MIT](LICENSE) — open source, free to fork and build upon.

---

<div align="center">

Made with ⛓ by a builder who believes in the open web

**Shelby Protocol × Aptos × Free Press**

⭐ **Star this repo** if you believe the internet should be free

</div>
