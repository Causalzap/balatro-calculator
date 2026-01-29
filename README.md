# 🃏 Balatro Calculator

<div align="center">

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![React](https://img.shields.io/badge/React-18-61DAFB?logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-5.0-646CFF?logo=vite&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/Tailwind-3.0-38B2AC?logo=tailwind-css&logoColor=white)

**The most accurate, drag-and-drop score predictor for Balatro.**
<br>
Maximize your Mult, optimize Joker placement, and conquer Ante 8.

[**🚀 Live Demo / 在线试用**](https://gamestrategyhub.com/)
</div>

---

## 📖 Introduction

**Balatro Calculator** is a precision tool designed for players who want to take the guesswork out of scoring. Unlike simple calculators, this engine accurately simulates the game's complex order of operations, specifically handling the interactions between **X Mult**, **Edition Bonuses**, and positional Jokers like *Blueprint* and *Brainstorm*.

Whether you are calculating a simple Flush or a game-breaking **Antimatter (6-slot)** build, this tool has you covered.

## ✨ Key Features

* **🎯 100% Accurate Math Engine:** Correctly processes the sequence: `Base Chips` -> `Add Chips` -> `Base Mult` -> `Add Mult` -> `X Mult` -> `Edition Bonuses`.
* **🖐️ Drag & Drop Interface:** Powered by `@dnd-kit`. Reorder Jokers instantly to see how placement affects your score (crucial for *Blueprint*).
* **🔓 Antimatter Ready:** The only calculator that supports unlocking the **6th Joker Slot** for endgame simulations.
* **🃏 Full Joker Database:** Includes data for 150+ Jokers with correct trigger types (Chips, Mult, X Mult).
* **💎 Edition Support:** Toggle **Foil** (+50 Chips), **Holographic** (+10 Mult), and **Polychrome** (X1.5 Mult) on any card.
* **📊 Smart Inputs:** Automatically detects Joker types. Manually adjust scaling values (e.g., *Campfire* or *Green Joker*).

## 📸 Screenshots

<div align="center">
  <h3>From Standard Run to Endgame</h3>
  <img src="public/screenshots/antimatter-score-comparison.jpg" alt="Balatro Score Comparison" width="800">
  <p><em>Unlocking the 6th slot with Antimatter doubles your score instantly.</em></p>
</div>

## 🛠️ Tech Stack

* **Framework:** React 18
* **Build Tool:** Vite
* **Styling:** Tailwind CSS
* **State Management:** React Hooks (`useReducer`)
* **Drag & Drop:** @dnd-kit/core & @dnd-kit/sortable
* **Icons:** Lucide React

## 🚀 Getting Started

To run this project locally:

1.  **Clone the repository**
    ```bash
    git clone [https://github.com/your-username/balatro-calculator.git](https://github.com/your-username/balatro-calculator.git)
    cd balatro-calculator
    ```

2.  **Install dependencies**
    ```bash
    npm install
    # or
    yarn install
    ```

3.  **Start development server**
    ```bash
    npm run dev
    ```

## 🤝 Contributing

Contributions are welcome! If you find a bug in the calculation logic or want to add new features (like Seed searching tools), feel free to open an issue or submit a Pull Request.

## 📄 License

This project is licensed under the MIT License.

---

<div align="center">
  <p>Built with ❤️ for the Balatro community.</p>
</div>
