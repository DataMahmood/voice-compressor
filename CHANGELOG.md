# Changelog

All notable changes to this project will be documented here.

## [1.2.0] - 2026-10-04

### Added
- Final approved Persian Turquoise image background.
- Final approved Lapis & Gold image background.
- Final replacement Isfahan Tile background image.
- Final Persian Carpet background image.
- Theme artwork stored under `assets/themes/` in the repository.

### Changed
- Theme backgrounds now use real image artwork instead of color-only backgrounds.
- Isfahan Tile uses full `cover` sizing, matching the approved replacement treatment.
- Persian Carpet keeps the full carpet image visible with fitted background sizing.
- Persian Turquoise uses dark, translucent readable surfaces over the image background.
- Carpet panels use a calmer neutral treatment to reduce red dominance while retaining the artwork.

## [1.1.0] - 2026-10-04

### Added
- Persian Turquoise theme.
- Lapis & Gold theme.
- Isfahan Tile theme.
- Persian Carpet theme.
- English interface.
- Persian interface with automatic RTL.
- Arabic interface with automatic RTL.
- Automatic LTR layout for English.
- Localized controls and compression status messages.
- Saved language and theme preferences using localStorage.

### Changed
- Persian Turquoise is now the default theme.
- UI surfaces, controls, drop zone and progress elements now adapt to the selected theme.

## [1.0.0] - 2026-09-27

### Added
- Standalone browser-based audio compressor.
- M4A and multiple common audio input formats.
- MP3 output with selectable bitrate.
- Mono conversion option.
- Speech-optimized 48 kbps preset.
- File-size comparison and compression percentage.
- Audio preview before download.
- Drag-and-drop file selection.
- Local browser processing for selected audio.
- FFmpeg single-thread core for direct HTML compatibility.
