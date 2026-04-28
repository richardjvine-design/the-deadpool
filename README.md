# ☠️ The Deadpool

A morbidly affectionate wager between friends. We rank, we predict, we wait. The closest forecaster takes the season.

![Dark Neon Theme](https://img.shields.io/badge/theme-dark%20neon-ff1f71) ![No Backend](https://img.shields.io/badge/backend-none-00f0ff) ![Just HTML](https://img.shields.io/badge/stack-single%20HTML%20file-a855f7)

## What Is This?

A single-page web app where a group of friends:

1. **Rank each other** in predicted order of death (1 = first to go)
2. **Predict departure years** for each person
3. **Place bets** with fake "Reaper Coins" on rank, date, or cause of death
4. **Give each other nicknames** — the person picks which one they want displayed
5. **Track standings** on a leaderboard

The death order is calculated as the **group average** of everyone's votes — more people vote, more accurate it gets.

## Features

- 🎨 **Dark neon aesthetic** with animated particle background
- 📸 **Camera/photo upload** — take a photo or pick from library (no URL pasting needed)
- 🗳️ **Vote-based ranking** — everyone ranks everyone, averages set the order
- 💰 **Reaper Coins economy** — 1,000 coins each, three bet types (Rank 3×, Date 5×, Cause 10×)
- 🏷️ **Nickname system** — suggest names for each other, pick your favourite
- 📝 **Famous Last Words** — everyone gets an epitaph quote
- 📱 **Mobile-first** — designed for passing around on a phone
- 💾 **Client-side storage** — data persists on device, no server needed

## How to Use

1. Download `deadpool.html`
2. Open it in any browser
3. Each person taps **"Update My Profile"**, selects themselves, fills in their details, and ranks everyone
4. Place bets on **The Register**
5. Check **Standings** to see who's winning

## Hosting

It's a single HTML file — host it anywhere:

- **GitHub Pages** — push to a repo, enable Pages, done
- **Netlify / Vercel** — drag and drop the file
- **Any web server** — just serve the HTML file
- **Local** — double-click to open in your browser

## Tech Stack

- Single HTML file (HTML + CSS + JS, no build step)
- Fonts: Syne, Outfit, JetBrains Mono (Google Fonts)
- Animated canvas particle background
- Client-side storage via browser localStorage / artifact storage
- No dependencies, no frameworks, no backend

## The Group

Pre-loaded with: Gav, Andy, Will, Miles, Jim, Rich

Add or remove members at any time through the app.

## License

This is a joke between friends. Do whatever you want with it.
