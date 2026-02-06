# Becca Moore - Accessible Portfolio Website

A WCAG 2.2 AA compliant portfolio website built with semantic HTML, CSS, and JavaScript. Designed to showcase accessibility expertise while maintaining a modern, professional aesthetic.

## ♿ Accessibility Features

This portfolio is **WCAG 2.2 AA compliant** and includes:

### Color & Contrast
- ✅ All text meets minimum 4.5:1 contrast ratio (AA standard)
- ✅ Large text meets 3:1 contrast ratio
- ✅ UI components meet 3:1 contrast for non-text elements
- ✅ Brand color (#e3037a) used strategically with AA-compliant variations

### Keyboard Navigation
- ✅ Skip to main content link for keyboard users
- ✅ Custom focus indicators (3px outline with 2px offset)
- ✅ Logical tab order through all interactive elements
- ✅ All functionality available via keyboard

### Semantic HTML & ARIA
- ✅ Proper heading hierarchy (h1 → h2 → h3)
- ✅ Semantic landmarks (nav, main, footer, article, section)
- ✅ ARIA labels on navigation and sections
- ✅ ARIA current state for active page
- ✅ Descriptive link text and button labels

### Images & Media
- ✅ Descriptive alt text for all images
- ✅ Title attribute on iframe for embedded Figma prototype
- ✅ Decorative images properly marked

### Motion & Animation
- ✅ Respects `prefers-reduced-motion` setting
- ✅ No auto-playing animations that can't be paused
- ✅ Animation duration reduced to 0.01ms for users who prefer reduced motion

### Other Features
- ✅ Relative units (rem/em) for scalable text
- ✅ Responsive design works at 200% zoom
- ✅ Clear visual distinction between visited and unvisited links
- ✅ Forms and interactive elements have visible labels

## 🎨 Design System

### Brand Colors
```css
--color-accent: #e3037a;        /* Primary brand magenta */
--color-accent-dark: #b8025f;   /* AA-compliant version for text */
--color-primary: #1a1a1a;       /* AAA contrast (16.7:1) */
--color-text-secondary: #3d3d3d; /* AAA contrast (9.7:1) */
```

### Typography
- Display: Crimson Pro (serif) - elegant, distinctive
- Body: DM Sans (sans-serif) - clear, readable

### Focus States
- 3px solid outline in brand color (#ff1a8f)
- 2px offset for clear visibility
- Consistent across all interactive elements

## 📁 File Structure

```
becs-moore.github.io/
├── index.html          # Homepage (WCAG 2.2 AA)
├── projects.html       # Projects grid (WCAG 2.2 AA)
├── clover-shop.html    # Project case study (WCAG 2.2 AA)
├── styles.css          # Accessible styling
├── script.js           # Keyboard & animation enhancements
├── assets/             # Images folder
│   ├── hero-shop.jpg
│   ├── image-shop-whiteboard.png
│   ├── image-shop-map.png
│   ├── image-shop-screens.png
│   └── image-shop-slider.jpg
└── README.md           # This file
```

## 🚀 Setup Instructions

### Quick Start with GitHub Pages

1. **Create a new repository**
   - Go to GitHub and create a new repository
   - Name it: `becs-moore.github.io` (replace with your actual GitHub username)
   - Make it **Public**
   - Do NOT initialize with README, .gitignore, or license

2. **Upload your files**
   - Download all the files from this project
   - In your new repository, click "uploading an existing file"
   - Drag and drop all files:
     - index.html
     - projects.html
     - clover-shop.html
     - styles.css
     - script.js
   - Create an `assets` folder and upload your images there
   - Commit the files

3. **Enable GitHub Pages**
   - Go to repository Settings
   - Click "Pages" in the left sidebar
   - Under "Source," select "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

4. **Wait a few minutes**
   - Your site will be live at: `https://becs-moore.github.io`

## ✏️ Customization

### Update Your Information

**In all HTML files:**
- Change "Becca Moore" to your name
- Update meta descriptions
- Update contact links with your email and social media

**In `styles.css`:**
- Modify brand colors (keep contrast ratios!)
- Adjust fonts if desired
- Customize spacing and layout

### Adding Projects

1. **Create a new project page** (copy `clover-shop.html` as a template)
2. **Add descriptive alt text** for all images
3. **Add the project to `projects.html`** by copying an `<article class="project-card">` element
4. **Upload project images** to the `assets` folder with descriptive filenames
5. **Test keyboard navigation** through the new project

### Maintaining Accessibility

When customizing, ensure you maintain:
- ✅ Color contrast ratios (use a contrast checker tool)
- ✅ Descriptive alt text for images
- ✅ Semantic HTML structure
- ✅ Keyboard navigation
- ✅ Focus indicators
- ✅ ARIA labels where needed

**Recommended Tools:**
- [WebAIM Contrast Checker](https://webaim.org/resources/contrastchecker/)
- [WAVE Browser Extension](https://wave.webaim.org/extension/)
- [axe DevTools](https://www.deque.com/axe/devtools/)
- Built-in browser accessibility audits (Chrome/Edge DevTools)

## 🧪 Testing Accessibility

### Quick Tests
1. **Keyboard navigation**: Tab through the entire site - can you access everything?
2. **Zoom test**: Zoom to 200% - is everything still readable?
3. **Screen reader**: Use VoiceOver (Mac) or NVDA (Windows) to navigate
4. **Color blindness**: Use browser extensions to simulate different types
5. **Reduced motion**: Enable in system preferences - animations should stop

### Automated Testing
Run these tools for comprehensive checks:
- WAVE (web accessibility evaluation tool)
- axe DevTools browser extension
- Lighthouse accessibility audit in Chrome DevTools

## 🎯 Features

- ✨ Modern, professional design with brand color integration
- ♿ WCAG 2.2 AA compliant
- 📱 Fully responsive (works on all devices)
- 🎨 Smooth animations (respects user preferences)
- 🖼️ Easy to embed Figma prototypes
- ⌨️ Full keyboard navigation support
- 🚀 Fast loading and optimized performance
- 🔍 SEO-friendly with semantic HTML

## 📝 Notes

- Keep image file sizes under 1MB for faster loading
- Always use descriptive alt text - imagine describing the image to someone over the phone
- Test with actual assistive technology users when possible
- Accessibility is an ongoing process - continue to test and improve

## 📚 Resources

- [WCAG 2.2 Guidelines](https://www.w3.org/WAI/WCAG22/quickref/)
- [WebAIM Articles](https://webaim.org/articles/)
- [A11y Project Checklist](https://www.a11yproject.com/checklist/)
- [MDN Accessibility Guide](https://developer.mozilla.org/en-US/docs/Web/Accessibility)

---

Built with ❤️ and ♿ accessibility in mind by Becca Moore
