# My Portfolio Website

A modern, responsive portfolio website showcasing my deployed applications and technical skills.

## Features

- 🎨 Modern and responsive design
- 📱 Mobile-friendly navigation
- 🚀 Smooth scrolling and animations
- 💼 Portfolio projects section with deployed apps
- 📧 Contact form
- 🎯 Skills showcase
- 🔗 Social media links

## Portfolio Projects

The website showcases the following deployed applications:

1. **E-Commerce Platform** - Full-stack e-commerce application
2. **Task Manager App** - Productivity application with drag-and-drop
3. **Weather Application** - Real-time weather information
4. **Blog Platform** - Modern blogging platform with markdown support
5. **Portfolio Builder** - Tool for creating portfolio websites
6. **Real-Time Chat App** - Messaging application with real-time features

## Technologies Used

- HTML5
- CSS3 (with modern features like Grid and Flexbox)
- Vanilla JavaScript
- Font Awesome icons

## Getting Started

### Viewing the Website

Simply open the `index.html` file in your web browser:

```bash
# On macOS
open index.html

# On Linux
xdg-open index.html

# On Windows
start index.html
```

Or use a local development server:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Updating Projects

Edit the projects section in `index.html` to add your own deployed applications:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-project-image.jpg" alt="Project Name">
        <div class="project-overlay">
            <a href="your-live-demo-url" class="btn btn-small" target="_blank">Live Demo</a>
            <a href="your-github-repo" class="btn btn-small btn-secondary" target="_blank">Code</a>
        </div>
    </div>
    <div class="project-content">
        <h3>Your Project Name</h3>
        <p>Project description...</p>
        <div class="project-tags">
            <span class="tag">Tech1</span>
            <span class="tag">Tech2</span>
        </div>
    </div>
</div>
```

### Customizing Colors

Edit the CSS variables in `styles.css`:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent: #ec4899;
    /* ... other colors */
}
```

### Updating Personal Information

Update the following sections in `index.html`:
- Hero section (name and description)
- About section
- Contact information
- Social media links

## Project Structure

```
my-portfolio/
├── index.html      # Main HTML file
├── styles.css      # Stylesheet
├── script.js       # JavaScript functionality
└── README.md       # Documentation
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the MIT License.

## Contact

For any questions or collaborations, feel free to reach out:

- Email: contact@isholaolatunde.com
- GitHub: [@isholaolatunde](https://github.com/isholaolatunde)

---

Built with ❤️ by Ishola Olatunde