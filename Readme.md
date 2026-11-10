# ⚔️ PyQuest: Chronicles of Python

[![Python 3 in Browser](https://img.shields.io/badge/Python-3.x%20via%20Skulpt-3776AB?logo=python&logoColor=white)](https://skulpt.org/)
[![Platform: Web & Mobile](https://img.shields.io/badge/Platform-Web%20%7C%20Mobile-blueviolet)](#)
[![Zero Dependencies](https://img.shields.io/badge/Build-Single%20HTML%20File-success)](#)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

> Master Python 3 from the ground up through a retro, turn-based fantasy RPG playable entirely in your web browser.

---

## 🌟 Overview

**PyQuest: Chronicles of Python** transforms the Python learning journey into a turn-based role-playing game. Players take on the mantle of an apprentice wizard in the realm of Bytehaven, using real Python code as magical incantations to battle logic monsters, unlock elemental synergies, and master core programming principles.

There are no simulated question prompts or multiple-choice quizzes: **damage is dealt strictly by executing valid, working Python code** compiled in-browser via the Skulpt Python 3 engine.

---

## 🎮 Key Features

- **50-Quest Curriculum across 5 Epic Acts**:
  - **Act I: Whispering Woods** (Quests 1–10): `print()`, types (`int`, `float`), arithmetic, modulo `%`, string manipulation (`.upper()`, `.strip()`), string formatting (`f-strings`), type casting.
  - **Act II: Swamp of Logic** (Quests 11–20): Booleans, relational operators, `if` / `elif` / `else` ladders, logical gates (`and`, `or`, `not`), membership testing (`in`), ternary expressions.
  - **Act III: Spire of Iteration** (Quests 21–30): `while` loops, countdowns, `break` / `continue` flow control, `for` loops, `range(start, stop, step)`, accumulator patterns, nested loops.
  - **Act IV: Vault of Data Structures** (Quests 31–40): Lists (`.append()`, `.pop()`, slicing `[start:stop]`, negative indices), tuples & unpacking, dictionaries & `.get()`, sets & deduplication, list comprehensions.
  - **Act V: Citadel of Masters** (Quests 41–50): Custom functions (`def` & `return`), positional & keyword parameters, default arguments, variable scope, lambda expressions, `.split()` / `.join()`, `try` / `except` error handling, object-oriented classes (`__init__`), and the Final Byte Dragon boss.

- **Elemental Affinity & Critical Strike System**:
  - Monsters have unique affinities (**Pyro 🔥**, **Cryo ❄️**, **Electro ⚡**, **Arcane 🌌**) with explicit weaknesses (1.5x damage) and resistances (0.75x damage).
  - Writing **idiomatic Python** (e.g., list comprehensions, `f-strings`, `.get()`, built-in accumulators like `sum()`) triggers a **2.0x Pythonic Critical Strike** with gold bonuses and particle effects.

- **Pedagogical Safety Net (2-Attempt Scroll Reveal)**:
  - If an apprentice fails an encounter twice, the **Ancient Scroll of Truth** unrolls with the working solution and an **Auto-Inscribe** button so players never get permanently stuck.

- **Mobile-First Design**:
  - Horizontal quick-syntax touch ribbon (`Tab`, `:`, `()`, `[]`, `{}`, quotes, operators, `def`, `print()`) designed with non-blurring event handlers so typing code on mobile keyboards is seamless.
  - Fixed 16px input font size to eliminate iOS Safari viewport auto-zoom quirks.

- **8-Bit Web Audio Synthesizer**:
  - Dynamically synthesizes chimes, elemental slashes, crits, and fizzle sounds via the browser's native Web Audio API—no heavy audio files to download. Includes a header volume slider and mute toggle.

- **Zero External Dependencies**:
  - Entire application engine, UI, styles, and audio run directly in any modern browser without local server requirements or installation steps.

---

## 🕹️ Controls & Interface

| Section | Description |
| :--- | :--- |
| **World Map (`🗺️`)** | Select quest chapters (Acts I–V) and launch combat encounters. Completed quests are tagged green and can be replayed at will. |
| **Combat Arena (`⚔️`)** | Displays the monster sprite, animated canvas particle effects, target weaknesses, and real-time HP bars. |
| **Tome of Wisdom** | Provides the computer science concept, syntax blueprint, objective instructions, and Pythonic Mastery tips for the active trial. |
| **Grimoire Editor** | The in-browser code editor. Supports standard keyboard typing and the mobile quick-syntax toolbar. |
| **Terminal Output** | Live runtime output window showing standard Python output (`stdout`), syntax errors, and combat feedback. |
| **Bytehaven Inn (`🍺`)** | Spend gold looted from monsters to rest, recover hit points, and prepare for future boss fights. |

---

## 🛠️ Built With

- **HTML5 & CSS3** (Responsive flexbox, CSS custom properties, grid layouts)
- **Vanilla JavaScript (ES6+)** (Game state machine, particle engine, local storage persistence)
- **[Skulpt](https://skulpt.org/)** (Client-side, browser-based Python 3 compilation)
- **Web Audio API** (Procedurally synthesized 8-bit sound effects)

---

## 📄 License

This project is licensed under the [MIT License](LICENSE) — feel free to modify, extend, and share it for educational and non-commercial purposes.