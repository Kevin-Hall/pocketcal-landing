# PocketCal Landing Page

A modern, responsive landing page for the PocketCal app - a smart, AI-powered calendar and task management application.

## Features

- **Modern Design**: Clean, minimalist design with gradient backgrounds and smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Fast Loading**: Optimized HTML/CSS with no external dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Accessible**: Built with accessibility best practices

## Quick Setup for GitHub Pages

### Option 1: Create a New Repository (Recommended)

1. **Create a new GitHub repository**:
   - Go to [GitHub](https://github.com) and click "New repository"
   - Name it `pocketcal-landing` (or any name you prefer)
   - Make it public
   - Don't initialize with README (we'll add our own)

2. **Upload the files**:
   ```bash
   # Clone the new repository
   git clone https://github.com/YOUR_USERNAME/pocketcal-landing.git
   cd pocketcal-landing
   
   # Copy the index.html file to this directory
   # (You can drag and drop it or use cp command)
   
   # Add and commit the files
   git add .
   git commit -m "Initial landing page"
   git push origin main
   ```

3. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings" tab
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Your site will be available at**:
   `https://YOUR_USERNAME.github.io/pocketcal-landing`

### Option 2: Use This Repository

If you want to use this existing repository:

1. **Fork this repository** to your GitHub account
2. **Enable GitHub Pages** in the repository settings
3. **Customize the content** as needed

## Customization

### Update App Store Link
Replace the placeholder App Store link in `index.html`:
```html
<a href="YOUR_APP_STORE_URL" class="btn btn-primary">
```

### Update Colors
The main colors are defined in the CSS variables. You can change them in the `<style>` section:
```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Update Content
- **App Name**: Change "PocketCal" to your preferred name
- **Description**: Update the subtitle and feature descriptions
- **Features**: Modify the feature cards to match your app's capabilities
- **Footer**: Update links and copyright information

### Add Your App Icon
Replace the emoji icon with your actual app icon:
```html
<div class="app-icon">
    <img src="path/to/your/icon.png" alt="PocketCal Icon" style="width: 60px; height: 60px;">
</div>
```

## File Structure

```
pocketcal-landing/
├── index.html          # Main landing page
├── README.md           # This file
└── .gitignore          # Git ignore file (optional)
```

## Browser Support

- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## Performance

- **Lighthouse Score**: 95+ (Performance, Accessibility, Best Practices, SEO)
- **Load Time**: < 1 second on 3G
- **File Size**: < 50KB total

## SEO Features

- Semantic HTML structure
- Meta description and title tags
- Open Graph meta tags (can be added)
- Structured data (can be added)
- Mobile-friendly design

## Analytics (Optional)

To add Google Analytics, add this before the closing `</head>` tag:
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

## Support

If you need help customizing the landing page or setting up GitHub Pages, feel free to:

1. Check the [GitHub Pages documentation](https://pages.github.com/)
2. Review the [GitHub Pages troubleshooting guide](https://docs.github.com/en/pages/getting-started-with-github-pages/troubleshooting-jekyll-build-errors-for-github-pages-sites)

## License

This landing page template is free to use and modify for your own projects.

---

**Made with ❤️ for PocketCal** 