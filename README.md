# Aimen Gaba - Personal Academic Website

Clean, minimal academic portfolio website built with HTML and CSS.

## 📁 File Structure

```
final-website/
├── index.html              # Homepage (bio, photo, recent highlights)
├── publications.html       # Publications organized by type
├── portfolio.html          # Project portfolio with cards
├── writing.html           # Blog/writing posts
├── teaching.html          # Teaching & service activities
├── news-archive.html      # Complete news archive
├── css/
│   └── styles.css         # Main stylesheet (all styles in one file)
├── js/
│   └── (empty - for future JavaScript if needed)
└── assets/
    ├── images/
    │   └── (add your photos here)
    └── cv.pdf             # Your CV (add this file)
```

## 🚀 Quick Start

### 1. Add Your Content

**Profile Photo:**
- Add your photo to `assets/images/profile.jpg`
- Update line 61 in `index.html` to use: `src="assets/images/profile.jpg"`

**CV:**
- Add your CV PDF to `assets/cv.pdf`
- The navigation automatically links to it

**Update Links:**
- Search for `mailto:agaba@umass.edu` and update with your email
- Update Google Scholar, LinkedIn URLs throughout

### 2. Customize Content

**Homepage (`index.html`):**
- Edit bio paragraphs (lines 57-67)
- Add/remove recent highlights (lines 78-94)
- Update achievement badges (lines 71-74)

**Publications (`publications.html`):**
- Add publications by copying the `.pub-item` div (example at lines 38-47)
- Update title, authors, venue, and links
- Your name should be in `<strong>` tags

**Portfolio (`portfolio.html`):**
- Add projects by copying `.project-card` div (example at lines 42-57)
- Update project images by replacing gradient or adding actual images
- Modify tags, title, and description

**Writing (`writing.html`):**
- Add blog posts by copying `.blog-post` article (example at lines 38-51)
- Update title, date, category, and excerpt

**Teaching (`teaching.html`):**
- Add courses/activities by copying `.teaching-item` div
- Update title, role, semester, and description

**News Archive (`news-archive.html`):**
- Add news items by copying `<li>` elements (lines 38-40)
- Format: `<span class="hl-date">Date</span> <span class="hl-text">News text</span>`

## 🎨 Styling Guide

All styles are in `css/styles.css`. The file is organized into clear sections:

### Color Scheme
- **Primary Blue:** `#0066cc` (links, accents)
- **Text Primary:** `#1a1a1a` (main text)
- **Text Secondary:** `#666` (meta info)
- **Borders:** `#e5e5e5` (subtle lines)

### Key CSS Classes

**Text Styles:**
- `.bio` - Biography paragraphs
- `.pub-title` - Publication titles
- `.project-title` - Project titles
- `.teaching-title` - Course/activity titles

**Layout:**
- `.container` - Centers content (max-width: 1100px)
- `.about-grid` - Homepage grid (text + photo)
- `.portfolio-grid` - Portfolio card grid
- `.highlights-list` - News/highlights list

**Components:**
- `.badge` - Achievement badges
- `.project-card` - Portfolio project cards
- `.pub-item` - Publication items
- `.teaching-item` - Teaching/service items

### Modifying Styles

**Change colors:**
Edit the color values in `css/styles.css`:
- Line 14: Body text color
- Line 21: Link color
- Search for `#0066cc` to change primary blue

**Adjust spacing:**
- Section spacing: `.section { margin-bottom: ... }`
- Item spacing: `.pub-item { margin-bottom: ... }`

**Change fonts:**
- Name font (serif): Line 48 `font-family: 'Crimson Pro', serif;`
- Body font: Line 11 (system fonts)

## 📱 Responsive Design

The site is fully responsive:
- Desktop: Full layout with grids
- Tablet/Mobile: Single column, stacked layouts
- Responsive breakpoint: 768px (see bottom of `styles.css`)

## 🔧 Common Edits

### Adding a New Publication

Copy this block in `publications.html`:

```html
<div class="pub-item">
    <div class="pub-title">Your Paper Title</div>
    <div class="pub-authors"><strong>Aimen Gaba</strong>, Co-authors</div>
    <div class="pub-venue">Conference/Journal Name Year</div>
    <div class="pub-links">
        <a href="#" class="pub-link">[Paper]</a>
        <a href="#" class="pub-link">[Slides]</a>
    </div>
</div>
```

### Adding a New Project

Copy this block in `portfolio.html`:

```html
<div class="project-card">
    <div class="project-image">Project Image</div>
    <div class="project-content">
        <div class="project-tags">
            <span class="project-tag">Tag1</span>
            <span class="project-tag">Tag2</span>
        </div>
        <h3 class="project-title">Project Title</h3>
        <p class="project-description">
            Project description here...
        </p>
    </div>
</div>
```

### Adding News Items

In `index.html` (recent highlights) or `news-archive.html` (full list):

```html
<li>
    <span class="hl-date">Month Year</span>
    <span class="hl-text">News description</span>
</li>
```

## 🌐 Deployment

### GitHub Pages
1. Create a new repository on GitHub
2. Upload all files (keep folder structure)
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at `username.github.io/repo-name`

### Custom Domain
1. Add `CNAME` file with your domain (e.g., `aimengaba.com`)
2. Update DNS records with your domain provider
3. Enable HTTPS in GitHub Pages settings

## 💡 Tips

- **Keep it updated:** Regularly add new publications, projects, and news
- **Test responsiveness:** View on mobile before deploying
- **Optimize images:** Compress photos before adding (keep under 500KB)
- **Backup regularly:** Keep a local copy of your site
- **Version control:** Use Git to track changes

## 📝 Notes

- All HTML files use relative links (easy to move/rename)
- Single CSS file makes styling changes simple
- Comments throughout code explain each section
- No JavaScript required (can add later if needed)
- Clean, semantic HTML structure

## 🆘 Troubleshooting

**Photo not showing:**
- Check file path matches `src` attribute
- Ensure file is in `assets/images/` folder
- Check file extension (jpg, png, etc.)

**Links not working:**
- Verify file names match exactly (case-sensitive)
- Check that all HTML files are in root directory
- Ensure CSS file is in `css/` folder

**Layout looks broken:**
- Clear browser cache
- Check that `styles.css` is linked in `<head>`
- Verify CSS file path is correct

---

**Last Updated:** March 2026  
**Design:** Clean academic style inspired by Steven Rick & Cindy Xiong  
**Built with:** HTML5, CSS3 (no frameworks needed)
