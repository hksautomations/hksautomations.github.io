# HKS Automations — Website

**Live URL:** https://hksautomations.com (after domain setup)
**GitHub Pages URL:** https://hksautomations.github.io

## File Structure

```
hksautomations/
├── index.html                  ← Main homepage
├── projects/
│   ├── lead-generation.html
│   ├── customer-support.html
│   ├── resume-analysis.html
│   ├── market-research.html
│   ├── gmail-organizer.html
│   ├── appointments.html
│   ├── onboarding.html
│   └── cold-outreach.html
├── images/                     ← Add your screenshots here
│   └── (add workflow screenshots)
├── README.md
├── HOW-TO-ADD-IMAGES.md
├── EXECUTION-PLAN.md
├── LEAD-FINDING-GUIDE.md
└── START-HERE.md
```

## Deploying to GitHub Pages

1. Go to your repository: github.com/hksautomations/hksautomations.github.io
2. Upload ALL files (keeping folder structure)
3. Settings → Pages → Deploy from main branch
4. Wait 2-3 minutes
5. Visit: https://hksautomations.github.io

## Connecting Custom Domain (hksautomations.com)

1. Buy domain on Namecheap
2. In Namecheap DNS, add:
   - Type: CNAME
   - Host: www
   - Value: hksautomations.github.io
3. In GitHub repo Settings → Pages → Custom domain: hksautomations.com
4. Wait 24 hours for DNS propagation

## Contact Form Setup (Free)

1. Go to formspree.io → Create account
2. Create new form
3. Copy your Form ID (looks like: xpzgkwqr)
4. In index.html, replace YOUR_FORM_ID with your actual ID
5. Test by submitting the form
