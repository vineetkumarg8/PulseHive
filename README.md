# PulseHive Media Website

A modern, responsive website for PulseHive Media - a social media and content creation company focused on local businesses and communities.

## Features

✅ **Fully Responsive** - Works beautifully on all devices (desktop, tablet, mobile)
✅ **Modern Design** - Clean, professional aesthetic with smooth animations
✅ **Fast Loading** - Optimized performance with vanilla JavaScript (no heavy frameworks)
✅ **Interactive Elements** - Smooth scrolling, mobile menu, form validation
✅ **Contact Form** - Ready to integrate with backend or form services
✅ **SEO Friendly** - Proper meta tags and semantic HTML

## File Structure

```
PulseHive/
├── index.html          # Main HTML file
├── styles.css          # All styling and responsive design
├── script.js           # JavaScript for interactivity
└── README.md          # This file
```

## How to Use

### Option 1: Open Locally
1. Simply double-click `index.html` to open it in your browser
2. The website will work immediately with no server required

### Option 2: Use Live Server (Recommended for Development)
1. Install the "Live Server" extension in VS Code
2. Right-click on `index.html` and select "Open with Live Server"
3. The website will open with live reload capabilities

### Option 3: Deploy Online
You can deploy this website for FREE on:
- **Netlify** (drag & drop deployment)
- **Vercel** (GitHub integration)
- **GitHub Pages** (free hosting)
- **Cloudflare Pages**

## Customization Guide

### Change Colors
Edit the CSS variables in `styles.css` (lines 9-18):
```css
:root {
    --primary-color: #6366f1;      /* Main brand color */
    --secondary-color: #ec4899;    /* Accent color */
    --text-dark: #1f2937;          /* Dark text */
    --text-light: #6b7280;         /* Light text */
}
```

### Update Content
- **Hero Section**: Edit lines 37-51 in `index.html`
- **Services**: Edit lines 56-81 in `index.html`
- **About**: Edit lines 86-110 in `index.html`
- **Contact**: Edit lines 115-137 in `index.html`

### Add Your Logo
Replace the text logo (line 20 in `index.html`) with an image:
```html
<img src="your-logo.png" alt="PulseHive" class="logo-img">
```

### Integrate Contact Form

The contact form currently simulates submission. To make it functional:

#### Option 1: FormSpree (Easiest)
1. Go to https://formspree.io/
2. Create a free account
3. Get your form endpoint
4. Update the form in `index.html`:
```html
<form action="https://formspree.io/f/YOUR_FORM_ID" method="POST">
```

#### Option 2: EmailJS
1. Sign up at https://www.emailjs.com/
2. Follow their integration guide
3. Update `script.js` with EmailJS code

#### Option 3: Your Own Backend
Update the form submission handler in `script.js` (lines 74-115) to send data to your API.

## Browser Support

✅ Chrome (latest)
✅ Firefox (latest)
✅ Safari (latest)
✅ Edge (latest)
✅ Mobile browsers

## Performance

- **No dependencies** - Pure HTML, CSS, JavaScript
- **Fast load time** - Minimal assets
- **Optimized animations** - Smooth 60fps performance
- **Lazy loading ready** - Easy to add for images

## Next Steps

1. **Add Images**: Include photos of your team, work samples, or client logos
2. **Portfolio Section**: Add a gallery of your content creation work
3. **Testimonials**: Include client reviews and success stories
4. **Blog**: Add a blog section for content marketing
5. **Analytics**: Integrate Google Analytics or similar
6. **Social Media Links**: Add your social media profiles to footer

## Support

For questions or customization help, feel free to reach out!

---

**Built with ❤️ for PulseHive Media**
*The pulse of your community*
