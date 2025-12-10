# 🌍 3D Earth Hand Tracking

Interactive 3D Earth visualization controlled by hand gestures using AI-powered hand tracking.

![Demo](https://img.shields.io/badge/Demo-Live-brightgreen)
![Three.js](https://img.shields.io/badge/Three.js-r128-blue)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hands-orange)

## ✨ Features

- **3D Earth Globe** - Beautiful rotating Earth with realistic textures and cloud layer
- **Hand Tracking Control** - Use your hand to control the globe via webcam
- **Gesture Recognition**:
  - 🖐 **Move hand** - Rotate the Earth
  - 👌 **Pinch (thumb-index)** - Zoom in/out
- **Auto-rotation** - Earth rotates automatically when no hand is detected
- **Star Field Background** - Immersive space environment

## 🚀 Live Demo

Open `index.html` in a web browser or visit the GitHub Pages link.

> **Note**: Camera access is required for hand tracking functionality.

## 🛠️ Technologies

- [Three.js](https://threejs.org/) - 3D graphics library
- [MediaPipe Hands](https://google.github.io/mediapipe/solutions/hands.html) - AI hand tracking
- Vanilla JavaScript, HTML5, CSS3

## 📖 Usage

1. Clone this repository
2. Open `index.html` in a modern web browser (Chrome, Edge, Firefox recommended)
3. Allow camera access when prompted
4. Use your hand to interact with the 3D Earth!

### Local Development

For best results, run with a local server:

```bash
# Using Node.js
npx serve .

# Using Python
python -m http.server 8000
```

Then open `http://localhost:3000` (or `http://localhost:8000` for Python)

## 🎮 Controls

| Gesture | Action |
|---------|--------|
| 🖐 Move hand | Rotate Earth horizontally/vertically |
| 👌 Pinch fingers | Zoom in (close) / Zoom out (apart) |
| No hand | Auto-rotate mode |

## 📝 License

MIT License - Feel free to use and modify!

## 🙏 Credits

- Earth texture: [NASA Blue Marble](https://visibleearth.nasa.gov/collection/1484/blue-marble)
- Hand tracking: [Google MediaPipe](https://google.github.io/mediapipe/)
