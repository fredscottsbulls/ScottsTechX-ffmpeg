# 🎬 ScottsTechX ffmpeg

<p align="center">
  <img src="https://img.shields.io/badge/ffmpeg-AV-Converter-00ff88?style=for-the-badge&logo=ffmpeg&logoColor=white" alt="ffmpeg"/>
  <img src="https://img.shields.io/badge/Open-Source-00ff88?style=for-the-badge&logo=github&logoColor=black" alt="Open Source"/>
</p>

> **Audio/video converter — convert formats, record, stream, and process multimedia.**

---

## ⚡ What It Does

ffmpeg converts between formats, records audio/video, streams media, and processes multimedia files from the command line.

## 🚀 Quick Usage

```bash
# Convert video to MP4
ffmpeg -i input.avi output.mp4

# Extract audio
ffmpeg -i video.mp4 -vn audio.mp3

# Record screen
ffmpeg -f x11grab -i :0.0 output.mp4

# Stream live
ffmpeg -i input.mp4 -f mpegts udp://localhost:2389

# Compress video
ffmpeg -i input.mp4 -crf 23 output.mp4
```

---

MIT © 2026
