# 🐬 Frankston Dolphins – Netball Rotation App

A game-day rotation tool for the Frankston Dolphins Under 13s netball team. Built to make quarter breaks fast and stress-free — see who plays where, who hands their bib to who, and manage last-minute changes on the fly.

---

## 📋 Table of Contents

- [Getting Started](#getting-started)
- [Navigating the App](#navigating-the-app)
- [The Three Views](#the-three-views)
  - [Overview](#-overview)
  - [By Quarter](#-by-quarter)
  - [Bib Handoffs](#-bib-handoffs)
- [Highlighting a Player](#highlighting-a-player)
- [Sharing the Rotation](#sharing-the-rotation)
- [Managing Absent Players](#managing-absent-players)
- [Editing Positions](#editing-positions)
- [Lock & Unlock](#lock--unlock)
- [Tips for Game Day](#tips-for-game-day)

---

## Getting Started

Open the app in any web browser on your phone, tablet or computer:

```
[https://your-netlify-url.netlify.app](https://dolphins-rotation.netlify.app/)
```

The app will automatically jump to **today's game**. If today isn't a game day, it will show the **next upcoming game** in the season. You can always tap any other date manually.

No login required for parents — just open and view. Editing is protected by a password (see [Lock & Unlock](#lock--unlock)).

---

## Navigating the App

### Selecting a Game Week

At the top of the screen is a row of **date buttons** — one for each game in the season. Swipe left or right to find a date, then tap it to load that week's rotation.

> 💡 The app opens on today's game automatically, so on game day you shouldn't need to tap anything.

### The Three Tabs

Below the date row are three tabs that switch between different views of the same rotation data:

| Tab | What it shows |
|-----|--------------|
| 🗓 Overview | All 4 quarters side by side in one table |
| 📍 By Quarter | One quarter at a time as large bib cards |
| 🔄 Bib Handoffs | Who passes their bib to who between quarters |

---

## The Three Views

### 🗓 Overview

Shows the **full game at a glance** — all 7 positions across all 4 quarters in a single table, plus who's on the bench each quarter.

- On **desktop/tablet**: shown as a table with columns for Q1, Q2, Q3 and Q4
- On **mobile**: shown as four stacked cards, one per quarter, for easy reading on a small screen

Use this view before the game to get a full picture of the rotation plan, or to quickly check what's coming up next.

---

### 📍 By Quarter

Shows **one quarter at a time** as large bib cards — one card per position showing the position name and the player assigned to it.

Tap **Q1, Q2, Q3 or Q4** to switch between quarters. The bench players for that quarter are listed at the bottom.

> 💡 This is the most useful view **during the game** — flick to the next quarter just before the break to see exactly who goes where.

---

### 🔄 Bib Handoffs

Shows **who hands their bib to who** at each quarter break.

Tap the transition you're about to make:
- **Q1 → Q2**
- **Q2 → Q3**
- **Q3 → Q4**

Each row shows one bib with an arrow:

```
Tyla          GS  →  Georgie S
(Q1 holder)  bib    (Q2 holder)
```

- **Pass** — one player hands their bib to another
- **Keeps** — the same player stays in that position, no handoff needed
- The **Coming on / Going off** bar at the top shows which players are rotating to/from the bench that quarter

> 💡 This is the fastest way to sort out the chaos at quarter time — every player just finds their name on the left and knows who to hand to on the right.

---

## Highlighting a Player

Tap the **★ Highlight a player** button in the header to pick a player whose name will be highlighted in red throughout every view — great for a parent who wants to easily track their own child across the rotation.

- The highlight is saved in your browser, so it persists when you reopen the app
- Tap the button again to change or remove the highlight
- Each person using the app can set their own highlight independently

---

## Sharing the Rotation

Tap the **⬆ Share this week's rotation** button at the bottom of the Overview tab.

You'll get two options:

**📋 Copy text** — copies a plain-text summary of the full rotation to your clipboard. Paste it directly into WhatsApp, a group chat, email or anywhere else. Great for sharing with parents before game day.

Example:
```
🐬 FRANKSTON DOLPHINS — 14 Mar 2026
Under 13s · Winter 2026
──────────────────────────────────────
POS   Q1          Q2          Q3          Q4
──────────────────────────────────────
GS    Tyla        Tyla        Billie      Josie
GA    Georgie F   Georgie F   Sadie       Georgie F
...
```

**🖼 Open image** — generates a branded image card of the rotation and opens it in a new tab. Long-press the image to save it to your photos, then share it anywhere.

---

## Managing Absent Players

If a player can't make it to a game, you can mark them as absent so their positions are clearly flagged and easy to reassign.

> ⚠️ You need to be **unlocked** to manage absences. See [Lock & Unlock](#lock--unlock).

### Marking a Player Absent

1. Unlock the app with the password
2. Tap **⚠ Absences** in the header
3. Find the player in the list and tap **Mark absent**
4. Tap **Done**

### What Happens Next

- An **amber banner** appears at the top of the Overview showing who's absent
- Every position that player was scheduled for shows an amber **✕** across all views
- A **positions need filling** panel appears listing every affected quarter and position
- Each gap has a dropdown showing available players — select one to fill that slot

### Removing an Absence

- Tap **⚠ Absences** → tap **✓ Absent** next to the player to unmark them
- Or tap the **×** on the amber chip in the absent banner

> 💡 Absences only apply to the currently selected game week — they won't carry over to other weeks.

---

## Editing Positions

If a last-minute change needs to be made to the rotation:

1. Unlock the app (see below)
2. Tap any player name in the **Overview** or **By Quarter** view
3. A picker will appear showing all players — tap the correct player
4. Tap **Save**

Changes are saved automatically in your browser.

---

## Lock & Unlock

The app is **locked by default** so parents can view the rotation but can't accidentally (or intentionally!) change anything.

### Unlocking

1. Tap the 🔒 **padlock icon** in the header
2. Enter the password: `Dolphins2026`
3. The padlock changes to 🔓 and editing is enabled

### Locking

- Tap the 🔓 padlock again to lock immediately
- The app **automatically locks** after **60 minutes** of inactivity
- The app **always starts locked** — unlocked state does not persist between sessions

> 🔐 Share the password only with the coach and team manager.

---

## Tips for Game Day

- **Before the game** — open Overview to check the full rotation plan and share it with parents via the Share button
- **During the game** — keep the app on the **By Quarter** tab, flick to the next quarter a few minutes before the break
- **At quarter time** — switch to **Bib Handoffs** and call out each row so players know who to find
- **If someone's missing** — unlock, tap Absences, mark them absent, and use the gap filler to reassign their positions before the game starts
- **Highlighting** — parents can tap ★ Highlight to follow their child through the rotation without needing to scan the whole table

---

## Season Details

| | |
|---|---|
| **Team** | Frankston Dolphins |
| **Division** | Under 13s |
| **Season** | Winter 2026 |
| **Games** | 14 Mar – 22 Aug 2026 |
| **Players** | Tyla, Josie, Georgie F, Sadie, Billie, Georgie S, Ava, Penny, Stella, Tora |

---

*Built with ❤️ for the Frankston Dolphins. For technical changes or updates, contact the team manager.*
