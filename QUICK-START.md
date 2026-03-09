# QUICK START GUIDE

## ✅ Your Website is Ready!

All pages are complete and ready to use. Here's what you have:

### 📄 Pages Included:
1. **index.html** - Homepage with bio, photo, highlights
2. **publications.html** - Research publications
3. **portfolio.html** - Project portfolio  
4. **writing.html** - Blog/writing
5. **teaching.html** - Teaching & service
6. **news-archive.html** - Full news archive

### 🎨 Design Features:
✅ Clean, academic style (inspired by Steven Rick + Cindy Xiong)
✅ System fonts (crisp, native look)
✅ Serif font for your name (Crimson Pro)
✅ Consistent 1100px width across all pages
✅ Responsive (works on mobile, tablet, desktop)
✅ Blue accent color (#0066cc)
✅ Compact spacing, information-dense

## 🚀 To Use This Website:

### Option 1: GitHub Pages (Recommended)
1. Create GitHub repository
2. Upload all files
3. Enable GitHub Pages in Settings
4. Done! Site is live

### Option 2: Any Web Host
1. Upload all files to your hosting
2. Keep folder structure intact
3. Point domain to hosting
4. Done!

## ✏️ First Steps:

### Must Do:
1. Add your photo to `assets/images/profile.jpg`
2. Add your CV to `assets/cv.pdf`  
3. Update email, Google Scholar, LinkedIn links
4. Replace placeholder publications/projects with real ones

### Should Do:
5. Update bio text in `index.html`
6. Add real news items
7. Customize colors if desired (edit `css/styles.css`)

## 📝 How to Edit Content:

### Add a Publication:
Open `publications.html`, find the relevant section, copy a `.pub-item` block:

```html
<div class="pub-item">
    <div class="pub-title">Paper Title</div>
    <div class="pub-authors"><strong>Aimen Gaba</strong>, Others</div>
    <div class="pub-venue">Conference 2026</div>
    <div class="pub-links">
        <a href="#" class="pub-link">[Paper]</a>
    </div>
</div>
```

### Add a Project:
Open `portfolio.html`, copy a `.project-card` block:

```html
<div class="project-card">
    <div class="project-image">Image Text</div>
    <div class="project-content">
        <div class="project-tags">
            <span class="project-tag">Tag</span>
        </div>
        <h3 class="project-title">Title</h3>
        <p class="project-description">Description...</p>
    </div>
</div>
```

### Add News:
Open `index.html` or `news-archive.html`, add to the `<ul>` list:

```html
<li>
    <span class="hl-date">Month Year</span>
    <span class="hl-text">News item text</span>
</li>
```

## 🎨 Customization:

All styling is in **one file**: `css/styles.css`

### Change Colors:
Search for `#0066cc` (primary blue) and replace
Search for `#1a1a1a` (text color) and replace

### Change Spacing:
Look for `margin-bottom:` or `padding:` values in `css/styles.css`

### Change Fonts:
- Name: Line 48 in `styles.css` (currently Crimson Pro serif)
- Body: Line 11 in `styles.css` (currently system fonts)

## 📱 Mobile Friendly:

The site automatically adapts to mobile screens:
- Text becomes larger
- Photo and text stack vertically
- Navigation becomes single column
- Portfolio cards become single column

Test by resizing your browser window!

## 🔗 File Organization:

```
Your Website/
├── index.html              ← Homepage
├── publications.html       ← Publications
├── portfolio.html          ← Portfolio
├── writing.html           ← Blog
├── teaching.html          ← Teaching
├── news-archive.html      ← News
├── css/
│   └── styles.css         ← ALL STYLES HERE
└── assets/
    ├── images/
    │   └── profile.jpg    ← ADD YOUR PHOTO
    └── cv.pdf             ← ADD YOUR CV
```

## 💡 Pro Tips:

1. **Keep backups** - Save your original files before making changes
2. **Test locally** - Open `index.html` in your browser before deploying
3. **Use comments** - HTML comments already added, add more as needed
4. **Update regularly** - Keep publications and news current
5. **Check links** - Test all links after deploying

## ❓ Need Help?

Check the full **README.md** file for:
- Detailed instructions
- Troubleshooting guide
- CSS class reference
- Deployment instructions

---

**You're all set!** 🎉

Your clean, professional academic website is ready to go.
Just add your content and deploy!
