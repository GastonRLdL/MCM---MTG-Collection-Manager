# 🃏 MTG Collection Manager — Physical-Aware Deck Builder

> Turn your Magic: The Gathering collection into a searchable, physically organized system.

---

## 🚀 Overview

Managing a Magic: The Gathering collection is easy… until you actually need to **find your cards**.

This project solves a core problem MTG players face:

> “I know I have the card… but where is it?”

This app connects:

* 📋 Decklists (via Moxfield)
* 📦 Your real collection
* 🗂️ Physical locations (binders, boxes, deckboxes)

---

## 💡 Key Idea

Instead of just tracking cards, this system answers:

* ✅ Do I have this card?
* ❌ What am I missing?
* 🔁 Is it used in another deck?
* 📍 Where exactly is it physically?

Example:

```
Cyclonic Rift → Staples Blue Box → Divider Instant → Slot 12
Sol Ring → Commander Binder → Page 3
```

---

## ⚔️ Core Feature (MVP)

### Deck → Collection → Physical Location

1. Import a deck from Moxfield
2. Compare against your collection
3. See:

   * Available cards
   * Missing cards
   * Cards in use in other decks
4. Locate each card physically
5. Build your deck efficiently
6. Reserve cards to avoid conflicts

---

## 🧭 User Flow

```
Import Deck → Compare → Locate → Build → Reserve
```

This is the main loop of the application.

---

## 🧱 Features (Planned)

### 📥 Deck Import

* Moxfield URL
* CSV support

### 🗂️ Collection Management

* Card inventory
* Multiple copies
* Card conditions
* Tags and filtering

### 📦 Physical Location System

* Hierarchical structure:

  * Binder → Page → Slot
  * Box → Divider → Position
  * Deckbox

### ⚔️ Deck Comparison Engine

* Availability check
* Conflict detection
* Missing cards
* Purchase suggestions

### 🔍 Smart Search

* Find any card instantly
* See:

  * total copies
  * available copies
  * exact location
  * deck usage

---

## 🧠 Tech Stack (Planned)

### Frontend

* Next.js (React + TypeScript)
* TailwindCSS
* TanStack Table

### Backend

* FastAPI (Python)
* PostgreSQL
* SQLAlchemy

### Integrations

* Scryfall API (card data)
* Moxfield (deck import)

---

## 📱 Future Features

* 📷 Card scanner (OCR / camera)
* 📲 Mobile app / PWA
* 🧾 QR system for binders and boxes
* 🤖 Deck suggestions based on your collection
* 💰 Price tracking

---

## 🏗️ Project Status

🚧 **Currently in early development (MVP phase)**

* [x] Concept design
* [x] UX & flow definition
* [ ] Database schema
* [ ] Backend API
* [ ] Frontend prototype
* [ ] Moxfield integration

---

## 🎯 Vision

To become the **standard tool for managing physical MTG collections**, bridging the gap between digital deckbuilding and real-world card organization.

---

## 🤝 Why this matters

There are great tools for:

* deck building (Moxfield, Archidekt)
* collection tracking

But almost none solve:

> “Where is my card right now?”

This project does.

---

## 📬 Contact / Collaboration

If you're interested in:

* collaborating
* investing
* or using this tool early

Feel free to reach out.

---

## 🧙‍♂️ Built for players who have said:

> “I swear I have that card somewhere…”
