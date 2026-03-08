# 🛡️ ShieldX — Web Security HTML Template

**Version:** 1.0.0 · **Author:** Tanbir · **License:** Commercial Use Allowed (Single End Product)

A premium, single-file HTML template for web security SaaS products, agencies, and cybersecurity startups. Dark, modern, and production-ready straight out of the box.

---

## ✨ What's Included

| File | Description |
|------|-------------|
| `index.html` | The complete template — HTML, CSS & JS in one file |
| `README.md` | This documentation file |
| `LICENSE.txt` | License terms |

> **Single-file design.** Everything (styles, scripts, layout) lives in `index.html`. No build tools, no frameworks, no dependencies to install.

---

## 🚀 How to Use

### Option 1 — Open Directly
Double-click `index.html` in your file explorer. It opens in any modern browser instantly.

### Option 2 — Local Dev Server (Recommended)
If you use VS Code, install the **Live Server** extension:

1. Right-click `index.html` → **"Open with Live Server"**
2. Your browser opens at `http://127.0.0.1:5500`
3. Edit and save — the browser auto-refreshes.

### Option 3 — Deploy to a Host
Upload `index.html` to any static host:
- **Netlify** — drag & drop the file at [netlify.com/drop](https://netlify.com/drop)
- **Vercel** — `vercel deploy`
- **GitHub Pages** — push to a repo and enable Pages
- **cPanel / FTP** — upload to your `public_html` folder

No server-side language required. Pure HTML/CSS/JS.

---

## 📁 Folder Structure

```
Web-security/
├── index.html       ← The entire template (HTML + CSS + JS)
├── README.md        ← Documentation (this file)
└── LICENSE.txt      ← License terms
```

> Everything is self-contained. If you add images or additional assets, create an `assets/` folder beside `index.html`.

---

## ✏️ How to Customize

Open `index.html` in any code editor (VS Code, Sublime Text, Notepad++, etc.).

---

### 🎨 Change Colors

All colors are defined as **CSS custom properties** at the very top of the `<style>` block (around line 18). You only need to edit this one place:

```css
:root {
  --primary:        #6366f1;   /* Main brand color (indigo) */
  --primary-dark:   #4f46e5;   /* Darker shade of primary */
  --secondary:      #8b5cf6;   /* Accent purple */
  --accent:         #06b6d4;   /* Cyan accent */
  --accent-green:   #10b981;   /* Success/green color */
  --bg-dark:        #0a0a0f;   /* Page background */
  --text-primary:   #f1f5f9;   /* Main text color */
  --text-secondary: #94a3b8;   /* Secondary text */
}
```

**Example — Change to a blue brand:**
```css
--primary:      #3b82f6;
--primary-dark: #2563eb;
--secondary:    #6366f1;
```

---

### ✍️ Change Text & Copy

Use your editor's **Find & Replace** (`Ctrl+H`) to swap out placeholder content:

| Placeholder | Replace With |
|-------------|--------------|
| `ShieldX` | Your product name |
| `shieldx.io` | Your domain |
| `AI-Powered Web Security Platform` | Your tagline |
| `14,200+` teams protected | Your real stats |
| Testimonial names/quotes | Real customer quotes |
| Pricing plan names/prices | Your actual pricing |

---

### 🖼️ Change Images / Avatars

This template uses **no external image files**. All visuals are created with:
- CSS gradients and shapes
- Inline SVG icons
- Emoji icons (e.g., 🛡️, 🤖, 🔥)

**To add a real logo or photo:**

1. Create an `assets/` folder in the same directory as `index.html`.
2. Place your image file inside it (e.g., `assets/logo.png`).
3. In `index.html`, replace the relevant element. For example, replace the text logo:

```html
<!-- Before -->
<div class="navbar__logo-icon">🛡</div>
ShieldX

<!-- After -->
<img src="assets/logo.png" alt="Your Brand" style="height:36px;">
```

---

### 🔤 Change Font

The template uses **Plus Jakarta Sans** from Google Fonts (loaded via CDN). To switch fonts:

1. Go to [fonts.google.com](https://fonts.google.com), pick a font, and copy the `<link>` tag.
2. Replace the existing font link in the `<head>`:

```html
<!-- Find this (around line 10): -->
<link href="https://fonts.googleapis.com/css2?family=Plus+Jakarta+Sans:wght@400;500;600;700;800&display=swap" rel="stylesheet">

<!-- Replace with your chosen font, e.g. Inter: -->
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
```

3. Update the CSS variable:

```css
--font-heading: 'Inter', sans-serif;
--font-body:    'Inter', sans-serif;
```

---

## 📦 Dependencies

This template has **zero npm dependencies**. Everything needed is either inline or loaded via CDN automatically.

| Resource | Type | How It's Loaded |
|----------|------|-----------------|
| [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) | Google Font | CDN `<link>` tag in `<head>` |
| Vanilla CSS | Styles | Inline `<style>` block |
| Vanilla JavaScript | Interactivity | Inline `<script>` block |

**No Bootstrap. No jQuery. No npm install required.**

---

## 🌐 Browser Support

| Browser | Supported |
|---------|-----------|
| Chrome 90+ | ✅ |
| Firefox 88+ | ✅ |
| Safari 14+ | ✅ |
| Edge 90+ | ✅ |
| Opera 76+ | ✅ |
| IE 11 | ❌ Not supported |

---

## 🔧 Sections Included

The template includes these fully-built sections:

1. **Navbar** — fixed, responsive, mobile hamburger menu
2. **Hero** — two-column layout with animated security dashboard mockup
3. **Trusted By** — infinite marquee logo strip
4. **Features** — 6-card feature grid with icons
5. **How It Works** — 3-step process with animated connectors
6. **Live Dashboard Demo** — browser-frame mockup with threat map SVG
7. **Stats** — animated count-up numbers
8. **Testimonials** — 3-card grid
9. **Pricing** — 3-plan pricing table with toggle
10. **FAQ** — accordion-style questions & answers
11. **CTA Banner** — conversion-focused call to action
12. **Footer** — links, social icons, newsletter input

---

## 📄 License

See [`LICENSE.txt`](LICENSE.txt) for the full license text.

### Quick Summary

| Use Case | Allowed? |
|----------|----------|
| Use for 1 personal project / website | ✅ Yes |
| Use for 1 client project | ✅ Yes |
| Modify the template | ✅ Yes |
| Use in a SaaS or web app (1 end product) | ✅ Yes |
| Sell or redistribute the **source code** | ❌ No |
| Include in a template bundle for resale | ❌ No |
| Create multiple end products from one license | ❌ No (buy additional licenses) |

> **Each license covers ONE end product.** If you build multiple websites using this template, please purchase a separate license for each.

---

## 💬 Support

Purchased on Gumroad? Leave a question on the product page or contact via the Gumroad messaging system. Please include a description of your issue and the browser/OS you're using.

---

## 🙌 Credits

- **Template Design & Code:** Tanbir
- **Font:** [Plus Jakarta Sans](https://fonts.google.com/specimen/Plus+Jakarta+Sans) by Ektype (SIL Open Font License)
- **Icons:** Inline SVGs (custom-drawn, license-free)

---

*Thank you for your purchase! If this template saved you time, a ⭐ review on Gumroad means the world. 🙏*
