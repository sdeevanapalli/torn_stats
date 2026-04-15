# Torn Stats — Compounding Gains Simulator

A single-page tool that models daily battle-stat growth in [Torn](https://www.torn.com) using a compound-interest simulation. Adjust your parameters and watch projections update live.

## Features

- **Live simulation** — charts your stat trajectory day-by-day
- **Key inputs** — starting stat, gym dots, starting happy, energy per day, milestone target
- **Faction perks** — collapsible breakdown of primary/secondary perk bonuses
- **Torn API integration** — enter a limited-access API key to auto-fill your current stats

## Usage

Just open `index.html` in any browser — no build step, no dependencies beyond a CDN-loaded Chart.js.

## Parameters

| Input | Description |
|---|---|
| Starting Stat | Your current battle stat value |
| Gym Dots | Your gym's dot rating (1–10) |
| Starting Happy | Happy at the start of each training session |
| Energy Per Day | Total energy spent training daily |
| Milestone Target | Stat value you're aiming to reach |
| Faction Perks | Per-stat bonus percentages from your faction |
