# Ahmed Bilal - Portfolio Website

A modern, responsive portfolio website with CERN-inspired design featuring research experience, projects, and achievements.

## 🎨 Features

- **CERN-Inspired Design**: Professional blue color scheme inspired by CERN's branding
- **Fully Responsive**: Works perfectly on desktop, tablet, and mobile devices
- **Smooth Animations**: Elegant scroll animations and hover effects
- **9 Featured Projects**: Showcasing ML, robotics, and embedded systems projects
- **Research Timeline**: Detailed internship experiences at NCP, NUST, and NED UET
- **Contact Form**: Ready-to-integrate contact functionality
- **SEO Optimized**: Meta tags and semantic HTML for better search visibility

## 📁 File Structure

```
portfolio-website/
├── index.html          # Main HTML file
├── style.css           # Stylesheet with CERN colors
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## 🚀 Quick Start

### Option 1: Open Locally
Simply open `index.html` in your web browser to view the portfolio.

### Option 2: Deploy to GitHub Pages (Recommended)

1. Create a new GitHub repository
2. Upload all files to the repository
3. Go to Settings → Pages
4. Select main branch as source
5. Your site will be live at: `https://yourusername.github.io/repository-name/`

#### Command Line Deployment:
```bash
# Navigate to the portfolio-website folder
cd portfolio-website

# Initialize git
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio website"

# Add remote repository
git remote add origin https://github.com/ahmedbilal9/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Option 3: Deploy to Netlify

1. Go to [netlify.com](https://netlify.com)
2. Drag and drop the `portfolio-website` folder
3. Get instant deployment with a custom URL
4. Optional: Add your custom domain

### Option 4: Deploy to Vercel

```bash
# Install Vercel CLI
npm i -g vercel

# Navigate to folder
cd portfolio-website

# Deploy
vercel
```

## 🎨 Customization

### Colors
Edit the CSS variables in `style.css`:
```css
:root {
    --cern-blue: #0053a1;
    --cern-light-blue: #1976d2;
    --cern-dark-blue: #003d75;
    /* Modify these to change the color scheme */
}
```

### Content
- **Personal Info**: Update name, email, and links in `index.html`
- **Projects**: Add/modify projects in the Projects section
- **Experience**: Update timeline items with your internships
- **Skills**: Add or remove skill tags as needed

### Contact Form Integration

The form is ready to integrate with email services. Recommended options:

#### Option A: EmailJS (Free)
```javascript
// In script.js, replace the TODO section with:
emailjs.init("YOUR_PUBLIC_KEY");

emailjs.send('service_id', 'template_id', data)
    .then(() => showFormMessage('Message sent!', 'success'))
    .catch(() => showFormMessage('Failed to send.', 'error'));
```

#### Option B: Formspree
```html
<!-- In index.html, modify the form tag: -->
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

#### Option C: Netlify Forms
```html
<!-- Add to form tag in index.html: -->
<form name="contact" method="POST" data-netlify="true">
```

## 📊 Features Breakdown

### Sections
- ✅ Hero with animated statistics
- ✅ About section with highlights
- ✅ Honors & Achievements timeline
- ✅ Skills grid with categories
- ✅ Research Experience timeline
- ✅ Projects showcase (9 projects)
- ✅ Contact form with social links
- ✅ Professional footer

### Interactivity
- ✅ Smooth scroll navigation
- ✅ Active navigation highlighting
- ✅ Scroll-triggered animations
- ✅ Hover effects on cards
- ✅ Form validation
- ✅ Responsive mobile menu

## 🔧 Technologies Used

- **HTML5**: Semantic markup
- **CSS3**: Modern styling with flexbox and grid
- **JavaScript**: Vanilla JS for interactivity
- **Google Fonts**: Cormorant Garamond & Work Sans
- **CSS Animations**: Smooth transitions and effects

## 📱 Browser Support

- ✅ Chrome (latest)
- ✅ Firefox (latest)
- ✅ Safari (latest)
- ✅ Edge (latest)
- ✅ Mobile browsers

## 🎯 SEO & Performance

- Meta tags for social sharing
- Semantic HTML5 elements
- Optimized CSS with minimal overhead
- Fast loading with external fonts
- Accessible navigation

## 📝 Next Steps

1. **Add Analytics**: Integrate Google Analytics or Plausible
2. **Custom Domain**: Purchase and connect a domain (e.g., ahmedbilal.dev)
3. **Blog Section**: Add a blog linking to Medium articles
4. **Dark Mode**: Implement theme toggle
5. **Project Screenshots**: Add images to project cards
6. **PDF Resume**: Add downloadable resume link
7. **Testimonials**: Add recommendations from mentors

## 🔒 Security Notes

- Form submissions should be handled server-side for security
- Use environment variables for API keys
- Enable HTTPS on deployment (automatic with GitHub Pages/Netlify)

## 📄 License

This portfolio template is free to use and modify for personal use.

## 👤 Contact

**Ahmed Bilal**
- Email: ahmedbilalned@gmail.com
- GitHub: [@ahmedbilal9](https://github.com/ahmedbilal9)
- LinkedIn: [ahmedbilal9](https://linkedin.com/in/ahmedbilal9)
- Medium: [@ahmedbilal9](https://medium.com/@ahmedbilal9)

---

Built with 💙 inspired by CERN's elegant design philosophy.