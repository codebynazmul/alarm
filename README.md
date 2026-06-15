# AlarmFlow ⏰

AlarmFlow is a sleek, premium, iOS-inspired web alarm clock application designed with a focus on smooth interactions, crisp typography, and high performance. It includes dynamic real-time clock monitoring, multi-sound custom synthesizers, and complete state persistence.

Live Project Link: [Your Hosted Link Here] (e.g., GitHub Pages)

---

## 📱 Features

* **Real-Time Dynamic Clock:** Implements a localized, ultra-precise current time display, complete with independent tracking for seconds and fully optimized layout responsiveness to prevent layout shifts.
* **Web Audio API Sound Engine:** Leverages raw custom-synthesized tones (`Beep`, `Digital`, `Chime`, `Pulse`) built completely on oscillator nodes—no external audio files or asset latency required.
* **Persistent Local Storage:** All created alarms, repeating schedules, and custom labels automatically save directly to the client's browser session.
* **Flexible Repeating Schedules:** Supports specific-day triggers (e.g., Mon, Wed, Fri), daily alarms, or single-use tasks that automatically switch off after firing.
* **Built-in Snooze Functionality:** Includes an intelligent 5-minute snooze window modifier that generates safe temporary tracking intervals.
* **iOS-Style Micro-Interactions:** Features high-fidelity interactive visual states, an expanding soundwave ringing visual overlay, adaptive swipe-ready heights, and custom custom-toggle inputs.

---

## 🛠️ Tech Stack & Architecture

* **Frontend Structure:** Semantic HTML5 Markup.
* **Styling Engine:** Vanilla CSS3 utilizing CSS Custom Properties (Variables) for color-theming, flexbox layouts, CSS keyframes for spatial bell animations, and modern viewport units (`100dvh`).
* **Core Logic:** Pure Modern Vanilla JavaScript (ES6+).
* **Audio Engine:** HTML5 Web Audio API (`AudioContext`).
* **Data Management:** LocalStorage API for lightweight state preservation.

---

## 🚀 Getting Started

Since AlarmFlow is built purely with native web technologies, there are no dependency trees to download or local build pipelines to run.

### Running Locally
1. Clone the repository down to your machine:
   ```bash
   git clone [https://github.com/YOUR_GITHUB_USERNAME/AlarmFlow.git](https://github.com/YOUR_GITHUB_USERNAME/AlarmFlow.git)
