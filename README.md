````markdown
# Teleprompter v2.0.0 Instructions

Welcome to **Teleprompter v2.0.0**! This guide walks you through all the features and how to use them effectively.

---

## 📖 How It Works
This teleprompter is designed to mimic a **professional broadcast setup**.  
- As you read, a **blue highlight** moves from word to word at the speed you set.  
- You can add **pauses** in your script. For example:  

```text
[pause-3]
````

This will pause for **3 seconds** after the paragraph.

* The **yellow pause icon ❙❙** gives you a heads-up before the pause, and a **large countdown** will appear on screen.

👉 Keep your eyes on the **faint red line** at the top of the screen. The script scrolls automatically to keep the highlighted word aligned with that line, so you can read naturally without shifting your gaze.

---

## 🎛 Main Controls (Bottom Center)

* **Play/Pause (▶ / ❙❙)**
  Starts or stops the teleprompter.
  *(Tip: you can also click anywhere on the script text to play or pause.)*

* **Reset (↺)**
  Instantly stops the teleprompter and returns the script to the beginning.

* **Settings (⚙️)**
  Opens or closes the settings panel where you can customize your experience.

---

## ⏸ Inline Pauses

You can command the teleprompter to **pause automatically** within your script.

* **Syntax:**

  ```text
  [pause-X]
  ```

  Replace **X** with the number of seconds (e.g., `[pause-5]` or `[pause-0.5]`).

* **Visual Cue:**
  A yellow pause icon ❙❙ will appear next to the word before the pause.

* **Countdown:**
  When the script reaches the pause, a **large countdown timer** appears. The teleprompter resumes automatically when it hits zero.

---

## ⚙️ Settings Panel

* **Speed**
  Controls the reading pace.

  * `1.0x` = normal pace (~180 words per minute).

* **Font Size & Line Height**
  Adjust for larger text or more line spacing for readability.

* **Theme**
  Choose between:

  * **Dark**
  * **Light**
  * **High Contrast** (yellow/black)

* **Mirror Mode**
  Flips text horizontally for use with physical teleprompter mirrors.

* **Highlight Line**
  Toggles the **blue word-by-word highlight** on/off.

