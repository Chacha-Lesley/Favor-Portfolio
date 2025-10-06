# Favor Khaoya Portfolio Website

A modern, responsive portfolio website showcasing marketing expertise, case studies, and creative campaigns.

## 🎨 Color Scheme

- **Primary Green**: `#2ad882`
- **Dark Background**: `#1f242b`
- **Black**: `#000000`
- **White**: `#ffffff`
- **Text Gray**: `#a8b2b9`
- **Card Background**: `#2a2f36`

## 📁 Folder Structure

```
portfolio/
│
├── index.html                 # Main HTML file
├── styles.css                 # All styling
├── script.js                  # JavaScript functionality
├── README.md                  # This file
│
├── images/
│   ├── profile/
│   │   └── favor-khaoya.jpg              # Profile picture (200x200px recommended)
│   │
│   ├── experience/
│   │   ├── company-logo-1.jpg            # Company logo 1
│   │   ├── company-logo-2.jpg            # Company logo 2
│   │   ├── proof-1.jpg                   # Work proof image 1
│   │   ├── proof-2.jpg                   # Work proof image 2
│   │   ├── proof-3.jpg                   # Work proof image 3
│   │   ├── proof-4.jpg                   # Work proof image 4
│   │   └── proof-5.jpg                   # Work proof image 5
│   │
│   ├── projects/
│   │   ├── digital-marketing.jpg         # Main project image
│   │   ├── proof-digital-1.jpg           # Proof for digital marketing
│   │   ├── proof-digital-2.jpg           # Proof for digital marketing
│   │   ├── content-strategy.jpg          # Main project image
│   │   ├── proof-content-1.jpg           # Proof for content strategy
│   │   ├── proof-content-2.jpg           # Proof for content strategy
│   │   ├── partnerships.jpg              # Main project image
│   │   ├── proof-partnership-1.jpg       # Proof for partnerships
│   │   ├── proof-partnership-2.jpg       # Proof for partnerships
│   │   ├── financial-optimization.jpg    # Main project image
│   │   ├── proof-financial-1.jpg         # Proof for financial optimization
│   │   └── proof-financial-2.jpg         # Proof for financial optimization
│   │
│   └── campaigns/
│       ├── campaign-1.jpg                # Campaign poster 1
│       ├── campaign-2.jpg                # Campaign poster 2
│       ├── campaign-3.jpg                # Campaign poster 3
│       ├── campaign-4.jpg                # Campaign poster 4
│       ├── campaign-5.jpg                # Campaign poster 5
│       └── campaign-6.jpg                # Campaign poster 6
│
└── assets/                    # Optional: Additional resources
    ├── fonts/                 # Custom fonts (if needed)
    └── icons/                 # Custom icons (if needed)
```

## 🖼️ Image Guidelines

### Profile Picture
- **Location**: `images/profile/favor-khaoya.jpg`
- **Recommended Size**: 200x200px
- **Format**: JPG or PNG
- **Style**: Professional headshot with good lighting

### Company Logos
- **Location**: `images/experience/`
- **Recommended Size**: 300x200px
- **Format**: JPG or PNG (PNG preferred for transparency)
- **Style**: Clean, professional logos

### Experience Proof Images
- **Location**: `images/experience/`
- **Recommended Size**: 400x300px
- **Format**: JPG or PNG
- **Content**: Screenshots of work, certificates, project deliverables

### Project Images
- **Location**: `images/projects/`
- **Main Images**: 600x400px
- **Proof Images**: 300x200px
- **Format**: JPG or PNG
- **Content**: Project screenshots, dashboards, reports, results

### Campaign Posters
- **Location**: `images/campaigns/`
- **Recommended Size**: 800x800px or 1080x1080px (square aspect ratio)
- **Format**: JPG or PNG
- **Content**: Your creative campaign designs and posters

## 🚀 Features

### Interactive Elements
- ✨ Smooth scrolling navigation
- 📱 Fully responsive mobile menu
- 🖼️ Image modal/lightbox for proof images
- 🎯 Scroll-triggered animations
- 🎨 Hover effects on all interactive elements
- 📊 Active navigation highlighting
- ⚡ Parallax effect on hero section

### Sections
1. **Hero** - Introduction with profile picture
2. **About** - Professional summary
3. **Experience** - Timeline with company logos and proof images
4. **Projects** - Case studies with results and proof
5. **Campaigns** - Creative campaign showcase
6. **Skills** - Categorized skill sets
7. **Published Work** - Articles and blogs
8. **Contact** - Email and LinkedIn

## 🛠️ Setup Instructions

1. **Download all files** (index.html, styles.css, script.js, README.md)

2. **Create the folder structure** as shown above

3. **Add your images**:
   - Replace placeholder image paths with your actual images
   - Ensure all images are optimized for web (compressed)
   - Maintain recommended dimensions for best results

4. **Customize content**:
   - Open `index.html` and update:
     - Company names in experience section
     - Campaign titles
     - Any additional information
   
5. **Update links**:
   - Replace LinkedIn URL with your actual profile
   - Add any additional social media links if needed

6. **Test locally**:
   - Open `index.html` in a web browser
   - Test all navigation and interactive elements
   - Verify images load correctly

7. **Deploy**:
   - Upload all files and folders to your web hosting
   - Or use platforms like GitHub Pages, Netlify, or Vercel

## 📝 Customization Guide

### Updating Colors
All colors are defined in CSS variables at the top of `styles.css`:
```css
:root {
    --primary-green: #2ad882;
    --dark-bg: #1f242b;
    --black: #000000;
    --white: #ffffff;
    --text-gray: #a8b2b9;
    --card-bg: #2a2f36;
}
```

### Adding More Campaigns
In `index.html`, add new campaign items in the campaigns section:
```html
<div class="campaign-item">
    <img src="images/campaigns/campaign-7.jpg" alt="Campaign 7">
    <div class="campaign-overlay">
        <h4>Your Campaign Title</h4>
    </div>
</div>
```

### Adding More Experience
Add new experience items in the experience timeline:
```html
<div class="experience-item">
    <div class="experience-image">
        <img src="images/experience/company-logo-3.jpg" alt="Company Logo">
    </div>
    <div class="experience-content">
        <h3>Job Title</h3>
        <h4 class="company-name">Company Name</h4>
        <p class="duration">Start Date - End Date</p>
        <ul class="responsibilities">
            <li>Responsibility 1</li>
            <li>Responsibility 2</li>
        </ul>
    </div>
</div>
```

## 🌐 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## 📱 Responsive Breakpoints

- **Desktop**: > 768px
- **Tablet**: 481px - 768px
- **Mobile**: < 480px

## ⚡ Performance Tips

1. **Optimize Images**:
   - Use tools like TinyPNG or ImageOptim
   - Target file sizes: < 200KB for large images, < 100KB for thumbnails

2. **Enable Lazy Loading**:
   - Images already include lazy loading via Intersection Observer
   - Add `data-src` attribute instead of `src` for lazy loading

3. **Minify Files** (for production):
   - Minify CSS and JavaScript
   - Use tools like UglifyJS or online minifiers

## 🔧 Troubleshooting

### Images not showing?
- Check file paths are correct
- Ensure images are in the correct folders
- Verify image file names match exactly (case-sensitive)

### Navigation not working?
- Ensure section IDs match href values
- Check JavaScript file is properly linked

### Mobile menu not opening?
- Clear browser cache
- Check console for JavaScript errors

## 📞 Support

For questions or issues:
- Email: Khaoyafavor@gmail.com
- LinkedIn: [Favor Khaoya](https://linkedin.com/in/favor-khaoya)

## 📄 License

This portfolio template is free to use and modify for personal use.

---

**Built with ❤️ by Favor Khaoya**