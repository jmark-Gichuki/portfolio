# Johnmark Gichuki - Professional Portfolio

A clean, professional portfolio website showcasing cybersecurity skills, IT experience, and technical projects.

## 🌟 Features

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile devices
- **Modern UI** - Clean, professional light theme with smooth animations
- **Fast Loading** - Optimized CSS and vanilla JavaScript (no heavy frameworks)
- **SEO Friendly** - Semantic HTML structure
- **Easy to Customize** - Well-organized code and clear structure

## 📁 Project Structure

```
portfolio/
│
├── index.html              # Home page
├── resume.html             # Resume/CV page
├── projects.html           # Projects showcase
├── labchallenges.html      # Lab challenges & walkthroughs
├── contact.html            # Contact information
├── README.md               # This file
│
└── assets/
    ├── css/
    │   └── style.css       # Main stylesheet
    ├── js/
    │   └── script.js       # JavaScript functionality
    └── img/
        └── profile.jpg     # Your profile photo (add this)
```

## 🚀 Getting Started

### 1. Setup in VS Code

1. **Create the folder structure:**
   - Create a folder named `portfolio`
   - Inside it, create folders: `assets/css`, `assets/js`, `assets/img`

2. **Add the files:**
   - Copy `index.html`, `resume.html`, `projects.html`, `labchallenges.html`, and `contact.html` to the root
   - Copy `style.css` to `assets/css/`
   - Copy `script.js` to `assets/js/`

3. **Add your profile photo:**
   - Add your profile photo as `profile.jpg` in `assets/img/`
   - Recommended size: 500x500px or larger, square aspect ratio

### 2. Customize the Content

**Update Links:**
- Replace placeholder LinkedIn and GitHub URLs with your actual profiles
- Update email addresses if different
- Add any additional social media links

**Personalize Content:**
- Modify project descriptions based on your actual projects
- Update lab challenges with your real HackTheBox/CyberShujaa work
- Add screenshots to project and lab sections if desired

**Optional Customizations:**
- Change color scheme in `style.css` (modify the `:root` variables)
- Add more sections as needed
- Include additional certifications or skills

### 3. Test Locally

1. **Open with VS Code Live Server:**
   - Install "Live Server" extension in VS Code
   - Right-click `index.html` and select "Open with Live Server"
   - Your portfolio will open in the browser

2. **Or simply open the HTML file:**
   - Double-click `index.html` to open in your default browser

3. **Test responsiveness:**
   - Resize browser window to test mobile view
   - Use browser DevTools (F12) to test different device sizes

## 🌐 Publishing to GitHub Pages

### Step 1: Create GitHub Repository

```bash
# Initialize git in your portfolio folder
git init

# Add all files
git add .

# Commit
git commit -m "Initial portfolio commit"

# Create repo on GitHub, then:
git remote add origin https://github.com/yourusername/portfolio.git
git branch -M main
git push -u origin main
```

### Step 2: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click **Settings** → **Pages**
3. Under "Source", select **main** branch
4. Click **Save**
5. Your site will be live at: `https://yourusername.github.io/portfolio`

### Step 3: Custom Domain (Optional)

1. Purchase a domain (e.g., from Namecheap, Google Domains)
2. Add a `CNAME` file to your repository with your domain
3. Configure DNS settings with your domain provider
4. Update GitHub Pages settings with custom domain

## 🎨 Color Customization

To change the color scheme, edit these CSS variables in `style.css`:

```css
:root {
    --primary-color: #2563eb;      /* Main blue color */
    --secondary-color: #1e40af;    /* Darker blue */
    --text-dark: #1f2937;          /* Main text color */
    --text-light: #6b7280;         /* Secondary text */
    --bg-light: #f9fafb;           /* Light background */
    --bg-white: #ffffff;           /* White background */
    --border-color: #e5e7eb;       /* Borders */
}
```

## 📱 Mobile Optimization

The portfolio is fully responsive with:
- Hamburger menu on mobile devices
- Optimized font sizes and spacing
- Touch-friendly buttons and links
- Fast loading on slow connections

## 🔧 Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript (ES6)** - Interactive features
- **Git** - Version control
- **GitHub Pages** - Free hosting

## 📝 Adding New Content

### To Add a New Project:

Copy this template in `projects.html`:

```html
<div class="project-card">
    <h3>🎯 Project Title</h3>
    <p class="project-meta">Tools: Tool1, Tool2 | Year</p>
    <p>Project description goes here...</p>
    <div class="project-links">
        <a href="#">🔗 View on GitHub</a>
        <a href="#">🌐 Live Demo</a>
    </div>
</div>
```

### To Add a New Lab Challenge:

Copy this template in `labchallenges.html`:

```html
<div class="lab-card">
    <h3>🧩 Lab X: Challenge Title</h3>
    <div class="lab-detail">
        <strong>Problem:</strong>
        <p>Description of the problem...</p>
    </div>
    <div class="lab-detail">
        <strong>Tools Used:</strong>
        <p>Tool1, Tool2, Tool3</p>
    </div>
    <div class="lab-detail">
        <strong>Approach:</strong>
        <p>Your methodology...</p>
    </div>
    <div class="lab-detail">
        <strong>Key Lessons:</strong>
        <p>What you learned...</p>
    </div>
</div>
```

## ✅ Checklist Before Publishing

- [ ] Add your profile photo to `assets/img/`
- [ ] Update all placeholder links (LinkedIn, GitHub)
- [ ] Verify email addresses are correct
- [ ] Test all navigation links work
- [ ] Check mobile responsiveness
- [ ] Proofread all content for typos
- [ ] Test on multiple browsers (Chrome, Firefox, Safari)
- [ ] Optimize images (compress if large)
- [ ] Add favicon (optional)
- [ ] Create GitHub repository
- [ ] Push to GitHub
- [ ] Enable GitHub Pages

## 🎯 Next Steps

1. **Expand Your Projects Section**
   - Add screenshots or demos
   - Link to GitHub repositories
   - Include detailed technical write-ups

2. **Grow Your Lab Challenges**
   - Document each HackTheBox machine you complete
   - Create detailed walkthroughs
   - Share your methodology and learnings

3. **Blog Section (Optional)**
   - Create a `blog.html` page
   - Write technical articles
   - Share cybersecurity insights

4. **Analytics (Optional)**
   - Add Google Analytics to track visitors
   - Monitor which pages get the most traffic

## 📞 Support

If you need help or have questions:
- Open an issue on GitHub
- Email: johnmarkgichuki@gmail.com

## 🏆 Portfolio Highlights

This portfolio demonstrates:
- Clean, professional web development skills
- Strong understanding of responsive design
- Cybersecurity knowledge and practical experience
- Technical writing and documentation abilities
- Project management and organization skills

## 📈 SEO Tips

To improve your portfolio's visibility:

1. **Add meta descriptions** to each page:
```html
<meta name="description" content="Johnmark Gichuki - Aspiring Cybersecurity Analyst with experience in IT support, networking, and ethical hacking.">
```

2. **Add relevant keywords** in your content
3. **Create a sitemap.xml** for search engines
4. **Submit to Google Search Console** after publishing
5. **Share on LinkedIn** and professional networks

## 🔒 Security Best Practices

- Don't commit sensitive information (API keys, passwords)
- Use environment variables for any sensitive data
- Keep dependencies updated
- Regularly review and update content
- Monitor for broken links

## 🎓 Learning Resources

Continue improving your skills:
- **HackTheBox** - Practice ethical hacking
- **TryHackMe** - Cybersecurity training
- **PortSwigger Web Security Academy** - Web application security
- **OWASP** - Web application security knowledge
- **GitHub** - Contribute to open source projects

## 📄 License

This portfolio template is free to use. Feel free to fork and customize for your own use!

---

**Built with ❤️ by Johnmark Gichuki**

*Last Updated: October 2025*