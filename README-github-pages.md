# Creative Portfolio Template for GitHub Pages 🎨

A stunning, modern portfolio website template perfect for creatives, designers, and developers. Showcase your projects, video edits, and graphic design work beautifully!

## 📁 Files Included

- `index.html` - Portfolio HTML with semantic structure
- `style.css` - Creative portfolio styling with vibrant gradients
- `script.js` - Interactive portfolio features
- `README-github-pages.md` - This file (optional)

## ✨ Portfolio Sections

### 🏠 Hero Section
- Personalized greeting with typing effect
- Creative subtitle and description
- Call-to-action buttons

### 👨‍💻 About Me
- Personal story and background
- Skills showcase with animated tags
- Professional stats counter
- Profile image and sticky card

### 💼 Projects
- Web development portfolio
- Interactive project cards with overlays
- Technology tags and live demo links
- Hover effects and animations

### 🎬 Video Edits
- Video portfolio showcase
- Play button interactions
- View statistics and descriptions
- Creative thumbnails

### 🎨 Graphic Design
- Design gallery with lightbox effects
- Poster and branding work
- Hover overlays with descriptions
- Parallax scroll effects

### 📧 Contact
- Working contact form
- Social media integration
- Contact information display

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

### Update Your Information

**Personal Details:**
- Replace "Your Name" with your actual name throughout the site
- Update the hero section with your title/subtitle
- Add your actual profile photo (replace the Unsplash URL)
- Update contact information and social media links

**Portfolio Content:**
- Replace project images and descriptions
- Update video thumbnails and statistics
- Add your actual graphic design work
- Customize skill tags to match your expertise

### Replace Portfolio Images

**Projects:**
- Upload your project screenshots to an `images/` folder
- Replace Unsplash URLs with your actual project images
- Update project descriptions and technologies used

**Video Edits:**
- Add thumbnails of your video work
- Link to actual video files or platforms (YouTube, Vimeo)
- Update view counts and video statistics

**Graphic Design:**
- Upload your design work (posters, branding, etc.)
- Organize by category or project type
- Add proper descriptions and context

### Colors & Design

The template uses a vibrant creative color scheme. Edit these in `style.css`:

```css
:root {
    --primary: #ff6b6b;        /* Coral red - main brand */
    --secondary: #4ecdc4;      /* Turquoise - secondary */
    --accent: #45b7d1;         /* Blue - accent color */
    --purple: #9b59b6;         /* Purple for variety */
    --orange: #f39c12;         /* Orange highlights */
}
```

**Creative Gradients:**
- `--gradient-primary`: Main coral to turquoise gradient
- `--gradient-purple`: Purple gradient for sections
- `--gradient-blue`: Blue gradient for highlights
- `--gradient-orange`: Orange gradient for CTAs

### Fonts

The template uses Inter font from Google Fonts. To change:
1. Replace the Google Fonts link in `<head>`
2. Update `--font-family` in CSS

### Add Your Own Sections

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

**Popular additions:**
- **Testimonials:** Client feedback and reviews
- **Blog:** Recent articles or thoughts
- **Services:** What you offer clients
- **Resume:** Downloadable CV/resume section

## ✨ Features Included

- **📱 Fully Responsive** - Perfect on all devices
- **🎨 Creative Design** - Vibrant colors and modern gradients
- **⚡ Interactive Animations** - Hover effects and scroll animations
- **🔍 SEO Optimized** - Proper meta tags and semantic HTML
- **📧 Working Contact Form** - Form validation and notifications
- **🧭 Smooth Navigation** - Smooth scroll and sticky nav
- **🎭 Portfolio Interactions** - Video players and image galleries
- **📊 Accessible** - WCAG guidelines followed
- **🎬 Video Integration** - Ready for YouTube/Vimeo embeds
- **🖼️ Image Galleries** - Lightbox effects and parallax scrolling

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

## 🎯 Perfect For

- **Creative Portfolios** - Designers, artists, creators
- **Developer Portfolios** - Web developers and programmers  
- **Video Editors** - Showcase reels and editing work
- **Graphic Designers** - Display posters, branding, logos
- **Freelancers** - All-in-one professional presence
- **Students** - Academic and project portfolios
- **Photographers** - Visual work and galleries
- **Content Creators** - Multi-media portfolio sites

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

**Happy creating!** 🎨✨

Show off your amazing work with this beautiful portfolio template!