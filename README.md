# Soccerway R1

**v1.0.0** — Live soccer scores from [Soccerway](https://us.soccerway.com/), wrapped for the Rabbit R1 (240x282).

![Soccerway R1 QR Code](qr-code.png)

**Live URL:** https://player585.github.io/Soccerway-R1/

## Install on R1

1. Scroll to **Creations** card
2. Tap **Create** → **Add via QR code**
3. Scan the QR code above

## Features

- **6 Quick Tabs** — Live, Matches, Leagues, News, Teams, Players
- **Iframe scaling** — 4 zoom levels for readable content on the small screen
- **Soccer aesthetic** — Dark green palette, animated soccer ball logo, live indicator
- **Dual scroll modes** — TAB mode (scroll = cycle tabs) or PAGE mode (scroll = scroll page)
- **Loading feedback** — Spinning soccer ball overlay while pages load

## R1 Controls

| Input | Action |
|-------|--------|
| **Scroll Wheel** | TAB mode: cycle tabs · PAGE mode: scroll page |
| **PTT Click** | Toggle scroll mode (Tab ↔ Page) |
| **Long Press** | Cycle zoom level (Default → Actual → Wide → Extra Wide) |
| **Touch** | Native scroll inside the page, tap any link or button |
| **Double-tap header** | Show help overlay |

## Tabs

| Tab | URL |
|-----|-----|
| LIVE    | us.soccerway.com (live scores home) |
| MATCHES | us.soccerway.com/matches/ |
| LEAGUES | us.soccerway.com/competitions/ |
| NEWS    | us.soccerway.com/news/ |
| TEAMS   | us.soccerway.com/teams/ |
| PLAYERS | us.soccerway.com/players/ |

## Tips

- First load shows a privacy/cookie banner — tap **I Accept** once and it remembers
- Use **touch** to scroll inside the iframe — it's the most reliable scroll method
- Switch to **PAGE mode** with PTT if you want the scroll wheel to scroll instead of cycle tabs
- The **Wide / Extra Wide** zoom levels let you see desktop-style content scaled down

## Keyboard (Browser Testing)

| Key | Action |
|-----|--------|
| Arrow Up/Down | Scroll wheel |
| Arrow Left/Right | Jump tab |
| Enter/Space | PTT click |
| Escape/Backspace | Long press (zoom cycle) |
| ? | Toggle help |

## Tech

- Single `index.html`, zero dependencies, zero build step
- Wraps Soccerway in an iframe with CSS `transform: scale()` for fit
- R1 hardware events: `scrollUp`, `scrollDown`, `sideClick`, `longPressStart`
- Hosted free on GitHub Pages
