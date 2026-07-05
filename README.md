# GenCount

A modern, responsive, single-page web application featuring a dual-column workspace tailored for developers and content creators. The left side hosts a powerful **Username and Password/Passphrase Generator** extracted from the main dashboard infrastructure, while the right side features a real-time **Character & Text Counter**.

## 🚀 Live Demo Features

### 1. Left Column: Security Generators

- **Username Generator:**
  - _Random Word Mode:_ Fetches random organic dictionary words with configuration options for capitalization and trailing numeric seeds.
  - _Plus Addressed Email Mode:_ Dynamically generates standard-compliant aliases (`user+suffix@domain.com`) for tracking source registrations.
  - _Catch-All Email Mode:_ Creates completely randomized prefixes targeted at a dedicated organizational domain name.
- **Password & Passphrase Generator:**
  - _Random Password:_ Generates highly secure cryptographically configured passwords with adjustable length up to **128 characters**. Fully filtered control over lowercase, uppercase, digits, and special characters, including an **Ambiguous Character Filter** to eliminate visual confusion (e.g., `l`, `1`, `O`, `0`).
  - _Memorable Passphrase:_ Constructs human-readable but highly secure combinations of random words bound together via custom delimiters using a responsive slider that scales from **3 to 20 words**.

### 2. Right Column: Text & Character Metrics

- **Live Analysis Input:** Tracks all textual adjustments instantly on character input strokes.
- **Comprehensive Indicators:** Evaluates character counts (with and without space definitions), precise word matching, standard sentence structure boundaries, and line-break metrics.
- **Reading Time Predictor:** Provides automated estimates of average content processing speeds based on universally certified standard reading baselines.

### 3. Integrated Enhancements

- **Theme Switcher:** Fluidly transitions between native system configurations via dedicated **Light and Dark modes**, adjusting standard backgrounds, field components, typography, and card panels.
- **SweetAlert2 Alerts:** Clipboard actions are processed via interactive UI toast frameworks instead of native system dialogs, delivering clean verification contexts and explicit error handling alerts if no value is generated.

---

## 🛠️ Technological Framework

The platform is designed as a standalone interface without requiring continuous compiling infrastructure:

- **Hypertext Framework:** HTML5 Semantic Structure
- **Visual Presentation Layout:** Bootstrap v5.3 (Native CSS Variables for responsive columns and component thematic modifications)
- **Icons Library:** Bootstrap Icons v1.11.3
- **Alert Layer Handling:** SweetAlert2 v11 JavaScript Injection Engine
- **Network Request Feeds:** Native JavaScript Fetch API linking directly to the [Random Word Database API](https://random-word-api.herokuapp.com/)

---

## 💻 Quick Start & Deployment

Since this suite is compiled within an optimized frontend single-page design architecture, deployment requires no build phase:

1. Clone or download the source directory containing the index file.
2. Launch the file (`index.html`) directly in any contemporary modern browser engine (Chrome, Safari, Edge, Firefox).
3. Alternatively, drop the file directly into static asset servers, Amazon S3 Buckets, GitHub Pages, or Vercel for instantly accessible global distribution.

---

## 📝 License

Distributed under the MIT License. See `LICENSE` inside the global project workspace repositories for additional data privacy and use terms.
