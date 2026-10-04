# Voice Compressor

A lightweight, privacy-first browser-based audio compressor powered by **FFmpeg.wasm**.

Compress and convert common audio formats such as **M4A, MP3, WAV, AAC, OGG, OPUS, FLAC, WebM, 3GP and AMR** to MP3 directly in your browser.

## Features

- Privacy-first: selected audio is not uploaded to a compression server
- Runs locally in the browser
- M4A → MP3 conversion
- 24 / 32 / 48 / 64 / 96 / 128 kbps output
- Optional Mono conversion
- Speech-optimized preset
- Before/after size comparison
- Compression percentage
- Built-in output preview
- Drag-and-drop file selection
- Single-file HTML app

### Themes

Voice Compressor v1.1.0 includes the four themes from the latest approved PDF Tolkit design:

- **Persian Turquoise** — default
- **Lapis & Gold**
- **Isfahan Tile**
- **Persian Carpet**

Theme preference is saved locally in the browser.

### Languages

- **English** — LTR
- **فارسی** — RTL
- **العربية** — RTL

The interface, controls and compression status messages are localized. Language preference is also saved locally.

## Recommended setting for speech

For lectures, voice notes, interviews and spoken recordings:

**48 kbps + Mono**

This is usually a good balance between intelligibility and file size.

## Quick start

1. Open the [Releases](../../releases) page.
2. Download `voice-compressor.html`.
3. Open it with **Google Chrome** or **Microsoft Edge**.
4. Select an audio file.
5. Choose the bitrate and click **Compress**.
6. Preview and download the MP3.

> The first run requires internet access because FFmpeg.wasm is loaded from a CDN. The selected audio file itself is processed locally in the browser.

## Technology

- HTML5
- CSS3
- Vanilla JavaScript
- FFmpeg.wasm
- FFmpeg single-thread core
- Browser localStorage for UI preferences

## Browser support

Chrome and Edge are recommended, particularly for larger recordings.

## Release

Current stable release: **v1.1.0**

## License

MIT License.

---

Created and maintained by [DataMahmood](https://github.com/DataMahmood).
