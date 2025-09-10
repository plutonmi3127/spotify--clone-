# Spotify Clone

A modern web-based music player inspired by Spotify, built with HTML, CSS, and JavaScript.

## Features

- 🎵 Music player with play/pause, next/previous controls
- 📱 Responsive design for mobile and desktop
- 🎨 Modern UI with dark theme
- 🔊 Volume control and mute functionality
- ⏯️ Seek bar for track navigation
- 📚 Playlist management
- 🎧 Real-time track information display

## Getting Started

### Prerequisites

- Node.js (for development server)
- A modern web browser

### Installation

1. Clone the repository:
```bash
git clone <your-repo-url>
cd spotify-clone
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:3000`

### Alternative: Simple HTTP Server

If you don't want to use Node.js, you can serve the files using any static file server:

```bash
# Using Python
python -m http.server 3000

# Using PHP
php -S localhost:3000
```

## Project Structure

```
spotify-clone/
├── index.html          # Main HTML file
├── style.css           # Main stylesheet
├── utility.css         # Utility classes
├── script.js           # JavaScript functionality
├── package.json        # Node.js dependencies
├── README.md           # This file
└── assets/             # Image files
    ├── logo.svg
    ├── home.svg
    ├── search.svg
    ├── playlist.svg
    ├── music.svg
    ├── play.svg
    ├── pause.svg
    ├── prevsong.svg
    ├── nextsong.svg
    ├── volume.svg
    ├── mute.svg
    ├── hamburger.svg
    └── close.svg
```

## Music Files Setup

To add music to your player:

1. Create a `songs` folder in your project root
2. Create subfolders for each album/playlist
3. Add MP3 files to each subfolder
4. Create an `info.json` file in each subfolder with metadata:
```json
{
  "title": "Album Title",
  "description": "Album Description"
}
```
5. Add a `cover.jpg` image for each album

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to repository Settings > Pages
3. Select source branch (usually `main`)
4. Your site will be available at `https://username.github.io/repository-name`

### Netlify

1. Connect your GitHub repository to Netlify
2. Set build command: `npm run build`
3. Set publish directory: `.` (root)
4. Deploy!

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Run `vercel` in your project directory
3. Follow the prompts

## Browser Support

- Chrome (recommended)
- Firefox
- Safari
- Edge

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is licensed under the MIT License.

## Acknowledgments

- Inspired by Spotify's design
- Icons from various sources
- Music player functionality built with Web Audio API
