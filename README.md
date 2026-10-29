# India Post Web Portal – Usability Evaluation & Redesign Prototype

An academic Human-Computer Interaction (HCI) case study and interactive front-end prototype identifying usability friction points in the official India Post digital portal and proposing human-centered design solutions based on Nielsen’s 10 Usability Heuristics and WCAG 2.1 AA standards.

---

## 🔗 Live Prototype
- **Live Demo:** [https://<your-username>.github.io/<repository-name>/](https://<your-username>.github.io/<repository-name>/)
- **Coursework:** Human-Computer Interaction (HCI)

---

## 📌 Project Overview

The official India Post portal serves millions of citizens daily, handling core public services like consignment tracking, postage calculation, and pincode location. However, its existing interface presents several critical HCI challenges:
- High cognitive load caused by dense departmental news feeds and buried core utilities.
- Onerous math puzzle CAPTCHAs hindering fast consignment lookups.
- Cryptic technical transit codes (`NSH DPT`, `ICH SUB`) lacking user-friendly delivery context.
- Inconsistent accessibility support across varied devices and screen readers.

This repository hosts a functional, single-page prototype that resolves these issues with a modern, task-centric architecture.

---

## 🛠️ Key Usability & HCI Enhancements

| Feature / Fix | Usability Heuristic Addressed | Description |
| :--- | :--- | :--- |
| **Task-First Action Hub** | Heuristic #8: Aesthetic & Minimalist Design | Replaces clustered links with a quick 4-tab utility card (Track, Calculate, Pincode, Pickup). |
| **Frictionless Tracking** | Heuristic #5: Error Prevention | Eliminates arbitrary CAPTCHAs and adds inline 13-character formatting validation. |
| **Intuitive Delivery Pipeline** | Heuristic #1 & #2: Visibility of System Status | Converts backend logistics acronyms into a visual 4-stage tracking timeline. |
| **Universal Accessibility** | Heuristic #7: Flexibility & Efficiency of Use | Includes interactive high-contrast modes and direct font-scaling controls (WCAG 2.1 AA). |
| **Interactive HCI Inspector** | Heuristic Review Mode | Built-in inspection mode highlighting specific design decisions mapped to Nielsen's heuristics. |

---

## 💻 Tech Stack
- **HTML5** (Semantic structure & ARIA accessibility)
- **Tailwind CSS / Pure CSS3** (Responsive task cards and layout)
- **Vanilla JavaScript** (Dynamic status timeline, postage estimator logic, and heuristic overlay toggles)

---

## 🚀 How to Run Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/](https://github.com/)<your-username>/<repository-name>.git
