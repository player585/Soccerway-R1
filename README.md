# Soccerway R1

**v2.0.0** — Native live soccer scores for the Rabbit R1 (240x282).

![Soccerway R1 QR Code](qr-code.png)

**Live URL:** https://player585.github.io/Soccerway-R1/

## Install on R1

1. Scroll to **Creations** card
2. Tap **Create** → **Add via QR code**
3. Scan the QR code above

## What it shows

Native scoreboard for 22 soccer leagues worldwide:

**International:** World Cup, Club World Cup, FIFA Confederations Cup, Women's World Cup, Copa America, Gold Cup, UEFA Nations League, Euros

**Club:** UEFA Champions League, UEFA Europa League, Premier League, La Liga, Serie A, Bundesliga, Ligue 1, MLS, NWSL, Liga MX, Brasileirão, Argentine Primera, FA Cup, Carabao Cup

## Tabs

- **LIVE** — only in-progress matches with running minute counter
- **TODAY** — every match scheduled, live, or finished across all leagues
- **LEAGUES** — pick a single competition to focus on

## R1 Controls

| Input | Action |
|-------|--------|
| **Scroll Wheel** | Navigate match cards / leagues |
| **PTT Click** | Open match detail · cycle tabs when empty |
| **Long Press** | Refresh now |
| **Touch** | Tap any card, league, or tab |

In match detail: PTT or Escape goes back.

## Features

- **Auto-refresh** every 30 seconds with countdown timer in footer
- **Live count badge** on LIVE tab and in header
- **Team logos** from ESPN CDN
- **Live minute counter** (e.g. "50'") for in-progress matches
- **Winner highlighting** on completed matches
- **Match detail** shows kickoff time, venue, full team names, status

## Tech

- Single `index.html`, zero dependencies, zero build step
- Data from ESPN's free public Soccer API (no auth)
- Soccer-themed dark green palette with animated soccer ball logo
- Hosted free on GitHub Pages

## Keyboard (Browser Testing)

| Key | Action |
|-----|--------|
| Arrow Up/Down | Scroll wheel |
| Arrow Left/Right | Switch tabs |
| Enter/Space | PTT click |
| Escape/Backspace | Back / refresh |
