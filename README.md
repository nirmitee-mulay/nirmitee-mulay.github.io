# Nirmitee Mulay - Academic Website

A modern, responsive academic website built for showcasing research, publications, and science communication work.

## 🌐 Live Site
Once deployed: https://nirmitee-mulay.github.io

## 📁 File Structure

```
nirmitee-mulay.github.io/
├── index.html              # Homepage
├── research.html           # Research projects and overview
├── publications.html       # Publications, presentations, grants
├── scicomm.html           # Science communication and art portfolio
├── cv.html                # Curriculum vitae (web version)
├── blog.html              # Blog (placeholder for future posts)
├── contact.html           # Contact information
├── style.css              # Main stylesheet
├── script.js              # JavaScript for interactivity
├── about_me.md            # Content source (not deployed)
├── README.md              # This file
├── images/                # Image directory
│   ├── profile.jpg        # Your profile photo
│   └── art/               # Art portfolio images
│       ├── piece1.jpg
│       ├── piece2.jpg
│       └── ...
└── files/                 # Downloadable files
    └── Nirmitee_Mulay_CV.pdf  # PDF version of CV
```

## 🚀 Quick Deployment to GitHub Pages

### Step 1: Clone Your Repository Locally

```bash
# Navigate to where you want the repo
cd ~/Documents/websites/

# Clone your repository
git clone git@github.com:nirmitee-mulay/nirmitee-mulay.github.io.git

# Enter the directory
cd nirmitee-mulay.github.io
```

### Step 2: Add Website Files

Copy all the website files from `/mnt/user-data/outputs/` into your cloned repository:

```bash
# Copy all HTML files
cp /path/to/outputs/*.html .
cp /path/to/outputs/*.css .
cp /path/to/outputs/*.js .
cp /path/to/outputs/*.md .
```

Or simply download them from Claude and drag them into your local repository folder.

### Step 3: Add Your Images

1. **Profile Photo**: Add your profile photo as `images/profile.jpg`
2. **Art Portfolio**: Add your artwork images in `images/art/` directory
   - Name them piece1.jpg, piece2.jpg, etc., or update the `scicomm.html` file with your actual filenames

### Step 4: Add Your CV PDF

1. Create a `files/` directory
2. Export your CV as PDF and save it as `files/Nirmitee_Mulay_CV.pdf`

### Step 5: Create Directory Structure

```bash
# In your repository directory
mkdir -p images/art
mkdir -p files
```

### Step 6: Commit and Push

```bash
# Add all files
git add .

# Commit with a message
git commit -m "Initial website deployment"

# Push to GitHub
git push origin main
```

### Step 7: Enable GitHub Pages

1. Go to your repository on GitHub: https://github.com/nirmitee-mulay/nirmitee-mulay.github.io
2. Click **Settings**
3. Scroll to **Pages** section (left sidebar)
4. Under **Source**, select **Deploy from a branch**
5. Select **main** branch and **/ (root)** folder
6. Click **Save**

Your site will be live at: https://nirmitee-mulay.github.io in a few minutes!

## ✏️ Customization Guide

### Update Contact Information

Edit these files to add your actual links:
- All pages: Update ORCID, Google Scholar, Bluesky links in the social buttons
- `contact.html`: Add your full contact details

### Add Missing Information

Several sections have placeholders. Update these:

1. **Publications (publications.html)**:
   - Add talk titles for ASSC 2025 and thesis talk
   - Add poster title from Qualia Structure meeting
   - Add DOI/journal info for the derealization paper

2. **Research (research.html)**:
   - Update project descriptions as they progress
   - Add specific theoretical frameworks you're interested in

3. **Profile Photo**:
   - Replace `images/profile.jpg` with your actual photo
   - Recommended size: 800x800px, square aspect ratio

4. **Art Portfolio (scicomm.html)**:
   - Add your artwork images to `images/art/`
   - Update gallery items with actual titles and descriptions
   - Add link to external portfolio if you have one

5. **CV PDF**:
   - Export your LaTeX CV as PDF
   - Save as `files/Nirmitee_Mulay_CV.pdf`

### Color Scheme

The site uses a blue/teal professional palette. To change colors, edit the CSS variables in `style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue */
    --secondary-color: #0891b2;    /* Teal */
    --accent-color: #06b6d4;       /* Light cyan */
    /* Change these to your preferred colors */
}
```

### Adding Blog Posts

When ready to add blog posts:

1. Create individual blog post HTML files (e.g., `blog-post-1.html`)
2. Update `blog.html` to replace the "Coming Soon" section with actual post previews
3. Consider using a static site generator like Jekyll for easier blog management

## 📱 Features

- **Responsive Design**: Works on desktop, tablet, and mobile
- **Modern UI**: Clean, professional academic aesthetic
- **SEO Optimized**: Meta tags for search engines
- **Fast Loading**: Minimal dependencies, optimized CSS
- **Accessible**: Semantic HTML, keyboard navigation
- **Interactive**: Smooth animations, lightbox for images

## 🔧 Technical Details

- **Framework**: Vanilla HTML/CSS/JavaScript (no dependencies!)
- **Fonts**: Inter from Google Fonts
- **Icons**: Inline SVG icons
- **Hosting**: GitHub Pages (free!)
- **Browser Support**: All modern browsers

## 🎨 Design Philosophy

- Clean, academic aesthetic
- Emphasis on content over decoration
- Mobile-first responsive design
- Accessible color contrast
- Fast, lightweight performance

## 📝 Content Management

All your content is in the HTML files. To update:

1. **News/Updates**: Edit the "Latest Updates" section in `index.html`
2. **Publications**: Add new entries in `publications.html`
3. **Research Projects**: Update project cards in `research.html`
4. **CV**: Update `cv.html` AND regenerate `files/Nirmitee_Mulay_CV.pdf`

## 🐛 Troubleshooting

**Images not showing?**
- Check file paths are correct
- Ensure images are in the `images/` directory
- Check that file extensions match (jpg vs jpeg)

**Site not updating?**
- Clear browser cache (Cmd/Ctrl + Shift + R)
- Wait a few minutes for GitHub Pages to rebuild
- Check GitHub Actions for build errors

**Mobile menu not working?**
- Ensure `script.js` is loading
- Check browser console for errors

## 🚀 Future Enhancements

Consider adding:
- [ ] Blog with actual posts
- [ ] Google Analytics (optional)
- [ ] Contact form integration
- [ ] RSS feed for blog
- [ ] Dark mode toggle
- [ ] Search functionality
- [ ] Multilingual support (Spanish!)

## 📊 Analytics (Optional)

To add Google Analytics:
1. Create a Google Analytics account
2. Add the tracking code to the `<head>` of each HTML file
3. Monitor traffic and visitor behavior

## 🔒 Privacy

This is a static site with no:
- Cookies
- User tracking (unless you add analytics)
- Forms that collect data
- Backend database

## 📄 License

© 2026 Nirmitee Mulay. All rights reserved.

Feel free to use this template for your own academic website, but please:
- Remove personal content
- Update with your own information
- Give credit if sharing the template

## 💬 Questions?

If you have questions about the website:
- Check this README first
- Review the code comments in HTML/CSS/JS files
- Contact me via the methods on the website

---

**Built with care for open science** 🔬✨

Last updated: February 2026
