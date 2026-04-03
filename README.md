# Galaxy-web-app

---

# 🌌 Galaxy's World Interactive Birthday Web App

> A fully personalised, single-file interactive web application built as a birthday gift for my best friend Galaxy's 18th birthday. Every pixel, every word, every feature was made with love. 💕

---

## 📋 Project Overview

**Galaxy's World** is a custom-built progressive web app that functions as a personal universe for Galaxy — a space where she can find letters from me, play games, track her mood, manage her finances in London, watch Chiikawa episodes without leaving the app, and receive a full birthday surprise at exactly midnight on April 2nd.

The entire application is contained in a **single HTML file** with no backend, no framework, no build step. It runs entirely in the browser and saves all data locally using the Web Storage API.

---

## ✨ Features

### 🎂 Birthday Surprise System
- Full-screen animated birthday screen triggers automatically at **midnight on April 2nd**, even if the app is already open
- Three-tier animated CSS cake with flickering candle flames
- Confetti canvas animation with physics (gravity, rotation, multiple shapes)
- Birthday melody generated entirely with the **Web Audio API** (no audio files)
- Live **countdown timer** on the home screen counting days, hours, minutes and seconds to the next birthday

### 🏠 Home
- Dynamic greeting based on time of day
- Live **London GMT clock** updating every second
- Friendship day counter (since October 2024)
- Daily Wisdom quotes & affirmations with tap-to-refresh
- **London Idea of the Day**  15 curated London activity suggestions
- **"Secret Note from Mariama"**  6 deeply personal messages with prev/next navigation
- Kawaii mood picker (5 moods logged to history)
- Chiikawa episodes **embedded inline with YouTube IFrame**  watch without leaving the app

### 💌 Letters
- 12 unlockable letters from Mariama, revealed one by one
- Envelope reveal animation, personal content, open/close state persisted

### 🎮 Games (16 total)
Star Catcher · Quiz Time · Memory Match · This or That · Would You Rather · Word Search · Space Snake · Cosmic Riddles · Outfit Builder · Breathing Game · Emoji Story · Kawaii Hangman · Reaction Test · Word Jumble · Pixel Art · Truth Bombs · Kawaii Match-3

All games award ⭐ stars and feed into the XP/levelling system.

### 📸 Gallery
- Photo wall with **polaroid-style display** and FileReader API upload
- Friendship Journey timeline (8 milestones)
- Bucket List with completion tracking
- Watch Together list (films/anime to watch together)

### 🎵 Vibe
- Vinyl record player UI with 8-track playlist
- **Ambient sound engine** built with Web Audio API (rain, café, space, forest, fireplace, waves, white noise) — no audio files used
- Girls' Night Generator (50+ combinations)
- **Spotify Mood Playlists** Good Vibes, Lo-Fi, Girly Pop, UK Hits London
- **Colour of My Mood** 10 colour swatches each with a poetic meaning

### 🔮 Mystic
- Tarot card picker (22 Major Arcana)
- Zodiac horoscope for all 12 signs
- Oracle question/answer (30 mystical responses)
- Kiss-o-meter compatibility calculator
- Constellation drawing canvas

### 💎 Glow Up
- Vision Board (image upload)
- Mood Orbit 7-day history visualisation
- Era Tracker (Soft Life, That Girl, Dark Academia…)
- Glow Up Challenges with progress tracking
- Manifestation Journal

### ✅ Space (Todo)
- To-Do list, Goals tracker with progress bars
- Morning & Evening Routine builder
- Notes pad (autosave)
- Habit Tracker with daily streaks

### 🔒 Vault
- PIN-protected secret space
- Secret Diary, Manifestation Capsule, Dream Log
- Self-Care Emergency prompts

### 💄 Beauty
- Skincare step tracker (AM/PM) with daily streak
- Hair care log
- Period cycle log

### 💝 Love
- Love language quiz
- Date ideas generator (50+ ideas)
- Relationship affirmations

### 💰 Finance (London Edition)
- Income/expense tracker in **£ GBP**
- Categories including 🚇 Transport/Tube
- Savings goals with progress bars
- **Quick currency converter** — £ to FCFA, EUR, USD, GHS, NGN, MAD
- London-specific UI copy

### 👤 Profile / Me
- Avatar picker (20 emoji options)
- XP & levelling system (levels 1–20)
- Achievement grid (10 unlockable badges)
- Easter egg system (5 hidden triggers including Konami code)
- Stars economy connected to every action in the app

---

## 🛠️ Tech Stack

| Technology | Usage |

| HTML5 | Single-file app structure |
| CSS3 + TailwindCSS CDN | Styling, animations, responsive layout |
| Vanilla JavaScript (ES6+) | All logic, state, interactions |
| Canvas API | Star background, confetti, games, constellation drawing |
| Web Audio API | Ambient sounds, birthday melody |
| YouTube IFrame API | Inline video player (no redirect) |
| Web Storage API | localStorage (state), sessionStorage (session flags) |
| FileReader API | Photo and vision board image upload |
| Intl.DateTimeFormat API | London timezone clock |
| Google Fonts | Plus Jakarta Sans, Be Vietnam Pro |

**No frameworks. No build tools. No dependencies. No backend. One file.**

---

## 📁 File Structure

```
index.html          ← The entire application (HTML + CSS + JS, ~4100 lines)
```

That's it. One file. Open it in any browser.


## 🚀 How to Use

1. Download `index.html`
2. Open it in any modern browser (Chrome, Safari, Firefox)
3. Enter the name **Galaxy** and set a PIN
4. Or tap **"Continue as Galaxy (demo)"** to jump straight in

> Works fully offline. No internet required after first load (fonts load from Google CDN).


## 🎯 Project Stats

| Metric | Value |

| Total development time | 209 hours |
| Journal entries | 62 sessions |
| Development period | 02 Jan 2025 → 19 Feb 2025 |
| Lines of code | ~4,100 |
| Sections | 13 |
| Mini-games | 16 |
| Letters written | 12 |
| Secret notes | 6 |
| Affirmations | 20+ |
| Quotes | 15+ |
| Ambient sounds | 7 |
| Easter eggs | 5 |
| Achievements | 10 |

 💡 Technical Highlights

- **Zero-dependency ambient audio**  all 7 ambient sounds are generated procedurally using the Web Audio API oscillators, filters and noise buffers. No `.mp3` files, no external CDN.
- **Birthday midnight trigger**  a `setInterval` running every 30 seconds checks if the clock has just turned midnight on April 2nd and fires the full surprise screen, even if the app has been open since the night before.
- **Single-file architecture**  the entire app including all data, all game logic, all CSS, and all JavaScript fits in one `.html` file that can be shared via AirDrop, WhatsApp, or email.
- **Stars economy**  every meaningful action (logging a mood, completing a habit, opening a letter, winning a game, writing a journal entry) awards stars that convert to XP and unlock new levels and achievements.
- **YouTube embed**  Chiikawa episodes play inside the app using the YouTube IFrame API. No redirect, no new tab, no leaving the experience.

 🌸 Made With Love

Built by Mariama for **Galaxy**, because some people deserve a whole universe 🐰✨


© 2026 Mariama — Personal project, not for redistribution
