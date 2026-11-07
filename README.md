# Portfolio Website

A modern, responsive portfolio website built with vanilla HTML, CSS, and JavaScript.

## Features

- **Responsive Design** - Works on mobile, tablet, and desktop
- **Dark Mode Support** - Automatically adapts to system preference
- **Accessible** - Semantic HTML, ARIA labels, keyboard navigation, reduced motion support
- **Smooth Animations** - Scroll-triggered animations with Intersection Observer
- **Mobile Navigation** - Hamburger menu with proper ARIA attributes
- **Contact Form** - Client-side validation with simulated submission
- **Skill Bars** - Animated progress bars
- **Project Showcase** - Card-based project grid with hover effects

## Project Structure

```
portfolio/
├── index.html      # Main HTML structure
├── styles.css      # All styling with CSS custom properties
├── script.js       # Vanilla JavaScript functionality
└── README.md       # This file
```

## Getting Started

Simply open `index.html` in a browser, or serve it with a local server:

```bash
# Using Python
python -m http.server 8000

# Using Node.js (npx)
npx serve .

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000`

## Customization

### Colors
Edit CSS custom properties in `styles.css`:

```css
:root {
    --color-primary: #2563eb;      /* Main brand color */
    --color-secondary: #64748b;    /* Secondary color */
    --color-accent: #0ea5e9;       /* Accent color */
    /* ... more variables */
}
```

### Content
Update `index.html` with your:
- Name and title
- About text
- Projects
- Skills
- Contact information
- Social links

### Fonts
The site uses Inter from Google Fonts. Change in `index.html`:

```html
<link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">
```

And in `styles.css`:

```css
--font-family: 'Inter', -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, sans-serif;
```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Performance

- No external dependencies (except Google Fonts)
- Minimal CSS and JS
- Optimized animations using `transform` and `opacity`
- Passive event listeners for scroll

## Accessibility

- Semantic HTML5 elements
- Proper heading hierarchy
- ARIA labels and roles
- Focus visible states
- Reduced motion support
- Color contrast ratios (WCAG AA)
- Keyboard navigable

## License

MIT License - Feel free to use and modify for your own portfolio.