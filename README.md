# 🔥 BARBAADI.COM — Ministry of Barbaadi 📜

> **Officially ruin your friends' reputations.**  
> Generate high-quality, totally fake, and 100% hilarious certificates for their everyday crimes, bad habits, and epic fails.

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub Stars](https://img.shields.io/github/stars/bhanu2006-24/barbaadi?style=social)](https://github.com/bhanu2006-24/barbaadi)
[![GitHub Forks](https://img.shields.io/github/forks/bhanu2006-24/barbaadi?style=social)](https://github.com/bhanu2006-24/barbaadi)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/bhanu2006-24/barbaadi/pulls)
[![Made with Chai](https://img.shields.io/badge/Made%20with-☕%20%26%20Sarcasm-orange.svg)](#)

---

## 🚀 Live Demo & Repository

- **GitHub Repository**: [https://github.com/bhanu2006-24/barbaadi](https://github.com/bhanu2006-24/barbaadi)
- **Live Website**: Available via GitHub Pages or simply by opening `index.html` in your browser!

---

## ✨ Features

- 🖼️ **Crystal-Clear Ultra-HD PNG Export (3X Scale)**: Download high-resolution uncompressed PNG images (2700 × 1950 px) ready for WhatsApp, Instagram Stories, Snapchat, and Twitter. No stretching, zero clipping!
- 📄 **Print-Ready A4 Landscape PDF**: One-click download of crisp, vector-proportional A4 PDF certificates suitable for framing or gifting.
- 📋 **Copy to Clipboard (One-Click)**: Copy the certificate image directly to your clipboard to paste into WhatsApp Web, Discord, Telegram, or Slack instantly.
- 🎨 **6 Distinct Visual Themes (Vibes)**:
  - 🧨 **Classic Barbaadi** — Vintage Parchment, Deep Crimson & Amber
  - 🐍 **Toxic Popat** — Toxic Neon Green & Poison Olive
  - 👑 **Royal Dhokha** — Majestic Purple & Gold
  - 🥶 **Berozgar Blue** — Chilled Ice Blue & Deep Slate
  - 🎀 **Panauti Pink** — Vibrant Hot Pink & Rose
  - ⚠️ **Chhapri Alert** — High-Contrast Caution Yellow & Black
- ⚡ **Auto-Scaling Live Responsive Preview**: Fits perfectly on any screen (mobile phones, tablets, laptops, ultra-wide monitors) without distorting the layout.
- ✍️ **20+ Built-In Savage Desi Roasts & Taunts**:
  - *"Chup-chap padhai karke top marne aur dosto ko na batane ka jurm"* (Secret Topper)
  - *"Har plan banakar end moment pe cancel karne par"* (The Goa Flaker)
  - *"Free ki daaru dekh kar pighal jane ki kamzori"*
  - *"Hamesha 'bas 5 min' bolkar ghar pe soye rehne ke liye"*
  - *"Diet ka natak karke akele poora pizza khane par"*
  - Plus full custom text input to craft your own personal insult!
- 🖋️ **Authentic Cursive Signatures & Custom Authority**: Personalize the issuer signature, recipient name, date of ruin, and official destination (*Narak ka Ticket*, *Mental Hospital Bed*, *Tihar Jail VIP Cell*, etc.).
- 🎯 **Quick Roast Presets**: 1-click buttons to load popular desi roast templates instantly.
- 🎉 **Canvas Confetti Blast**: Celebrates every ruined reputation with an energetic confetti burst!
- 🔒 **100% Client-Side & Private**: Runs completely in the browser. Zero server processing, zero watermark, zero signups required.

---

## 🛠️ Tech Stack

- **Core**: HTML5, Semantic CSS3, Vanilla JavaScript (ES6+)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/) (CDN) with Custom Glassmorphism UI
- **Typography**: [Google Fonts](https://fonts.google.com/) (`Oswald`, `Dancing Script`, `Great Vibes`, `Poppins`)
- **Rendering & Canvas**: [html2canvas](https://html2canvas.hertzen.com/) (High-DPI off-screen rendering pipeline)
- **PDF Generation**: [jsPDF](https://github.com/parallax/jsPDF) (A4 Landscape formatting)
- **Micro-Interactions**: [canvas-confetti](https://www.npmjs.com/package/canvas-confetti)

---

## 📂 Project Structure

```text
barbaadi/
├── index.html       # Complete application (UI, generator form, live preview, canvas logic)
├── LICENSE          # MIT License
├── README.md        # Comprehensive documentation & guide
└── .gitignore       # Standard git ignore patterns
```

---

## ⚡ Quick Start / Local Setup

No build steps, bundlers, or `npm install` needed! This is a zero-dependency, pure client-side application.

### Option 1: Just Open in Browser
1. Clone this repository:
   ```bash
   git clone https://github.com/bhanu2006-24/barbaadi.git
   ```
2. Navigate to the project directory:
   ```bash
   cd barbaadi
   ```
3. Open `index.html` in your favorite web browser:
   - On macOS: `open index.html`
   - On Windows: `start index.html`
   - On Linux: `xdg-open index.html`

### Option 2: Run with a Local Server (Recommended for testing Web Share / Clipboard API)
```bash
# Using Python 3:
python3 -m http.server 8000

# Using Node (npx serve):
npx serve .
```
Then open `http://localhost:8000` in your browser.

---

## 📖 How to Ruin a Friend (Step-by-Step)

1. **Pick the Target 🎯**: Enter your friend's full name (or notorious nickname).
2. **Choose the Vibe 🎨**: Select from 6 aesthetic themes to match their personality.
3. **Select the Crime 📝**: Pick from our preloaded savage roasts, sweet taunts, or type your own custom insult.
4. **Choose Destination & Sign 🚓**: Assign their final destination (*Narak*, *Tihar Jail*, etc.) and put your signature (*"Tera Baap"*, *"Dost"*, etc.).
5. **Download & Expose 📤**:
   - Hit **Download PNG** to get a 3X Ultra-HD image for WhatsApp groups and Instagram stories.
   - Hit **Download PDF** for a printable certificate to physically hand to them.
   - Hit **Copy Image** to paste directly into your chats.

---

## 💡 Troubleshooting: Certificate Export

| Issue | Cause | Fix Implemented |
|---|---|---|
| **Certificate cut on mobile** | Viewport clipping inside small containers | Cloned off-screen at full 900×650 dimensions prior to rendering |
| **Blurry / Pixelated text** | Low default canvas scale | 3× HD render pipeline (2700×1950 px resolution) |
| **Stretched certificate in PDF/PNG** | Mismatched canvas aspect ratio | Strict 900:650 landscape ratio lock with automatic centering |
| **Cut-off date or cursive signature** | Negative baseline line-height | Harmonized cursive box metrics and descender clearance |

---

## 🤝 Contributing

Contributions, roast suggestions, and new themes are always welcome!

1. Fork the Project (`https://github.com/bhanu2006-24/barbaadi/fork`)
2. Create your Feature Branch (`git checkout -b feature/EpicRoast`)
3. Commit your Changes (`git commit -m "Add new college hostel roasts"`)
4. Push to the Branch (`git push origin feature/EpicRoast`)
5. Open a Pull Request

---

## 📜 License

Distributed under the **MIT License**. See [`LICENSE`](LICENSE) for more information.

---

## 👑 Author & Credits

Created by **Bhanu Pratap Saini** ([@bhanu2006-24](https://github.com/bhanu2006-24)).  
*Disclaimer: Created purely for entertainment, humor, and harmless fun among friends. Ruin responsibly!* 💀🔥
