# Sunil Thakur - Professional Profile Website

A modern, interactive profile website showcasing 20+ years of AI/ML expertise and professional experience.

## Features

- **Modern Design**: Clean, professional layout with smooth animations and gradients
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Interactive Elements**:
  - Smooth scrolling navigation
  - Animated counters for statistics
  - Hover effects on cards and projects
  - Dynamic timeline for experience
  - Project card tilt effects
- **Performance Optimized**: Fast loading with minimal dependencies
- **SEO Friendly**: Semantic HTML structure

## Sections

1. **Hero Section**: Eye-catching introduction with social links
2. **About**: Professional summary with key highlights
3. **Experience**: Interactive timeline of career progression
4. **Skills**: Organized skill categories with tags
5. **Projects**: Featured AI/ML projects with descriptions
6. **Education**: Academic background and certifications
7. **Contact**: Multiple ways to get in touch

## Technologies Used

- HTML5
- CSS3 (Custom Properties, Flexbox, Grid, Animations)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons

## Local Development

1. Clone or download this repository
2. Open `index.html` in your browser
3. No build process required!

## GitHub Pages Deployment

### Option 1: Deploy from Main Branch

1. **Initialize Git Repository** (if not already done):
   ```bash
   cd /Users/sunil.k.thakur/Desktop/Sunil/Playground/Claude_Play/Profile
   git init
   git add .
   git commit -m "Initial commit: Modern profile website"
   ```

2. **Create GitHub Repository**:
   - Go to https://github.com/new
   - Repository name: `sunil-thakur-profile` (or your preferred name)
   - Make it public
   - Don't initialize with README (we already have one)
   - Click "Create repository"

3. **Push to GitHub**:
   ```bash
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/sunil-thakur-profile.git
   git push -u origin main
   ```

4. **Enable GitHub Pages**:
   - Go to your repository on GitHub
   - Click "Settings" → "Pages"
   - Under "Source", select "main" branch
   - Select "/ (root)" folder
   - Click "Save"
   - Your site will be published at: `https://YOUR_USERNAME.github.io/sunil-thakur-profile/`

### Option 2: Deploy as User/Organization Site

If you want your site at `https://YOUR_USERNAME.github.io/`:

1. Create a repository named exactly: `YOUR_USERNAME.github.io`
2. Push your code to this repository
3. GitHub Pages will automatically deploy from the main branch

## Customization

### Update Profile Image
Replace the profile placeholder in `index.html`:
```html
<div class="profile-placeholder">
    <i class="fas fa-user"></i>
</div>
```

With an actual image:
```html
<img src="path/to/your-photo.jpg" alt="Sunil Thakur" style="width: 100%; height: 100%; object-fit: cover; border-radius: 50%;">
```

### Change Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #7c3aed;
    --accent-color: #06b6d4;
    /* ... other variables ... */
}
```

### Add/Modify Content
All content is in `index.html`. Simply edit the text, add sections, or modify existing ones.

### Social Links
Update social links in the hero section and contact section:
```html
<a href="https://linkedin.com/in/thakursunil" target="_blank">
    <i class="fab fa-linkedin"></i>
</a>
```

## Performance Tips

1. **Optimize Images**: If you add images, compress them using tools like TinyPNG
2. **Lazy Loading**: For images, add `loading="lazy"` attribute
3. **Minify Files**: For production, consider minifying CSS and JS files

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## File Structure

```
Profile/
│
├── index.html          # Main HTML file
├── styles.css          # All styles and animations
├── script.js           # Interactive functionality
└── README.md          # This file
```

## Features Breakdown

### Animations
- Fade in on scroll
- Smooth transitions
- Hover effects
- Typing effects (optional)
- Parallax scrolling
- Animated counters

### Interactive Elements
- Mobile-responsive hamburger menu
- Active navigation highlighting
- Smooth scroll to sections
- Project card interactions
- Email copy functionality
- Timeline animations

## Future Enhancements

Consider adding:
- [ ] Dark mode toggle
- [ ] Blog section
- [ ] Testimonials
- [ ] Download resume button
- [ ] Contact form with backend
- [ ] Analytics (Google Analytics)
- [ ] More project details with modal popups

## Troubleshooting

### Site not showing on GitHub Pages
- Wait 5-10 minutes after deployment
- Check Settings → Pages for deployment status
- Ensure repository is public
- Check browser console for errors

### Styling looks broken
- Clear browser cache
- Check that all files are uploaded
- Verify file paths are correct

### Links not working
- Check that all href attributes are correct
- For external links, include `https://`

## Credits

- Icons: [Font Awesome](https://fontawesome.com/)
- Design: Custom modern design
- Animations: Custom CSS animations

## License

This is a personal portfolio website. Feel free to use as inspiration for your own profile.

## Contact

**Sunil Thakur**
- Email: sunilforu@gmail.com
- Phone: +65 86708174
- LinkedIn: [linkedin.com/in/thakursunil](https://linkedin.com/in/thakursunil)
- Location: Singapore

---

**Note**: Replace `YOUR_USERNAME` with your actual GitHub username in all commands and URLs above.
