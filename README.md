# 🎰 Loto Predictor AI v4

A sophisticated, mobile-first Web Application (PWA) designed for statistical analysis and advanced generation of lottery combinations (specifically optimized for 6/49 systems). 

This project demonstrates the practical application of **probabilistic algorithms**, **local data persistence**, and **modern UI/UX principles** without the need for a complex backend.

---

## 🚀 Core Features

- **Triple-Mode Generation Engine:**
  - **Random Balanced:** Generates variants based on the "Bell Curve" sum theory (115-185).
  - **Sector Distribution:** Ensures an even spread across the ticket grid (Low, Mid, and High number ranges) to avoid clustering.
  - **AI Hot/Cold Logic:** A strategic algorithm that picks numbers based on historical frequency (3 Hot + 2 Cold + 1 Random).
- **Dynamic Data Analysis:**
  - Users can manually input official draw results.
  - The app automatically recalculates the frequency and latency of all 49 numbers in real-time.
- **Automated Verification:** - Cross-references saved history with official results, highlighting winning numbers with visual cues.
- **PWA Ready:** Fully responsive design, optimized to be "Added to Home Screen" on iOS and Android for a native app feel.
- **Privacy-Centric:** All data is stored locally via `localStorage`. No personal data ever leaves the device.

## 🛠️ Technical Stack

- **Frontend:** HTML5, CSS3 (Tailwind CSS)
- **Logic:** Vanilla JavaScript (ES6+)
- **Storage:** Web Storage API (localStorage)
- **Deployment:** GitHub Pages

## 🧠 The Algorithm Behind the "Predictions"

Unlike "magic" number generators, this app focuses on **Hazard Organization**. It filters out mathematically improbable combinations (e.g., all even numbers, or sums under 50) and favors "balanced" variants that mirror real-world lottery draw patterns.

The **Hot/Cold** engine tracks the "weights" of numbers, allowing users to apply a data-driven approach to their intuition-based picks.

## 📦 How to Use

1. **Clone the repo:** `git clone https://github.com/YOUR_USERNAME/loto-predictor-ai.git`
2. **Open `index.html`** in any modern browser.
3. **On Mobile:** Open the live link and select "Add to Home Screen" for the full experience.

---

*Disclaimer: This is a statistical tool and does not guarantee financial winnings. Play responsibly.*
