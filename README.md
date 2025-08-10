# Personal Portfolio Website

A modern, responsive personal portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your professional experience, skills, and projects.

## Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Interactive Elements**: Hover effects, smooth scrolling, and animated components
- **Project Showcase**: Card-based project display with hover descriptions
- **Skills Section**: Organized technical skills with visual tags
- **Work Experience**: Timeline-style experience display
- **Professional Image**: Dedicated section for your profile photo
- **Social Links**: Easy access to your professional profiles

## Quick Start

1. **Clone or Download** this repository
2. **Customize** the content in `index.html` with your information
3. **Replace** placeholder images with your actual photos
4. **Deploy** to GitHub Pages or any web hosting service

## Customization Guide

### 1. Personal Information

Edit the header section in `index.html`:

```html
<h1 class="name">Your Name</h1>
<p class="subtitle">Your Title</p>
<p class="description">
    Your brief professional description here.
</p>
```

### 2. Profile Image

Replace the placeholder image URL with your actual photo:

```html
<img src="path/to/your/photo.jpg" alt="Your Name" class="profile-image">
```

**Recommended image specifications:**
- Size: 300x300 pixels (minimum)
- Format: JPG, PNG, or WebP
- Style: Professional headshot with good lighting

### 3. About Me Section

Update the "About Me" content:

```html
<div class="profile-info">
    <h2>About Me</h2>
    <p>
        Your detailed personal description here.
    </p>
</div>
```

### 4. Technical Skills

Modify the skills section to match your expertise:

```html
<div class="skill-category">
    <h3>Frontend</h3>
    <div class="skill-tags">
        <span class="skill-tag">Your Skill 1</span>
        <span class="skill-tag">Your Skill 2</span>
        <!-- Add more skills -->
    </div>
</div>
```

### 5. Projects

Update each project card with your actual projects:

```html
<a href="https://github.com/yourusername/project" class="project-card" target="_blank">
    <div class="project-image">
        <img src="path/to/project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description that appears on hover.</p>
    </div>
</a>
```

### 6. Work Experience

Update the experience timeline:

```html
<div class="experience-item">
    <div class="experience-date">2023 - Present</div>
    <div class="experience-content">
        <h3>Your Job Title</h3>
        <h4>Company Name</h4>
        <p>Your job description and achievements.</p>
        <div class="experience-tech">
            <span class="tech-tag">Technology 1</span>
            <span class="tech-tag">Technology 2</span>
        </div>
    </div>
</div>
```

### 7. Social Links

Update the footer with your actual social media profiles:

```html
<div class="social-links">
    <a href="https://github.com/yourusername" target="_blank" class="social-link">
        <i class="fab fa-github"></i>
    </a>
    <a href="https://linkedin.com/in/yourusername" target="_blank" class="social-link">
        <i class="fab fa-linkedin"></i>
    </a>
    <a href="mailto:your.email@example.com" class="social-link">
        <i class="fas fa-envelope"></i>
    </a>
</div>
```

## Deployment Options

### GitHub Pages (Recommended)

1. Create a new repository on GitHub
2. Upload all files to the repository
3. Go to Settings > Pages
4. Select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Your site will be available at `https://yourusername.github.io/repository-name`

### Other Hosting Services

- **Netlify**: Drag and drop the folder to deploy
- **Vercel**: Connect your GitHub repository
- **Firebase Hosting**: Use Firebase CLI to deploy
- **Traditional Web Hosting**: Upload files via FTP

## File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## Customization Tips

### Colors
The website uses a purple gradient theme. To change colors, edit the CSS variables in `styles.css`:

```css
/* Main gradient colors */
background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
```

### Fonts
The website uses Inter font from Google Fonts. To change fonts, update the font-family in `styles.css`:

```css
font-family: 'Your-Font', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
```

### Animations
All animations are CSS-based for smooth performance. You can adjust timing by modifying transition properties in `styles.css`.

## Performance Optimization

- Images are optimized for web use
- CSS and JavaScript are minified for production
- Font loading is optimized with font-display: swap
- Smooth scrolling and animations use hardware acceleration

## Accessibility

- Semantic HTML structure
- Proper heading hierarchy
- Alt text for images
- Focus indicators for keyboard navigation
- High contrast color scheme
- Screen reader friendly

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing or deploying your portfolio website, feel free to:

1. Check the customization guide above
2. Review the HTML structure in `index.html`
3. Modify CSS styles in `styles.css`
4. Add custom JavaScript functionality in `script.js`

## Contributing

Feel free to fork this project and customize it for your needs. If you make improvements that could benefit others, consider submitting a pull request.

---

**Happy coding! 🚀** 