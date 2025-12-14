# Nexus Digital - Premium Digital Agency Website

A fully static, responsive digital agency website inspired by modern agency design aesthetics.

## 🚀 Features

- **Modern Design**: Clean, minimal aesthetic with premium feel
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile
- **Smooth Animations**: Scroll-triggered animations and micro-interactions
- **No Build Tools**: Pure HTML5, CSS3, and vanilla JavaScript
- **SEO Optimized**: Semantic HTML and proper meta tags
- **Performance Optimized**: Lazy loading and efficient animations

## 📁 Project Structure

```
digital_agency/
├── index.html          # Main HTML file
├── style.css           # Complete stylesheet
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## 🛠️ Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern features including Grid, Flexbox, and animations
- **Vanilla JavaScript**: No frameworks or dependencies
- **Google Fonts**: Inter font family
- **Font Awesome**: Icon library (CDN)
- **Unsplash**: Placeholder images

## 🚀 Quick Start

1. Clone or download the files
2. Open `index.html` in your browser
3. Or serve with a local server:
   ```bash
   python -m http.server 8000
   # then visit http://localhost:8000
   ```

## 📱 Responsive Breakpoints

- **Desktop**: 1200px and up
- **Tablet**: 768px - 1199px
- **Mobile**: 767px and below

## 🎨 Design Features

### Typography
- Inter font family for clean, modern look
- Large, bold headlines with gradient accents
- Strong visual hierarchy

### Color Scheme
- Primary: Purple gradient (#667eea to #764ba2)
- Dark: #1a1a1a
- Light: #ffffff and #f8f9fa
- Text: #666 for secondary content

### Animations
- Fade-in animations on scroll
- Parallax effects on hero section
- Hover states with smooth transitions
- Typing effect for hero title
- Counter animations for statistics

## 📄 Sections

1. **Hero**: Full-screen introduction with call-to-action
2. **About**: Agency overview and capabilities
3. **Work**: Case study grid with hover effects
4. **Services**: Service offerings with icons
5. **Clients**: Client logo grid
6. **Contact**: Contact form and information
7. **Footer**: Links and social media

## 🌐 GitHub Pages Deployment

### Method 1: Direct Upload

1. Create a new repository on GitHub named `your-username.github.io`
2. Upload all files to the repository
3. Visit `https://your-username.github.io`

### Method 2: Using GitHub Desktop

1. Clone the repository locally
2. Add all files to the repository
3. Commit and push to GitHub
4. Enable GitHub Pages in repository settings

### Method 3: Command Line

```bash
# Initialize git repository
git init
git add .
git commit -m "Initial commit"

# Add remote and push
git branch -M main
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main

# Enable GitHub Pages in repository settings
# Settings > Pages > Source: Deploy from a branch > Main branch
```

### GitHub Pages Settings

1. Go to your repository on GitHub
2. Click **Settings** tab
3. Scroll down to **Pages** section
4. Under **Build and deployment**, select **Deploy from a branch**
5. Choose **Main** branch and **/(root)** folder
6. Click **Save**
7. Your site will be available at `https://your-username.github.io/your-repo`

## 🔧 Customization

### Changing Colors
Edit the CSS variables at the top of `style.css`:

```css
:root {
    --primary-gradient: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    --dark-color: #1a1a1a;
    --light-color: #ffffff;
    --text-secondary: #666;
}
```

### Updating Content
- **Text**: Edit directly in `index.html`
- **Images**: Replace Unsplash URLs with your own images
- **Services**: Modify service cards in the services section
- **Work**: Update case study items with your projects

### Adding New Sections
1. Add HTML section in `index.html`
2. Add corresponding styles in `style.css`
3. Add scroll animation in `script.js` if needed

## 🚀 Performance Features

- **Lazy Loading**: Images load as needed
- **Intersection Observer**: Efficient scroll animations
- **Debounced Events**: Optimized scroll handlers
- **Minimal Dependencies**: Only essential external libraries

## 🌟 Browser Support

- Chrome/Chromium 60+
- Firefox 55+
- Safari 12+
- Edge 79+

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📞 Support

For questions or support, please open an issue in the GitHub repository.
