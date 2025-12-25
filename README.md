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
bash
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
GitHub: github.com/qalicha28-dev28

Instagram: instagram.com/qalicha_najma

TikTok: tiktok.com/@qalicha_najma

Setup Instructions
1. Create Project Structure
bash
# Create project directory
mkdir portfolio-website
cd portfolio-website

# Create HTML file
touch index.html

# Create CSS file
touch styles.css

# Create README file
touch README.md

# Create images directory
mkdir Images
2. Add Your Profile Image
bash
# Place your profile image in the Images folder
# Ensure it's named Image.jpg
# Supported formats: JPG, PNG, WebP
3. Copy HTML Code
bash
# Open index.html in your preferred editor
# Copy and paste the HTML code provided
# Save the file
4. Copy CSS Code
bash
# Open styles.css in your preferred editor
# Copy and paste the CSS code provided
# Save the file
5. Test Locally
bash
# Open index.html in your browser
# Test all links and responsive design
# Use Chrome DevTools for mobile testing
Deployment to Vercel
Option 1: Vercel CLI (Recommended)
bash
# Install Vercel CLI globally
npm install -g vercel

# Login to Vercel (first time only)
vercel login

# Deploy from project directory
cd portfolio-website
vercel

# Follow the prompts
# Choose default options for:
# - Set up and deploy: Yes
# - Which scope: Personal
# - Link to existing project: No
# - Project name: portfolio-website
# - Directory: . (current directory)
Option 2: Drag & Drop on Vercel Website
Visit vercel.com/new

Drag and drop your portfolio-website folder

Vercel will automatically detect and deploy

Your site will be live in seconds

Option 3: Connect GitHub Repository
Push your code to GitHub:

bash
# Initialize git repository
git init

# Add all files
git add .

# Commit changes
git commit -m "Initial commit: Portfolio website"

# Add remote repository (replace with your GitHub URL)
git remote add origin https://github.com/yourusername/portfolio-website.git

# Push to GitHub
git branch -M main
git push -u origin main
Connect GitHub to Vercel:

Go to vercel.com/new

Click "Import Git Repository"

Select your portfolio-website repository

Click "Import"

Deploy automatically

Customization Guide
Update Personal Information
bash
# Edit the HTML file to update:
# 1. Name and job title
# 2. Skills and percentages
# 3. About me text
# 4. Contact information
Change Colors
bash
# Edit styles.css and modify these CSS variables:
:root {
    --primary: #667eea;    /* Change primary color */
    --secondary: #764ba2;  /* Change secondary color */
    --accent: #f56565;     /* Change accent color */
}
Add New Skills
bash
# Add new skill item in HTML (in skills section):
<div class="skill-item">
    <div class="skill-header">
        <span class="skill-name">New Skill</span>
        <span class="skill-percentage">85%</span>
    </div>
    <div class="skill-bar">
        <div class="skill-progress new-skill-progress"></div>
    </div>
</div>

# Then add in CSS:
.new-skill-progress { width: 85%; }
Testing Commands
Validate HTML
bash
# Use W3C Validator
curl -H "Content-Type: text/html; charset=utf-8" \
--data-binary @index.html \
https://validator.w3.org/nu/?out=gnu
Validate CSS
bash
# Use W3C CSS Validator
curl -H "Content-Type: text/css" \
--data-binary @styles.css \
https://jigsaw.w3.org/css-validator/validator
Test Responsive Design
bash
# Open Chrome DevTools for testing:
# 1. Open index.html in Chrome
# 2. Press F12 or Ctrl+Shift+I
# 3. Click Toggle Device Toolbar (Ctrl+Shift+M)
# 4. Test different device sizes
Troubleshooting
Common Issues and Solutions
Images Not Displaying
bash
# Check image path and file name
ls -la Images/
# Ensure file is named exactly: Image.jpg
# Check file permissions
chmod 644 Images/Image.jpg
CSS Not Loading
bash
# Verify CSS file path in HTML
grep 'styles.css' index.html
# Should show: <link rel="stylesheet" href="styles.css">

# Check CSS file exists
ls -la styles.css
Links Not Working
bash
# Test each link manually
# Check for typos in URLs
# Verify target="_blank" and rel attributes
Performance Optimization
Image Optimization
bash
# Install ImageMagick for optimization
sudo apt-get install imagemagick  # Ubuntu/Debian
brew install imagemagick         # macOS

# Optimize profile image
convert Images/Image.jpg -quality 85 -resize 500x500 Images/Image-optimized.jpg
Minify CSS (Optional)
bash
# Install CSS minifier
npm install -g css-minifier

# Minify CSS file
css-minifier -o styles.min.css styles.css
Maintenance
Update Dependencies
bash
# Check for broken CDN links
# Test Font Awesome and Google Fonts links
# Update CDN URLs if needed
Regular Testing
bash
# Test all contact links monthly
# Verify social media profiles are active
# Check responsive design on new devices
Support
For issues or questions:

Check this README for solutions

Verify file structure and naming

Test on different browsers

Clear browser cache if issues persist

License
This project is open source and available for personal and commercial use.

Last Updated: January 2025
Version: 1.0.0
Deployment Platform: Vercel
Status: Production Ready

