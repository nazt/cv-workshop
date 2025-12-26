# Nat Weerawan - CV Website

A professional, single-page CV/Portfolio website showcasing the work of Nat Weerawan (nazt) - an Academic Hacker, IoT Engineer, and Civic Tech Innovator.

## 🎨 Design Philosophy

**"Academic Hacker"** - A unique blend of academic paper aesthetics and developer portfolio design.

### Key Features

- **Clean Semantic HTML5** - Accessible, SEO-optimized structure
- **Pure CSS3** - No frameworks, no dependencies
- **Dark Mode First** - Deep slate background with Safety Orange & Electric Blue accents
- **Print-Optimized** - Professional PDF generation ready
- **Responsive Design** - Mobile-first approach, works on all devices
- **Performance Focused** - Minimal file sizes, fast loading

## 🚀 Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Custom properties (CSS variables), Grid, Flexbox
- **Typography** - Serif headings, Sans-serif body, Monospace code
- **Color Scheme** - Dark mode with accent gradients

## 📁 Project Structure

```
cv-workshop/
├── index.html      # Main HTML structure (20KB)
├── styles.css      # Main stylesheet with dark theme (16KB)
├── print.css       # Print/PDF optimized styles (8KB)
└── README.md       # This file
```

## 🖥️ Local Development

```bash
# Clone the repository
git clone https://github.com/nazt/cv-workshop.git
cd cv-workshop

# Start a local server (choose one)
python3 -m http.server 8080
# or
npx serve
# or
php -S localhost:8080

# Open in browser
open http://localhost:8080
```

## 📄 Print to PDF

1. Open the website in your browser
2. Press `Ctrl+P` (or `Cmd+P` on Mac)
3. Select "Save as PDF"
4. Ensure "Background graphics" is enabled
5. Save your professional CV!

The print stylesheet automatically:
- Hides navigation and footer
- Optimizes spacing for 1-2 pages
- Converts colors for print
- Shows link URLs in parentheses

## 🎯 Sections

- **Header** - Name, titles, social links
- **Hero** - Executive summary & threefold contribution
- **Technical Projects** - WiFiConnector, CMMC_NB-IoT with code examples
- **Community** - Chiang Mai Maker Club, "Show & Tell" format
- **Civic Tech** - FloodBoy early warning system (Radar, AI, Solar)
- **Research** - Energy systems & Healthcare technology
- **Appendix** - Technologies table, certifications

## 🎨 Color Palette

```css
--color-bg-primary: #0f1419      /* Deep Slate */
--color-bg-secondary: #1a1f29    /* Elevated Dark */
--color-accent-orange: #ff6b35   /* Safety Orange */
--color-accent-blue: #00b4d8     /* Electric Blue */
--color-accent-success: #10b981  /* Success Green */
```

## ✨ Features

- **Vertical Timeline** - Visual project history
- **Syntax-Highlighted Code Blocks** - Professional code presentation
- **Project Cards** - Organized with impact metrics
- **Responsive Tables** - Mobile-friendly technology listing
- **Smooth Scrolling** - Enhanced navigation experience
- **Accessibility** - Semantic HTML, ARIA labels, keyboard navigation

## 📊 Performance

- **File Size** - Total: ~44KB (uncompressed)
- **Load Time** - Sub-second on modern connections
- **Lighthouse Score** - Targeting 100/100
- **No External Dependencies** - Zero HTTP requests for libraries

## 🔗 Links

- **GitHub**: [@nazt](https://github.com/nazt)
- **Live Demo**: [https://nazt.github.io/cv-workshop/](https://nazt.github.io/cv-workshop/)

## 📝 License

This CV template is open source. Feel free to fork and customize for your own use.

---

Built with ❤️ using semantic HTML5 & CSS3
