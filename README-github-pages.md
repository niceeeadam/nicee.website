# Beautiful GitHub Pages Template 🚀

A modern, responsive HTML5 website template perfect for GitHub Pages. Just drag and drop the files into your repository!

## 📁 Files Included

- `index.html` - Main HTML file with semantic structure
- `style.css` - Modern CSS with beautiful gradients and animations
- `script.js` - Interactive JavaScript features
- `README-github-pages.md` - This file (optional)

## 🚀 Quick Setup

1. **Create a GitHub Repository:**
   - Go to GitHub and create a new repository
   - Name it `your-username.github.io` (for user site) or any name (for project site)

2. **Upload Files:**
   - Drag and drop all files into your repository
   - Or clone the repo and copy files locally

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Set source to "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Save

4. **Your site is live!**
   - Visit `https://your-username.github.io/repository-name`

## 🎨 Customization Guide

### Update Content

**Basic Info:**
- Edit the `title` and meta descriptions in `<head>`
- Replace "YourSite" with your brand name
- Update contact information in the contact section

**Sections:**
- **Hero:** Main headline and description
- **About:** Project overview with feature cards
- **Features:** Key features or services
- **Contact:** Contact form and information

### Colors & Design

The template uses CSS custom properties for easy theming. Edit these in `style.css`:

```css
:root {
    --primary: #6366f1;        /* Main brand color */
    --secondary: #8b5cf6;      /* Secondary color */
    --accent: #06b6d4;         /* Accent color */
    --text-primary: #1f2937;   /* Main text color */
    --text-secondary: #6b7280; /* Secondary text */
}
```

### Fonts

The template uses Inter font from Google Fonts. To change:
1. Replace the Google Fonts link in `<head>`
2. Update `--font-family` in CSS

### Add More Sections

Copy any existing section structure and modify:

```html
<section id="new-section" class="new-section">
    <div class="container">
        <div class="section-header">
            <h2 class="section-title">New Section</h2>
            <p class="section-description">Description here</p>
        </div>
        <!-- Your content here -->
    </div>
</section>
```

## ✨ Features Included

- **📱 Fully Responsive** - Works on all devices
- **🎨 Modern Design** - Beautiful gradients and animations
- **⚡ Fast Loading** - Pure HTML/CSS/JS, no frameworks
- **🔍 SEO Optimized** - Proper meta tags and semantic HTML
- **📧 Contact Form** - Working form with validation
- **🧭 Smooth Navigation** - Smooth scroll and sticky nav
- **🎭 Interactive Effects** - Hover animations and scroll effects
- **📊 Accessible** - WCAG guidelines followed

## 🛠️ Advanced Customization

### Adding Images

1. Create an `images/` folder in your repository
2. Upload your images
3. Reference them in HTML: `<img src="images/your-image.jpg" alt="Description">`

### Custom Domain

1. Add a `CNAME` file to your repository root
2. Add your domain name (e.g., `yoursite.com`)
3. Configure DNS settings at your domain provider

### Analytics

Add Google Analytics by inserting the tracking code before `</head>`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🎯 Use Cases

Perfect for:
- Personal portfolios
- Project showcases
- Small business websites
- Landing pages
- Documentation sites
- Resume websites

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🤝 Contributing

Feel free to fork this template and make it your own! If you create improvements, consider sharing them back.

## 📄 License

This template is free to use for any purpose. No attribution required, but appreciated!

---

**Happy coding!** 🎉

If you need help customizing this template, feel free to open an issue or check GitHub Pages documentation.