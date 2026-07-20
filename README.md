# FRC 11784 Alconbury Robotics Website

Welcome to the official website for FRC Team 11784 Alconbury Robotics!

## 📁 Project Structure

```
website/
├── index.html              # Home page
├── outreach.html           # Outreach page (empty - ready for content)
├── sponsorship.html        # Sponsorship page (empty - ready for content)
├── open-source.html        # Open source materials page (empty - ready for content)
├── blog.html               # Blog page (empty - ready for content)
├── css/
│   └── style.css          # Main stylesheet with green & yellow color scheme
├── js/
│   └── script.js          # JavaScript for navigation & interactions
├── assets/                # Folder for images, logos, and media files
│   ├── images/            # Team photos, event photos
│   ├── logos/             # Sponsor logos, team logos
│   └── documents/         # PDFs, sponsorship packets, etc.
└── README.md              # This file
```

## 🎨 Color Scheme

The website uses the Alconbury Robotics brand colors:
- **Primary Green**: `#1a5d3a` (Dark Green)
- **Secondary Green**: `#2d7d52` (Medium Green)
- **Light Green**: `#4fa373`
- **Primary Yellow**: `#f4b819` (Gold/Yellow)
- **Dark Gray**: `#2c3e50` (Text)

These colors are defined as CSS variables in `css/style.css` and can be easily customized.

## 📖 Getting Started

### 1. Viewing the Website
- Simply open `index.html` in your web browser
- All pages are linked through the navigation menu
- The website is fully responsive and works on mobile devices

### 2. Editing Content

#### Adding Content to Existing Pages
Each page has a placeholder section with `📋 Content Coming Soon`. Replace this with your actual content:

```html
<div class="placeholder">
    <h3>📋 Content Coming Soon</h3>
    <p>Your content here</p>
</div>
```

#### Adding Images
1. Place images in the `assets/images/` folder
2. Reference them in HTML:
```html
<img src="assets/images/your-image.jpg" alt="Description">
```

#### Creating New Blog Posts
1. Create a new HTML file (e.g., `blog-post-1.html`)
2. Copy the structure from `blog.html`
3. Replace the content section with your blog post
4. Add a link to your new post on the main `blog.html` page

#### Adding Sponsor Logos
1. Place sponsor logos in `assets/logos/`
2. Create a sponsors section on your pages:
```html
<div class="sponsors-grid">
    <img src="assets/logos/sponsor1.png" alt="Sponsor 1">
    <img src="assets/logos/sponsor2.png" alt="Sponsor 2">
</div>
```

### 3. Customizing the Style

#### Change the Color Scheme
Edit the CSS variables at the top of `css/style.css`:
```css
:root {
    --primary-green: #1a5d3a;  /* Change to your primary color */
    --primary-yellow: #f4b819; /* Change to your accent color */
    /* ... other colors ... */
}
```

#### Add Custom CSS
Add your own styles at the bottom of `css/style.css` without affecting the existing styles.

#### Modify the Navigation
Edit the `<nav>` section in any HTML file to change menu items or add new links.

### 4. Navigation Menu
All pages have the same navigation menu. To add a new page:
1. Create the new HTML file
2. Add a link to the menu in **all** HTML files:
```html
<li><a href="new-page.html">New Page</a></li>
```

## 🔧 Technical Details

### No Dependencies
This website uses **only HTML, CSS, and vanilla JavaScript** - no frameworks or build tools needed. This makes it:
- Easy to host anywhere (GitHub Pages, your own server, etc.)
- Simple to edit and maintain
- Fast to load
- Independent of any third-party libraries

### Responsive Design
The website is mobile-friendly and includes:
- Mobile hamburger menu
- Responsive grid layouts
- Flexible typography

### Browser Support
Works on all modern browsers (Chrome, Firefox, Safari, Edge)

## 📝 Content Suggestions

### Home Page
- Already includes: Team name, tagline, quick navigation
- Consider adding: Video hero, latest news, upcoming events

### Outreach Page
- Team community engagement initiatives
- STEM education programs
- School visits and demonstrations
- Photo galleries

### Sponsorship Page
- Your fundraising needs
- Sponsorship tier packages
- Benefits for sponsors
- Contact information
- Sponsor logos

### Open Source Page
- GitHub repository links
- CAD files and designs
- Code samples and documentation
- Build guides and tutorials

### Blog Page
- Competition recaps
- Technical articles
- Team member spotlights
- Build season updates
- Lessons learned

## 📧 Contact & Social Media

Consider adding:
- Email address
- Social media links (Facebook, Instagram, LinkedIn, Twitter/X, GitHub)
- Discord server link
- Mailing list signup

## 🚀 Deployment

You can host this website for free on:
- **GitHub Pages**: Push your repository to GitHub and enable Pages
- **Netlify**: Drag and drop your website folder
- **Vercel**: Connect your repository
- **Any web hosting service**: Upload the files via FTP

## 🎯 Next Steps

1. Add your team's content to each page
2. Upload team photos and logos to the `assets/` folder
3. Customize the colors if desired
4. Add social media links
5. Deploy to a web host

## 📞 Need Help?

- Reference the HTML comments in each file
- Check the CSS utility classes (`.text-center`, `.mt-1`, `.mb-2`, etc.)
- All sections have placeholder content with suggestions

Good luck with FRC Team 11784! Go Dragons! 🐉

---

**Last Updated**: July 2026
**Created for**: FRC Team 11784 Alconbury Robotics
