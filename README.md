# 🛡️ AI Password Strength Checker

An advanced password validator that uses **Shannon Entropy** and **Heuristic Logic** to evaluate password security beyond simple character rules.

## ✨ Features
- **Entropy Analysis:** Calculates bits of randomness to determine brute-force resistance.
- **Pattern Detection:** Identifies keyboard walks (e.g., `qwerty`) and common sequences.
- **Visual Feedback:** Color-coded strength bars and real-time security insights.
- **Modern UI:** Built with Tailwind CSS and Lucide icons.

## 🚀 Quick Start
1. Clone this repo.
2. Run `npm install`.
3. Run `npm start` to view the app at `localhost:3000`.

## 🧠 How it Works
The engine scores passwords based on their mathematical complexity ($L \cdot \log_2(R)$) and then applies penalties for common human-created patterns that hackers exploit.
