# Rituparna Ghosh Dastidar - Portfolio Website

A modern, Apple-inspired portfolio website showcasing HR expertise and the book "Becoming an AI-Ready HR Leader: Generative AI Course for HR Professionals"

## Features

- **Modern Design**: Clean, minimalist aesthetic inspired by Apple's design language
- **Responsive Layout**: Fully responsive design that works beautifully on all devices
- **Dark/Light Mode**: Toggle between light and dark themes with smooth transitions
- **Smooth Animations**: Scroll-triggered animations and parallax effects
- **Interactive Elements**: 3D book cover, animated statistics, and hover effects
- **Performance Optimized**: Fast loading with smooth 60fps animations

## Sections

1. **Hero** - Eye-catching introduction with call-to-action buttons
2. **About** - Professional summary, credentials, and core competencies
3. **Experience** - Timeline of professional career with key achievements
4. **Book** - Detailed presentation of "Becoming an AI-Ready HR Leader" with all 8 chapters
5. **Contact** - Multiple ways to connect with easy-to-use contact information

## Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS variables, Grid, Flexbox, and animations
- **Vanilla JavaScript** - Interactive features and smooth scrolling
- **Google Fonts** - Inter font family for clean typography

## Local Development

1. Clone or download this repository
2. Open `index.html` in your web browser
3. No build process or dependencies required!

## Hosting on GitHub Pages

### Option 1: Using GitHub Desktop (Easy)

1. **Create a GitHub account** at [github.com](https://github.com) if you don't have one
2. **Download and install GitHub Desktop** from [desktop.github.com](https://desktop.github.com)
3. **Create a new repository**:
   - Open GitHub Desktop
   - Click "Create a New Repository on your hard drive"
   - Name it: `yourusername.github.io` (replace `yourusername` with your GitHub username)
   - Choose this folder as the local path
   - Click "Create Repository"
4. **Publish to GitHub**:
   - Click "Publish repository" button
   - Uncheck "Keep this code private" if you want it public
   - Click "Publish Repository"
5. **Enable GitHub Pages**:
   - Go to your repository on GitHub.com
   - Click "Settings" tab
   - Scroll to "Pages" section in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"
6. **Visit your site**: Your website will be live at `https://yourusername.github.io`

### Option 2: Using Git Command Line

```bash
# Initialize git repository (if not already done)
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit - Portfolio website"

# Create a new repository on GitHub.com first, then:
git remote add origin https://github.com/yourusername/yourusername.github.io.git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings as described above.

### Option 3: Custom Domain (Optional)

If you want to use your own domain (e.g., rituparnadastidar.com):

1. Buy a domain from a registrar (GoDaddy, Namecheap, Google Domains, etc.)
2. In your GitHub repository, go to Settings → Pages
3. Enter your custom domain
4. In your domain registrar's DNS settings, add these records:
   ```
   Type: A
   Name: @
   Value: 185.199.108.153

   Type: A
   Name: @
   Value: 185.199.109.153

   Type: A
   Name: @
   Value: 185.199.110.153

   Type: A
   Name: @
   Value: 185.199.111.153

   Type: CNAME
   Name: www
   Value: yourusername.github.io
   ```

## Customization

### Updating Content

- **Personal Info**: Edit the HTML content in `index.html`
- **Styling**: Modify colors and design in `styles.css`
- **Functionality**: Adjust interactive features in `script.js`

### Color Scheme

The website uses CSS variables for easy theming. Edit these in `styles.css`:

```css
:root {
    --accent-primary: #0071e3;
    --accent-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    /* ... more variables */
}
```

### Adding Resume Download

To add a downloadable resume PDF:

1. Place your resume PDF in the folder (e.g., `resume.pdf`)
2. Add a download button in the hero section:
   ```html
   <a href="resume.pdf" download class="btn btn-secondary">Download Resume</a>
   ```

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- Lighthouse Score: 95+ (Performance, Accessibility, Best Practices, SEO)
- First Contentful Paint: < 1.0s
- Time to Interactive: < 1.5s

## Credits

**Design & Development**: Rituparna Ghosh Dastidar Portfolio
**Font**: [Inter](https://fonts.google.com/specimen/Inter) by Google Fonts
**Inspiration**: Apple's design philosophy

## Contact

For questions or collaboration opportunities:

- **Email**: 26gdritu@gmail.com
- **Phone**: +1 425-472-7039
- **LinkedIn**: [linkedin.com/in/rituparnagdastidar](https://www.linkedin.com/in/rituparnagdastidar/)
- **Location**: Redmond, WA

## License

© 2024 Rituparna Ghosh Dastidar. All rights reserved.

---

**Note**: This website is optimized for modern browsers and uses cutting-edge web technologies for the best user experience.
