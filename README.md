# Head Lice Management Interactive Quiz

**Created by Dr. Samar J Melhem, MSc, MA, PhD**

An interactive educational quiz with 50 questions covering head lice management, with a strong focus on pharmacologic treatment.

## Features

- **30 Multiple Choice Questions** - Comprehensive coverage of pharmacologic management
- **10 Matching Questions** - Connect concepts, mechanisms, and treatments
- **10 Fill-in-the-Blank Questions** - Test recall of key facts and terminology
- **Integrated Figures** - Visual learning aids from the original lecture
- **Instant Feedback** - Detailed explanations and study tips for each question
- **Export Functionality** - Save answers as CSV or Excel files
- **Colorful Interface** - Engaging purple and green design
- **Mobile Responsive** - Works on all devices

## How to Host on GitHub Pages

### Option 1: Quick Upload (Easiest)

1. **Create a new GitHub repository:**
   - Go to https://github.com/new
   - Name your repository (e.g., `head-lice-quiz`)
   - Make it **Public**
   - Click "Create repository"

2. **Upload files:**
   - Click "uploading an existing file"
   - Drag and drop ALL files from the `standalone-quiz` folder:
     - `index.html`
     - `README.md`
     - The entire `images` folder
   - Click "Commit changes"

3. **Enable GitHub Pages:**
   - Go to repository Settings → Pages
   - Under "Source", select "main" branch
   - Click "Save"
   - Your quiz will be live at: `https://[your-username].github.io/[repository-name]/`

### Option 2: Using Git Command Line

```bash
# Navigate to the standalone-quiz folder
cd /path/to/standalone-quiz

# Initialize git repository
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit: Head Lice Management Quiz"

# Add your GitHub repository as remote
git remote add origin https://github.com/[your-username]/[repository-name].git

# Push to GitHub
git branch -M main
git push -u origin main
```

Then enable GitHub Pages in repository settings as described in Option 1, step 3.

### Option 3: Using GitHub Desktop (User-Friendly)

1. Download and install [GitHub Desktop](https://desktop.github.com/)
2. Click "File" → "Add Local Repository"
3. Select the `standalone-quiz` folder
4. Click "Publish repository" button
5. Choose repository name and make it public
6. Click "Publish Repository"
7. Enable GitHub Pages in repository settings (see Option 1, step 3)

## File Structure

```
standalone-quiz/
├── index.html          # Main quiz file (self-contained)
├── README.md           # This file
└── images/             # Lecture figures
    ├── page-02.png
    ├── page-04.png
    ├── page-05.png
    ├── page-06.png
    ├── page-07.png
    ├── page-11.png
    └── [other images]
```

## Important Notes

- **All files must be uploaded** - The quiz needs the `images` folder to display figures
- **Case-sensitive paths** - GitHub Pages is case-sensitive, so maintain exact folder names
- **Wait 2-5 minutes** - After enabling GitHub Pages, it may take a few minutes to go live
- **Custom domain** - You can add a custom domain in GitHub Pages settings if desired

## Using the Quiz

1. Students fill out all 50 questions
2. Click "Submit Quiz" when complete
3. View instant results with explanations and study tips
4. Export answers to CSV or Excel for record-keeping

## Technical Details

- **Pure HTML/CSS/JavaScript** - No build process required
- **External Dependencies:**
  - SheetJS (XLSX) library for Excel export (loaded from CDN)
- **Browser Compatibility:** Modern browsers (Chrome, Firefox, Safari, Edge)

## Troubleshooting

**Images not showing?**
- Ensure the `images` folder is in the same directory as `index.html`
- Check that folder name is exactly `images` (lowercase)
- Verify all image files were uploaded

**Quiz not loading?**
- Check browser console for errors (F12)
- Ensure JavaScript is enabled
- Try a different browser

**GitHub Pages not working?**
- Verify repository is public
- Check that Pages is enabled in Settings
- Wait 5 minutes and refresh
- Check the Pages URL matches your repository name

## License

Educational material created for academic purposes.

## Contact

For questions about the content, please contact Dr. Samar J Melhem.

---

**Version:** 1.0  
**Last Updated:** October 2024

