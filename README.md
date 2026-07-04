# 🎨 Chloe's Colorful Creations

A bright, fully-responsive business website for custom handmade crafts and colorful gifts.

## ✨ Features

- **Interactive Slideshow** – Auto-rotating gallery of 19 featured pieces with manual navigation
- **Responsive Design** – Mobile-first layout that looks great on all devices (540px–1120px+)
- **Accessible** – ARIA labels, keyboard navigation, semantic HTML
- **No Dependencies** – Pure HTML, CSS, and vanilla JavaScript—no build tools required
- **Smooth Animations** – Soft transitions and hover effects throughout
- **Custom Branding** – Vibrant color palette with colorful gradient backgrounds

## 📂 Structure

```
CCC/
├── index.html          # Main page (hero, about, work, contact)
├── style.css           # All styling (responsive, animations, theme)
├── public/             # Image assets (featured creations)
├── .gitignore          # Git ignore list
└── README.md           # This file
```

## 🚀 Quick Start

### Option 1: GitHub Pages (Easiest)
1. Go to your repository **Settings** → **Pages**
2. Under "Build and deployment," select:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/root` (or `/ (root)`)
3. Click **Save**
4. Your site will be live at: `https://srt1975.github.io/CCC/`

### Option 2: Local Development
Simply open `index.html` in your browser—no server required for basic testing.

For a true local server (if needed):
```bash
# With Python 3
python -m http.server 8000

# With Python 2
python -m SimpleHTTPServer 8000

# With Node.js
npx http-server
```

Then visit `http://localhost:8000`

## 🎯 Customization

### Change Colors
Edit the CSS variables at the top of `style.css`:
```css
:root {
    --ink: #27183d;      /* Dark purple */
    --plum: #7c3aed;     /* Button purple */
    --rose: #ef476f;     /* Pink/red */
    --sun: #ffd166;      /* Yellow */
    --mint: #06d6a0;     /* Teal */
    --sky: #3a86ff;      /* Blue */
    --cream: #fffaf2;    /* Off-white */
}
```

### Edit Slideshow Speed
In `index.html`, adjust the `autoPlayIntervalTime` (in milliseconds):
```javascript
const autoPlayIntervalTime = 3000; // Change 3000 to your preferred speed (e.g., 5000 = 5 seconds)
```

### Update Contact Info
Find the contact section (around line 243 in `index.html`):
- Phone numbers: `1-417-274-1950` and `1-417-274-4986`
- Email: `krauterdye@gmail.com` and `stevenrthomure@gmail.com`
- Add social links (Facebook, Instagram, etc.)

## 📸 Adding New Images

1. Add your images to the `public/` folder
2. In `index.html`, find the slideshow section (around line 71) and add a new slide:
   ```html
   <div class="slide">
       <img src="public/your-image.jpg" alt="Description of creation">
       <div class="slide-caption">
           <h3>Title</h3>
           <p>Short description</p>
       </div>
   </div>
   ```

## 📱 Browser Support

- Chrome/Edge 90+
- Firefox 88+
- Safari 14+
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🔗 Links & Integration

### Coming Soon
- **Catalog Link** – Add a Shopify store, Google Sheet, or custom product page
- **Order Form** – Connect a Google Form, Stripe checkout, or custom form service

### Social Integration
Add links to:
- Facebook (already mentioned in contact section)
- Instagram
- TikTok
- Pinterest

## 📋 To-Do List for Next Steps

- [ ] Enable GitHub Pages deployment
- [ ] Add catalog/shop integration
- [ ] Create order form
- [ ] Add social media links
- [ ] Set up email forwarding/contact form backend
- [ ] Optimize images for faster load times
- [ ] Add favicon
- [ ] Consider email newsletter signup

## 📄 License

© 2026 Chloe's Colorful Creations. All rights reserved.

---

**Questions?** Contact via text or email (see contact section on the site).
