# 🚚 Supply Chain Game — HAN University of Applied Sciences

A browser-based supply chain management simulation built with [Streamlit](https://streamlit.io). Student teams take on the role of a logistics company and make strategic decisions across eight quarters, responding to real-world disruptions while trying to maximise profit, service level, ESG performance and supply chain resilience.

---

## 🚀 Getting Started

### 1. Clone or upload the file

Add `UPDATED_SYD.py` to the root of a GitHub repository.

### 2. Install dependencies

You need Python 3.9+ and the following packages:

```bash
pip install streamlit pandas
```

### 3. Run the app

```bash
streamlit run UPDATED_SYD.py
```

The app will open in your browser at `http://localhost:8501`.

### 4. Deploy on Streamlit Community Cloud (recommended for classroom use)

1. Push `UPDATED_SYD.py` to a public (or private) GitHub repository.
2. Go to [share.streamlit.io](https://share.streamlit.io) and sign in.
3. Click **New app**, select your repository and set the main file to `UPDATED_SYD.py`.
4. Click **Deploy**. Streamlit will provide a public URL you can share with students.

---

## 🎮 How the Game Works

Each team plays through **8 quarters**. At the start of every quarter a real-world supply chain event is introduced (e.g. a port strike, a tariff shock, a demand surge). Teams then make decisions in four departments before reviewing their results and moving on.

### Quarters & Events

| Quarter | Event | Learning objective |
|---------|-------|--------------------|
| Q1 | Current State Analysis | Supply Chain Mapping & KPI Diagnosis |
| Q2 | Supplier Strategy | Supplier Selection & Sourcing Strategy |
| Q3 | Rotterdam Port Strike | Risk Management & Resilience |
| Q4 | Demand Surge | Forecasting & Capacity Planning |
| Q5 | Sustainability Pressure | ESG & Sustainable Supply Chains |
| Q6 | Tariff Shock | Global Sourcing & Total Landed Cost |
| Q7 | Market Volatility | Agility & Flexibility |
| Q8 | CEO Challenge | Integrated Decision-Making |

### Departments

Each quarter teams make one decision per department:

- **📦 Purchasing** — choose your sourcing strategy (cost focus, quality focus, local sourcing, etc.)
- **🏭 Operations** — set production and stock levels in response to demand conditions
- **🛒 Sales** — decide on pricing and customer fulfilment approach
- **🔗 Supply Chain** — select logistics and distribution strategies

Every choice has a direct, visible impact on the team's KPIs.

### KPIs tracked

| KPI | Description |
|-----|-------------|
| Efficiency Score | Overall team performance score (0–100) |
| Net Profit | Financial result after all costs |
| Revenue | Total sales revenue |
| Inventory Value | Value of stock held |
| Service Level | % of customer orders fulfilled on time |
| ESG Score | Environmental, Social & Governance rating |
| Risk Level | Supply chain exposure to disruption (lower is better) |
| Lead Time | Average days from order to delivery |

### Strategy profiles

At the end of the game each team is assigned a strategy profile based on their decisions:

- 🛡️ **Resilient Strategist** — high service level, low risk
- 🌱 **Green Leader** — strong ESG performance
- 📈 **Cost Controller** — profit-focused, balanced risk
- ⚡ **Risk Taker** — high profit, high risk
- 📦 **Inventory Hoarder** — large safety stock
- ⚖️ **Balanced Operator** — well-rounded across all KPIs

---

## 📊 End-of-Round: Class Comparison

At the end of every quarter (and in the Final Report) teams see how they rank against five simulated peer teams:

- 🏆 A ranked leaderboard showing all 6 teams
- 📊 Bar charts for Score, Net Profit, Service Level and Risk Level
- 💡 Personalised tips based on where the team is falling behind the class average

Peer team performance scales realistically across quarters, so the competition stays meaningful throughout the game.

---

## 📋 Pages Overview

| Page | Description |
|------|-------------|
| 🏠 Start | Set team name, group and difficulty level |
| 📝 Decision Log | View all decisions made so far this quarter |
| 📦 Purchasing | Make the purchasing decision for this quarter |
| 🏭 Operations | Set stock and production levels |
| 🛒 Sales | Make the sales and fulfilment decision |
| 🔗 Supply Chain | Choose your logistics strategy |
| 📋 Quarter Summary | KPI overview, class comparison, group reflection |
| 🏁 Final Report | Full game summary, strategy profile, decision history |
| 👨‍🏫 Instructor view | Password-protected instructor control panel |

---

## 👨‍🏫 Instructor View

The instructor panel is password protected.

**Password: `Oliver123`**

From the instructor panel you can:

- **Trigger custom events** — override the default quarter event with any of the eight built-in scenarios (port strike, tariff shock, demand surge, etc.)
- **Adjust KPIs manually** — directly change score, profit, service level, risk, ESG and lead time for demonstration or correction purposes
- **Pause the game** — freeze student progress between quarters
- **Reset the game** — restart from quarter 1 with default values

> ⚠️ Keep the password confidential. Share the app URL with students but do not share the instructor password.

---

## ⚙️ Difficulty Levels

At the start screen teams select a difficulty:

| Level | Effect |
|-------|--------|
| Easy | More forgiving KPI thresholds, wider forecast tolerance |
| Medium | Default balanced experience |
| Hard | Tighter margins, narrower forecast tolerance, harsher event impacts |

---

## 🗂️ File Structure

```
your-repo/
└── UPDATED_SYD.py   ← the entire application (single file)
```

No additional files, databases or configuration are required.

---

## 🛠️ Built With

- [Streamlit](https://streamlit.io) — UI framework
- [Pandas](https://pandas.pydata.org) — data tables and leaderboard

---

## 📄 License

This simulation was developed for educational use at HAN University of Applied Sciences. Please contact the course team before redistributing or adapting the material.
