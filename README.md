# Flymate

**Should I book this flight?** Flymate gives a traveller one clear answer before they pay: book now, wait, or switch to a better flight, and why.

Built for the *Predictive Model Track: Predict Early, Decide Better* hackathon.

## What it does

- **Detect**: predicts the chance of a 30+ minute delay and how the fare will move before departure.
- **Categorize**: names the cause (weather at either airport, peak-hour congestion, knock-on delays, holiday demand, price trend).
- **Prioritize**: ranks flights that day by fare plus delay risk, and ranks reasons by impact.
- **Explain**: every reason comes with a next move, often one tap (switch flight, see cheapest, see trend).

## Try it

Open `Flymate.html` in a browser. No install, no login.

- Pick route, date (up to 3 months ahead), time of day, airline and the price you see.
- Live-style flight tracker, animated rain / temperature / wind map, fare calendar, price forecast, delay history, best-time heat map and a 7-day weather view.

## Data

All data in this demo is **simulated** with realistic patterns: afternoon storms and monsoon seasons, weekday and holiday fare demand, airline seat sales, and fares that rise from about 18 days before departure. The model and UI are built so real sources (historical fares, Open-Meteo weather, flight schedules) can replace the simulated values later.
