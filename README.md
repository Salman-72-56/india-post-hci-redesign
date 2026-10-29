# India Post Portal – HCI Case Study & Front-End Redesign Prototype

An academic Human-Computer Interaction (HCI) usability evaluation and functional front-end redesign prototype addressing cognitive friction, layout clutter, and accessibility issues on the official India Post digital web portal.

---

## 🌐 Live Prototype & Links

- **Live Interactive Website:** [https://salman-72-56.github.io/india-post-hci-redesign/](https://salman-72-56.github.io/india-post-hci-redesign/)
- **GitHub Repository:** [https://github.com/Salman-72-56/india-post-hci-redesign](https://github.com/Salman-72-56/india-post-hci-redesign)
- **Coursework:** Human-Computer Interaction (HCI)
- **Author:** MD Salman

---

## 📌 Problem Statement & HCI Background

The official India Post portal handles essential public utility services for millions of daily visitors, including consignment tracking, postage calculation, and pincode lookups. However, a heuristic evaluation reveals several systemic usability flaws:

1. **High Cognitive Overhead (Heuristic #8 - Aesthetic & Minimalist Design):** The default landing page prioritizes internal departmental bulletins, tenders, and dense multi-level navigation trees over the top core actions users visit the site to perform.
2. **Excessive Interaction Friction (Heuristic #5 - Error Prevention):** Tracking simple packages requires solving arithmetic CAPTCHAs, creating barriers for elderly users, people with cognitive impairments, or users on mobile devices.
3. **Cryptic System Terminology (Heuristic #1 & #2 - Visibility of System Status / Match with Real World):** Tracking logs display internal backend transit acronyms (such as `NSH DPT`, `ICH SUB`) without human-readable transit explanations.
4. **Suboptimal Accessibility Compliance:** Inadequate contrast ratios and limited responsive viewport optimization create barriers for screen-reader and low-vision accessibility.

---

## 🚀 Key Usability Solutions Implemented

This prototype addresses the core usability issues through a clean, single-page, task-first interface:

| Feature / UI Component | Usability Heuristic Addressed | Design Fix & Implementation |
| :--- | :--- | :--- |
| **Task-First Action Hub** | **#8: Minimalist Design** | Replaces buried navigation links with an instant 4-tab utility console for primary tasks: *Track Consignment, Calculate Postage, Find Pincode, and Request Pickup*. |
| **Frictionless Tracking Engine** | **#5: Error Prevention** | Eliminates obstructive CAPTCHA puzzles; incorporates inline 13-character validation with one-click test numbers for demoing delivery states. |
| **Visual Delivery Pipeline** | **#1 & #2: Visibility of Status** | Replaces technical backend logistics codes with an intuitive 4-stage visual timeline (Booked → Dispatched → In Transit → Out for Delivery). |
| **Dynamic Postage Calculator** | **#6: Recognition over Recall** | Provides real-time rate estimation based on destination type and package weight with immediate breakdown cards. |
| **Universal Accessibility (WCAG 2.1 AA)** | **#7: Flexibility & Efficiency** | Features built-in font-size scaling (`A-`, `A`, `A+`), high-contrast vision mode, and multi-language support toggles. |
| **Interactive HCI Inspector** | **Heuristic Review Mode** | Built-in inspection mode highlighting specific design decisions mapped directly to Nielsen's Usability Heuristics. |

---

## 💻 Tech Stack & Architecture

- **HTML5:** Semantic document outline with accessible ARIA tags and landmark regions.
- **Tailwind CSS / Pure CSS3:** Responsive grid layouts, modern typography hierarchy, and custom dark/high-contrast styling.
- **Vanilla JavaScript (ES6+):** Client-side tab switching, interactive consignment status generation, dynamic postage calculation, and heuristic overlay toggles. Zero heavy external dependencies.

---

## 🛠️ How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Salman-72-56/india-post-hci-redesign.git](https://github.com/Salman-72-56/india-post-hci-redesign.git)
