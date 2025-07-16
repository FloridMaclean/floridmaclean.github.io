# Florid Maclean - Portfolio Website

A modern, responsive portfolio website showcasing expertise in mobile development and teaching at Fanshawe College.

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Fully Responsive**: Optimized for all devices (desktop, tablet, mobile)
- **Interactive Elements**: Smooth scrolling, hover effects, and animations
- **Professional Sections**: Hero, About, Experience, Skills, Projects, Teaching, and Contact
- **Contact Form**: Functional contact form with validation
- **Performance Optimized**: Fast loading with optimized assets

## 📁 Project Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and animations
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Setup Instructions

1. **Clone or Download**: Get the project files to your local machine
2. **Open in Browser**: Simply open `index.html` in your web browser
3. **Local Development**: For development, you can use any local server:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js (if you have http-server installed)
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

## 🎨 Customization Guide

### Personal Information
Update the following sections in `index.html`:

1. **Hero Section** (lines 60-75):
   ```html
   <h1 class="hero-title">
       Hi, I'm <span class="highlight">Your Name</span>
   </h1>
   <p class="hero-subtitle">Your Title</p>
   <p class="hero-description">
       Your personal description here...
   </p>
   ```

2. **About Section** (lines 85-105):
   ```html
   <p>
       Your personal story and background...
   </p>
   ```

3. **Experience Timeline** (lines 120-160):
   ```html
   <div class="timeline-content">
       <h3>Your Job Title</h3>
       <h4>Company Name</h4>
       <p class="timeline-date">Year - Year</p>
       <p>Job description...</p>
   </div>
   ```

4. **Skills Section** (lines 170-220):
   - Update skill names and percentages
   - Modify the `width` property in the `skill-progress` divs

5. **Projects Section** (lines 230-290):
   ```html
   <div class="project-content">
       <h3>Project Name</h3>
       <p>Project description...</p>
       <div class="project-tech">
           <span>Technology 1</span>
           <span>Technology 2</span>
       </div>
   </div>
   ```

6. **Contact Information** (lines 350-380):
   ```html
   <div class="contact-item">
       <i class="fas fa-envelope"></i>
       <div>
           <h4>Email</h4>
           <p>your.email@example.com</p>
       </div>
   </div>
   ```

### Styling Customization

#### Colors
Update the color scheme in `styles.css`:

```css
/* Primary Colors */
--primary-color: #6366f1;      /* Main brand color */
--secondary-color: #fbbf24;    /* Accent color */
--text-color: #1f2937;         /* Main text color */
--light-bg: #f8fafc;          /* Light background */
```

#### Fonts
Change the font family in `styles.css`:

```css
body {
    font-family: 'Your Font', sans-serif;
}
```

Add your preferred font from Google Fonts in the `<head>` section of `index.html`.

### Adding New Sections

1. **Create the HTML structure** in `index.html`
2. **Add corresponding CSS** in `styles.css`
3. **Update navigation** if needed
4. **Add JavaScript functionality** if required

## 📱 Responsive Design

The website is fully responsive with breakpoints at:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🎯 Key Features Explained

### Navigation
- Fixed navigation bar with smooth scrolling
- Mobile hamburger menu
- Active section highlighting

### Animations
- Intersection Observer for scroll-triggered animations
- Skill bar progress animations
- Counter animations for statistics
- Typing effect on hero title

### Contact Form
- Form validation (client-side)
- Success/error notifications
- Simulated form submission

### Performance
- Optimized images and assets
- Smooth scrolling
- Efficient CSS animations

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you need help customizing this portfolio or have questions, feel free to reach out!

---

**Built with ❤️ for mobile development and education** 