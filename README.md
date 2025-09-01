# Modern Photography Portfolio

A stunning, modern portfolio website template designed for photographers, UI/UX designers, and creative professionals. Features contemporary design elements, smooth animations, and a sophisticated black, white, and olive green color scheme.


##  Features

- ** Modern Design**: Contemporary UI with glassmorphism effects and gradient backgrounds
- ** Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- ** Smooth Animations**: Custom cursor, parallax effects, and scroll-triggered animations
- ** Sophisticated Color Scheme**: Professional black, white, and olive green palette
- ** Performance Optimized**: Fast loading with efficient CSS and JavaScript
- ** Accessible**: Semantic HTML and keyboard navigation support
- ** Contact Form**: Functional contact form with validation
- ** Social Integration**: Easy social media links setup


##  Quick Start

### Option 1: Use This Template
1. Click the "Use this template" button above
2. Name your repository (e.g., `your-portfolio`)
3. Clone your new repository:
   ```bash
   git clone https://github.com/your-username/your-portfolio.git
   cd your-portfolio
   ```

### Option 2: Fork This Repository
1. Fork this repository
2. Clone your fork:
   ```bash
   git clone https://github.com/your-username/modern-photography-portfolio.git
   cd modern-photography-portfolio
   ```

### Option 3: Download
1. Download the ZIP file
2. Extract to your desired location
3. Open `index.html` in your browser

## ⚙️ Customization

### 1. Personal Information
Edit `index.html` and replace:

```html
<!-- Update navigation -->
<a href="#" class="logo">Your Name</a>

<!-- Update hero section -->
<h1>Your Title</h1>
<p class="subtitle">Your Profession</p>
<p class="description">Your personal description</p>

<!-- Update contact information -->
<span>Your Phone</span>
<span>Your Email</span>
<span>Your Location</span>
```

### 2. Add Your Images
Create an `images/` folder and add:
- `profile.jpg` - Your professional photo (600x800px recommended)
- Portfolio images (800x600px recommended)
- `preview.png` - Screenshot for README (optional)

### 3. Update Content Sections

**About Section:**
```html
<div class="about-text fade-in">
    <h2>About Me</h2>
    <p>Your first paragraph about yourself...</p>
    <p>Your second paragraph about your journey...</p>
    <div class="skills">
        <span class="skill-tag">Your Skill</span>
        <!-- Add more skills -->
    </div>
</div>
```

**Portfolio Section:**
```html
<div class="portfolio-item fade-in">
    <img src="images/your-image.jpg" alt="Project Title">
    <div class="portfolio-overlay">
        <h3>Project Title</h3>
        <p>Project description</p>
    </div>
</div>
```

### 4. Social Media Links
Update the social links in the contact section:
```html
<a href="https://facebook.com/yourprofile" target="_blank">
    <i class="fab fa-facebook-f"></i>
</a>
```

## Color Customization

Want different colors? Edit the CSS variables in `styles.css`:

```css
:root {
    --accent: #6b8e23;        /* Olive Green - Main accent */
    --accent-light: #9acd32;  /* Yellow Green - Light accent */
    --accent-dark: #556b2f;   /* Dark Olive Green - Dark accent */
    --accent-sage: #87a96b;   /* Sage Green - Soft accent */
}
```

### Popular Alternative Color Schemes:

**Ocean Blue:**
```css
--accent: #2563eb;
--accent-light: #60a5fa;
--accent-dark: #1d4ed8;
--accent-sage: #3b82f6;
```

**Royal Purple:**
```css
--accent: #7c3aed;
--accent-light: #a78bfa;
--accent-dark: #6d28d9;
--accent-sage: #8b5cf6;
```

**Sunset Orange:**
```css
--accent: #ea580c;
--accent-light: #fb923c;
--accent-dark: #c2410c;
--accent-sage: #f97316;
```

## 📁 File Structure

```
modern-photography-portfolio/
├── index.html          # Main HTML file
├── styles.css          # All styling (external file)
├── script.js           # JavaScript functionality (external file)
├── images/             # Your images directory
│   ├── profile.jpg     # Your profile photo
│   ├── portfolio-1.jpg # Portfolio images
│   └── ...
├── README.md           # Documentation
└── LICENSE             # License file (optional)
```

## Deployment

### GitHub Pages (Free)
1. Push your code to GitHub
2. Go to repository Settings
3. Navigate to "Pages" section
4. Select "Deploy from a branch"
5. Choose "main" branch
6. Your site will be available at `https://username.github.io/repository-name`

### Netlify (Free)
1. Connect your GitHub repository to Netlify
2. Deploy automatically with each push
3. Custom domain support available

### Vercel (Free)
1. Import your GitHub repository
2. Automatic deployments
3. Excellent performance optimization

## Technical Stack

- **HTML5**: Semantic markup for accessibility
- **CSS3**: Modern features including Grid, Flexbox, Custom Properties
- **Vanilla JavaScript**: No frameworks, pure performance
- **Font Awesome**: Icons for social media and contact
- **Google Fonts**: Professional typography

## Browser Support

- ✅ Chrome/Chromium 60+
- ✅ Firefox 55+
- ✅ Safari 12+
- ✅ Edge 79+
- ✅ Mobile browsers (iOS Safari, Chrome Mobile)

## Customization Tips

### For Photographers:
- Use high-resolution images (at least 1920x1080)
- Showcase variety in your portfolio
- Include behind-the-scenes content
- Add photography-specific skills

### For UI/UX Designers:
- Show case studies in portfolio items
- Include design process images
- Highlight design tools in skills
- Add links to Behance/Dribbble

### For Web Developers:
- Showcase live projects with links
- Include code snippets in descriptions
- Highlight technical skills
- Add GitHub profile link

## Troubleshooting

### Common Issues:

**Images not loading:**
- Check file paths are correct
- Ensure images are in the `images/` folder
- Verify image file extensions match HTML

**Animations not working:**
- Make sure `script.js` is linked correctly
- Check browser console for JavaScript errors
- Ensure CSS and JS files are in the same directory

**Layout issues on mobile:**
- Test with browser developer tools
- Check viewport meta tag is present
- Verify responsive CSS is loading

## Contributing

Contributions are welcome! Here's how you can help:

1. **Report Bugs**: Open an issue describing the problem
2. **Suggest Features**: Share ideas for improvements
3. **Submit Pull Requests**: Fix bugs or add features
4. **Improve Documentation**: Help make instructions clearer

### Development Setup:
```bash
# Clone the repository
git clone https://github.com/your-username/modern-photography-portfolio.git

# Navigate to project
cd modern-photography-portfolio

# Open in your preferred editor
code .

# Open index.html in browser to test changes
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Showcase

If you use this template for your portfolio, we'd love to see it! Share your creation by:
- Opening an issue with your portfolio URL
- Tagging us on social media
- Adding your site to our showcase section

## Connect

Created by **Nikini Fernando**
-  Portfolio: [your-portfolio-url]
-  Email: nikiniwarnakula@gmail.com
-  LinkedIn: [your-linkedin]
-  Instagram: [your-instagram]

---

###  Show Your Support

If this template helped you create an amazing portfolio, please give it a star! It helps others discover this resource.

**Made with ❤️ for the creative community**