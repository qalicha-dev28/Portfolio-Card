Professional Portfolio Website
Project Overview
A modern, responsive portfolio website built with pure HTML and CSS, showcasing web development skills and professional contact information.

Features
Fully Responsive Design - Mobile-first approach with optimized layouts

Modern UI/UX - Clean design with smooth animations and transitions

Accessibility First - ARIA labels, semantic HTML, and keyboard navigation

Functional Contact Links - Working social media and communication links

Performance Optimized - Fast loading times with optimized assets

Cross-Browser Compatible - Works on all modern browsers

Technologies Used
HTML5 - Semantic markup

CSS3 - Custom properties, Grid, Flexbox, animations

Font Awesome - Icon library

Google Fonts - Inter font family

Vanilla JavaScript - Minimal interactivity

Project Structure
text
portfolio-website/
├── index.html
├── styles.css
├── README.md
└── Images/
    └── Image.jpg
Contact Information
Direct Contact
Email: borunajma69@gmail.com (pre-filled message template)

Phone: +254 783 0788 (click-to-call)

WhatsApp: +254 783 0788 (direct messaging)

Social Media
GitHub: https://github.com/qalicha28-dev28

Instagram: https://instagram.com/qalicha_najma

TikTok: https://tiktok.com/@qalicha_najma

Quick Start
1. Create Project Structure
bash
mkdir portfolio-website
cd portfolio-website
touch index.html styles.css README.md
mkdir Images
2. Add Profile Image
Place your image in Images/Image.jpg

3. Copy HTML Code
Open index.html and paste the provided HTML code

4. Copy CSS Code
Open styles.css and paste the provided CSS code

5. Test Locally
bash
# On macOS:
open index.html

# On Linux:
xdg-open index.html

# On Windows:
start index.html
Deployment to Vercel
Install Vercel CLI
bash
npm install -g vercel
Login to Vercel
bash
vercel login
Deploy Your Site
bash
cd portfolio-website
vercel
Follow the prompts:

Set up and deploy? → Press Enter

Which scope? → Press Enter

Link to existing project? → Type n and press Enter

Project name? → Type portfolio-website and press Enter

Directory? → Press Enter

Your site will be live at: https://portfolio-card-five.vercel.app/

Redeploy After Changes
bash
vercel --prod
Customization
Update Contact Info
Edit these in index.html:

Lines 197-213: Email and phone

Lines 229-254: Social media links

Change Colors
Edit in styles.css (lines 15-25):

css
:root {
    --primary: #667eea;    /* Primary color */
    --secondary: #764ba2;  /* Secondary color */
    --accent: #f56565;     /* Accent color */
}
Add New Skill
Add this HTML:

html
<div class="skill-item">
    <div class="skill-header">
        <span class="skill-name">New Skill</span>
        <span class="skill-percentage">85%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress new-skill-progress"></div>
    </div>
</div>
Add this CSS:

css
.new-skill-progress { width: 85%; }
Testing
Check Files
bash
ls -la
ls -la Images/
Validate HTML
bash
curl -H "Content-Type: text/html; charset=utf-8" --data-binary @index.html https://validator.w3.org/nu/?out=gnu
Validate CSS
bash
curl -H "Content-Type: text/css" --data-binary @styles.css https://jigsaw.w3.org/css-validator/validator
Troubleshooting
Vercel Issues
bash
vercel logs
vercel --debug
Images Not Loading
bash
ls -la Images/Image.jpg
CSS Not Applying
bash
grep "styles.css" index.html
Maintenance
Update Site
bash
# Make changes, then:
vercel --prod
Check Deployments
bash
vercel list
Remove Deployment
bash
vercel remove portfolio-website
Quick Commands Summary
bash
# Create and deploy:
mkdir portfolio-website && cd portfolio-website
touch index.html styles.css README.md
mkdir Images
# Add image to Images/Image.jpg
# Copy HTML/CSS code
npm install -g vercel
vercel login
vercel
Resources
Vercel Docs: https://vercel.com/docs

HTML Validator: https://validator.w3.org

CSS Validator: https://jigsaw.w3.org/css-validator

Last Updated: December 2025
Version: 1.0.0
Deployment: Vercel
Status: Production Ready

