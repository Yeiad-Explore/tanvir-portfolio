# Tanvir Ahmed - Portfolio Website

A modern, responsive portfolio website showcasing my work as a Research & Data Analyst and AI/ML Enthusiast.

## 🚀 Features

- **Modern Design**: Clean, professional layout with smooth animations
- **Dark/Light Theme**: Toggle between dark and light modes with persistent preference
- **Fully Responsive**: Optimized for all device sizes (desktop, tablet, mobile)
- **Interactive Elements**: Smooth scrolling, hover effects, and animated components
- **Contact Form**: Functional contact form with validation
- **Project Showcase**: Detailed project cards with links to GitHub and demos
- **Professional Sections**: Complete portfolio including skills, experience, education, and achievements

## 📋 Sections

1. **Hero Section**: Professional introduction with call-to-action buttons
2. **About Me**: Personal background and quick facts
3. **Skills**: Technical and soft skills with visual tags
4. **Work Experience**: Timeline of professional experience
5. **Projects**: Featured projects with descriptions and links
6. **Publications**: Research publications and papers
7. **Achievements**: Awards and competition results
8. **Education**: Academic background and qualifications
9. **Contact**: Contact information and message form

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with CSS Grid, Flexbox, and animations
- **JavaScript (ES6+)**: Interactive functionality and theme management
- **Font Awesome**: Icons for enhanced visual appeal
- **Google Fonts**: Inter font family for typography

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- No additional dependencies required

### Installation

1. **Clone or Download** the repository
   ```bash
   git clone [repository-url]
   cd tanvir-port
   ```

2. **Open the website**
   - Simply open `index.html` in your web browser
   - Or use a local server for development:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js
     npx serve .
     
     # Using PHP
     php -S localhost:8000
     ```

3. **Customize the content**
   - Edit `index.html` to update personal information
   - Modify `styles.css` to change colors, fonts, or layout
   - Update `script.js` for additional functionality

## 🎨 Customization

### Personal Information
Update the following in `index.html`:
- Name and title in the hero section
- About me content
- Work experience details
- Project information
- Contact details

### Styling
Modify CSS variables in `styles.css`:
```css
:root {
    --primary-color: #4f46e5;    /* Main brand color */
    --secondary-color: #10b981;  /* Accent color */
    --text-primary: #1f2937;     /* Main text color */
    /* ... other variables */
}
```

### Adding Projects
Add new project cards in the projects section:
```html
<div class="project-card">
    <div class="project-image">
        <img src="project-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Title</h3>
        <p>Project description...</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">GitHub</a>
        </div>
    </div>
</div>
```

## 📱 Responsive Design

The website is fully responsive and optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🌙 Theme System

The website includes a built-in dark/light theme system:
- Toggle button in the navigation
- Theme preference saved in localStorage
- Smooth transitions between themes
- All components adapt to the selected theme

## 📧 Contact Form

The contact form includes:
- Client-side validation
- Success/error notifications
- Responsive design
- Form reset after submission

*Note: The form currently shows a success message. To make it functional, integrate with a backend service or email service like Formspree, Netlify Forms, or EmailJS.*

## 🔧 Browser Support

- Chrome 60+
- Firefox 60+
- Safari 12+
- Edge 79+

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Feel free to fork this project and customize it for your own portfolio. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

## 📞 Support

If you have any questions or need help customizing the portfolio, feel free to reach out!

---

**Built with ❤️ by Tanvir Ahmed**
