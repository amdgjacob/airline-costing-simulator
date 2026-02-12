# ✈️ Airline Costing Simulator

An interactive web app that demonstrates how cost allocation decisions impact route profitability in the airline industry. Inspired by a Harvard Business School case study discussed in the Internal Information for Strategic Decisions course at Chicago Booth.

**🔗 Live Demo:** [airline-costing-simulator.netlify.app](https://airline-costing-simulator.netlify.app/)

## Features

- **Dashboard with Key Metrics** — Revenue, Variable Direct Costs, Overhead Costs, Net Income, and Profit Margin
- **Real-time Route Toggling** — Add or remove routes and instantly observe % changes in revenue, costs, and margin
- **Per-Route Visualization** — View direct and overhead cost split, revenue, and profit/loss for each individual route
- **Customizable Cost Behavior** — Adjust the percentage mix of variable vs. fixed overhead costs to see how allocation assumptions change profitability
- **The Death Spiral** — Demonstrates how dropping "unprofitable" routes causes fixed costs to be reallocated, potentially making remaining routes appear unprofitable too

## Tech Stack

- React + TypeScript
- Vite
- Tailwind CSS
- Recharts

## Getting Started

```bash
npm install
npm run dev
```

## License

MIT
