# School Cafeteria PIN Practice Pad

An interactive, browser-based simulator replicating the physical 12-key PIN pads commonly used in elementary school lunchrooms (such as Horizon / InVision POS terminals). 

Built to help kindergarten and early elementary students build the tactile familiarity and muscle memory needed to enter their 4-digit student lunch ID quickly and confidently in the lunch line.

---

## Features

- **Exact Cafeteria Layout:** Mimics the inverted 10-key arrangement (`7 8 9` on top, `1 2 3` below, with bottom-corner **CLEAR** and **ENTER** keys).
- **Realistic Audio & Haptic Cues:** Uses the Web Audio API to produce mechanical beeps on keystrokes, success chimes, error buzzes, and mobile vibration feedback without requiring external media files.
- **Client-Side Privacy:** Each family sets their child’s 4-digit lunch number locally via the **Set PIN** button. PINs are stored strictly on the user’s local browser (`localStorage`) and are never sent to a server or tracked.
- **Cross-Platform & Zero Install:** Runs out of the box on iOS Safari and Android Chrome, with support for fullscreen "Add to Home Screen" app-like launching.

---

## Quick Start for Parents

1. Open the [live practice pad](https://<your-username>.github.io/<repo-name>/) in Safari (iOS) or Chrome (Android).
2. Tap the **Set PIN** button at the bottom and enter your child's 4-digit lunch code.
3. Have your child practice:
   - Entering their 4 digits using their index finger.
   - Using the red **CLEAR** button to reset if they hit an incorrect number.
   - Hitting the green **ENTER** button to submit.

### Add to Home Screen (Recommended)

- **iPhone / iPad:** Tap the **Share** button in Safari $\rightarrow$ scroll down and select **Add to Home Screen** $\rightarrow$ tap **Add**.
- **Android:** Tap the **three dots (⋮)** in Chrome $\rightarrow$ select **Add to Home screen** (or **Install app**).

---

## Author

Created by **Ganesh Arjunan** for school parents and young learners.
