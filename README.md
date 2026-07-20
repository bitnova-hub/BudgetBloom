BudgetBloom

A simple, no-signup budgeting app for tracking expenses, setting savings goals, and managing Zakat — built for both individuals and families.

Live app: https://bitnova-hub.github.io/BudgetBloom/

Features
Individual or Family mode — track your own budget, or share one budget across household members with a per-member spending breakdown
Expense categories — Rent, Bills, Grocery, Shopping, Children/Pocket Money, Transport, Health, Education, Zakat & Charity, Entertainment, plus your own custom categories
Budget envelopes — set a monthly limit per category and track progress at a glance
Savings goals — set a target amount and date, and get automatic daily/monthly/yearly saving suggestions
Zakat helper — a quick 2.5%-based estimate on eligible savings (for guidance only — confirm exact calculations with a scholar or trusted Zakat calculator)
Smart insights — rule-based tips on savings rate, overspending, and budget alerts, generated from your own data
Reports — spending-by-category breakdown and a 6-month spending trend
Multi-currency — PKR, USD, EUR, GBP, SAR, AED
Dark mode
Local data & backup — all data stays on your device (localStorage); export a full JSON backup anytime from Settings
Tech

Single self-contained index.html file — plain HTML, CSS, and JavaScript, no build step, no external backend. Charts are drawn natively with the Canvas API.

Running locally

Just open index.html in any modern browser — no server or installation needed.

Deploying your own copy
Fork or download this repo
Upload index.html to a new GitHub repository
Go to Settings → Pages, set source to your main branch, root folder
Your app will be live at https://<your-username>.github.io/<repo-name>/
Data & privacy

All data (transactions, budgets, goals) is stored locally in your browser via localStorage. Nothing is sent to a server. Clearing your browser data or switching devices/browsers will reset the app unless you've exported a backup first.

Disclaimer

The Zakat calculator provides a general estimate based on a common guideline and is not a religious ruling. Please consult a qualified scholar or a dedicated Zakat calculator for precise obligations.
