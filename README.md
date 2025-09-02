# Sachin Chopra - Music Showcase Website

A comprehensive, modern website showcasing both contemporary and classical music, designed for easy deployment on Vercel.

## 🎵 Features

- **Landing Page**: Beautiful hero section with clear navigation to all music sections
- **Modern Music**: Spotify artist profile and album showcase with cover art
- **Classical Performances**: YouTube video integration and PDF program display
- **Classical Playlists**: 20+ curated playlists organized into 3 categories
- **Responsive Design**: Optimized for all devices
- **Modern UI**: Glassmorphism effects, smooth animations, and professional styling

## 🚀 Quick Start

### Local Development

1. Clone or download this repository
2. Open `index.html` in your browser, or run a local server:
   ```bash
   npx serve .
   ```

### Deploy to Vercel

1. Push your code to a GitHub repository
2. Connect your GitHub account to Vercel
3. Import your repository in Vercel dashboard
4. Deploy automatically (no build configuration needed)

Alternatively, use Vercel CLI:
```bash
npm install -g vercel
vercel
```

## 📝 Customization Guide

### 1. Modern Music Section (`modern-music.html`)

**Artist Profile:**
- Replace `YOUR_ARTIST_ID` with your Spotify artist ID
- Find your artist ID: Right-click your artist profile → Share → Copy Spotify URI
- Extract the ID from: `spotify:artist:YOUR_ARTIST_ID`

**Albums:**
- Replace `YOUR_ALBUM_ID_X` with actual album IDs
- Update album titles and descriptions
- Add cover art by replacing the placeholder divs with `<img>` tags

### 2. Classical Performances (`classical-performances.html`)

**YouTube Video:**
- Replace `YOUR_VIDEO_ID` with your actual YouTube video ID
- Find video ID in your YouTube URL: `youtube.com/watch?v=YOUR_VIDEO_ID`

**Program PDF:**
- Add your `program.pdf` file to the project root
- The page will automatically display it

### 3. Classical Playlists (`classical-playlists.html`)

**Playlist Links:**
- Replace `YOUR_PLAYLIST_ID_X` with actual Spotify playlist IDs
- Find playlist ID: Right-click playlist → Share → Copy Spotify URI
- Extract ID from: `spotify:playlist:YOUR_PLAYLIST_ID`

**Customization:**
- Update playlist titles to match your actual names
- Rewrite descriptions to reflect your personal curation
- Adjust categories if needed (currently: Relaxed, Epic, Deep-Dives)
- Add/remove playlist cards to match your collection

### 4. Adding Cover Art

Replace placeholder divs with actual images:
```html
<!-- Replace this: -->
<div class="album-cover">
    <span>Album Cover Art</span>
</div>

<!-- With this: -->
<div class="album-cover">
    <img src="path/to/your/album-cover.jpg" alt="Album Title" style="width: 100%; height: 100%; object-fit: cover; border-radius: 10px;">
</div>
```

## 📁 Project Structure

```
Music Website/
├── index.html              # Landing page
├── modern-music.html       # Spotify artist & albums
├── classical-performances.html # YouTube & PDF program
├── classical-playlists.html    # Curated playlists
├── styles.css             # All styling
├── script.js              # Interactive features
├── vercel.json            # Vercel deployment config
├── package.json           # Project metadata
├── program.pdf            # Your concert program (add this)
└── README.md              # This file
```

## 🎨 Design Features

- **Glassmorphism**: Modern frosted glass effects
- **Gradient Backgrounds**: Beautiful color transitions
- **Smooth Animations**: Hover effects and loading animations
- **Responsive Grid**: Adapts to all screen sizes
- **Accessibility**: Proper contrast and semantic HTML
- **Performance**: Optimized for fast loading

## 🔧 Technical Details

- **Framework**: Vanilla HTML/CSS/JS (no build process required)
- **Fonts**: Inter font family from Google Fonts
- **Icons**: Font Awesome 6
- **Deployment**: Static hosting on Vercel
- **Browser Support**: Modern browsers (Chrome, Firefox, Safari, Edge)

## 📱 Responsive Breakpoints

- Desktop: 1200px+
- Tablet: 768px - 1199px
- Mobile: 480px - 767px
- Small Mobile: <480px

## 🎯 Next Steps

1. **Add Your Content**: Replace all placeholder IDs and descriptions
2. **Upload Media**: Add your program PDF and any cover art images
3. **Test Locally**: Verify all links and content work correctly
4. **Deploy**: Push to Vercel for live hosting
5. **Share**: Your music showcase is ready for the world!

## 💡 Tips

- Use high-quality images (at least 500x500px) for cover art
- Keep descriptions engaging and personal
- Test all Spotify/YouTube links before deploying
- Consider adding Google Analytics for visitor insights

---

Built with ❤️ for showcasing the beauty of music across genres and eras. 