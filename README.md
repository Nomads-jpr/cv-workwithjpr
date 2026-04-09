# CV - Jan Rojek

Modern, professional CV in German and English with responsive design and print optimization.

## Files

- `index-de.html` - German version (Lebenslauf)
- `index-en.html` - English version (Resume)
- `styles.css` - Main stylesheet
- `print.css` - Print-optimized styles for PDF export
- `photo.jpg` - Profile photo (needs to be added)

## Quick Start

1. **Add your photo**: Copy your profile photo to this folder as `photo.jpg`
2. **Open in browser**: Double-click `index-de.html` or `index-en.html`
3. **View the CV**: The design will render in your browser

## Export to PDF

### Method 1: Browser Print (Recommended)

1. Open `index-de.html` or `index-en.html` in Chrome/Firefox
2. Press `Cmd+P` (Mac) or `Ctrl+P` (Windows)
3. Select "Save as PDF" as destination
4. Settings:
   - Paper size: A4
   - Margins: None
   - Background graphics: ON (important!)
5. Click "Save"

### Method 2: Using Chrome DevTools

1. Open the HTML file in Chrome
2. Press `Cmd+Shift+P` (Mac) or `Ctrl+Shift+P` (Windows)
3. Type "Capture full size screenshot" and press Enter
4. Converts to high-quality PNG

## Customization

### Colors

Edit the CSS variables in `styles.css`:

```css
:root {
  --primary: #2d3748;      /* Main dark color */
  --accent: #3182ce;       /* Blue accent */
  --bg-sidebar: #f7fafc;   /* Sidebar background */
}
```

### Photo

The photo uses circular styling with a border. Replace `photo.jpg` with your preferred image. Recommended size: 400x400px or larger, square format.

### Content

Edit the HTML files directly to update:
- Contact information
- Work experience
- Skills and competencies
- Education
- Portfolio links

## LinkedIn Integration

Update the LinkedIn link in both HTML files:
```html
<a href="https://linkedin.com/in/YOUR-PROFILE" target="_blank">LinkedIn</a>
```

## Print Tips

- Use Chrome for best print quality
- Enable "Background graphics" in print settings
- The print stylesheet automatically optimizes font sizes and spacing for A4
- Skill tags and colored elements will print correctly

## Photo Instructions

Your CV needs a profile photo. To add it:

1. Export your photo from the original CV PDF, OR
2. Use a high-quality headshot (minimum 400x400px)
3. Save as `photo.jpg` in this folder

The CSS will automatically:
- Crop it to a circle
- Add a professional border
- Scale it appropriately for screen and print

---

Created: December 2025
