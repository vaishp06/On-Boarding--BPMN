# MSIS Onboarding Portal - Static Website

This is a static HTML/CSS/JS version of the MSIS Onboarding Portal, converted from ASP.NET Core Razor Pages.

This is a static HTML/CSS/JS version of the MSIS Onboarding Portal, converted from ASP.NET Core Razor Pages.

## 📁 Structure

```
static-site/
├── index.html              # Home page
├── food.html              # Dining & Food page
├── bus.html               # Transportation page
├── onboarding.html        # Onboarding resources page
├── privacy.html           # Privacy policy page
├── css/
│   └── style.css         # Custom styles
├── js/
│   └── site.js          # Custom JavaScript
├── images/              # All images
└── lib/                 # Bootstrap & jQuery libraries
```

## 🚀 How to Run

### Option 1: Open Directly
Simply open `index.html` in your web browser.

### Option 2: Local Server (Recommended)
Using Python:
```bash
cd static-site
python3 -m http.server 8000
```
Then open http://localhost:8000 in your browser.

Using Node.js (with npx):
```bash
cd static-site
npx serve
```

### Option 3: VS Code Live Server
1. Install "Live Server" extension in VS Code
2. Right-click on `index.html`
3. Select "Open with Live Server"

## 🌐 Deployment Options

### GitHub Pages
1. Create a new repository on GitHub
2. Push the `static-site` folder contents
3. Enable GitHub Pages in repository settings
4. Your site will be live at `https://username.github.io/repo-name`

### Netlify
1. Drag and drop the `static-site` folder to netlify.com/drop
2. Or connect your GitHub repository for automatic deployments

### Vercel
```bash
npm i -g vercel
cd static-site
vercel
```

## 📝 Notes

- All Razor syntax has been converted to standard HTML
- Links use `.html` extensions instead of Razor routing
- Some pages (like TA Documents, FAQs, etc.) are placeholder links - you'll need to create those pages
- Images referenced in pages should exist in the `images/` folder

## ⚙️ Customization

- Edit `css/style.css` to modify styles
- Update navigation links in each HTML file's `<nav>` section
- Add new pages by copying the structure from existing HTML files

## 🔧 Missing Pages

The following pages are referenced in navigation but not yet created:
- ta.html
- faqs.html
- newsletters.html
- slides.html
- lindner-map.html
- advisor-sessions.html
- meet-student-ambassadors.html
- bbk.html
- linkedin.html
- careers.html
- graduate-certificates.html
- choosing-classes.html
- 25live.html
- events.html
- learning-career.html

Create these pages using the same template structure as existing pages.
