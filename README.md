# Kanav Kaul - Personal Website

A professional portfolio website showcasing experience, skills, and projects.

## Features

- Responsive design that works on all devices
- Smooth scrolling navigation
- Professional timeline for work experience
- Skills showcase with interactive tags
- Contact information and links
- Modern, clean UI with animations

## Deployment to GitHub Pages

### Method 1: Using Git (Recommended)

1. Create a new repository on GitHub named `<your-username>.github.io`
   - Example: `kanavkaul.github.io`

2. Initialize and push your code:
```bash
cd /Users/kanav.kaul/Desktop/notes
git init
git add index.html styles.css script.js README.md
git commit -m "Initial commit: Personal website"
git branch -M main
git remote add origin https://github.com/<your-username>/<your-username>.github.io.git
git push -u origin main
```

3. Enable GitHub Pages:
   - Go to your repository Settings
   - Navigate to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"

4. Your site will be live at: `https://<your-username>.github.io`

### Method 2: Using GitHub Web Interface

1. Create a new repository on GitHub named `<your-username>.github.io`
2. Upload the files: `index.html`, `styles.css`, `script.js`
3. Enable GitHub Pages in repository Settings > Pages
4. Select "main" branch as source

## Customization

### Updating Content

- **Personal Info**: Edit the hero section in `index.html`
- **Experience**: Modify the timeline items
- **Skills**: Update the skill tags in the skills section
- **Projects**: Add or modify project cards
- **Contact**: Update contact information

### Styling

- **Colors**: Modify CSS variables in `styles.css` `:root` section
- **Fonts**: Change the Google Fonts import in `index.html`
- **Layout**: Adjust grid layouts in respective CSS sections

## Technologies Used

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Inter)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is open source and available for personal use.
