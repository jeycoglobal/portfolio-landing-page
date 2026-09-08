# Jeremy's Portfolio

A beautiful, responsive portfolio landing page showcasing projects, skills, and experience.

## 🚀 Live Demo

Your portfolio is live at: **https://jeycoglobal.github.io/portfolio-landing-page/**

## 📋 Features

- ✨ Modern dark theme with gradient accents
- 📱 Fully responsive design (mobile, tablet, desktop)
- 🎯 Smooth navigation and scroll animations
- 💬 Contact form functionality
- 🎨 Interactive hover effects
- ⚡ Fast loading and optimized performance

## 📁 Project Structure

```
portfolio-landing-page/
├── index.html      # Main HTML file
├── styles.css      # Styling and animations
├── script.js       # Interactive functionality
└── README.md       # This file
```

## 🛠️ Customization Guide

### 1. **Update Your Information**
Edit `index.html` and update:
- Your name and title in the hero section
- About section with your bio
- Project details and links
- Skills list
- Social media links in footer

### 2. **Add Your Projects**
Replace the project cards with your actual projects:
```html
<div class="project-card">
    <h3>Your Project Name</h3>
    <p>Project description</p>
    <div class="project-tags">
        <span class="tag">Technology</span>
    </div>
    <a href="https://your-project-link.com" class="project-link">View Project →</a>
</div>
```

### 3. **Customize Colors**
Edit the CSS variables in `styles.css`:
```css
:root {
    --primary-color: #6366f1;      /* Change this */
    --secondary-color: #ec4899;    /* Change this */
    --dark-bg: #0f172a;
    --card-bg: #1e293b;
}
```

### 4. **Update Social Links**
In the Contact section, update:
```html
<a href="https://github.com/your-username" class="social-link">GitHub</a>
<a href="https://linkedin.com/in/your-profile" class="social-link">LinkedIn</a>
<a href="https://twitter.com/your-handle" class="social-link">Twitter</a>
```

## 🌐 GitHub Pages Setup

Your portfolio is already configured to use GitHub Pages!

### To enable it:
1. Go to your repository settings
2. Scroll to "Pages" section
3. Under "Build and deployment", select:
   - **Source**: Deploy from a branch
   - **Branch**: `main` / `root`
4. Click Save
5. Wait a few minutes for deployment

Your site will be live at: `https://jeycoglobal.github.io/portfolio-landing-page/`

## 🚀 Alternative Hosting Options

If you want a custom domain or different hosting:

### **Vercel (Recommended)**
1. Go to [vercel.com](https://vercel.com)
2. Sign up with GitHub
3. Import this repository
4. It will auto-deploy with every push

### **Netlify**
1. Go to [netlify.com](https://netlify.com)
2. Connect your GitHub account
3. Select this repository
4. Deploy in one click

## 📝 Making Updates

After you push changes to GitHub:
- **GitHub Pages**: Updates automatically (takes ~1 min)
- **Vercel**: Deploys automatically
- **Netlify**: Deploys automatically

## 💡 Tips

- Keep your projects and skills up to date
- Add real project links to showcase your work
- Include screenshots or images in your projects
- Update contact information regularly
- Test on mobile devices to ensure responsiveness

## 📞 Need Help?

Check out these resources:
- [GitHub Pages Docs](https://docs.github.com/en/pages)
- [HTML/CSS Guide](https://developer.mozilla.org/en-US/docs/Web)
- [JavaScript Basics](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

---

**Made with ❤️ by Jeremy**