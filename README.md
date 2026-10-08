# Wild Beats — Trelum
A tiny animal music studio. Tap or drag four animals onto the stage, switch music styles, change the tempo, and share your own mix by link. No accounts, backend, or paid services.

Music is synthesized locally with the Web Audio API: percussion, chord keys, bass, and melody share a single audio clock. Audio starts after an interaction. Mixes are saved on this device; shared links encode only animal selection, style and tempo. Backgrounding the page pauses audio. Animal artwork is AI-generated; musical movement is CSS animation. Trelum brand SVGs are supplied originals.

Run with a static HTTP server. GitHub Pages deployment uses the files in `github-pages/` at repository root. Keep the Mochi World site separate.

## Controls
Tap an animal to add/remove it, or drag it onto the stage. Play/Pause controls music. Surprise me chooses a band and style. Share mix opens a shareable link. Clear stage starts fresh.
