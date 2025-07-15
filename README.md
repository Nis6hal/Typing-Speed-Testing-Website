# 🚀 Typing Speed Test

A modern, feature-rich typing speed test application built with vanilla HTML, CSS, and JavaScript. Test your typing speed, improve your accuracy, and track your progress with an intuitive and beautiful interface.

![Typing Speed Test](https://img.shields.io/badge/Status-Live-brightgreen)
![Version](https://img.shields.io/badge/Version-1.0.0-orange)

## ✨ Features

### 🎯 Core Functionality
- **Real-time WPM calculation** - Words Per Minute tracking
- **Accuracy measurement** - Character-by-character accuracy checking
- **Progress visualization** - Visual progress bar and typing indicators
- **Multiple quote sources** - Prewritten quotes or custom text input
- **Timer modes** - Unlimited or 60-second challenge mode

### 🎨 User Experience
- **Modern UI/UX** - Clean, responsive design with smooth animations
- **Dark/Light theme** - Toggle between themes with persistent settings
- **Customizable themes** - Unlock new themes as you level up
- **Animated backgrounds** - Matrix rain, particles, and gradient options
- **Sound feedback** - Audio cues for correct/incorrect typing
- **Zen mode** - Distraction-free typing experience

### 🏆 Gamification
- **XP & Leveling system** - Gain experience points and unlock features
- **Achievements & Badges** - Earn badges for milestones
- **Daily challenges** - New quote each day with streak tracking
- **Practice mode** - Focus on your weak keys based on error analysis
- **Leaderboards** - Local and global high scores
- **Confetti celebrations** - Visual rewards for achievements

### 📊 Analytics & Progress
- **History tracking** - Save and review past typing sessions
- **Progress charts** - Visual representation of WPM and accuracy trends
- **Error heatmap** - Identify commonly mistyped characters
- **Export functionality** - Download typing history as CSV
- **Shareable results** - Generate and download result images

### 🎵 Additional Features
- **Background music** - Multiple ambient tracks for focus
- **Avatar system** - Upload custom avatars or generate pixel art
- **Nickname customization** - Personalize your profile
- **Keyboard shortcuts** - Quick actions for power users
- **Accessibility** - Screen reader support and keyboard navigation

## 🚀 Quick Start

### Option 1: Direct Usage
Simply open `typingtest.html` in any modern web browser. No installation required!

### Option 2: Local Development
1. Clone or download the repository
2. Open `typingtest.html` in your browser
3. Start typing!

## 🎮 How to Use

### Basic Typing Test
1. **Select quote type**: Choose between prewritten quotes or custom text
2. **Configure options**: Enable/disable sound, time limits, or zen mode
3. **Start typing**: Begin typing in the input field
4. **View results**: See your WPM, accuracy, and progress in real-time
5. **Complete test**: Finish the quote to save your results

### Advanced Features

#### Daily Challenges
- Click "Play" on the daily challenge bar
- Complete the daily quote to maintain your streak
- Track your daily progress and achievements

#### Practice Mode
- Click the dumbbell icon to enter practice mode
- Focus on your commonly mistyped characters
- Double-click to exit practice mode

#### Theme Customization
- Click the palette icon to access theme gallery
- Unlock new themes by gaining XP and leveling up
- Customize your typing experience

#### Zen Mode
- Click the leaf icon for distraction-free typing
- Hide all UI elements except the quote and input
- Perfect for focused practice sessions

## 🎯 Keyboard Shortcuts

| Shortcut | Action |
|----------|--------|
| `Escape` | Restart current test |
| `Ctrl + P` | Pause/Resume typing |
| `Enter` (in nickname input) | Save nickname |

## 📊 Understanding Your Results

### WPM (Words Per Minute)
- Calculated using the standard 5 characters per word
- Real-time updates as you type
- Best WPM tracked per quote

### Accuracy
- Character-by-character comparison
- Percentage of correctly typed characters
- Perfect accuracy achievements available

### Progress Tracking
- Visual progress bar shows completion percentage
- Color-coded character feedback (green = correct, red = incorrect)
- Active character indicator with blinking cursor

## 🏆 Achievement System

### Available Badges
- **50+ WPM** - Reach 50 words per minute
- **100% Accuracy** - Achieve perfect accuracy
- **10+ Tests** - Complete 10 typing tests
- **Daily Challenge** - Complete daily challenges

### Leveling System
- Gain XP for each completed test
- Bonus XP for high WPM and accuracy
- Unlock themes and features as you level up

## 🎨 Customization Options

### Themes
- **Default** - Clean blue theme
- **Matrix** - Green terminal aesthetic
- **Retro** - Orange and red vintage look
- **Zen** - Calm green and blue
- **Rainbow** - Vibrant color scheme

### Backgrounds
- **None** - Clean background
- **Matrix** - Animated matrix rain
- **Particles** - Floating particle animation
- **Gradient** - Smooth color gradient

### Music Tracks
- **Zen Garden** - Calming ambient sounds
- **Focus Flow** - Concentration music
- **Retro Vibes** - Nostalgic tunes
- **None** - Silent mode

## 📱 Browser Compatibility

- ✅ Chrome/Chromium (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (responsive design)

## 🔧 Technical Details

### Technologies Used
- **HTML5** - Semantic markup and accessibility
- **CSS3** - Modern styling with CSS variables and animations
- **Vanilla JavaScript** - No frameworks, pure functionality
- **Local Storage** - Persistent data storage
- **Canvas API** - Custom animations and graphics
- **Web Audio API** - Sound feedback system

### Data Storage
- All data stored locally in browser localStorage
- No external dependencies or server requirements
- Privacy-focused with no data collection

### Performance
- Optimized for smooth 60fps animations
- Efficient character-by-character processing
- Minimal memory footprint

## 🛠️ Development

### File Structure
```
TypingTest/
├── typingtest.html    # Main application file
└── README.md         # This documentation
```

### Key Components
- **Quote Management** - Random quote selection and cycling
- **Timer System** - Accurate timing with pause/resume
- **Input Processing** - Real-time character validation
- **Statistics Engine** - WPM and accuracy calculations
- **UI Components** - Responsive design elements
- **Gamification** - XP, levels, and achievements

### Adding Features
The modular JavaScript structure makes it easy to add new features:
1. Add new quotes to the `preQuotes` array
2. Create new themes in the `THEMES` array
3. Add badges to the `BADGES` array
4. Extend the achievement system

## 🤝 Contributing

Contributions are welcome! Here are some ways to contribute:

### Feature Ideas
- Additional quote categories (literature, programming, etc.)
- More theme options
- Advanced statistics and analytics
- Multiplayer typing competitions
- Integration with external quote APIs

### Bug Reports
- Test on different browsers and devices
- Report any issues with specific steps to reproduce
- Include browser version and operating system

### Code Improvements
- Optimize performance
- Enhance accessibility
- Add new animations or effects
- Improve mobile experience

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- **Google Fonts** - Beautiful typography (Montserrat)
- **FontAwesome** - Icon library
- **Pixabay** - Background music tracks
- **CSS Grid & Flexbox** - Modern layout techniques
- **Web APIs** - Canvas, Audio, and Storage APIs

## 📞 Support

If you encounter any issues or have questions:

1. **Check browser compatibility** - Ensure you're using a modern browser
2. **Clear browser cache** - Sometimes helps with display issues
3. **Check console errors** - Open developer tools for error messages
4. **Try different browsers** - Test in Chrome, Firefox, or Safari

## 🎯 Roadmap

### Planned Features
- [ ] Multi-language support
- [ ] Advanced statistics dashboard
- [ ] Social sharing integration
- [ ] Cloud sync (optional)
- [ ] Typing lessons and tutorials
- [ ] Custom quote categories
- [ ] Advanced practice modes
- [ ] Mobile app version

### Version History
- **v1.0.0** - Initial release with core features
- Complete typing test functionality
- Theme system and customization
- Achievement and gamification features
- Responsive design and accessibility

---

**Happy Typing!** 🚀

*Improve your typing speed, accuracy, and efficiency with this comprehensive typing test application.* 
