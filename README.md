# Tracker Keuangan

A personal finance and investment tracker that runs as an installable web app (PWA). It works offline and **all data stays on your own device**.

## Problem Solving

Most budgeting apps either need an account and a server, or ignore investments. This tracker keeps daily cash records and an investment portfolio in one place, with no backend and no tracking.

## Features

- Multiple wallets (e-wallet, bank, cash) with live balances
- Income, expense, transfer, and gig-income entries (gross, fuel cost, net, daily average)
- Investment log: buy and sell with fees, average cost, unrealized and realized profit or loss
- Asset allocation overview and monthly reports with category budgets
- Offline support, installable on Android and iOS home screens
- Backup and restore through a copyable JSON export

## Tech Stack

Vanilla HTML, CSS, and JavaScript. Web App Manifest and Service Worker for installability and offline use. Data is stored in the browser's `localStorage`.

## Installation

1. Fork or upload these files to a GitHub repository.
2. Go to **Settings > Pages**, choose the `main` branch and the `/ (root)` folder, then save.
3. Open the published URL in Chrome (Android) or Safari (iOS).
4. Use **Install app** or **Add to Home Screen**.

## Privacy

No analytics, no server, no network requests with your data. Records live only in your browser storage. Clearing site data removes them, so use **Pengaturan > Salin cadangan data** regularly and keep the backup somewhere private. Never commit a backup to this repository.
