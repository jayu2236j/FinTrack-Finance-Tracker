# 💰 FinTrack — Personal Finance Dashboard

A full-stack inspired personal finance management app with expense tracking, income logging, budget monitoring, savings goals, and interactive Chart.js visualizations — all behind a clean, dark dashboard UI.

![FinTrack Preview](https://img.shields.io/badge/Status-Live-brightgreen) ![HTML](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![ChartJS](https://img.shields.io/badge/Chart.js-FF6384?logo=chartdotjs&logoColor=white)

---

## 🌐 Live Demo
👉 [https://jayu2236j.github.io/FinTrack-Finance-Tracker](https://jayu2236j.github.io/FinTrack-Finance-Tracker)

---

## ✨ Features

- 📊 **Dashboard Overview** — Total balance, monthly income, expenses & savings rate at a glance
- 💳 **Transaction Management** — Add income and expense entries with category, date & description
- 📈 **Bar Chart** — Income vs expenses comparison across the last 6 months
- 🍩 **Doughnut Chart** — Spending breakdown by category
- 🎯 **Budget Tracker** — Per-category monthly spending limits with color-coded progress bars
- 🏆 **Savings Goals** — SVG ring charts tracking progress toward financial milestones
- 🗂️ **Full Transaction List** — Sorted history with icons, categories, and amounts
- 📱 **Fully Responsive** — Sidebar layout adapts to all screen sizes

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 | App structure & layout |
| CSS3 | Dashboard UI, grid, animations |
| Vanilla JavaScript | State management, CRUD logic, rendering |
| Chart.js | Bar chart & doughnut chart visualizations |
| SVG | Custom ring/donut charts for savings goals |

---

## 🚀 Getting Started

### Option 1 — Open Directly
Just open `index.html` in any browser. No installation or build tools needed.

### Option 2 — Clone the Repo
```bash
git clone https://github.com/jayu2236j/FinTrack-Finance-Tracker.git
cd FinTrack-Finance-Tracker
open index.html
```

---

## 📁 Project Structure

```
FinTrack-Finance-Tracker/
│
├── index.html        # Full app (HTML + CSS + JS + Chart.js)
└── README.md         # Project documentation
```

---

## 📸 Pages & Sections

| Page | Description |
|---|---|
| **Dashboard** | Summary cards, bar chart, pie chart, recent transactions |
| **Transactions** | Add new income/expense, view full transaction history |
| **Budget** | Monthly category budgets with visual progress bars |
| **Goals** | Savings goals with animated SVG ring progress charts |

---

## 💡 How It Works

1. **Add transactions** from the Transactions tab — enter description, amount, category & date
2. **Dashboard updates instantly** — balance, charts and recent list refresh in real time
3. **Budget bars** show how much of each category limit you've used this month
4. **Goals** track how close you are to reaching each savings target

> Note: Data is stored in memory (JavaScript state). Refreshing the page resets to demo data. A future version will integrate PostgreSQL + Express backend with persistent storage.

---

## 🔮 Future Improvements

- [ ] Node.js + Express REST API backend
- [ ] PostgreSQL database with normalized schema
- [ ] JWT authentication (Login / Sign Up)
- [ ] Export transactions to CSV
- [ ] Recurring transaction support
- [ ] Dark/light theme toggle
- [ ] Email budget alerts

---

## 👨‍💻 Author

**Jay Champaneri**
- GitHub: [@jayu2236j](https://github.com/jayu2236j)
- Email: jaychampaneri2004@gmail.com
- University of Winnipeg — Applied Computer Science (2023–2026)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).
