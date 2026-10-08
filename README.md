# GenCount

A modern, responsive, single-page web application featuring a dual-column workspace tailored for developers and content creators. The left side hosts a powerful **Username and Password/Passphrase Generator**, while the right side features a real-time **Character & Text Counter**.

## 🚀 Features

### 1. Left Column: Security Generators

- **Username Generator:**
  - _Random Word Mode:_ Generates random words from an offline dictionary, with options to capitalize and append random digits.
  - _Plus-Addressed Email Mode:_ Creates standard plus-addressed aliases (`local+suffix@domain.com`) based on a user-provided base email (defaults to `user@example.com`).
  - _Catch-All Email Mode:_ Generates a random local part against a specified domain (defaults to `example.com`).
- **Password & Passphrase Generator:**
  - _Random Password:_ Creates highly secure passwords using the Web Crypto API for randomness. Adjustable length (5–128 characters) with toggles for uppercase, lowercase, digits, and special characters. Includes an **Ambiguous Character Filter** to avoid visually similar characters (`l`, `1`, `O`, `0`). A live strength meter estimates entropy in bits.
  - _Memorable Passphrase:_ Builds human-readable passphrases from a built-in word list, with a slider for word count (3–20 words), custom separator, and optional capitalization.

### 2. Right Column: Text & Character Metrics

- **Live Analysis:** Updates all metrics in real time as you type or paste text.
- **Comprehensive Indicators:** Tracks characters, characters without spaces, words, sentences, lines, and paragraphs.
- **Reading Time Predictor:** Estimates reading time based on a standard 200 words-per-minute reading speed.

### 3. Integrated Enhancements

- **Theme Switcher:** Toggle between light and dark modes. The preference is saved in `localStorage` and respects the system preference on first visit.
- **SweetAlert2 Toasts:** Clipboard actions and errors are reported via non-intrusive toasts that adapt to the current theme.
- **Fully Responsive:** The layout stacks gracefully on mobile devices and expands to a two-column grid on larger screens.

## 🛠️ Technology Stack

- **HTML5** semantic structure
- **Bootstrap v5.3** for responsive layout and theming (CSS variables)
- **Bootstrap Icons v1.11.3**
- **SweetAlert2 v11** for toast notifications
- **Web Crypto API** for cryptographically secure random values
- No external API dependencies — all word lists and logic are bundled locally

## 💻 Quick Start & Deployment

This is a standalone, single-page application with no build step required.

1. Download or clone the repository.
2. Open `index.html` directly in any modern browser (Chrome, Firefox, Safari, Edge).
3. Alternatively, deploy the file to any static hosting service (GitHub Pages, Vercel, Netlify, Amazon S3, etc.).
