# Aarohi Sharma - Reels Editor for Fitness Coaches Portfolio

A modern, vibrant portfolio website for Aarohi Sharma, a specialized reels editor focused on helping fitness coaches turn their content into client-generating machines. This website showcases her editing expertise, service packages, and provides a platform for fitness coaches to get in touch.

## 🎨 Features

- **Modern Design**: Clean, vibrant design with gradient colors and smooth animations
- **Responsive Layout**: Fully responsive design that works on all devices
- **Interactive Elements**: Smooth scrolling, hover effects, and animated counters
- **Contact Form**: Functional contact form with validation
- **Portfolio Showcase**: Grid layout to display fitness coaching reels
- **Pricing Packages**: Three tier pricing structure ($500, $650, $800)
- **Testimonials Section**: Client success stories and feedback videos
- **Service Sections**: Specialized reels editing for fitness coaches
- **Social Media Integration**: Direct links to Instagram portfolio

## 🚀 Getting Started

### Prerequisites
- A modern web browser
- Basic knowledge of HTML, CSS, and JavaScript (for customization)

### Installation
1. Download or clone the repository
2. Open `index.html` in your web browser
3. The website should load immediately with all functionality

## 📁 File Structure

```
Aarohi Portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🎯 Customization Guide

### 1. Personal Information
Update the following sections in `index.html`:

#### Hero Section
```html
<h1 class="hero-title">Hello, I'm <span class="highlight">Aarohi Sharma</span></h1>
<h2 class="hero-subtitle">Reels Editor for Fitness Coaches</h2>
```

#### About Section
```html
<p>I'm Aarohi Sharma, a specialized reels editor focused on helping fitness coaches...</p>
```

#### Contact Information
```html
<p>editsbyaaro@gmail.com</p>
<p>Bihar, India</p>
```

### 2. Statistics
Update the stats in the stats section:
```html
<div class="stat-number">500K+</div>
<div class="stat-label">Views Generated</div>
```

### 3. Services
Modify the services section to match fitness coaching focus:
```html
<div class="service-card">
    <div class="service-icon">
        <i class="fas fa-dumbbell"></i>
    </div>
    <h3>Fitness Reels Editing</h3>
    <p>Transform your workout videos into engaging reels...</p>
</div>
```

### 4. Portfolio
Replace placeholder portfolio items with fitness coaching content:
```html
<div class="portfolio-item">
    <div class="portfolio-image">
        <!-- Add fitness coaching video thumbnails -->
        <div class="placeholder-video">
            <i class="fas fa-play"></i>
        </div>
    </div>
    <div class="portfolio-overlay">
        <h3>Transformation Reels</h3>
        <p>Before & After Stories</p>
    </div>
</div>
```

### 5. Social Media Links
Update the social media links in the contact section:
```html
<div class="social-icons">
    <a href="https://www.instagram.com/editsby.aaro/" target="_blank" class="social-icon">
        <i class="fab fa-instagram"></i>
    </a>
</div>
```

### 6. Colors and Styling
Customize the color scheme in `styles.css`:

#### Primary Colors (Yellowish Theme)
```css
:root {
    --primary-color: #f59e0b;      /* Main brand color - Amber */
    --secondary-color: #eab308;    /* Accent color - Yellow */
    --accent-color: #f97316;       /* Highlight color - Orange */
    --success-color: #22c55e;      /* Success messages - Green */
    --warning-color: #f59e0b;      /* Warning messages - Amber */
    --info-color: #3b82f6;         /* Info messages - Blue */
}
```

#### Yellowish Gradients
```css
--gradient-primary: linear-gradient(135deg, #fbbf24 0%, #f59e0b 100%);
--gradient-secondary: linear-gradient(135deg, #fde047 0%, #eab308 100%);
--gradient-accent: linear-gradient(135deg, #fed7aa 0%, #fb923c 100%);
```

### 7. Images and Media
Replace placeholder images with your actual content:

1. **Profile Image**: Replace the placeholder in the hero section with your photo
2. **About Image**: Add a professional photo in the about section
3. **Portfolio Images**: Add thumbnails or screenshots of your video projects

### 8. Form Functionality
The contact form currently shows a success message. To make it functional:

1. **Email Integration**: Connect to an email service like EmailJS or Formspree
2. **Backend Integration**: Set up a backend server to handle form submissions
3. **CRM Integration**: Connect to a CRM system for lead management

## 🎨 Design Customization

### Typography
The website uses Google Fonts:
- **Primary**: Poppins (Sans-serif)
- **Secondary**: Playfair Display (Serif)

To change fonts, update the Google Fonts link in the HTML head and modify the CSS variables.

### Layout Adjustments
- **Section Spacing**: Modify `--section-padding` in CSS
- **Container Width**: Adjust `max-width` in `.container` class
- **Grid Layouts**: Modify grid-template-columns for different layouts

### Animations
Customize animations in `script.js`:
- **Scroll Animations**: Adjust timing and effects
- **Counter Animations**: Modify speed and easing
- **Hover Effects**: Customize transform and transition properties

## 📱 Mobile Optimization

The website is fully responsive with:
- Mobile-first design approach
- Touch-friendly navigation
- Optimized images and layouts
- Fast loading times

## 🔧 Technical Features

### JavaScript Functionality
- Smooth scrolling navigation
- Active section highlighting
- Form validation and submission
- Animated counters
- Intersection Observer for scroll animations
- Mobile menu toggle
- Notification system

### CSS Features
- CSS Grid and Flexbox layouts
- CSS Custom Properties (variables)
- Smooth transitions and animations
- Responsive breakpoints
- Modern CSS features (backdrop-filter, etc.)

## 🚀 Deployment

### Local Development
1. Open the files in a code editor
2. Use a local server (Live Server extension in VS Code)
3. Test all functionality

### Web Hosting
1. Upload files to your web hosting provider
2. Ensure all files are in the same directory
3. Test the website on different devices

### Recommended Hosting Platforms
- **Netlify**: Easy deployment with drag-and-drop
- **Vercel**: Great for static sites
- **GitHub Pages**: Free hosting for GitHub repositories
- **Traditional Hosting**: Any web hosting service

## 📞 Support and Customization

### Key Features Added
1. **Pricing Section**: Three-tier package structure for fitness coaches
2. **Testimonials**: Client success story video placeholders
3. **Specialized Content**: Fitness-focused services and portfolio
4. **Direct Links**: Google Drive portfolios and Instagram integration
5. **Conversion Focus**: Business-oriented copy and CTAs

### Performance Optimization
- Compress images before uploading
- Minify CSS and JavaScript for production
- Use a CDN for external resources
- Enable browser caching

## 📄 License

This template is created for AADI's portfolio. Feel free to customize and use for your own projects.

## 🤝 Contributing

If you find any issues or have suggestions for improvements, feel free to:
1. Report bugs
2. Suggest new features
3. Submit pull requests

## 📧 Contact

For questions about this portfolio template or reels editing services, contact Aarohi at editsbyaaro@gmail.com or visit her Instagram @editsby.aaro

**Portfolio Links**:
- Client Work: https://drive.google.com/drive/folders/1zFXOPH_9hOkFB2_IfOKNus6t3KVaj95I
- Testimonials: https://drive.google.com/drive/folders/1nVTain6V5rXXSpat9GVPRbazOPitZ61W

---

**Note**: This portfolio is optimized for fitness coaches seeking professional reels editing services. The pricing packages are designed for international clients targeting 5-6 figure scaling.
