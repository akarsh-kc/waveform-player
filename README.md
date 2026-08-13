# 🌊 Waveform — Local Player

**Offline-first local music player with equalizer, playlists, and lyrics.
Your files never leave your device.**

Waveform is a single-page, installable web app (PWA) for playing your own
audio files — no accounts, no uploads, no streaming. Import your tracks once
and they're stored locally in your browser, ready to play offline any time.

---

## ✨ Features

- **100% local & private** — audio files are read directly from your device
  and stored in your browser's IndexedDB. Nothing is ever uploaded anywhere.
- **Installable PWA** — add it to your desktop taskbar or phone home screen
  and it runs like a native app, fully offline after the first load.
- **Rich tag support** — automatically reads ID3 (MP3) and FLAC metadata,
  including embedded cover art.
- **Built-in equalizer** — 10+ presets (Flat, Harman Target, V-Shaped, Bass
  Boost, Bass Head, Treble Boost, Vocal/Podcast, Rock, Pop, Hip-Hop & R&B,
  Dance/EDM, Jazz, Classical, Acoustic, Movie/Cinema) plus fully custom bands,
  with automatic headroom management so boosted bands never clip.
  A limiter keeps output clean at any EQ setting.
- **Grid & list library views** — switch between a visual grid with cover
  art and quality badges, or a compact list, and sort by name, file size, or
  estimated quality.
- **Quality badges** — each track shows its format and estimated bitrate at
  a glance (e.g. `HD FLAC`, `320k`), so you always know what you're listening to.
- **Playlists & favorites** — organize your library your way.
- **Recently played** — quick access to what you've been listening to.
- **Shuffle & repeat** — off / repeat-all / repeat-one.
- **Synced lyrics (LRC)** — load `.lrc` files for line-by-line synced lyrics
  alongside each track.
- **Light on dependencies** — no build step, no frameworks, no backend.
  Just static files.

## 🚀 Getting started

1. Open the hosted app (or clone this repo and serve it locally / via
   GitHub Pages).
2. Click **Import** and select audio files or a whole folder from your device.
3. That's it — your library is saved locally and will still be there next
   time you open the app.
4. Optional: use your browser's "Install App" / "Add to Home Screen" /
   "Add to taskbar" option to run Waveform like a native app, offline.

## 🗂️ Project structure
