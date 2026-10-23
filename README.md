# Fine Downloader

**A lightweight desktop video and audio downloader.**

Fine Downloader is a desktop application built with Python and PyQt6, powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp). It provides a clean graphical interface for downloading online media with configurable quality and output locations.

## Features

- **Simple interface:** Download media through a graphical desktop application.
- **Video downloads:** Select from available video quality options.
- **Audio downloads:** Extract audio into supported formats.
- **Progress tracking:** Monitor download progress, speed, and estimated time remaining where available.
- **Custom save locations:** Choose where downloaded files are stored.
- **Persistent settings:** Keep application preferences between launches.
- **Download history:** Retain download history between sessions.
- **yt-dlp updates:** Update yt-dlp using the project's supported update mechanism.

## Installation

### Linux Mint / Ubuntu

Download the latest compatible `.deb` installer from the project's GitHub Releases page.

Install it using:

```bash
sudo apt install ./fine-downloader_VERSION_amd64.deb
```

Replace `fine-downloader_VERSION_amd64.deb` with the actual downloaded filename.

Launch the application from your application menu or run:

```bash
fine-downloader
```

### Dependencies

The application uses:

- Python
- PyQt6
- yt-dlp
- FFmpeg for supported media merging and processing

The Debian package declares its required system dependencies. Install requirements according to the project's documentation when running from source.

## Usage

1. Open Fine Downloader.
2. Paste a supported media URL.
3. Fetch the available media information.
4. Choose the desired download quality or audio option.
5. Select an output location.
6. Start the download and monitor its progress.

Available options depend on the source website and the media formats it provides.

## Updating yt-dlp

Fine Downloader includes a project-supported mechanism for updating yt-dlp. See the project documentation for instructions and supported options.

## Compatibility

- **Current packaged platform:** Linux Mint / Ubuntu-based Linux, 64-bit Intel/AMD.
- **Other platforms:** Support must be verified separately before being advertised.
- **Android:** Planned, not currently advertised as a released platform.

## Responsible Use

Use Fine Downloader only for media you own, have permission to download, or are otherwise legally entitled to save. Respect applicable copyright laws, website terms, and access restrictions.

Fine Downloader does not grant permission to download any particular content.

## Technology

- [Python](https://www.python.org/)
- [PyQt6](https://www.riverbankcomputing.com/software/pyqt/)
- [yt-dlp](https://github.com/yt-dlp/yt-dlp)
- [FFmpeg](https://ffmpeg.org/)

## Version

Current release: **1.2.0**

See [CHANGELOG.md](CHANGELOG.md) for version history and changes.

## License

The project's license has not yet been specified. A license should be added before distributing the source code for reuse.

---

**Fine Downloader**  
*Simple. Lightweight. Built for your desktop.*
