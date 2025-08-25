# FlickZone Discord Server Website

A modern, responsive website for the FlickZone Discord server - your ultimate destination for movies, TV shows, and music discussions.

## 🎬 About FlickZone

FlickZone is a vibrant Discord community where entertainment enthusiasts come together to discuss:
- **Movies**: Latest blockbusters, hidden gems, and classic films
- **TV Shows**: Binge-worthy series, plot theories, and character development
- **Music**: Diverse genres, new artists, and favorite tracks

## ✨ Features

- **Responsive Design**: Optimized for desktop, tablet, and mobile devices
- **Modern UI/UX**: Cinematic theme with smooth animations and transitions
- **Interactive Elements**: Hover effects, scroll animations, and dynamic counters
- **Team Showcase**: Meet our dedicated staff with role hierarchy
- **Performance Optimized**: Fast loading with optimized assets

## 🚀 Deployment on GitHub Pages

### Quick Setup

1. **Fork or Clone this repository**
   ```bash
   git clone https://github.com/yourusername/flickzone-website.git
   cd flickzone-website
   ```

2. **Enable GitHub Pages**
   - Go to your repository settings
   - Scroll down to "Pages" section
   - Select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. **Your website will be live at:**
   ```
   https://yourusername.github.io/flickzone-website/
   ```

### File Structure

```
flickzone-website/
├── index.html              # Main HTML file
├── assets/
│   ├── css/
│   │   └── style.css       # Main stylesheet
│   ├── js/
│   │   └── script.js       # JavaScript functionality
│   └── images/
│       ├── flickzone-logo.png
│       ├── hero-background.jpg
│       └── vintage-film.jpg
├── README.md               # This file
└── .gitignore             # Git ignore file
```

## 🛠️ Customization

### Updating Discord Invite Link

Replace the `#` in the "Join FlickZone Discord" buttons with your actual Discord invite link:

```html
<!-- In index.html, find and update these links -->
<a href="YOUR_DISCORD_INVITE_LINK" class="btn btn-primary">
<a href="YOUR_DISCORD_INVITE_LINK" class="btn btn-join">
```

### Changing Colors

The website uses CSS custom properties for easy color customization. Edit the `:root` section in `assets/css/style.css`:

```css
:root {
    --primary-color: #d4af7a;      /* Gold/tan color from logo */
    --secondary-color: #2c3e50;    /* Dark blue-gray */
    --accent-color: #e74c3c;       /* Red accent */
    --dark-bg: #1a1a1a;           /* Dark background */
    --darker-bg: #0f0f0f;         /* Darker background */
    /* ... */
}
```

### Adding Team Members

To add real team member information, edit the team section in `index.html`:

```html
<div class="member-info">
    <h3 class="member-name">Actual Name</h3>
    <p class="member-role">Role Title</p>
    <p class="member-description">Member description...</p>
</div>
```

### Updating Statistics

Modify the statistics in the join section:

```html
<div class="stat-number" data-target="YOUR_NUMBER">0</div>
<div class="stat-label">Your Label</div>
```

## 🎨 Design Features

- **Cinematic Theme**: Movie-inspired design with film reels and camera imagery
- **Gradient Backgrounds**: Beautiful gradients matching the logo colors
- **Smooth Animations**: CSS animations and JavaScript interactions
- **Responsive Grid**: Flexible layouts that work on all screen sizes
- **Modern Typography**: Cinzel serif font for headings, Inter for body text

## 📱 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

Feel free to submit issues and enhancement requests!

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

**Built with ❤️ for the FlickZone community**

