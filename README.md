# Lumen — Speed Reader

A research-backed RSVP (Rapid Serial Visual Presentation) speed reader for desktop and mobile.

## Features

- **One word at a time** with optimal recognition point (ORP) highlighting
- **Multi-format support**: PDF, DOCX, EPUB, TXT, RTF, HTML
- **Text-to-speech**: voice reads aloud while visual word syncs with audio
- **Offline-first**: works completely offline; saves progress to browser storage
- **Chapter detection & navigation**: auto-detects chapters, tap to jump to any sentence
- **Adjustable speed**: 100–1200 WPM with keyboard shortcuts (↑/↓)
- **Dark & light themes**: easy on the eyes, toggle anytime
- **No install, no signup**: drop the HTML file in a browser, start reading

## Quick Start

1. Download `lumen-speed-reader.html` or use the live link below
2. Double-click to open in your browser (or open via the GitHub Pages link)
3. Upload a document (PDF, Word doc, ebook, etc.)
4. Press **Play** (spacebar) to start
5. Adjust speed with the slider or ↑/↓ keys

## How It Works

**ORP Highlighting**: Each word is broken at the Optimal Recognition Point—the letter your eye naturally lands on. This keeps your eyes centered and eliminates wandering.

**Sentence-driven Audio**: When text-to-speech is on, the app speaks one sentence at a time and syncs the visual word display to the spoken word via the browser's `boundary` event. Perfect sync, no lag.

**Persistent Progress**: Your reading position, WPM, and voice choice are saved automatically. Resume right where you left off.

**Chapter Index**: For books with chapters, Lumen auto-detects them and lets you jump to any chapter or sentence via the hamburger menu.

## Keyboard Shortcuts

| Key | Action |
|-----|--------|
| **Space** | Play/Pause |
| **←** / **→** | Back/forward 5 words (hold Shift for 50) |
| **↑** / **↓** | Increase/decrease speed ±25 WPM |
| **V** | Toggle voice on/off |
| **T** | Toggle dark/light theme |
| **M** | Open menu (chapters/library) |
| **Esc** | Close menu |

## Fonts & Design

- **Lexend** for the main reading word — research shows it improves reading speed and comprehension
- **Dark & light themes** both optimized for low-glare, high-contrast reading
- **Offline-first architecture** using IndexedDB so 1000+ page documents don't bloat RAM

## Browser Support

Works in all modern browsers (Chrome, Safari, Firefox, Edge). Speech synthesis available on all platforms but sounds best on macOS (Samantha, Alex) and Windows (Zira, David).

## License

MIT — use, modify, share freely.
