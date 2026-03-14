# 💎 FyndrWealth — Find Your Financial Freedom

> A free, all-in-one personal finance web app. No account required. No ads. No fluff.

![FyndrWealth](https://img.shields.io/badge/FyndrWealth-Free%20%26%20Open-2563eb?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Live-10b981?style=for-the-badge)
![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red?style=for-the-badge)

**Live App:** [fyndrwealth.com](https://fyndrwealth.com)

---

## What is FyndrWealth?

FyndrWealth is a mobile-first personal finance app that runs entirely in your browser. It helps everyday people take control of their money — budget smarter, crush debt, track spending, and build real wealth — without needing a finance degree or a paid subscription.

Everything works instantly with no login required. Just open it and start.

---

## Features

### 🏠 Financial Health Score
A real-time 0–100 score that reflects your actual financial situation. It updates as you add income, expenses, debts, and savings goals — giving you a clear picture of where you stand and what to improve.

### 💸 Budget & Expense Tracker
Set your monthly take-home income and add all your recurring expenses. FyndrWealth automatically flags each expense as Necessary, Trim, Review, or Invest-related — and shows your 50/30/20 budget split with live bar charts.

### 🧾 Spending Tracker
Log every purchase in seconds. Filter by category, view daily and monthly totals, and watch a live budget bar track how much of your monthly allowance you've used.

### 🛠️ Financial Tools
- **Net Worth Tracker** — add assets and liabilities to see your real net worth
- **Savings Goals** — set targets with monthly contributions and automatic ETAs
- **Bill Reminders** — never miss a payment with color-coded due date alerts
- **What If Calculator** — see how extra monthly savings grow with compound interest
- **Tax Estimator** — estimate take-home pay with federal brackets, state tax, and FICA
- **Income History** — track multiple income sources across primary, side, and passive income

### 💳 Debt Crusher
Enter all your debts and choose your payoff strategy:
- **Avalanche** — pay highest APR first, saves the most in interest
- **Snowball** — pay smallest balance first, builds momentum

Use the extra payment slider to see exactly how many months and dollars you save.

### 📊 Track Tab
- **Spending Heatmap** — visualize your spending intensity day by day with color-coded calendar views
- **No Spend Day Tracker** — mark no-spend days, build streaks, and watch your savings compound

### 📅 Bills Tab
- **Bill Reminders** — manage all recurring bills in one place
- **Monthly Checklist** — check off bills as you pay them each month

### 📰 Financial Tips
Curated personal finance insights covering investing, debt, saving, taxes, and mindset. A rotating daily money tip appears on your dashboard every day.

### 🔥 Streaks & Milestones
Stay consistent — earn badges as you hit financial milestones. A daily login streak keeps you accountable.

### 🤖 AI Financial Advisor
Powered by Claude. Ask anything about budgeting, debt payoff, investing, or savings — and get personalized advice based on your actual financial data.

### 📖 Financial Glossary
25+ financial terms explained in plain English. Searchable and organized by category — accessible inside the AI tab.

### 🚀 Onboarding Quiz
A 5-question setup wizard that personalizes FyndrWealth to your financial situation on first use.

---

## Tech Stack

| Layer | Technology |
|---|---|
| Frontend | Vanilla HTML, CSS, JavaScript — no frameworks |
| Fonts | Plus Jakarta Sans + Fira Code (Google Fonts) |
| AI | Anthropic Claude API |
| Hosting | Netlify (auto-deploy from GitHub) |
| Domain | fyndrwealth.com (Namecheap) |
| Auth (coming) | Supabase |
| Payments (coming) | Stripe |

No build tools. No npm. No dependencies. Two files — open in any browser, works on any device.

---

## Project Structure

```
money-map/
├── index.html       # Full app (all features, logic, and styles in one file)
├── README.md        # This file
```

FyndrWealth is intentionally kept as a single self-contained HTML file. This makes it instantly deployable, easy to audit, fast, and offline-capable (except AI Advisor).

---

## Running Locally

No setup required.

```bash
git clone https://github.com/patrickstf/money-map.git
cd money-map
open index.html
```

Or just drag `index.html` into any browser.

---

## Roadmap

### Free Improvements (In Progress)
- [ ] Supabase user accounts — save and sync data across devices
- [ ] localStorage persistence for guest users
- [ ] Push notifications for bill due dates
- [ ] PWA manifest for better home screen install

### Pro Plan — $4.99/month (Planned)
- [ ] Full data persistence + cloud sync
- [ ] PDF export of reports
- [ ] AI memory across sessions
- [ ] 12-month historical trend charts
- [ ] Custom expense categories
- [ ] Monthly email spending report

### Family Plan — $9.99/month (Planned)
- [ ] Up to 6 family members
- [ ] Shared family dashboard
- [ ] Individual privacy controls
- [ ] Shared savings goals
- [ ] Teen Mode and Couple Mode

### Big Swings (Future)
- [ ] Native iOS app
- [ ] Native Android app
- [ ] Browser extension for automatic spend logging
- [ ] Bank connection via Plaid

---

## Mobile Install

FyndrWealth is designed to feel like a native app on mobile.

**iPhone / iPad:**
1. Open [fyndrwealth.com](https://fyndrwealth.com) in Safari
2. Tap the Share button ⬆️
3. Tap "Add to Home Screen" → Tap "Add"

**Android:**
1. Open [fyndrwealth.com](https://fyndrwealth.com) in Chrome
2. Tap the three-dot menu ⋮
3. Tap "Add to Home Screen" → Tap "Add"

A full native iOS and Android app is in development.

---

## License & Copyright

```
Copyright © 2025 FyndrWealth / fyndrwealth.com — All Rights Reserved.
Unauthorized copying, reproduction, modification, or distribution is strictly prohibited.
```

This project is source-available for transparency but is **not open source**. You may view the code but may not copy, redistribute, or build competing products from it without written permission.

---

## Contact

- **Website:** [fyndrwealth.com](https://fyndrwealth.com)
- **Support & Feedback:** support@fyndrwealth.com

---

<div align="center">
  <strong>Built with 💎 by FyndrWealth</strong><br/>
  <em>Find Your Financial Freedom</em>
</div>
