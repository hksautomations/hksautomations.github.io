# How to Add Project Images

Each project page has an image placeholder. Here's how to add real screenshots.

## Step 1: Take Screenshots

### Best image: Your n8n workflow screenshot
1. Open workflow in n8n
2. Zoom out to show entire workflow
3. Windows: Win + Shift + S
4. Mac: Cmd + Shift + 4
5. Save as PNG

### Tips for great screenshots:
- Show the FULL workflow (zoom out)
- Make sure node labels are readable
- Use n8n's clean white background
- At least 1200px wide

## Step 2: Create Images Folder on GitHub

1. In your repository, click "Add file" → "Create new file"
2. Type: images/placeholder.txt
3. Add any text, commit
4. Now you have an images/ folder!

## Step 3: Upload Screenshots

Name your files EXACTLY as follows:
- lead-generation.png
- customer-support.png
- resume-analysis.png
- market-research.png
- gmail-organizer.png
- appointments.png
- onboarding.png
- cold-outreach.png

Upload all to the images/ folder.

## Step 4: Update Project Pages

In each project HTML file, find:
```html
<div class="proj-image">
    <div class="proj-image-placeholder">🎯</div>
    <div class="proj-image-hint">📸 Add your n8n workflow screenshot here</div>
</div>
```

Replace with:
```html
<div class="proj-image">
    <img src="../images/lead-generation.png" alt="Lead Generation Workflow">
</div>
```

## Recommended Image Size
- Width: 1200-1600px
- Height: 600-800px
- Format: PNG
- File size: Under 500KB (use compressor.io to reduce)
