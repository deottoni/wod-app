# WOD Timer App 🏋️

A modern, minimalist workout timer application designed for CrossFit and functional fitness workouts. Currently features EMOM (Every Minute On the Minute) timing with integrated music playback and voice callouts.

[![Live Demo](https://img.shields.io/badge/demo-live-success)](https://deottoni.github.io/wod-app)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)

## ✨ Features

### Current Features (v1.0)
- **EMOM Timer**: Customizable rounds (1-60 minutes)
- **Music Integration**: Built-in curated playlists
  - Techno/House
  - Hip Hop
  - Electronic/EDM
- **Smart Audio Ducking**: Music automatically fades during voice callouts and beeps
- **Voice Callouts** (masculine voice):
  - "Halfway" at 30 seconds
  - "10 seconds remaining" at 10 seconds
  - 3-2-1 countdown beeps
- **Visual Timer**: Large circular progress indicator
- **Round Counter**: Clear display of current round progress
- **Mobile-First Design**: Optimized for phone and tablet displays
- **TV Mirroring Ready**: Perfect for AirPlay/Roku screen mirroring

### Coming Soon
- Tabata Timer
- AMRAP Timer
- Stopwatch
- Custom Interval Timer
- User-uploaded music playlists
- Workout history tracking

## 🚀 Quick Start

### Live Demo
Visit the live app: [https://deotoni.github.io/wod-app](https://deottoni.github.io/wod-app)

### Local Development
1. Clone the repository:
```bash
git clone https://github.com/deotoni/wod-app.git
cd wod-app
```

2. Open `index.html` in your browser:
```bash
# macOS
open index.html

# Linux
xdg-open index.html

# Windows
start index.html
```

No build process or dependencies required! The app runs entirely in the browser.

## 📱 Usage

### Basic Setup
1. Open the app on your phone or computer
2. Select the number of rounds (default: 10)
3. Choose your music playlist
4. Press "Start Timer"

### For Garage Gym TV Display
1. Open the app on your phone
2. Start your workout
3. Mirror your phone to TV via:
   - **iPhone**: AirPlay to Apple TV/Roku
   - **Android**: Screen Mirroring to Roku/Smart TV
4. Music and timer beeps will play through TV speakers

### Adding Custom Music
To add your own music playlists:
1. Fork the repository
2. Host your MP3 files (via GitHub, Dropbox, Google Drive, etc.)
3. Update the `MUSIC_LIBRARY` object in `index.html` with your music URLs
4. Commit and push - GitHub Pages will auto-update

### Audio Features
- Music plays continuously throughout the workout
- Automatic volume ducking during callouts
- Voice callouts at key intervals (30s, 10s)
- 3-2-1 countdown beeps at the end of each minute

## 🛠️ Technology Stack

- **Frontend**: React 18 (via CDN)
- **Styling**: Tailwind CSS
- **Audio**: Web Audio API + Speech Synthesis API
- **Deployment**: GitHub Pages
- **Build**: None required - pure HTML/JS

## 🎨 Design Philosophy

The app features a **hardcore, industrial aesthetic** with:
- Steel, black, and grey color palette
- Old silver accents
- Minimalist, distraction-free interface
- Large, easy-to-read numbers
- Purpose-built for intense workouts

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Roadmap & Feature Requests
Check out the [Issues](https://github.com/deottoni/wod-app/issues) page for planned features and known issues. Feel free to suggest new features!

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Royalty-free workout music provided by [Pixabay](https://pixabay.com/music/)
- Built with [React](https://reactjs.org/)
- Styled with [Tailwind CSS](https://tailwindcss.com/)

## 📞 Support

Having issues or questions?
- Open an [Issue](https://github.com/deottoni/wod-app/issues)
- Check out [Discussions](https://github.com/deottoni/wod-app/discussions)

## 🔮 Future Plans

- [ ] Tabata timer mode
- [ ] AMRAP timer mode  
- [ ] Custom interval builder
- [ ] User music upload support
- [ ] Workout history/stats
- [ ] PWA (Progressive Web App) support
- [ ] Dark/Light theme toggle
- [ ] Export workout data
- [ ] Social sharing features

---

**Built with 💪 for the fitness community**

[Report Bug](https://github.com/deottoni/wod-app/issues) · [Request Feature](https://github.com/deottoni/wod-app/issues) · [View Demo](https://deottoni.github.io/wod-app)
