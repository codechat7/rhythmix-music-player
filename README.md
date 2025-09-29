# 🎵 Rhythmix - 90s Bollywood Music Player

![React](https://img.shields.io/badge/React-18.2.0-blue)
![Tailwind CSS](https://img.shields.io/badge/TailwindCSS-3.0-38B2AC)
![License](https://img.shields.io/badge/License-MIT-green)

A beautiful, fully responsive music player web application showcasing 90s Bollywood classics with modern UI/UX design principles.

## 🌟 Features

### 🎶 Audio Features
- **Real Audio Playback** using HTML5 Audio API
- **Play/Pause Controls** with resume functionality
- **Next/Previous Track** navigation
- **Progress Bar** with click-to-seek capability
- **Volume Control** with visual slider
- **Auto-play Next** when current song ends

### 🎨 UI/UX Features
- **Dark/Light Theme Toggle** with localStorage persistence
- **Glassmorphism Design** with backdrop blur effects
- **Fully Responsive Layout** for mobile, tablet, and desktop
- **Animated Album Art** with vinyl record design
- **Smooth Transitions** and hover effects
- **Real-time Notifications** for user actions
- **Playlist Management** with drill-down navigation

### ⚡ Technical Features
- Custom React Hooks for audio state management
- Component-based architecture
- Optimized performance with proper cleanup
- Keyboard shortcuts support
- Cross-browser compatibility
- Modular and maintainable code structure

## 🎹 Keyboard Shortcuts
- `Space` - Play/Pause
- `→` - Next Track
- `←` - Previous Track
- `T` - Toggle Theme

## 🚀 Live Demo
[View Live Demo](your-deployment-link-here)

## 📸 Screenshots

### Light Theme
![Light Theme](screenshots/light-theme.png)

### Dark Theme
![Dark Theme](screenshots/dark-theme.png)

### Playlist View
![Playlist View](screenshots/playlist-view.png)

## 🛠️ Tech Stack

- **Frontend Framework:** React 18.2.0
- **Styling:** Tailwind CSS (via CDN)
- **Audio:** HTML5 Audio API
- **State Management:** React Hooks (useState, useEffect, useRef)
- **Storage:** localStorage for theme persistence
- **Build Tool:** Create React App

## 📁 Project Structure
```
rhythmix-music-player/
├── public/
│   ├── audio/                # Audio files
│   └── index.html
├── src/
│   ├── components/
│   │   ├── LeftPanel.js     # Playlist & navigation
│   │   ├── RightPanel.js    # Now playing interface
│   │   └── Notification.js  # Toast notifications
│   ├── data/
│   │   └── songsData.js     # Songs & playlist data
│   ├── hooks/
│   │   └── useAudio.js      # Custom audio hook
│   ├── App.js               # Main component
│   ├── App.css              # Custom styles
│   └── index.js             # Entry point
└── package.json
```

## 🚀 Getting Started

### Prerequisites
- Node.js (v14.0 or higher)
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/your-username/rhythmix-music-player.git
cd rhythmix-music-player
```

2. Install dependencies
```bash
npm install
```

3. Add your audio files
```bash
mkdir public/audio
# Place your MP3 files in public/audio/
```

4. Start the development server
```bash
npm start
```

5. Open [http://localhost:3000](http://localhost:3000)

## 🎵 Adding Your Own Songs

1. Place MP3 files in `public/audio/` folder
2. Update `src/data/songsData.js`:
```javascript
{
  id: 1,
  title: "Your Song Title",
  artist: "Artist Name",
  movie: "Movie Name",
  year: "Year",
  duration: 300, // seconds
  albumArt: "custom-art",
  audioUrl: "/audio/your-song.mp3",
  category: ["bollywood-classics"]
}
```

## 🎨 Customization

### Themes
Modify theme colors in `src/App.js` and `src/App.css`

### Album Artwork
Customize album art in `src/data/songsData.js` - `albumArtData` object

### Playlists
Add new playlists in `src/data/songsData.js` - `playlists` array

## 📱 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👨‍💻 Author

**Susmita**
- GitHub: [@your-username](https://github.com/your-username)
- LinkedIn: [Your LinkedIn](https://linkedin.com/in/your-profile)

## 🙏 Acknowledgments

- Inspired by modern music streaming platforms
- 90s Bollywood music for the nostalgia
- React community for amazing tools and resources

## 📧 Contact

For any queries or suggestions, feel free to reach out!

---

**Made with ❤️ and lots of ☕**
