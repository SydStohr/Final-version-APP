🚚 Supply Chain Game — HAN University of Applied Sciences
A browser-based supply chain management simulation built with Streamlit. Student teams take on the role of a logistics company and make strategic decisions across eight quarters, responding to real-world disruptions while trying to maximise profit, service level, ESG performance and supply chain resilience.

🚀 Getting Started
1. Clone or upload the file
Add UPDATED_SYD.py to the root of a GitHub repository.
2. Install dependencies
You need Python 3.9+ and the following packages:
bashpip install streamlit pandas
3. Run the app
bashstreamlit run UPDATED_SYD.py
The app will open in your browser at http://localhost:8501.
4. Deploy on Streamlit Community Cloud (recommended for classroom use)

Push UPDATED_SYD.py to a public (or private) GitHub repository.
Go to share.streamlit.io and sign in.
Click New app, select your repository and set the main file to UPDATED_SYD.py.
Click Deploy. Streamlit will provide a public URL you can share with students.


🎮 How the Game Works
Each team plays through 8 quarters. At the start of every quarter a real-world supply chain event is introduced (e.g. a port strike, a tariff shock, a demand surge). Teams then make decisions in four departments before reviewing their results and moving on.
Quarters & Events
QuarterEventLearning objectiveQ1Current State AnalysisSupply Chain Mapping & KPI DiagnosisQ2Supplier StrategySupplier Selection & Sourcing StrategyQ3Rotterdam Port StrikeRisk Management & ResilienceQ4Demand SurgeForecasting & Capacity PlanningQ5Sustainability PressureESG & Sustainable Supply ChainsQ6Tariff ShockGlobal Sourcing & Total Landed CostQ7Market VolatilityAgility & FlexibilityQ8CEO ChallengeIntegrated Decision-Making
Departments
Each quarter teams make one decision per department:

📦 Purchasing — choose your sourcing strategy (cost focus, quality focus, local sourcing, etc.)
🏭 Operations — set production and stock levels in response to demand conditions
🛒 Sales — decide on pricing and customer fulfilment approach
🔗 Supply Chain — select logistics and distribution strategies

Every choice has a direct, visible impact on the team's KPIs.
KPIs tracked
KPIDescriptionEfficiency ScoreOverall team performance score (0–100)Net ProfitFinancial result after all costsRevenueTotal sales revenueInventory ValueValue of stock heldService Level% of customer orders fulfilled on timeESG ScoreEnvironmental, Social & Governance ratingRisk LevelSupply chain exposure to disruption (lower is better)Lead TimeAverage days from order to delivery
Strategy profiles
At the end of the game each team is assigned a strategy profile based on their decisions:

🛡️ Resilient Strategist — high service level, low risk
🌱 Green Leader — strong ESG performance
📈 Cost Controller — profit-focused, balanced risk
⚡ Risk Taker — high profit, high risk
📦 Inventory Hoarder — large safety stock
⚖️ Balanced Operator — well-rounded across all KPIs


📊 End-of-Round: Class Comparison
At the end of every quarter (and in the Final Report) teams see how they rank against five simulated peer teams:

🏆 A ranked leaderboard showing all 6 teams
📊 Bar charts for Score, Net Profit, Service Level and Risk Level
💡 Personalised tips based on where the team is falling behind the class average

Peer team performance scales realistically across quarters, so the competition stays meaningful throughout the game.

📋 Pages Overview
PageDescription🏠 StartSet team name, group and difficulty level📝 Decision LogView all decisions made so far this quarter📦 PurchasingMake the purchasing decision for this quarter🏭 OperationsSet stock and production levels🛒 SalesMake the sales and fulfilment decision🔗 Supply ChainChoose your logistics strategy📋 Quarter SummaryKPI overview, class comparison, group reflection🏁 Final ReportFull game summary, strategy profile, decision history👨‍🏫 Instructor viewPassword-protected instructor control panel

👨‍🏫 Instructor View
The instructor panel is password protected.
Password: Oliver123
From the instructor panel you can:

Trigger custom events — override the default quarter event with any of the eight built-in scenarios (port strike, tariff shock, demand surge, etc.)
Adjust KPIs manually — directly change score, profit, service level, risk, ESG and lead time for demonstration or correction purposes
Pause the game — freeze student progress between quarters
Reset the game — restart from quarter 1 with default values


⚠️ Keep the password confidential. Share the app URL with students but do not share the instructor password.


⚙️ Difficulty Levels
At the start screen teams select a difficulty:
LevelEffectEasyMore forgiving KPI thresholds, wider forecast toleranceMediumDefault balanced experienceHardTighter margins, narrower forecast tolerance, harsher event impacts

🗂️ File Structure
your-repo/
└── UPDATED_SYD.py   ← the entire application (single file)
No additional files, databases or configuration are required.

🛠️ Built With

Streamlit — UI framework
Pandas — data tables and leaderboard


📄 License
This simulation was developed for educational use at HAN University of Applied Sciences. Please contact the course team before redistributing or adapting the material.
