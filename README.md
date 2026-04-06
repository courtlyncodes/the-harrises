# 💍 #2Hands2Harris: The Wedding Experience

A bespoke, high-fashion wedding platform developed for the union of **Tomneshia & Dominique**. This project departs from standard templates (Zola/TheKnot) to deliver a high-contrast, editorial digital experience inspired by *Vogue* and *Modern Luxury*.

## ✨ The Aesthetic
* **Typography:** A curated blend of **Bodoni Moda** (Display), **Montserrat** (Modern Sans), and **Mea Culpa** (Calligraphy).
* **Visuals:** High-resolution photography featuring custom "staircase" typography overlays.
* **Color Palette:**
    * `#0E0E0E` (Onyx Black)
    * `#FAF8F3` (Ivory)
    * `#E2C97E` (Champagne Gold)

## 🛠️ Technical Stack
* **Frontend:** HTML5, CSS3 (Flexbox/Grid), and Vanilla JavaScript.
* **Typography Engine:** Google Fonts API with `opsz` (Optical Sizing) and `wght` variable axis support for hairline-thin rendering.
* **Backend (RSVP):** Google Apps Script (GAS) integration for real-time guest list management via Google Sheets.
* **Responsive Engine:** Custom `@media` breakpoints specifically tuned for mobile portrait optimization of landscape assets.

## 🚀 Key Features
* **Custom Hero Carousel:** A fluid, full-width image slider with `object-position` logic to ensure subjects remain in-frame on narrow mobile viewports.
* **The "Staircase" Logo:** A CSS-engineered `<h1>` logo using `em` relative units to maintain perfect kerning and alignment across all screen sizes.
* **Serverless RSVP:** A lightweight, fetch-based RSVP system that bypasses heavy third-party plugins for a faster, cleaner user journey.
* **Luxury Navigation:** A blur-effect (`backdrop-filter`) navigation bar that transitions from transparent to semi-opaque on scroll.

## 📱 Mobile Considerations
Special attention was paid to the **Mobile UX**, addressing common issues with wide-format photography on vertical screens:
* Dynamic `vh` height adjustments for the Hero section.
* Viewport-dependent `clamp()` typography to prevent text overlap on faces.
* Custom `object-position` anchors to prioritize subjects in zoomed-in mobile views.

## 🔧 Installation & Setup
1.  **Clone the Repo:**
    ```bash
    git clone [https://github.com/courtlyncodes/wedding-site.git](https://github.com/courtlyncodes/wedding-site.git)
    ```
2.  **Configuration:** Update the `scriptURL` in `index.html` with your Google Apps Script deployment URL.
3.  **Deploy:** Push to GitHub Pages or any static hosting provider.

---
### ✍️ Author
**Courtlyn B.** | *Software Engineer & Master of Science Candidate*
