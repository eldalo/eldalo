# elDalo Portfolio Website

## Project Overview

This is a personal portfolio website for Diego Alexander Londoño Marín (elDalo), a FullStack Software Engineer with +15 years of experience. The site showcases his professional background, skills, and contact information in a clean, responsive design.

The project is a static HTML/CSS/JavaScript website built with Bootstrap 4.6.0 as the CSS framework foundation. It features a modern, minimalist design with a green color scheme and uses custom CSS for styling on top of Bootstrap components.

### Key Technologies and Features:
- HTML5, CSS3
- Bootstrap 4.6.0 (customized)
- Responsive design for all device sizes
- Progressive Web App (PWA) capabilities (manifest.json)
- Custom typography with Bebas Neue fonts
- Mobile-optimized layout
- Social media integration

## Project Structure

```
/Users/eldalo/Sites/Owner/eldalo/
├── .prettierrc                 # Code formatting configuration
├── index.html                  # Main HTML page
├── README.md                   # Project description and tech stack badges
├── assets/
│   ├── manifest.json          # PWA manifest file
│   ├── css/
│   │   ├── components.css     # Bootstrap 4.6.0 CSS
│   │   └── style.css          # Custom CSS
│   ├── fonts/                 # Custom fonts (Bebas Neue)
│   └── images/                # Images including profile photo and favicon
```

## Building and Running

This is a static website that can be served directly from a web server or deployed to a hosting platform:

### Local Development
1. Open `index.html` directly in a browser for immediate viewing
2. For local server functionality (if needed for PWA features), use:
   ```bash
   # Using Python
   python -m http.server 8000
   
   # Using Node.js
   npx http-server
   
   # Using PHP
   php -S localhost:8000
   ```

### Deployment
The site can be deployed to any static hosting service such as:
- GitHub Pages
- Netlify
- Vercel
- AWS S3
- Any traditional web hosting service

## Development Conventions

### Code Formatting
- Prettier is configured with:
  - Single quotes for strings
  - Auto line endings
  - 2-space tab width
  - Trailing commas for all
  - Arrow parentheses always present
  - Semicolons enabled

### CSS Structure
- Uses Bootstrap 4.6.0 as base framework (in `components.css`)
- Custom styles in `style.css` override Bootstrap defaults
- CSS custom properties (variables) for consistent theming
- Mobile-first responsive approach with media queries

### Design Elements
- Primary colors: Various shades of green
- Typography: Bebas Neue for titles, Helvetica for body text
- Layout: Bootstrap grid system with custom modifications
- Responsive breakpoints: Mobile, tablet, desktop

## Key Files and Their Purpose

- `index.html`: Main page containing all content - profile, experience, skills, contact info
- `assets/css/style.css`: Custom styles that override Bootstrap defaults
- `assets/css/components.css`: Minified Bootstrap 4.6.0 framework
- `assets/manifest.json`: PWA configuration file
- `.prettierrc`: Code formatting rules
- `README.md`: Professional summary with technology badges

## Maintenance and Updates

To update content:
1. Edit `index.html` for profile information, experience, and skills
2. Modify `assets/css/style.css` for styling changes
3. Update `README.md` for technology stack changes
4. Add new images to the `assets/images/` directory as needed

The site is designed to be easily maintainable with minimal dependencies.