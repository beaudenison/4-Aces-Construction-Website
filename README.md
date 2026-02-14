# 4 Aces Construction Website

A professional, modern, and responsive website for 4 Aces Construction - a quality construction and remodeling company based in Spokane, Washington.

## 🏗️ Company Information

- **Company Name**: 4 Aces Construction
- **Location**: Spokane, WA
- **Address**: 2708 N Napa St, Spokane, WA 99207
- **Phone**: (509) 370-9295

## ✨ Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI/UX**: Clean, professional design with smooth animations
- **Service Showcase**: Highlights bathroom remodeling, flooring installation, and general construction services
- **Customer Reviews**: Displays authentic customer testimonials
- **Contact Form**: Easy-to-use form for potential clients to reach out
- **Smooth Navigation**: Smooth scrolling with active section highlighting
- **Mobile Menu**: Hamburger menu for mobile devices

## 🛠️ Technologies Used

- **HTML5**: Semantic markup for better SEO
- **CSS3**: Modern styling with flexbox and grid layouts
- **JavaScript**: Interactive features and form handling
- **Font Awesome**: Professional icons throughout the site

## 📁 File Structure

```
4-Aces-Construction-Website-2/
├── index.html          # Main HTML file
├── styles.css          # All CSS styling
├── script.js           # JavaScript functionality
└── README.md          # This file
```

## 🚀 Getting Started

### Option 1: Open Locally
Simply open the `index.html` file in your web browser.

### Option 2: Use a Local Server
For the best experience, use a local development server:

```bash
# Using Python 3
python -m http.server 8000

# Using PHP
php -S localhost:8000

# Using NPM (if you have Node.js installed)
npx serve
```

Then navigate to `http://localhost:8000` in your browser.

## 📧 Contact Form Setup

The contact form currently displays an alert when submitted. To make it functional, you can integrate with:

### Option 1: EmailJS (Recommended for static sites)
1. Sign up at [EmailJS](https://www.emailjs.com/)
2. Create an email service and template
3. Add EmailJS SDK to index.html:
```html
<script src="https://cdn.jsdelivr.net/npm/@emailjs/browser@3/dist/email.min.js"></script>
```
4. Update the form submission in script.js with your EmailJS credentials

### Option 2: FormSpree
1. Sign up at [FormSpree](https://formspree.io/)
2. Update the form action attribute with your FormSpree endpoint
3. Change form method to "POST"

### Option 3: Backend API
Create your own backend API to handle form submissions and send emails.

## 🎨 Customization

### Colors
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #ff6b35;      /* Orange */
    --secondary-color: #004e89;    /* Blue */
    --dark-color: #1a1a2e;         /* Dark Navy */
    --light-color: #f4f4f4;        /* Light Gray */
}
```

### Content
- Update company information in `index.html`
- Modify services, reviews, and about sections
- Change hero background image URL in `styles.css`

### Images
To add custom images:
1. Create an `images/` folder
2. Add your images
3. Update the image paths in HTML and CSS

## 📱 Sections

1. **Hero Section**: Eye-catching intro with call-to-action buttons
2. **Services**: Six service cards highlighting different offerings
3. **About**: Company information with key features
4. **Reviews**: Customer testimonials
5. **Contact**: Contact information and form
6. **Footer**: Quick links and company info

## 🌐 Deployment

### GitHub Pages
1. Push code to GitHub
2. Go to repository Settings > Pages
3. Select main branch as source
4. Your site will be live at `https://yourusername.github.io/repository-name/`

### Netlify
1. Create account at [Netlify](https://netlify.com)
2. Drag and drop your project folder
3. Site will be live instantly with automatic HTTPS

### Vercel
1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in project directory
3. Follow prompts to deploy

## 📄 License

This website is created for 4 Aces Construction. All rights reserved.

## 🤝 Support

For questions or support regarding this website, please contact:
- **Phone**: (509) 370-9295
- **Address**: 2708 N Napa St, Spokane, WA 99207

---

Built with ❤️ for 4 Aces Construction