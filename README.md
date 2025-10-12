# Photo Album - Static Website

A simple and elegant static photo album website built with HTML and CSS.

## Features

- Responsive grid layout that adapts to all screen sizes
- Clean and modern design
- Hover effects on photo cards
- Easy to customize and add photos

## How to Use

### 1. Add Your Photos

1. Place your photo files in the `photos/` directory
2. Supported formats: JPG, PNG, GIF, WebP
3. Recommended image size: 800x600px or larger

### 2. Update the HTML

Edit `index.html` and update the photo cards:

```html
<div class="photo-card">
    <img src="photos/your-photo.jpg" alt="Description">
    <div class="photo-caption">
        <h3>Your Photo Title</h3>
        <p>Your photo description</p>
    </div>
</div>
```

### 3. Add More Photos

To add more photos, simply copy and paste the photo card structure:

- Duplicate a `<div class="photo-card">` block
- Update the `src` attribute with your photo filename
- Update the title and description
- The grid will automatically adjust

### 4. Customize

**Change Header:**
Edit the header section in `index.html`:
```html
<header>
    <h1>My Photo Album</h1>
    <p>A collection of my favorite moments</p>
</header>
```

**Change Colors:**
Edit `styles.css`:
- Header gradient: Line 18-19
- Card hover effect: Line 54-57
- Footer background: Line 77

### 5. View Your Album

Simply open `index.html` in any web browser, or host it on:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service

## File Structure

```
static/
├── index.html          # Main HTML file
├── styles.css          # Stylesheet
├── photos/             # Your photos go here
│   └── .gitkeep
└── README.md           # This file
```

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Tips

- Use consistent image sizes for best results
- Optimize images before uploading (compress for web)
- Keep file names simple (no spaces or special characters)
- Update the footer copyright year as needed

## License

Free to use for personal or commercial projects.
