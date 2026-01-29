# Portfolio Website

A modern, responsive portfolio website showcasing professional experience, education, and skills.

## Features

- **Modern Design**: Clean, professional aesthetic with gradient accents and smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Smooth Animations**: Intersection Observer API for fade-in effects and smooth scrolling
- **Interactive Navigation**: Fixed navbar with active state highlighting
- **Performance Optimized**: Lightweight and fast-loading

## Getting Started

### Viewing the Website

Simply open `index.html` in your web browser. No build process or dependencies required!

### Local Development

1. Clone or download this repository
2. Open `index.html` in your preferred web browser
3. For a better development experience, you can use a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then navigate to `http://localhost:8000` in your browser.

## Customization

### Update Contact Information

Edit the contact section in `index.html` (around line 200) to update:
- Email address
- LinkedIn profile URL
- GitHub profile URL

### Modify Colors

Edit the CSS variables in `styles.css` (at the top of the file) to customize the color scheme:

```css
:root {
    --primary-color: #6366f1;
    --secondary-color: #8b5cf6;
    --accent-color: #ec4899;
    /* ... other variables */
}
```

### Add or Modify Content

- **Professional Summary**: Edit the `#about` section in `index.html`
- **Experience**: Modify the `.timeline-item` elements in the `#experience` section
- **Education**: Update the `.education-card` elements in the `#education` section

## File Structure

```
personal_website/
├── index.html      # Main HTML file
├── styles.css      # All styling and animations
├── script.js       # JavaScript for interactivity
└── README.md       # This file
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Deployment

You can deploy this website to any static hosting service:

- **Netlify**: Drag and drop the folder or connect to Git
- **Vercel**: Import the project and deploy
- **GitHub Pages**: Push to a repository and enable Pages
- **Any web hosting**: Upload all files to your web server

## License

This portfolio template is free to use and modify for personal and commercial projects.
