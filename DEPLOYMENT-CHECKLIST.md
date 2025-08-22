# GitHub Pages Deployment Checklist ✅

## Before Uploading

- [ ] **Customize Content**
  - [ ] Update page title in `index.html`
  - [ ] Replace "YourSite" with your brand name
  - [ ] Update contact information
  - [ ] Customize hero section text
  - [ ] Update meta descriptions for SEO

- [ ] **Update Links**
  - [ ] Replace placeholder URLs in `robots.txt` and `sitemap.xml`
  - [ ] Update social media links (if added)
  - [ ] Check all internal links work

- [ ] **Test Locally** (Optional)
  - [ ] Open `index.html` in browser
  - [ ] Test on mobile device
  - [ ] Check all forms and interactions work

## Upload to GitHub

- [ ] **Create Repository**
  - [ ] Name: `username.github.io` (user site) or project name
  - [ ] Set to Public
  - [ ] Don't initialize with README if uploading files

- [ ] **Upload Files**
  - [ ] Drag and drop all files to repository
  - [ ] Or use Git: `git add .` → `git commit -m "Initial site"` → `git push`

## Enable GitHub Pages

- [ ] **Go to Settings**
  - [ ] Navigate to repository Settings
  - [ ] Click on "Pages" in left sidebar

- [ ] **Configure Source**
  - [ ] Source: "Deploy from a branch"
  - [ ] Branch: "main" (or your default branch)
  - [ ] Folder: "/ (root)"
  - [ ] Click "Save"

## After Deployment

- [ ] **Verify Site**
  - [ ] Visit your site URL (shown in Pages settings)
  - [ ] Test all sections and links
  - [ ] Check mobile responsiveness

- [ ] **SEO Setup** (Optional)
  - [ ] Update `sitemap.xml` with your actual URL
  - [ ] Update `robots.txt` with your actual URL
  - [ ] Submit sitemap to Google Search Console

- [ ] **Custom Domain** (Optional)
  - [ ] Add CNAME file with your domain
  - [ ] Configure DNS at your domain provider
  - [ ] Enable HTTPS in Pages settings

## Common Issues & Solutions

**Site not loading?**
- Wait 5-10 minutes after enabling Pages
- Check that repository is public
- Ensure `index.html` is in root directory

**Styles not working?**
- Check file paths are correct
- Ensure `.nojekyll` file is present

**Form not working?**
- GitHub Pages only serves static files
- Consider using services like Formspree or Netlify Forms

**Need custom functionality?**
- Add JavaScript for client-side features
- Use third-party services for backend features

---

🎉 **Your site should now be live!**

Visit: `https://your-username.github.io/repository-name`