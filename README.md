# 💰 FinanceFlow PRO

> A complete personal finance manager — works on any device, no app install needed.

![Version](https://img.shields.io/badge/version-8.0-blue)
![Offline](https://img.shields.io/badge/works-offline-green)
![Free](https://img.shields.io/badge/cost-free-brightgreen)

---

## 📱 Live App

👉 **[Open FinanceFlow PRO](https://YOUR_USERNAME.github.io/financeflow)**

Works on Android, iPhone, and PC — just open in Chrome.

---

## ✨ Features

### 🏠 Dashboard
- Monthly Net Savings overview
- Income, EMIs, Bills, Expenses summary
- Available Cash Balance (after all deductions)
- Credit Card usage tracker
- Collapsible sections for clean view

### 📋 Bills
- Add recurring bills (monthly, quarterly, yearly, one-time)
- Variable bill amounts — enter fresh amount each month
- Mark paid via **UPI/Bank** or **Credit Card**
- Overdue alerts and notifications
- Filter by category (Credit Card, Electricity, Mobile, etc.)

### 🏦 EMIs
- Track all active EMIs
- CC EMIs auto-marked as credit card payment
- Remaining EMI balance shown in Net Worth
- Mark paid per month

### 💳 Transactions
- Add income & expense transactions
- Personal / Home categories
- Paste bank SMS to auto-import transactions
- Import UPI Lite / BHIM CSV

### 📈 More — Investments
- Stocks, FD, PF, PPF, MF, RD, Gold, Crypto, NPS
- Track invested vs current value
- Profit & Loss display

### 💸 More — I Lent
- Group multiple loans to same person
- Tap to expand individual entries
- Mark collected, track overdue
- Counts in Net Worth automatically

### 🤝 More — Borrowed
- Track money you owe others
- Mark returned with actual amount
- Overdue alerts

### 💫 More — Given / Help
- Money given where return is not expected
- Group by person with expandable history
- Choose per entry whether to count in Net Worth
- Mark returned if they ever pay back

### 🙏 More — Donations
- Track donations by recipient
- Monthly and total donation summary

### 🏘️ More — Property
- Add plots, flats, land
- Log irregular payments with Principal + Interest split
- Progress bar showing % of total cost paid
- Payment history with dates
- Property value shown in Net Worth

### 📅 More — Yearly View
- Full year income, EMI, spend, savings summary
- Month-by-month breakdown table
- Export yearly PDF report

### ☁️ Google Drive Sync
- Real-time sync across all devices
- Auto-saves within 2 seconds of any change
- One-time setup with Google OAuth
- Step-by-step setup guide built into app

### 📤 Manual Backup
- Export data as `.json` file
- Import on any device
- No data ever lost

---

## 🏦 Net Worth / Total Assets Includes

| Item | Included |
|------|----------|
| Bank Balance | ✅ |
| Cash / UPI | ✅ |
| Investments | ✅ |
| Money to Collect (Lent) | ✅ |
| Given/Help (if opted in) | ✅ |
| Property Value | ✅ |
| Borrowed (owed by you) | ➖ Deducted |
| EMI Remaining Balance | ➖ Deducted |

---

## 🚀 How to Use

### On Android
1. Open the link in **Chrome**
2. Tap ⋮ → **Add to Home Screen**
3. Use like a native app — works offline ✅

### On PC
1. Open the link in **Chrome**
2. Bookmark it for quick access
3. All data syncs via Google Drive

### Cross-Device Sync
1. Tap **🔄 Backup / Sync** on dashboard
2. Follow the 5-step Google Drive setup guide
3. Sign in on any device — data loads automatically

---

## 🔒 Privacy & Security

- ✅ **Your data never leaves your control**
- ✅ Stored in your own **browser localStorage**
- ✅ Synced to **your own Google Drive** (not our servers)
- ✅ No ads, no tracking, no subscriptions
- ✅ Open source — you can see every line of code

---

## 📦 Tech Stack

- Pure **HTML + CSS + JavaScript** — single file, zero dependencies
- Works as **PWA** (installable on Android/iPhone)
- **Google Drive API** for cross-device sync
- **localStorage** for offline data persistence
- **jsPDF** for PDF report generation

---

## 🛠️ Setup for Developers

To enable Google Drive sync on your own hosted version:

1. Go to [Google Cloud Console](https://console.cloud.google.com)
2. Create a new project
3. Enable **Google Drive API**
4. Create **OAuth 2.0 Client ID** (Web application)
5. Add your GitHub Pages URL to Authorised JavaScript Origins
6. Paste the Client ID in the app → **🔄 Backup / Sync**

---

## 📄 License

Free to use for personal use. Built with ❤️ for managing finances the simple way.
