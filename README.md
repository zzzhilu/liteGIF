# LiteGif 🎞️

[中文版 (Chinese Version)](README_TW.md)

**LiteGif** is a lightweight, modern tool for converting MP4 videos to GIF. Built with WPF (.NET 6), it offers a dark-themed UI, precise timeline scrubbing, and instant preview loop.


## ✨ Key Features

- **Accurate Trimming**: Drag `[` and `]` handles with frame-accurate precision.
- **Modern UI**: Sleek dark mode with ergonomic controls.
- **Auto-Loop Preview**: Instantly see your selected clip loop.
- **Smart Export**: Auto-saves GIFs with timestamped filenames in the source folder.

## 🚀 Usage

1. **Drag & Drop** an MP4 video into the window.
2. **Trim** the video using the Start/End handles.
3. Click **Export GIF**.

## 🛠️ Build

- Requires **.NET 6.0**.
- **ffmpeg.exe** must be placed in the output directory.
- Run `dotnet build`.
