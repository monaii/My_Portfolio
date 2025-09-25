# Mona Pouresmaeil - Portfolio Website

A modern, responsive portfolio website showcasing my transition from software engineering to AI/ML and data science.

## 🚀 Live Demo

Once deployed, your portfolio will be available at: `https://monaii.github.io/portfolio`

## 📋 About

This portfolio website highlights:
- My background in software engineering
- Current transition to AI/ML and data science
- Academic achievements and ongoing master's studies
- Professional goals and internship opportunities
- Links to professional profiles (LinkedIn, GitHub, Kaggle)

## 🛠️ Technologies Used

- **HTML5** - Semantic markup and structure
- **CSS3** - Modern styling with Flexbox and Grid
- **JavaScript** - Interactive functionality and animations
- **Font Awesome** - Professional icons
- **Google Fonts** - Inter font family for clean typography

## 📁 Project Structure

```
portfolio/
├── index.html          # Main HTML file
├── styles.css          # CSS styles and responsive design
├── script.js           # JavaScript functionality
├── images/             # Folder for images and assets
│   └── profile.jpg     # Your profile photo (add this file)
└── README.md           # Project documentation
```

## 🚀 Deployment to GitHub Pages

### Step 1: Create GitHub Repository

1. Go to [GitHub](https://github.com) and sign in to your account (`monaii`)
2. Click the "+" icon in the top right corner and select "New repository"
3. Name your repository `portfolio`
4. Make sure it's set to **Public**
5. **Do NOT** initialize with README, .gitignore, or license (we already have files)
6. Click "Create repository"

### Step 2: Upload Your Files

#### Option A: Using GitHub Web Interface (Easiest)

1. In your new repository, click "uploading an existing file"
2. Drag and drop all files (`index.html`, `styles.css`, `script.js`, `README.md`) into the upload area
3. Add a commit message like "Initial portfolio website"
4. Click "Commit changes"

#### Option B: Using Git Commands (If you have Git installed)

```bash
# Navigate to your portfolio folder
cd /Users/mona/Desktop/projects/portfolio

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial portfolio website"

# Add remote repository (replace with your actual repo URL)
git remote add origin https://github.com/monaii/portfolio.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click on the "Settings" tab
3. Scroll down to "Pages" in the left sidebar
4. Under "Source", select "Deploy from a branch"
5. Choose "main" branch and "/ (root)" folder
6. Click "Save"

### Step 4: Access Your Live Website

- Your website will be available at: `https://monaii.github.io/portfolio`
- It may take a few minutes for the site to become available
- GitHub will show you the URL in the Pages settings

## 🎨 Customization

### Adding Your Photo

1. Add your profile photo to the `images/` folder
2. Name it `profile.jpg` (or update the filename in `index.html` if different)
3. Recommended size: 400x400 pixels or larger (square format works best)
4. The photo will be automatically cropped to a circle and optimized for all devices

### Adding Your Projects

1. Open `index.html`
2. Find the "Projects" section
3. Replace placeholder project cards with your actual projects
4. Update project descriptions, technologies, and links

### Updating Personal Information

1. Modify the hero section with your specific details
2. Update the About section with your personal story
3. Add or remove skills in the Skills section
4. Update education details as needed

### Styling Changes

1. Open `styles.css`
2. Modify colors by changing the CSS custom properties
3. Adjust fonts, spacing, or layout as desired

## 📱 Features

- **Responsive Design** - Works on all devices
- **Modern UI/UX** - Clean, professional appearance
- **Smooth Animations** - Engaging user experience
- **SEO Friendly** - Proper meta tags and semantic HTML
- **Fast Loading** - Optimized performance
- **Accessible** - WCAG compliant design

## 🔧 Local Development

To run the website locally:

1. Open `index.html` in your web browser
2. Or use a local server:
   ```bash
   # Using Python 3
   python -m http.server 8000
   
   # Using Node.js (if you have live-server installed)
   npx live-server
   ```

## 📞 Contact Information

- **LinkedIn**: [Mona Pouresmaeil](https://linkedin.com/in/mona-pouresmaeil-8b04a82b4/)
- **GitHub**: [monaii](https://github.com/monaii)
- **Kaggle**: [monapouresmaeil](https://kaggle.com/monapouresmaeil)

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Note**: Remember to update your projects section as you complete new work, and keep your skills and experience sections current as you progress in your AI/ML journey!