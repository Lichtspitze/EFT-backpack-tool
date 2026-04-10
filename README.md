# Tarkov Backpack Value

Ranks every backpack in Escape from Tarkov by storage efficiency — slots per ruble — using live flea market data. Helps you figure out which backpack gives you the most inventory space for your money.

**[Live Demo →](https://lichtspitze.github.io/tarkov-backpack-tool)**


---

## What it does

- Pulls live backpack prices and stats from the [Tarkov.dev GraphQL API](https://tarkov.dev/api/)
- Calculates storage efficiency as slots per 10,000 ₽ for every backpack
- Compares flea market price vs. cheapest available barter trade side by side
- Visualises the top 20 most efficient backpacks in a bar chart
- Sortable table with full grid layout breakdown per backpack
- Toggle between 24h average price and last low price as the cost basis

## Tech

- Vanilla JS, HTML, CSS — no build step, no dependencies
- Tarkov.dev GraphQL API for live pricing and item data
- Chart.js for the bar chart visualisation
- Hosted on GitHub Pages

## Usage

Open the [live demo]([https://lichtspitze.github.io/tarkov-backpack-tool)](https://lichtspitze.github.io/tarkov-backpack-tool). Sort and filter the table to find the best backpack for your budget. Switch the price basis between 24h average and last low price depending on how you like to shop.

To run locally, clone the repo and open `index.html` in a browser — no server needed.

```bash
git clone https://github.com/lichtspitze/tarkov-backpack-tool.git
cd tarkov-backpack-tool
open index.html
```
