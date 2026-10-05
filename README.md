# poker-ml-tracker
A web-based Texas Hold'em poker platform powered by Machine Learning to analyze player behavior, detect bluffs, calculate win probabilities, and feature dynamic leaderboards for both winners and evaluated losers.

# Poker AI & Machine Learning Analytics Platform

An interactive web application that combines a fully functional Texas Hold'em poker game with machine learning capabilities. The system analyzes player behavior in real-time, calculates winning probabilities, detects bluffs, and tracks comprehensive performance metrics through dedicated leaderboards.

---

## 🚀 Features & Core Capabilities

- **Interactive Poker Engine:** A complete game loop handling blinds, betting rounds (Pre-flop, Flop, Turn, River), and hand evaluation.
- **Mathematical Probability Engine:** Real-time calculation of *outs* and win probabilities based on community and hole cards.
- **Machine Learning Behavioral Analysis:** Tracks player tendencies (aggression, fold rates, betting patterns) to identify behavioral profiles and detect bluffs.
- **Dual Ranking System (Leaderboards):**
  - **Winners Ranking:** Displays the names of winning players, their final scores, and the **total number of hands** played to achieve victory.
  - **Losers Evaluation Ranking:** Displays players who lost, their performance scores, and a **qualitative evaluation/grade** of their gameplay to help them improve.
- **Data Persistence:** Automatically saves match data and player histories to build a robust dataset for future model training.

---

## 🛠️ Proposed Development Roadmap

To ensure smooth delivery and robust architecture, this project is built in sequential phases:

1. **Phase 1: Core Game Structure & Rules**
   - Implement the deck handling, card dealing, and fundamental poker hand ranking rules (Pair, Flush, Straight, etc.).
2. **Phase 2: Mathematical Probability Engine**
   - Calculate pot odds, outs, and statistical winning odds dynamically during gameplay.
3. **Phase 3: Database & Score Integration**
   - Set up data persistence to record matches, player names, scores, and hand counts. Implement the dual ranking logic.
4. **Phase 4: Behavioral Machine Learning**
   - Train models to recognize player styles (e.g., tight, aggressive, loose) using historical action data.
5. **Phase 5: Advanced AI & Bluff Detection**
   - Implement predictive logic to spot bluffs and suggest optimal tactical decisions based on learned patterns.

---

## 🏆 Ranking & Scoring System Details

The platform features two distinct leaderboards to showcase different aspects of player performance:

1. **Winners Hall of Fame:**
   - **Data shown:** Player Name, Final Score, Hands Played.
   - **Purpose:** Highlights efficiency and dominance in winning matches.
2. **Improvement & Evaluation Board (Losers):**
   - **Data shown:** Player Name, Final Score, Comprehensive Game Evaluation Grade/Note.
   - **Purpose:** Provides constructive feedback and a grading metric on what went wrong during their gameplay.

---

## 💻 Recommended Tech Stack

- **Backend & ML:** Python (Flask/FastAPI, Scikit-Learn / TensorFlow, Pandas)
- **Frontend:** React, Vue, or Streamlit (for quick dashboard rendering)
- **Database:** PostgreSQL or SQLite

---
