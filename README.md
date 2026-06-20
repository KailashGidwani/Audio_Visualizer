# 🎵 Audio Visualizer Studio

A beautiful, browser-based audio visualizer that transforms your music into stunning visual experiences. Upload any audio file, choose from multiple visualization styles, customize colors, and **record your visualizer as a video**.

![Audio Visualizer Studio](https://img.shields.io/badge/Type-Audio%20Visualizer-ff6b6b?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Browser-4ecdc4?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Working-success?style=for-the-badge)

## ✨ Features

- **4 Visualization Styles**
  - 📊 Frequency Bars
  - 🔵 Circular Bars
  - 〰️ Waveform
  - ✨ Particles

- **Customization Options**
  - 🎨 6 Color Themes
  - 🎚️ Sensitivity, Smoothing & Bar Count sliders
  - 🖼️ Background options (Gradient, Solid, Black)
  - 📹 Video Quality selection (480p, 720p, 1080p)

- **Recording & Export**
  - 🎥 Record the visualizer canvas as a video (WebM)
  - 🎙️ Audio is included in the recording
  - 💾 Download the recorded video

- **Supported Audio Formats**
  - MP3, WAV, M4A, OGG, AAC, FLAC

## 🚀 How to Use

1. **Open `audio_visualizer.html`** in any modern browser (Chrome, Edge, Firefox).
2. **Upload an audio file** by dragging it onto the upload area or clicking to browse.
3. **Play** the audio and watch the visualization come to life.
4. **Customize** the visualizer using the controls panel on the right:
   - Change the visualization style
   - Adjust sensitivity and smoothing
   - Pick a color theme
   - Choose a background style
5. **Record** your visualizer by clicking the Record button — it captures both visuals and audio.
6. **Download** the recorded video as a `.webm` file.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| HTML5 Canvas | Rendering visualizations |
| Web Audio API | Audio analysis (FFT, frequency data) |
| MediaRecorder API | Video recording & export |
| Vanilla JavaScript | No frameworks or dependencies |

## 📁 Project Structure

```
Audio_Visualizer/
├── audio_visualizer.html   # Single-file application (HTML + CSS + JS)
└── README.md               # You are here
```

## 📋 Requirements

- A modern browser with Web Audio API support (Chrome 49+, Edge 79+, Firefox 51+, Safari 14.1+)

## 📸 Preview

Upload any audio file and choose from 4 visualization styles with 6 color themes. Record and export your visualizer as video directly from the browser.

## 🤝 Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

Made with ❤️ by [KailashGidwani](https://github.com/KailashGidwani)
