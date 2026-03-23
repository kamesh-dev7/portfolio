# PORTFOLIO - Developer Portfolio

A high-performance, precision-coded personal developer portfolio for **Kamesh**, engineered with a modular, terminal-driven aesthetic and modern architectural design. Built to be lightweight, incredibly fast, and beautifully dark-themed.

## 🔥 Key Features
- **Cyberpunk / Editorial Aesthetic:** A striking dark-mode interface featuring glowing text, glassmorphism navigation, and carefully curated fonts (Sora, Space Grotesk, Inter).
- **Responsive Navigation:** A seamlessly linked, multi-page structure consisting of Home (`index.html`), About (`about.html`), and Work/Projects Archive (`projectinfo.html`).
- **Tailwind CSS Integration:** Configured dynamically through a centralized `tailwind-config.js` script, allowing for infinite scalability and theming across all pages.
- **Micro-Interactions & Animations:** Smooth scrolling behavior, interactive hover states, scalable element transitions, and a pulse-animated mock terminal segment.
- **Custom Assets Context:** Contains dedicated placements for custom profile photography and an injectable Instagram QR Code configuration (`_mr_broken_soul_007_qr.png`).

## 🛠️ Technical Stack
- **Structure:** HTML5
- **Styling:** CSS3 (Vanilla `global.css`) & Tailwind CSS (via CDN)
- **Logic / Config:** ES6 Javascript (`tailwind-config.js`)
- **Typography:** Google Fonts (`Inter`, `Space Grotesk`, `Sora`)
- **Icons:** Google Material Symbols

## 📂 Project Structure
```text
/
├── index.html            # The main landing page / hero / features
├── about.html            # Biography, skills matrix, and terminal mock interface
├── projectinfo.html      # Comprehensive archive of previous deployed MERN projects
├── global.css            # Reusable CSS for bespoke aesthetic classes
└── tailwind-config.js    # Shared Tailwind themes (Color palettes, custom fonts)
```

## 🚀 Getting Started
This project relies entirely on client-side rendering with CDN scripts, meaning there is no build process required to run the codebase natively!

1. Clone the repository:
   ```bash
   git clone https://github.com/kamesh-dev7/portfolio.git
   ```
2. Open `index.html` in any modern web browser or use a tool like VS Code Live Server to experience the layout instantly.
3. Make sure to drag and drop your `_mr_broken_soul_007_qr.png` file directly into the project root directory so that the UI maps it correctly.

## 📡 Contact Parameters
- **Developer / Architect:** Kamesh
- **Focus Areas:** Scalable Architectures, MERN Stack, Fullstack Optimization
- **Email Protocol:** [devkamesh72@gmail.com](mailto:devkamesh72@gmail.com)
- **Instagram Registry:** [@mr_broken_soul_007](https://instagram.com)
- **GitHub Node:** [@kamesh-dev7](https://github.com/kamesh-dev7)

---
*Built with Precision © <span id="year"></span>*
<script>
    document.getElementById("year").textContent = new Date().getFullYear();
</script> 
