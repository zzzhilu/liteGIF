# LiteGif 🎞️

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
- **ffmpeg.exe** must be placed in the output directory. https://www.ffmpeg.org/download.html#build-windows
- Run `dotnet build`.


# LiteGif 🎞️

**LiteGif** 是一個輕量、現代化的 MP4 轉 GIF 工具。基於 WPF (.NET 6) 開發，擁有質感深色介面、精確的時間軸拖曳與即時預覽功能。

## ✨ 特色功能

- **精準裁切**：透過「開始」與「結束」把手，進行格數精確的片段修剪。
- **現代化介面**：符合人體工學的深色主題設計，長時間使用不刺眼。
- **循環預覽**：選取範圍會自動循環播放，所見即所得。
- **智慧匯出**：自動以時間戳記命名並儲存於原始影片資料夾，簡化流程。

## 🚀 使用方法

1. **拖放** MP4 影片至視窗中。
2. 拖曳下方綠色/橘色把手以 **裁切** 想要的片段。
3. 點擊 **Export GIF** 即可匯出。

## 🛠️ 建置需求

- 需安裝 **.NET 6.0**。
- 必須將 **ffmpeg.exe** 放置於執行檔目錄中。 https://www.ffmpeg.org/download.html#build-windows
- 使用 `dotnet build` 指令進行編譯。
