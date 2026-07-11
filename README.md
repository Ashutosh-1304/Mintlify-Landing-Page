# Mintlify Landing Page Clone (HTML & CSS Only)

This project is a **static clone of the Mintlify landing page**, recreated using **only HTML and CSS**. The goal of this clone is to practice modern UI layout, typography, color systems, and visual hierarchy without relying on JavaScript or external frameworks.

---

## 📌 Project Scope

* **Technology used:**

  * HTML5
  * CSS3 (Flexbox, Grid, custom properties)
* **Not used:**

  * JavaScript
  * Frameworks (React, Tailwind, Bootstrap, etc.)

This ensures the focus remains on **pure frontend fundamentals**.

---

## 🧩 Sections Recreated

The following sections from the original Mintlify landing page were recreated:

1. **Hero Section**

   * Headline and subheading
   * Call-to-action buttons
   * Background visuals (gradients / images)
   * Centered content alignment

2. **Navigation Bar (Header)**

   * Logo placement
   * Navigation links
   * Sticky / fixed positioning behavior
   * Semi-transparent background with blur effect

3. **Features Section**

   * Grid-based card layout
   * Icons or placeholders
   * Short feature descriptions

4. **Documentation Preview / Highlight Section**

   * Two-column layout
   * Text on one side, visual preview on the other

5. **Footer Section**

   * Brand name
   * Basic links (Docs, GitHub, Community, etc.)
   * Minimal dark-themed styling

> ⚠️ Note: This clone focuses on **visual structure and styling**, not full functionality.

---

## 🎨 Fonts Used

The typography closely matches Mintlify’s clean and modern style.

* **Primary Font:**

  * `Inter`, sans-serif

```css
font-family: 'Inter', sans-serif;
```

* **Font Weights Used:**

  * 400 (Regular)
  * 500 (Medium)
  * 600 (Semi-bold)
  * 700 (Bold)

Font sizes are scaled using **rem units** for responsiveness and consistency.

---

## 🎨 Color Palette

The color system follows Mintlify’s dark, minimal aesthetic.

### Primary Colors

| Purpose        | Color      | Hex Code  |
| -------------- | ---------- | --------- |
| Background     | Dark Black | `#08090A` |
| Primary Text   | White      | `#FFFFFF` |
| Secondary Text | Light Gray | `#A1A1AA` |
| Accent / CTA   | Blue       | `#3B82F6` |

### CSS Variables Example

```css
:root {
  --bg-dark: #08090A;
  --text-white: #FFFFFF;
  --text-muted: #A1A1AA;
  --accent-blue: #3B82F6;
}
```

Using CSS variables ensures **easy theming and maintainability**.

---

## 📐 Layout Techniques Used

* **Flexbox**

  * Navigation alignment
  * Button groups

* **CSS Grid**

  * Feature cards
  * Section layouts

* **Positioning**

  * `position: fixed` / `sticky` for navbar
  * `z-index` layering for backgrounds

* **Visual Effects**

  * `backdrop-filter: blur()`
  * Gradients and subtle shadows

---

## 🚀 Purpose of This Clone

* Strengthen HTML & CSS fundamentals
* Understand modern SaaS landing page design
* Practice real-world UI cloning
* Build a portfolio-ready frontend project

---

## 📂 How to Run

1. Clone the repository
2. Open `index.html` in any modern browser

No build tools or dependencies required.

---

## 📱 Responsiveness Note

This project is **non-responsive by design**.

* It is optimized for **desktop view only**
* Best viewed at **100% browser zoom**
* Mobile and tablet layouts are **not implemented**

The primary goal was to replicate the **desktop UI and visual styling** of the Mintlify landing page using pure HTML and CSS.

---

## 📎 Disclaimer

This project is created for educational purposes only.

All design inspiration belongs to **Mintlify**. No commercial use is intended.
