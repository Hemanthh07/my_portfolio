# Personal Portfolio Website

A clean, modern, and responsive portfolio website built with HTML, CSS, and JavaScript. Perfect for showcasing your projects, skills, and personality as a Product Manager.

## Features

- 🎨 **Modern Design**: Clean and professional look with smooth animations
- 📱 **Responsive**: Works perfectly on desktop, tablet, and mobile devices
- ⚡ **Fast Loading**: Optimized for performance
- 🎯 **SEO Friendly**: Proper meta tags and semantic HTML
- 🔗 **Social Media Integration**: Easy to add your social media links
- 📝 **Easy to Customize**: Simple structure to update content

## Quick Start

1. **Open the website**: Double-click on `index.html` or open it in your browser
2. **Customize content**: Edit the HTML file to add your information
3. **Update styling**: Modify `styles.css` to change colors and layout
4. **Add functionality**: Edit `script.js` for custom interactions

## Customization Guide

### 1. Personal Information

Edit `index.html` to update:

- **Name**: Replace "Your Name" with your actual name
- **Title**: Update the hero subtitle and page title
- **About section**: Write your personal story and experience
- **Stats**: Update the numbers in the about section (years of experience, projects, etc.)

### 2. Projects & Side Hustles

In the projects section, update each project card with:

- **Project name**: Replace "Project Name 1" with your actual project names
- **Description**: Write about what the project does and its impact
- **Tags**: Add relevant skills or categories
- **Links**: Add actual URLs to your projects or case studies

### 3. Social Media Links

Update the social links in the contact section with your actual profiles:

```html
<a href="https://linkedin.com/in/yourprofile" class="social-link" target="_blank">
    <i class="fab fa-linkedin"></i>
    <span>LinkedIn</span>
</a>
```

### 4. Colors & Styling

In `styles.css`, you can customize:

- **Primary color**: Change `#2563eb` (blue) to your preferred color
- **Gradient**: Modify the hero background gradient
- **Fonts**: Change the Google Fonts import link
- **Spacing**: Adjust padding and margins

### 5. Profile Picture

Replace the placeholder icon with your actual photo:

1. Add your photo to the portfolio folder
2. Replace the profile placeholder div with:
```html
<div class="hero-image">
    <img src="your-photo.jpg" alt="Your Name" class="profile-photo">
</div>
```
3. Add CSS for the photo:
```css
.profile-photo {
    width: 300px;
    height: 300px;
    border-radius: 50%;
    object-fit: cover;
    border: 3px solid rgba(255, 255, 255, 0.2);
}
```

## File Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
├── script.js           # JavaScript functionality
└── README.md           # This file
```

## Deployment Options

### Option 1: GitHub Pages (Free)
1. Create a GitHub repository
2. Upload your portfolio files
3. Go to Settings > Pages
4. Select source branch and save

### Option 2: Netlify (Free)
1. Go to netlify.com
2. Drag and drop your portfolio folder
3. Get a free URL instantly

### Option 3: Vercel (Free)
1. Go to vercel.com
2. Connect your GitHub repository
3. Deploy automatically

### Option 4: Custom Domain
1. Buy a domain (Namecheap, GoDaddy, etc.)
2. Point it to your hosting provider
3. Update DNS settings

## Tips for Product Managers

1. **Show Impact**: Focus on metrics and outcomes in your project descriptions
2. **Tell Stories**: Use case studies to demonstrate your problem-solving approach
3. **Highlight Leadership**: Emphasize team management and cross-functional collaboration
4. **Include Process**: Show your product development methodology
5. **Add Personality**: Let your unique traits shine through in the content

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

If you need help customizing your portfolio, feel free to:
- Check the comments in the code files
- Modify the CSS variables for easy color changes
- Add more sections as needed

---

**Built with ❤️ for Product Managers who love to build things** 