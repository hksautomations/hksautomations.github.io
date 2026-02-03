# HKS Automations - Portfolio Website

Professional portfolio showcasing production-grade AI automation systems built with n8n + LLMs.

## 🚀 Live Site
Once deployed: `https://hksautomations.github.io`

## 📂 Structure
```
hks-portfolio/
├── index.html              # Main landing page
├── projects/               # Individual project pages
│   ├── lead-generation.html
│   ├── customer-support.html
│   └── ... (other projects)
└── README.md
```

## 🎨 Features
- Modern, distinctive design that avoids generic AI aesthetics
- Mobile-responsive layout
- Fast loading (no external dependencies except fonts)
- SEO-optimized
- Professional presentation of 8+ automation systems

## 📦 Deployment to GitHub Pages

### Step 1: Create GitHub Repository
1. Go to https://github.com/new
2. Repository name: `hksautomations.github.io` (must be exact)
3. Set to **Public**
4. Click "Create repository"

### Step 2: Upload Files
**Option A: Using GitHub Web Interface**
1. Click "uploading an existing file"
2. Drag and drop all files from `hks-portfolio` folder
3. Commit changes

**Option B: Using Git CLI**
```bash
cd hks-portfolio
git init
git add .
git commit -m "Initial portfolio website"
git branch -M main
git remote add origin https://github.com/hksautomations/hksautomations.github.io.git
git push -u origin main
```

### Step 3: Enable GitHub Pages
1. Go to repository Settings
2. Click "Pages" in left sidebar
3. Source: Deploy from branch "main"
4. Folder: / (root)
5. Click "Save"

### Step 4: Wait & Access
- GitHub will build your site (takes 1-2 minutes)
- Access at: `https://hksautomations.github.io`

## ✏️ Customization

### Update Contact Info
Edit `index.html` and all project pages:
- Email: `hks.automations@gmail.com`
- LinkedIn: Update links to your actual profile
- GitHub: Update links to your repositories

### Add New Projects
1. Create new HTML file in `projects/` folder
2. Use `projects/lead-generation.html` as template
3. Update project details
4. Add link in `index.html` projects grid

### Color Scheme
Modify CSS variables in `<style>` section:
```css
:root {
    --bg-dark: #0a0a0f;
    --accent-cyan: #00fff5;
    --accent-magenta: #ff00ff;
}
```

## 📧 Contact
Harvish Shah  
Email: hks.automations@gmail.com  
GitHub: https://github.com/hksautomations  
LinkedIn: https://www.linkedin.com/in/hks-automations

## 📄 License
© 2026 HKS Automations. All rights reserved.
