# MandarinSOS Website

A simple, fast static website for mandarinsos.com featuring Privacy Policy, Terms of Use, support contact, and app information.

## 🚀 Quick Start

This is a **static HTML website** - no build process, no dependencies, just pure HTML/CSS.

### To View Locally:
1. Open `index.html` in any web browser
2. Or use a local server:
   ```bash
   # Python 3
   python3 -m http.server 8000
   
   # Node.js (if you have it)
   npx serve .
   ```
3. Visit `http://localhost:8000`

## 📁 File Structure

```
MandarinSOS website/
├── index.html      # Main homepage with app info
├── privacy.html    # Privacy Policy page
├── terms.html      # Terms of Use page
├── styles.css      # All styles (single file)
└── README.md       # This file
```

## 🎨 Design Features

- **Fast Loading**: Pure HTML/CSS, no JavaScript frameworks
- **Mobile Responsive**: Works on all devices
- **Modern Design**: Clean, professional look
- **SEO Friendly**: Proper meta tags and semantic HTML

## 📝 Content

### Homepage (`index.html`)
- App description and features
- Download link (App Store badge)
- Support email: hi@mandarinsos.com

### Privacy Policy (`privacy.html`)
- Data collection practices
- How data is used and stored
- Third-party services
- User rights

### Terms of Use (`terms.html`)
- Subscription terms
- Free vs Premium features
- Payment and cancellation policies
- Acceptable use guidelines

## 🌐 Deployment

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Push these files
3. Enable GitHub Pages in repository settings
4. Point your domain to GitHub Pages

### Option 2: Netlify (Free)
1. Drag and drop this folder to [Netlify Drop](https://app.netlify.com/drop)
2. Add custom domain: mandarinsos.com
3. Done!

### Option 3: Traditional Web Hosting
1. Upload all files via FTP/SFTP
2. Point domain to hosting
3. Done!

## 🔧 Customization

### Colors
Edit CSS variables in `styles.css`:
```css
:root {
    --primary-color: #FF6B35;    /* Main brand color */
    --secondary-color: #004E89;   /* Secondary color */
    --text-color: #2C3E50;        /* Text color */
}
```

### App Store Link
Update the App Store badge link in `index.html`:
```html
<a href="https://apps.apple.com/app/mandarinsos" target="_blank">
```

### Support Email
All pages reference: `hi@mandarinsos.com`

## 📱 App Store Badge

The App Store badge uses Apple's official badge generator. Replace the URL in `index.html` once your app is live on the App Store.

## ⚡ Performance

- **No JavaScript**: Pure HTML/CSS = instant loading
- **Minimal CSS**: Single file, optimized
- **No External Dependencies**: Everything is self-contained
- **Mobile Optimized**: Responsive design, fast on mobile

## 🔒 Security

- No user input forms (static site)
- No tracking scripts
- HTTPS ready (works with SSL)

## 📧 Support

For website questions or updates, contact: **hi@mandarinsos.com**

---

**Built for speed and simplicity.** No frameworks, no build tools, just fast, reliable HTML.

