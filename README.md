# Robert Baker Portfolio Website

Professional portfolio website for Robert Baker, Senior Instructional Designer specializing in healthcare learning solutions, compliance training, and AI-enhanced leadership development.

## 🌐 Live Site
[Your site will be live at: https://yourusername.github.io](https://yourusername.github.io)

## 🚀 Quick Setup Guide

### Step 1: Create a New Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the **"+"** icon in the top right → **"New repository"**
3. Repository name: `yourusername.github.io` (replace `yourusername` with your actual GitHub username)
   - Example: If your username is `rbaker87`, name it `rbaker87.github.io`
4. Description: "Professional portfolio for Robert Baker - Senior Instructional Designer"
5. Set to **Public**
6. Check **"Add a README file"**
7. Click **"Create repository"**

### Step 2: Upload Your Files

**Option A: Upload via GitHub Web Interface (Easiest)**

1. Click **"Add file"** → **"Upload files"**
2. Drag and drop these files:
   - `index.html`
   - `styles.css`
3. Add commit message: "Initial portfolio setup"
4. Click **"Commit changes"**

**Option B: Use GitHub Desktop (Recommended for ongoing updates)**

1. Download [GitHub Desktop](https://desktop.github.com/)
2. Clone your repository
3. Copy all files into the local folder
4. Commit and push changes

**Option C: Use Git Command Line**

```bash
git clone https://github.com/yourusername/yourusername.github.io.git
cd yourusername.github.io
# Copy your files here
git add .
git commit -m "Initial portfolio setup"
git push origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **"Settings"** (top right)
3. Scroll down to **"Pages"** (left sidebar under "Code and automation")
4. Under **"Source"**, select **"Deploy from a branch"**
5. Under **"Branch"**, select **"main"** and **"/ (root)"**
6. Click **"Save"**
7. Wait 2-3 minutes, then visit: `https://yourusername.github.io`

🎉 **Your site is now live!**

## 📁 File Structure

```
yourusername.github.io/
├── index.html          # Homepage
├── styles.css          # Main stylesheet
├── projects.html       # Projects page (to be added)
├── about.html          # About page (to be added)
├── contact.html        # Contact page (to be added)
├── assets/             # Folder for files
│   ├── images/         # Project screenshots, headshot
│   ├── documents/      # Resume PDF
│   └── samples/        # Portfolio samples
└── README.md          # This file
```

## 🎨 Brand Colors

- **Deep Navy:** `#1B365D` - Primary brand color, headers
- **Bright Teal:** `#00B4A6` - Secondary color, accents
- **Warm Orange:** `#F07B3F` - Call-to-action buttons
- **Light Gray:** `#F8F9FA` - Page backgrounds
- **Dark Gray:** `#343A40` - Body text, footer

## 🔧 Customization Guide

### Update Your Information

1. **Contact Info** - Edit in `index.html`:
   - Email: Line 139
   - Phone: Line 140
   - Location: Line 141

2. **LinkedIn Profile** - Edit in `index.html`:
   - Line 146: Replace `yourprofile` with your LinkedIn username

3. **Stats** - Update in `index.html`:
   - Lines 33-52: Your actual metrics

### Add Your Resume

1. Create an `assets` folder in your repository
2. Upload your resume as `robert-baker-resume.pdf`
3. The download link is already configured: `href="assets/robert-baker-resume.pdf"`

### Add Images

1. Create `assets/images/` folder
2. Upload your professional headshot: `headshot.jpg`
3. Upload project screenshots
4. Reference in HTML: `<img src="assets/images/headshot.jpg" alt="Robert Baker">`

## 📄 Adding More Pages

### Projects Page (Coming Next)
- Showcase your work with problem-solution-results format
- Include Innovation Forge, compliance training redesign, symposium

### About Page
- Professional bio
- Skills and expertise
- Career journey
- Personal interests

### Contact Page
- Contact form
- Email link
- LinkedIn profile
- Phone number

## 🌐 Custom Domain (Optional)

Want to use your own domain like `robertbaker.dev`?

1. Buy a domain from [Namecheap](https://www.namecheap.com) or [Google Domains](https://domains.google)
2. In your repository, create a file named `CNAME`
3. Add your domain: `robertbaker.dev`
4. Configure DNS settings in your domain registrar:
   - Add A records pointing to GitHub's IPs:
     - `185.199.108.153`
     - `185.199.109.153`
     - `185.199.110.153`
     - `185.199.111.153`
   - Or add CNAME record pointing to `yourusername.github.io`
5. Wait 24-48 hours for DNS propagation

## 🔄 Updating Your Site

### Quick Edits (Small Changes)
1. Go to your repository on GitHub
2. Click on the file you want to edit
3. Click the pencil icon (Edit this file)
4. Make changes
5. Scroll down, add commit message, click "Commit changes"
6. Changes go live in 1-2 minutes

### Major Updates (Multiple Files)
1. Clone repository to your computer
2. Make all changes locally
3. Test by opening `index.html` in a browser
4. Commit and push changes
5. Changes go live automatically

## 📱 Mobile Responsive

The site is fully responsive and looks great on:
- Desktop (1920px+)
- Laptop (1024px - 1920px)
- Tablet (768px - 1024px)
- Mobile (320px - 768px)

## ♿ Accessibility

- WCAG AA compliant color contrast
- Semantic HTML structure
- Alt text for images (add when you include them)
- Keyboard navigable
- Screen reader friendly

## 🚀 Performance

- Minimal dependencies (no heavy frameworks)
- Fast load times
- Optimized for Core Web Vitals
- Clean, semantic HTML5
- Efficient CSS

## 📊 Analytics (Optional)

Add Google Analytics to track visitors:

1. Get your Google Analytics tracking ID
2. Add this before `</head>` in `index.html`:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-XXXXXXXXXX"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-XXXXXXXXXX');
</script>
```

## 🐛 Troubleshooting

### Site not showing up?
- Wait 5-10 minutes after enabling GitHub Pages
- Check Settings → Pages shows green checkmark
- Clear browser cache
- Try incognito/private browsing mode

### Changes not appearing?
- GitHub Pages cache can take 1-5 minutes
- Hard refresh: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)
- Check commit history to confirm changes were pushed

### CSS not loading?
- Verify `styles.css` is in the same folder as `index.html`
- Check browser console (F12) for errors
- Verify file name spelling matches exactly

## 📞 Support

Need help? Common resources:
- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [GitHub Community Forum](https://github.community)
- [W3Schools HTML/CSS](https://www.w3schools.com)

## 📝 Version History

- **v1.0** (2025) - Initial portfolio launch
  - Homepage with hero, stats, expertise sections
  - Mobile responsive design
  - Brand color system implementation
  - Professional navigation

## 📜 License

© 2025 Robert Baker. All rights reserved.

---

**Built with:** HTML5, CSS3, and ❤️

**Hosted on:** GitHub Pages (Free!)

**Last Updated:** November 2025
