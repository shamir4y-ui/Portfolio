<!-- ============================================
     Personal Portfolio Website
     ============================================ -->

# Personal Portfolio Website

A modern, responsive, and fully functional personal portfolio website built with HTML, CSS, and JavaScript. This website is hosted on GitHub Pages and showcases your skills, projects, and professional experience.

## 🎨 Features

- **Responsive Design**: Fully mobile-friendly and works seamlessly on all devices
- **Modern Styling**: Clean and professional design with smooth animations
- **Multiple Sections**:
  - Hero Section: Eye-catching introduction
  - About Me: Personal introduction and background
  - Projects: Showcase of your work with project cards
  - Skills: Organized display of technical and soft skills
  - Contact: Contact form and social media links
  - Navigation: Sticky navigation with smooth scrolling

- **Smooth Animations**: Fade-in effects and hover animations
- **Interactive Contact Form**: Email validation and user feedback
- **Social Media Integration**: Links to your professional profiles
- **Accessibility**: Semantic HTML and proper ARIA attributes

## 📁 File Structure

```
Portfolio/
├── index.html           # Main HTML file with all sections
├── styles.css          # Complete styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md           # This file
```

## 🚀 Getting Started

### Option 1: Local Development

1. Clone the repository:
```bash
git clone https://github.com/shamir4y-ui/Portfolio.git
cd Portfolio
```

2. Open the `index.html` file in your browser:
   - Simply double-click the file, or
   - Use a local server (e.g., Python: `python -m http.server 8000`)

### Option 2: View Hosted Version

Visit your GitHub Pages URL: `https://shamir4y-ui.github.io/Portfolio/`

## 🎯 Customization Guide

### 1. Update Personal Information

Edit `index.html` and replace the following:

- **Name**: Change "Shamir" to your name in the hero section and footer
- **Email**: Replace `your.email@example.com` with your actual email
- **Phone**: Replace the phone number with your contact number
- **About Text**: Update the About Me section with your personal information

```html
<!-- Example: Update email -->
<a href="mailto:your.email@example.com">your.email@example.com</a>
```

### 2. Update Projects

Modify the projects section to showcase your actual projects:

```html
<div class="project-card">
    <div class="project-icon">
        <i class="fas fa-laptop-code"></i>
    </div>
    <h3 class="project-title">Your Project Name</h3>
    <p class="project-description">Describe your project here</p>
    <a href="your-project-url" class="project-link">View Project</a>
</div>
```

### 3. Update Skills

Edit the skills section to reflect your actual technical skills:

```html
<div class="skill-category">
    <h3>Your Category</h3>
    <ul class="skill-list">
        <li>Skill 1</li>
        <li>Skill 2</li>
        <li>Skill 3</li>
    </ul>
</div>
```

### 4. Update Social Media Links

Find the social media section and add your actual profile URLs:

```html
<a href="https://linkedin.com/in/yourprofile" class="social-icon" title="LinkedIn">
    <i class="fab fa-linkedin"></i>
</a>
```

### 5. Customize Colors

Edit the CSS variables in `styles.css` to match your brand:

```css
:root {
    --primary-color: #6366f1;        /* Main brand color */
    --primary-dark: #4f46e5;         /* Darker shade */
    --secondary-color: #ec4899;      /* Accent color */
    /* ... other colors ... */
}
```

## 🌐 Deploying to GitHub Pages

### Prerequisites
- GitHub account
- Git installed on your computer

### Steps

1. **Initialize Git Repository** (if not already done):
```bash
git init
git add .
git commit -m "Initial commit: Add portfolio website"
```

2. **Push to GitHub**:
```bash
git branch -M main
git remote add origin https://github.com/shamir4y-ui/Portfolio.git
git push -u origin main
```

3. **Enable GitHub Pages**:
   - Go to repository Settings
   - Scroll to "GitHub Pages" section
   - Select `main` branch as source
   - Save

4. **Access Your Site**:
   - Your portfolio will be available at: `https://shamir4y-ui.github.io/Portfolio/`
   - It may take 1-2 minutes to build and deploy

### Custom Domain (Optional)

1. Update your domain registrar's DNS settings
2. In GitHub Pages settings, add your custom domain
3. GitHub will automatically configure SSL/TLS

## 📱 Responsive Breakpoints

The portfolio is optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px to 1199px
- **Mobile**: Below 768px
- **Small Mobile**: Below 480px

## 🎬 Features Explained

### Smooth Scrolling
Navigation links smoothly scroll to sections using the Intersection Observer API.

### Contact Form
- Validates email format
- Provides user feedback on submission
- Resets automatically after success

### Animations
- Fade-in effects on page load
- Hover animations on cards and buttons
- Scroll-triggered animations

## 🛠️ Technologies Used

- **HTML5**: Semantic markup and structure
- **CSS3**: Modern styling with CSS Grid and Flexbox
- **JavaScript (ES6)**: Vanilla JavaScript for interactivity
- **Font Awesome**: Icon library for social media and project icons
- **Google Fonts**: (Optional) System fonts used for consistency

## 📦 Dependencies

The portfolio uses Font Awesome icons from a CDN:
```html
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
```

No npm packages or build tools required!

## ✨ Best Practices Implemented

- Semantic HTML structure
- Mobile-first responsive design
- CSS custom properties for easy customization
- Smooth scroll behavior
- Performance optimizations
- Accessibility considerations
- Clean, readable code structure

## 🐛 Troubleshooting

### GitHub Pages not showing content
1. Ensure `index.html` is in the root directory
2. Check that the branch is set to `main` in Settings
3. Wait 1-2 minutes for GitHub to rebuild

### Styles not loading
1. Hard refresh the page (Ctrl+Shift+R or Cmd+Shift+R)
2. Clear browser cache
3. Verify CSS file is in the same directory as HTML

### Contact form not working
The form provides visual feedback but doesn't send emails automatically. To enable email functionality, integrate with a service like:
- [Formspree](https://formspree.io/)
- [EmailJS](https://www.emailjs.com/)
- [Netlify Forms](https://www.netlify.com/products/forms/)

## 📝 License

This project is open source and available for personal and commercial use.

## 🤝 Contributing

Feel free to fork this project and customize it for your needs. If you create an improved version, consider sharing it with the community!

## 💡 Tips for Success

1. **Keep it Updated**: Regularly update your projects and skills
2. **Add Personality**: Customize colors and fonts to reflect your brand
3. **Be Authentic**: Write genuine descriptions of your work
4. **Show Your Best Work**: Feature projects you're proud of
5. **Stay Active**: Update your portfolio as you grow
6. **Ask for Feedback**: Get colleagues to review your portfolio

## 📞 Support

For help with GitHub Pages, visit: https://docs.github.com/en/pages

For HTML/CSS/JavaScript help: https://developer.mozilla.org/

## 🎓 Learning Resources

- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [Web.dev](https://web.dev/)
- [GitHub Pages Documentation](https://docs.github.com/en/pages)

---

**Happy Portfolio Building! 🚀**

Made with ❤️ for aspiring developers and professionals
