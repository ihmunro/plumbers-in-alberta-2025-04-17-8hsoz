# Plumbers in Alberta Directory Website

![Website Preview](./images/preview.png)

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Directory Structure](#directory-structure)
- [Customization Guide](#customization-guide)
- [Deployment](#deployment)
- [Troubleshooting](#troubleshooting)
- [Support](#support)

## Overview
A comprehensive directory website showcasing plumbers across Alberta. The site features a responsive 3-column grid layout, search functionality, and categorized listings.

## Features
- Responsive 3-column grid layout
- Search functionality
- Category filtering
- Contact forms for each listing
- Mobile-friendly design
- SEO optimized structure
- Fast loading times

## Getting Started

### Prerequisites
- Text editor (VS Code recommended)
- Basic HTML/CSS knowledge
- Web hosting account

### Installation
1. Download the website files
2. Extract to your local machine
3. Open `index.html` to preview locally

## Directory Structure
```
plumbers-alberta/
├── index.html
├── css/
│   ├── style.css
│   └── responsive.css
├── js/
│   ├── main.js
│   └── search.js
├── images/
│   └── listings/
└── data/
    └── directory.json
```

## Customization Guide

### Adding New Directory Listings
1. Open `data/directory.json`
2. Add new listing using the following format:
```json
{
  "id": "unique-id",
  "name": "Plumber Name",
  "category": "Residential",
  "phone": "(555) 555-5555",
  "address": "123 Main St, Calgary, AB",
  "website": "https://example.com"
}
```

### Modifying Categories
1. Open `index.html`
2. Locate the category section:
```html
<div class="categories">
  <!-- Add or modify categories here -->
  <button class="category-btn" data-category="residential">Residential</button>
</div>
```

### Updating Hero Section
1. Open `index.html`
2. Find the hero section:
```html
<section class="hero">
  <h1>Your Title Here</h1>
  <p>Your description here</p>
</section>
```

### Customizing Colors
1. Open `css/style.css`
2. Modify the root variables:
```css
:root {
  --primary-color: #007bff;
  --secondary-color: #6c757d;
  --background-color: #ffffff;
}
```

## Deployment

### Standard Hosting
1. Upload all files to your hosting provider
2. Ensure file permissions are set correctly
3. Test all functionality

### Custom Domain Setup
1. Purchase domain name
2. Update DNS settings:
   - A Record: Point to your hosting IP
   - CNAME: www to your domain
3. Wait for DNS propagation (24-48 hours)

## Troubleshooting

### Common Issues
- **Images not loading**: Check file paths and permissions
- **Search not working**: Verify `search.js` is properly linked
- **Mobile layout issues**: Clear browser cache, check responsive.css

### Performance Optimization
- Compress images using tools like TinyPNG
- Minify CSS/JS files
- Enable browser caching
- Use a CDN for assets

## Support

### Resources
- [Documentation Wiki](https://wiki.example.com)
- [Video Tutorials](https://tutorials.example.com)
- [Support Forum](https://forum.example.com)

### Contact
For technical support:
- Email: support@example.com
- Phone: (555) 123-4567
- Hours: Mon-Fri, 9AM-5PM MST

### Updates
Subscribe to our newsletter for updates:
- [Newsletter Signup](https://newsletter.example.com)

---

© 2024 Plumbers in Alberta. All rights reserved.