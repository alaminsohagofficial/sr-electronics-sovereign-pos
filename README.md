# SR Electronics Park — Sovereign POS

**An Enterprise of Salsabilah Amin Limited** • **Powered by Gemini**

A 100% browser-based, single-file Point of Sale (POS), inventory, and accounting web application built for **SR Electronics Park**. Preloaded with real showroom records and stored locally in the browser (`localStorage`), it runs with zero third-party backend dependencies and full JSON backup/restore control.

---

## Core Modules

| Module | Bengali Label | Key Capabilities |
| :--- | :--- | :--- |
| **Dashboard** | ড্যাশবোর্ড | 8 real-time KPI cards, period filter (`All Time`, `This Month`, `Today`), 3 Chart.js visualizations (monthly sales trend, sales/purchase/expense comparison, cash vs. due), low-stock alerts, and due invoice collection |
| **POS Terminal** | POS বিক্রয় | Live search by product, SKU, or brand; category filter; cart controls; quick-add customer; fixed/`%` discount; optional 5% VAT; multi-method payments (`Cash`, `bKash`, `Nagad`, `Card`, `Due`); Invoice Layout selector; and print-ready receipt |
| **Products & Stock** | পণ্য ও স্টক | 277 preloaded products (206 active) with SKU, category, brand, warranty, cost/sale price, stock count, alert threshold, and CSV export |
| **Sales & Invoices** | বিক্রয় ও ইনভয়েস | 712 preloaded invoices (৳15,442,551.78 total), `Paid`/`Due` status filter, one-click due collection, live layout-switchable receipt re-printing, and CSV export |
| **Purchases & Expenses** | ক্রয় ও ব্যয় | 71 preloaded supplier purchase records (৳5,943,390.50 total), stock purchase entry (auto-updates stock & supplier due), and categorized business expense logging |
| **Customers & Suppliers** | গ্রাহক ও সরবরাহকারী | 454 customers with Customer Group badges (Loyalty Club, B2B, EMI/Due tiers) + 11 suppliers with due tracking and one-click due settlement |
| **Reports, Layouts & Backup** | রিপোর্ট ও ডেটা ব্যাকআপ | Profit & Loss summary (Gross Sales, COGS, Expenses, Net Profit), **Invoice Layouts** manager (**Minister** default, **MyOne**, **Butterfly Marketing Limited**, **SR Electronics Park** + custom layouts), full JSON export/import restore, and data reset |

## Built-In Utilities

- **Multi-Brand Invoice Layouts:** Switch between **Minister** (default for *Salsabilah Amin Limited*), **MyOne**, **Butterfly Marketing Limited**, and **SR Electronics Park** during checkout or inside the receipt preview modal before printing.
- **Bilingual Interface (`BN` / `EN`):** Instant switching between Bengali and English navigation labels.
- **Theme Toggle (`Dark` / `Light`):** Sovereign dark mode with golden 3D `SR` monogram and electric cyan/gold glow, plus a high-contrast light mode.
- **Quick Calculator:** Built-in modal calculator accessible from the top header.
- **Print-Ready Receipts:** Dedicated `@media print` styling for clean thermal or A4 invoice printing.

## Tech Stack

- **Structure & Logic:** Single-file HTML5 + Vanilla JavaScript (ES6+) (`index.html`)
- **Styling:** Tailwind CSS (`3.4.17` CDN) + CSS custom properties
- **Charts:** Chart.js (`4.4.1` CDN)
- **Typography:** Google Fonts (`Inter` & `Noto Sans Bengali`)
- **Storage:** Browser `localStorage` (`sr_electronics_sovereign_pos_v2`)

## Quick Start

1. Clone the repository:
   ```bash
   git clone https://github.com/alaminsohagofficial/salsabilah-empire-pos.git
   cd salsabilah-empire-pos
   ```
2. Open `index.html` directly in any modern web browser, or deploy the repository with **GitHub Pages** for instant web access.

## Data Sovereignty & Backup

- No data is transmitted to external servers; all records remain in your local browser storage.
- Use **রিপোর্ট ও ডেটা ব্যাকআপ → সম্পূর্ণ ব্যাকআপ (JSON)** regularly to download a portable backup file (or import `sr_electronics_real_backup.json` via **ব্যাকআপ রিস্টোর (JSON)** to sync across devices).

---

**SR Electronics Park** — An Enterprise of Salsabilah Amin Limited • **Powered by Gemini**
