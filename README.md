# 🌱 Eco Exchange — Circular Economy & Barter Trading Platform

A community-driven, zero-currency C2C exchange platform engineered to reduce consumer waste by replacing monetary transactions with a peer-to-peer digital credit economy ("Eco Points").

🔗 **Live Application:** [[https://<your-username>.github.io/eco-exchange/](https://github.com/higazeoday9-cmd/eco-exchange.git)](https://<your-username>.github.io/eco-exchange/)

---

## 📌 Features

- **Peer-to-Peer Barter Marketplace:** Enrolled members can list pre-owned items, attach image assets via FileReader, and browse catalog offerings with dynamic DOM rendering.
- **Eco Points Incentive Model:** Users are rewarded 30 Eco Points upon publishing an item listing to incentivize circular economy participation.
- **Digital Eco Wallet System:** Dedicated wallet accounts with unique identifiers (`WALLET-<timestamp>`), balance queries, and peer-to-peer point transfers with balance validation.
- **Client-Side Data Persistence:** Built a persistent state layer utilizing the browser's `localStorage` API to serialize and manage user rosters, marketplace inventory, and wallet ledgers across browser sessions.
- **Business Architecture & Process Engineering:** Formulated full enterprise analysis models including Porter's 5 Forces, activity duration networks, and BPMN 2.0 transaction workflows covering C2C fulfillment and authentication protocols.

---

## 🛠️ Tech Stack & Methods

- **Frontend:** Semantic HTML5, Responsive CSS3 (Flexbox, Grid, CSS Keyframe Animations)
- **Scripting & State:** Vanilla JavaScript (ES6+), DOM Manipulation, Web Storage API (`localStorage`), FileReader API
- **Systems Analysis:** BPMN 2.0 Collaboration Diagrams, Porter's Five Forces Analysis, CPM/PERT Project Scheduling

---

## 📂 Project Structure

```text
├── index.html            # Landing page and platform value proposition
├── about.html            # Mission, vision, and sustainability principles
├── add-item.html         # Item submission form with Base64 image encoding
├── browse-items.html     # Dynamic marketplace gallery populated from localStorage
├── sign-in.html          # Authentication portal and local user session manager
├── wallet.html           # Ledger console for balance tracking and point transfers
├── styles.css            # Global shared responsive stylesheets
└── docs/                 # Systems analysis documentation and BPMN schematics
