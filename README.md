# ❤️ I Love You Animation

A beautiful, interactive "I LOVE YOU" text animation with dynamic background effects and sound. Built with mo.js animation library and pure HTML/CSS/JavaScript.

![Love Animation Demo](https://img.shields.io/badge/status-active-success.svg)
![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=flat&logo=javascript&logoColor=%23F7DF1E)

## ✨ Features

- **Animated Typography** - Letters move, transform and create a heart shape
- **Dynamic Background** - Morphing color blobs with animated grid overlay
- **Sound Effects** - Subtle audio feedback synchronized with animations
- **Particle Effects** - Burst animations and circular effects
- **Responsive Design** - Adapts to different screen sizes
- **Looping Animation** - Continuously plays every 4.3 seconds
- **Single File** - Everything in one HTML file for easy deployment

## 🎬 Demo

The animation features:
- Letters of "I LOVE YOU" animating independently
- White lines moving to frame the text
- A red heart that grows and pulses in the center
- Particle burst effects at key moments
- Smooth transitions and easing effects
- Dark mode with colorful gradient blobs

## 🚀 Quick Start

1. **Clone the repository**
```bash
git clone https://github.com/redoanuzzaman/love-animation.git
cd love-animation
```

2. **Open the file**
```bash
# Simply open the HTML file in your browser
open index.html
# or
double-click the index.html file
```

That's it! No build process, no dependencies to install.

## 📁 File Structure

```
love-animation/
├── index.html          # Complete animation (HTML + CSS + JS)
└── README.md          # Documentation
```

## 🎨 Customization

### Change Colors

Edit the color variables in the CSS section:

```css
/* Letter color */
.lttr {
  fill: #763c8c; /* Purple letters */
}

/* Heart color */
colHeart: "#fa4843" /* Red heart */

/* Background colors */
background: #0f0c29; /* Dark base */
```

### Adjust Animation Speed

Modify the timing variables in JavaScript:

```javascript
const move = 1000;  // Movement duration (ms)
const boom = 200;   // Burst duration (ms)

// Loop interval
setInterval(() => {
  loveTl.replay();
}, 4300); // Change this value
```

### Disable Sound

Remove or comment out the audio elements:

```html
<!-- Comment out these lines -->
<!--
<audio class="blup" style="display: none">
  <source src="..." type="audio/ogg">
</audio>
-->
```

## 🛠️ Technologies Used

- **[mo.js](https://mojs.github.io/)** - Motion graphics library for web
- **HTML5** - Structure and audio
- **CSS3** - Styling and animations
- **Vanilla JavaScript** - Animation logic and interactions

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ⚠️ IE11 (limited support)

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 💡 Ideas for Enhancement

- [ ] Add different animation patterns
- [ ] Color theme selector
- [ ] Custom text input
- [ ] Export as GIF/video
- [ ] Mobile touch interactions
- [ ] Multiple language support
- [ ] Preset animation styles

## 👨‍💻 Author

**Redoanuzzaman**
- GitHub: [@redoanuzzaman](https://github.com/redoanuzzaman)
- Email: redoanuzzaman707@gmail.com
- Website: [redoan.dev](https://redoan.dev)

## 🙏 Acknowledgments

- Animation inspiration from creative coding community
- mo.js library by [Oleg Solomka](https://github.com/legomushroom)
- Sound effects from [Freesound](https://freesound.org/)

## 💖 Show your support

Give a ⭐️ if you like this project!

---

Made with ❤️ and JavaScript
