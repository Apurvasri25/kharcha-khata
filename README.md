# 📒 Kharcha Khata (செலவு கணக்கு)

A ledger-book inspired expense tracker built with plain HTML, CSS and JavaScript. No frameworks, no build step, no backend.

**Live demo:** _add your deployed link here_

## Features
- Add, edit and delete income and expense transactions
- Amounts in ₹ with Indian number formatting (₹1,25,000)
- Dashboard: total balance, monthly income, monthly spending, savings rate
- Charts (Chart.js): spending by category, 30-day trend, income vs expense by month
- Monthly budgets per category with progress bars that turn amber and red
- Search, filter by category and type, sort by date or amount
- Smart insights (e.g. "Food is up 30% vs last month")
- CSV export and import
- Light and dark mode, fully responsive
- Data saved in the browser (localStorage), with sample data on first load

## Tech
HTML5, CSS3 (custom properties, grid), vanilla JavaScript, Chart.js 4.4.1, Google Fonts (Young Serif, Hind Madurai)

## Run locally
Open `index.html` in any browser. That's it.

## Deploy
- **Netlify:** drag the folder onto app.netlify.com/drop
- **GitHub Pages:** push to a repo, then Settings → Pages → deploy from `main`

## Limitations (planned for v2)
- No user accounts, so data stays on one device and browser
- Needs internet for the chart library and fonts
- No custom categories or recurring expenses yet

## Roadmap
- [ ] Login and signup (Node.js + Express + SQLite, bcrypt, JWT)
- [ ] Sync across devices
- [ ] Custom categories and recurring expenses
- [ ] PDF monthly report

## Author
Made by _your name_
