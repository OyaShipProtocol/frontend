# 🌍 SendXpress Frontend

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Next.js](https://img.shields.io/badge/Next.js-13-black)](https://nextjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5-blue)](https://www.typescriptlang.org/)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind-3-38bdf8)](https://tailwindcss.com/)

> **The social commerce storefront for SendXpress — discover global suppliers and pay with Stellar escrow.**

SendXpress Frontend is the Next.js web application connecting importers with verified global suppliers. Browse the social product feed, negotiate in real-time chat, and pay safely through Soroban smart contract escrow on Stellar.

---

## ✨ Core Features

- 🌍 **Supplier Discovery**: Social feed of global product listings with filters and search.
- 💬 **Real-Time Chat**: Negotiate prices and terms directly with suppliers.
- 🔒 **Stellar Escrow**: Freighter wallet integration for trustless escrow payments.
- 📦 **Shipment Tracking**: Live order status from warehouse to doorstep.
- ⭐ **Trust Scores**: On-chain reputation for every supplier and importer.
- 🌗 **Dark / Light Mode**: System-aware theme with smooth toggling.

---

## 🗂️ Project Structure

```
├── pages/
│   ├── _app.tsx            # App shell
│   └── index.tsx           # Landing page
├── components/
│   ├── atoms/              # Button, Card, Toast, ThemeToggle, Input
│   ├── molecules/          # SupplierCard, ChatPreview, DealCard, WalletData
│   └── organisms/          # Navbar, Feed, ChatDrawer, EscrowModal
├── hooks/
│   ├── useAccount.ts       # Stellar wallet state
│   ├── useTheme.ts         # Dark/light mode
│   └── useToast.ts         # Notifications
├── shared/
│   ├── contracts.ts        # Soroban contract bindings
│   └── utils.ts            # Shared utilities
└── styles/
    └── globals.css         # Tailwind base
```

---

## 🚀 Getting Started

```bash
npm install
cp .env.example .env
npm run dev
```

**Related repos:**
- [SendXpress/backend](https://github.com/SendXpress/backend) — REST API
- [SendXpress/smartcontract](https://github.com/SendXpress/smartcontract) — Soroban escrow
- [SendXpress/mobile](https://github.com/SendXpress/mobile) — iOS app

---

## 📜 License

MIT License. Copyright (c) 2026 SendXpress.
