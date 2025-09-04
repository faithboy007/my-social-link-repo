# Elegant Social Links Profile

A modern, responsive, and accessible social links profile page built with pure HTML and CSS. This single-file solution features a beautiful glass-morphism card design with smooth animations and full dark/light mode support.

## Features

- **Pure HTML/CSS**: No JavaScript required
- **Fully Responsive**: Works on all screen sizes
- **Dark/Light Mode**: Automatically adapts to user preference
- **Accessibility**: ARIA labels, keyboard navigation, reduced motion support
- **Modern Design**: Glass-morphism effect with gradient accents
- **Performance Optimized**: CSS-only animations and effects
- **Social Media Icons**: Built-in SVG icons for popular platforms

## Customization

### Personal Information
Edit the following sections to personalize your profile:
```html
<h1 id="title">Your Name Here</h1>
<p>Your Title • Your Description</p>
```

### Social Links
Update the social media links by modifying the href attributes:
```html
<a class="social" href="https://your-profile-url" target="_blank" rel="noopener noreferrer" aria-label="Platform name">
  <!-- SVG icon remains the same -->
  <span class="label">Platform Name</span>
  <span class="hint">Action text</span>
</a>
```

### Color Scheme
Modify the CSS custom properties in the `:root` selector to change the color scheme:
```css
:root {
  --bg: #your-background-color;
  --fg: #your-text-color;
  --accent-start: #your-gradient-start;
  --accent-end: #your-gradient-end;
  /* More color variables available */
}
```

### Adding New Social Links
Duplicate one of the existing social link blocks and update the SVG icon, URL, and text.

## Browser Support

This project supports all modern browsers including:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## Accessibility Features

- Semantic HTML structure
- Proper ARIA labels and roles
- Keyboard navigation support
- Reduced motion preferences respected
- High contrast support through CSS variables

## Deployment

Simply upload the HTML file to any web server or use services like:
- GitHub Pages
- Netlify
- Vercel
- Any traditional web hosting

## License

This project is open source and available under the MIT License.

## Credits

Designed and built with modern CSS features including:
- CSS Grid and Flexbox
- CSS Custom Properties (Variables)
- backdrop-filter for glass effect
- color-mix() function for translucent colors
- conic-gradient for animated border

## Support

For questions or issues, please check the code comments or refer to modern CSS documentation for the features used.
