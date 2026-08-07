# 📱 PocketBook — Mobile Money Agent OS

PocketBook is a pan-African Mobile Money (MoMo) operating system designed specifically for kiosk agents, money exchangers, and banking operators.

## 🚀 Features

- 💳 **Dual-Wallet & Cash Ledger:** Simultaneous balance tracking for Lonestar MTN, Orange Money, and physical cash.
- 💬 **SMS Auto-Recording:** Intelligent parser auto-detecting transaction amounts, carriers, and customer phone numbers from Mobile Money SMS messages.
- 📊 **Detailed Register Report:** Real-time metrics (# Txns, Turnover, Commissions), date filter pills (`Today`, `7 Days`, `30 Days`, `This Month`), and provider search filters.
- ⚡ **AI Smart Float Advisor:** Proactive liquidity alerts warning agents before float depletion.
- 🔍 **EOD Drawer Cash Reconciliation:** End-of-day audit assistant comparing drawer cash against system float movements.
- 🏢 **Multi-Branch Management:** Kiosk owner dashboard for managing sub-agents and branch join codes.
- 🔗 **Referral Program & Payouts:** Built-in agent invitation system.
- 🔒 **Shift Lock Controller:** Shift opening/closing locks preventing unauthorized post-shift edits.
- 🌓 **Dark & Light Mode:** Toggleable theme with custom warm African color system (`#C65D3B` Terracotta, `#D97706` Amber, `#4A2E1B` Cocoa).

## 🛠️ Running Locally

Open `index.html` directly in any web browser, or launch a local server:

```bash
npm run dev
```

## 🌐 Deploying on Render

### Option A: Automatic Blueprint (Recommended)
1. Push your repository to GitHub / GitLab.
2. Go to [Render Dashboard](https://dashboard.render.com/) -> **New** -> **Blueprint**.
3. Connect your repository. Render will automatically pick up `render.yaml` and deploy your site!

### Option B: Manual Static Site Setup
1. Go to **Render Dashboard** -> **New** -> **Static Site**.
2. Connect your GitHub repository.
3. Set the following settings:
   - **Name:** `pocketbook-app`
   - **Build Command:** *(leave empty)*
   - **Publish Directory:** `./` (or `.` depending on repo root)
4. Click **Create Static Site**.

