## Overview

**Dexter** stands as the link connecting the immersive browser-based basketball simulation game, [Basketball-GM](https://play.basketball-gm.com/), with dozens of multiplayer leagues being run over Discord servers. In the realm of Basketball-GM, there is large, dedicated community which thrives on strategy, competition, and collaboration. The absence of a natural multiplayer feature within Basketball-GM is challenge for most. Dexter not only fills this void but elevates the multiplayer league experience to new heights.

![Dexter](/public/dexter-example.png)

Dexter empowers users to take control of their teams and engage with their leagues in unprecedented ways. From making real-time management decisions to interacting with league dynamics, Dexter transforms how players and managers alike participate in the game, ensuring a seamless, interactive, and enriched Basketball-GM experience.

### Features

- **Team Management Made Easy**
  - Access detailed **team information** including rosters, payroll, and players.
  - **Directly manage your team** with capabilities to make free agency offers, waive and trade players, and edit player positions.

- **Built-In Free Agency Algorithm**
  - Free Agency offers made by teams are placed into a weight-based algorithm that decides where players will sign based on various factors about the player, teams, and current state of the game.

- **In-depth Player Insights**
  - View comprehensive player information, encompassing statistical data and skills.

- **League Information on Demand**
  - Get up-to-date **league information**, including Luxury Tax and MLE (Mid-Level Exception) amounts, roster limits, and more.

---
### Tools for League Managers



Dexter isn't just for players. League Managers gain access to powerful tools designed to maintain the integrity and excitement of the league:

- **Custom Rulesets Enforcement:** Tailor the game to your league's preferences.
- **Efficient Transaction Processing:** Manage league transactions with ease.
- **Seamless League File Management:** Utilize **'Hephaestus'**, my private JSON API *(built with Fastify)*, to directly upload and generate download links for the latest league file.

---

## What it's composed of
- **Frameworks:** Node.js, Typescript
- **Database Management:** PostgreSQL
- **Caching Solution:** Redis
