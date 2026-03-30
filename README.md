# 💰 FinanceFlow PRO

> A complete personal finance manager — works on any device, no app install needed.

![Version](https://img.shields.io/badge/version-8.0-blue)
![Offline](https://img.shields.io/badge/works-offline-green)
![Free](https://img.shields.io/badge/cost-free-brightgreen)

---

## 📱 Live App

👉 **[Open FinanceFlow PRO](https://balasantu.github.io/FinanceFlow)**

Works on Android, iPhone, and PC — just open in Chrome.

---

## ✨ Features

### 🏠 Dashboard (Home)
- Monthly Net Savings overview
- Income, EMIs, Bills, Expenses summary
- Available Cash Balance (after all deductions)
- Credit Card usage tracker
- Collapsible sections — Bills, EMIs, Credits & Debits, Total Balance
- Only active bills & EMIs shown — skipped/inactive are hidden automatically

### 📋 Bills
- Add recurring bills — monthly, quarterly, yearly, one-time
- **Variable amounts** — enter fresh amount each month (₹0 by default for new months)
- **✏️ Edit amount** for any specific month without affecting others
- Mark paid via **UPI/Bank** or **Credit Card**
- **⏸ Skip** — hide a bill for one specific month only
- **🚫 Inactive** — stop bill from appearing from current month onwards
- Inactive bills shown as collapsible dropdown — activate anytime
- Overdue alerts and notifications
- ⚡ Quick manage panel — see all bills, toggle per month

### 🏦 EMIs
- Track all active EMIs with installment number
- **✏️ Edit amount** per month — for variable last EMI
- **⏸ Skip** — hide EMI for one specific month
- **🚫 Inactive** — stop EMI from current month onwards
- Inactive EMIs shown as collapsible dropdown
- **💰 Prepayment** — extra payment with two options:
  - Reduce tenure (fewer months, same EMI)
  - Reduce EMI amount (same months, lower EMI)
  - Live calculation shown before confirming
- **✅ Preclosure** — mark loan as fully closed, removed from all calculations
- CC EMIs auto-marked as credit card payment
- Remaining EMI balance deducted from Net Worth

### 💳 Transactions
- Add income & expense transactions for any month
- When viewing an old month, date defaults to that month automatically
- Personal / Home / Borrowed categories
- Paste bank SMS to auto-import transactions
- Import UPI Lite / BHIM CSV

### 📈 More — Investments
- Stocks, FD, PF, PPF, MF, RD, Gold, Crypto, NPS
- Track invested vs current value with P&L

### 💸 More — I Lent
- **Grouped by person** — multiple loans to same person shown as one card
- Tap to expand individual entries
- Mark collected, track overdue
- Counts in Net Worth automatically

### 🤝 More — Borrowed
- Track money you owe others
- Mark returned with actual amount
- Overdue alerts

### 💫 More — Given / Help
- Money given where return is not compulsory
- Grouped by person, expandable history
- Choose per entry whether to count in Net Worth
- Mark returned if they ever pay back

### 🙏 More — Donations
- Track donations by recipient
- Monthly and total donation summary

### 🏘️ More — Property
- Add plots, flats, land with agreement cost & current value
- Log **irregular payments** with Principal + Interest split
- Progress bar showing % of total cost paid
- **Auto-marks as FULLY PAID** when principal reaches 100%
- Full payment history preserved even after completion
- Property value shown in Net Worth

### 📅 More — Yearly View
- Full year income, EMI, spend, savings summary
- Month-by-month breakdown table
- Export yearly PDF report

### 📄 PDF Reports — 3 Types
- **Monthly Report** — income, EMIs, bills, expenses, transactions
- **Yearly Report** — month-by-month annual summary
- **Full Financial Report** — complete snapshot including Net Worth, Investments, Property, Lent, Borrowed, Given/Help, Donations, Active EMIs

### ☁️ Google Drive Sync
- Real-time sync across all devices
- Auto-saves within 2 seconds of any change
- Built-in step-by-step setup guide with direct links
- One-time setup — sign in on each device, data loads automatically

### 📤 Manual Backup
- Export data as `.json` file
- Import on any device
- Previous `.json` files fully compatible with new versions

---

## 🏦 Net Worth Breakdown

| Component | Effect |
|-----------|--------|
| Bank Balance | Added |
| Cash / UPI | Added |
| Investments | Added |
| Lent (pending) | Added |
| Given/Help (if opted in) | Added |
| Property Value | Added |
| Borrowed (owed by you) | Deducted |
| EMI Remaining Balance | Deducted |

---

## 📱 Skip vs Inactive vs Delete

| Action | Effect |
|--------|--------|
| ⏸ Skip | Hide for one specific month only |
| 🚫 Inactive | Hide from current month onwards — past months untouched |
| 🗑️ Delete | Permanently removes from all months |

---

## 🚀 How to Use

### On Android
1. Open the link in **Chrome**
2. Tap ⋮ menu → **Add to Home Screen**
3. Use like a native app — works offline

### On PC
1. Open the link in **Chrome**
2. Bookmark for quick access

### Cross-Device Sync
1. Tap **🔄 Backup / Sync** on the dashboard
2. Follow the 5-step Google Drive setup guide (built into the app)
3. Sign in on any device — data loads automatically

---

## 🔒 Privacy & Security

- Your data never leaves your control
- Stored in your own **browser localStorage**
- Synced only to **your own Google Drive**
- No ads, no tracking, no subscriptions
- Open source — every line of code is visible in the HTML file

---

## 🛠️ Google Drive Setup

1. Go to [Google Cloud Console](https://console.cloud.google.com)
2. Create a new project (e.g. "FinanceFlow")
3. Enable **Google Drive API**
4. Create **OAuth 2.0 Client ID** → Web application
5. Add your GitHub Pages URL to Authorised JavaScript Origins
6. Paste the Client ID in app → 🔄 Backup / Sync → Connect

The full step-by-step guide with clickable links is built into the app.

---

## 💾 Data Note

App uses `ffpro6` as the localStorage key. Data is stored per domain — `file://` and `github.io` have separate storage. Use Export → Import to move data between them the first time.

---

## 📄 License

Free to use for personal use.
