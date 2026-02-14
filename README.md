# Construction Company Website

A professional, modern, and responsive website template for a construction and remodeling company. This project was created as a portfolio piece to demonstrate web development skills with HTML, CSS, and JavaScript.

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
project/
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

This is a portfolio project. Feel free to use it as a template for your own projects.

---

Built as a portfolio demonstration of modern web development