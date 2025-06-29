# Intellium.space - GitHub Pages Ready

A modern AI-powered platform for sports betting and trading predictions. This repository contains the static website files optimized for GitHub Pages deployment.

## 🚀 GitHub Pages Deployment

### Automatic Deployment (Recommended)

1. **Fork or Upload to GitHub**
   - Create a new repository on GitHub
   - Upload all files to your repository

2. **Enable GitHub Pages**
   - Go to repository Settings → Pages
   - Set Source to "Deploy from a branch"
   - Select "main" branch and "/ (root)" folder
   - Click Save

3. **Access Your Site**
   - Your site will be available at: `https://yourusername.github.io/repository-name`
   - It may take a few minutes to deploy initially

### Manual Configuration

If you want to use a custom domain:

1. Add a `CNAME` file to the root directory with your domain name
2. Configure your DNS settings to point to GitHub Pages
3. Update the `_config.yml` file with your actual domain

## 📁 File Structure

```
intellium.space/
├── index.html              # Main homepage (GitHub Pages entry point)
├── about/
│   ├── index.html
│   ├── styles.css
│   └── scripts.js
├── features/
│   ├── index.html
│   ├── styles1.css
│   └── scripts.js
├── pricing/
│   ├── index.html
│   ├── styles.css
│   └── scripts.js
├── order-confirmation/
│   ├── index.html
│   ├── styles.css
│   └── scripts.js
├── home/
│   ├── index.html
│   ├── styles.css
│   ├── script1.js
│   └── script2.js
├── _config.yml             # Jekyll configuration
└── README.md               # This file
```

## 🔧 Technical Details

- **Framework**: Static HTML/CSS/JavaScript (Webflow-generated)
- **Hosting**: GitHub Pages with Jekyll
- **Navigation**: Relative paths for cross-page linking
- **CSS**: Individual stylesheets per page for optimization
- **Images**: Hosted on Webflow CDN (external resources)

## 🌐 Features

- **Responsive Design**: Mobile and desktop optimized
- **AI-Powered Predictions**: Sports betting and trading insights
- **Modern UI**: Clean, professional interface
- **Mongolian Language**: Localized content
- **E-commerce Integration**: Pricing and subscription pages

## 📝 Customization

### Updating Content
- Edit HTML files directly in each directory
- CSS files are located alongside HTML files
- JavaScript functionality is split across multiple files

### Styling
- Each page has its own CSS file
- Global styles are managed through Webflow classes
- External fonts loaded from Google Fonts

### Navigation
- All navigation uses relative paths (`../page/`)
- Logo links return to homepage (`../`)
- Consistent navigation across all pages

## 🛠 Development

For local development:

1. Clone the repository
2. Open `index.html` in a browser
3. Use a local server for testing (e.g., `python -m http.server`)

## 📧 Contact

For questions or support, contact: contact@intellium.space

## 📄 License

© 2025 Intellium. All rights reserved. 