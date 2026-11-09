# AdStudio

A video editor for ads and short-form video that runs entirely in the browser. No install and no upload: your files stay on your device.

## Features

- **Multi-track timeline:** Main, Overlay (picture-in-picture), two Text tracks and two Audio tracks. Drag, trim, split, duplicate, snapping, and a magnetic main track.
- **Text:** 8 styles (Title, Caption, Meme, Neon, Label, Script, Comic and more), in/out animations, and karaoke-style word highlighting.
- **Captions from script:** paste a script and it is split and timed across a range.
- **Filters and adjustments:** 12 presets plus brightness, contrast, saturation, hue, blur and vignette.
- **Transitions:** fade, slide, zoom, spin and blur.
- **Speed and sound:** 0.25× to 4× speed, volume up to 200%, fades, and extract audio.
- **Beat maker:** royalty-free music loops generated in the browser.
- **Aspect ratios:** 9:16, 16:9, 1:1, 4:5 and 3:4, with a blurred or solid background.
- **Export:** MP4 (H.264) at 720p or 1080p.
- **Auto-save:** the project is saved in the browser (localStorage and IndexedDB).
- **AI tab:** AI editor, hook and hashtag writer, and video review. These only work when the page is opened as a Claude artifact.

## Run it

It is a single file, `index.html`. Use either option:

- Open `index.html` in Chrome or Edge.
- Turn on GitHub Pages: **Settings → Pages → Branch: main / root**.

## Keyboard shortcuts

| Key | Action |
|---|---|
| Space | Play / pause |
| S | Split at playhead |
| Delete | Delete selected |
| Ctrl+D | Duplicate |
| Ctrl+Z / Ctrl+Shift+Z | Undo / redo |
| ← → | Step one frame (Shift: 1 second) |
| Ctrl + mouse wheel | Zoom timeline |

## Notes

- Export records in real time, so a 1-minute video takes about 1 minute. Keep the tab open and in front while it runs.
- Chrome or Edge gives the best results. Filters may not show in Safari.
