# Rachel Goldberg - Artist Portfolio

A beautiful, responsive portfolio website showcasing Rachel Goldberg's artistic work. The design features a harmonious blend of organic and geometric elements, creating a modern and elegant aesthetic.

## Features

- **Responsive Design**: Optimized for all devices and screen sizes
- **Organic-Geometric Aesthetic**: Smooth curves combined with precise geometric accents
- **Smooth Animations**: Subtle animations and transitions for enhanced user experience
- **Contact Form**: Functional contact form with validation
- **Gallery Section**: Showcase artwork with hover effects
- **Mobile-First**: Fully responsive with mobile menu

## Sections

1. **Hero Section**: Eye-catching introduction with animated floating shapes
2. **About Me**: Personal story and professional statistics
3. **Gallery**: Portfolio showcase with artwork details
4. **Contact**: Contact information and message form

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter & Playfair Display)

## Deployment on Cloudflare Pages

### Prerequisites
- A Cloudflare account
- Your portfolio files ready for deployment

### Steps to Deploy

1. **Prepare Your Files**
   - Ensure all files are in the root directory:
     - `index.html`
     - `styles.css`
     - `script.js`
     - `README.md`

2. **Connect to Cloudflare Pages**
   - Log in to your Cloudflare dashboard
   - Navigate to "Pages" in the sidebar
   - Click "Create a project"

3. **Choose Your Source**
   - Select "Direct Upload" for manual deployment
   - Or connect your GitHub repository if you prefer Git-based deployment

4. **Upload Your Files**
   - If using Direct Upload:
     - Drag and drop your project folder
     - Or click "Browse files" to select your files
   - If using Git:
     - Connect your repository
     - Cloudflare will automatically detect the build settings

5. **Configure Build Settings** (if using Git)
   - Build command: Leave empty (static site)
   - Build output directory: Leave empty (files are in root)
   - Root directory: Leave empty (if files are in root)

6. **Deploy**
   - Click "Deploy site"
   - Cloudflare will process your files and provide a URL

7. **Custom Domain** (Optional)
   - In your Pages project settings, go to "Custom domains"
   - Add your domain and follow the DNS configuration instructions

### Environment Variables
No environment variables are required for this static site.

### Build Commands
This is a static site, so no build commands are needed.

## Customization

### Colors
The color scheme can be modified in the CSS variables at the top of `styles.css`:

```css
:root {
    --primary-color: #2c3e50;
    --secondary-color: #e74c3c;
    --accent-color: #3498db;
    /* ... other variables */
}
```

### Content
- Update the personal information in `index.html`
- Replace placeholder images with actual artwork
- Modify contact details and social media links

### Adding Artwork
To add real artwork to the gallery:

1. Replace the `artwork-placeholder` divs with actual images
2. Update the artwork titles and descriptions
3. Ensure images are optimized for web (recommended size: 800x600px)

## Performance

The site is optimized for performance with:
- Minimal JavaScript
- Optimized CSS
- Web-safe fonts
- Responsive images
- Efficient animations

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers

## License

This project is created for Rachel Goldberg's personal portfolio use.

## Support

For deployment issues, refer to [Cloudflare Pages documentation](https://developers.cloudflare.com/pages/). 