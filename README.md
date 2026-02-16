# Bases Audio Player Plugin

An Obsidian plugin that automatically adds audio players to Bases views for your Music properties.

## ⚡ Quick Start

### What you need:
- Node.js installed on your computer
- An Obsidian vault
- Audio files (.mp3, .wav, .ogg, .m4a) in your vault

### Installation in 4 steps:

1. **Copy all files** to `.obsidian/plugins/bases-audio-player/` in your vault

2. **Open terminal** in that folder and run:
   ```bash
   npm install
   npm run build
   ```

3. **Activate the plugin** in Obsidian:
   - Settings → Community Plugins → Bases Audio Player (turn on)

4. **Done!** Open a Bases view with a Music property and see the audio players appear

## 📝 Usage

Make sure your frontmatter looks like this:

```yaml
---
Music: [[my-music.mp3]]
---
```

Open a Bases view (table or card) and the audio link automatically becomes a player!

## ❓ Problems?

See `INSTALLATION.md` for detailed instructions and troubleshooting.

## 🎵 Features

- ✅ Works in table view
- ✅ Works in card view  
- ✅ Automatic detection of audio files
- ✅ Supports .mp3, .wav, .ogg, .m4a
- ✅ Shows filename below the player (table view)
- ✅ Centered overlay on cover art (card view)
- ✅ Beautiful outlined SVG play/pause icons
- ✅ Automatic pause of other players when starting new one

## 📦 Files

- `main.ts` - Plugin code
- `manifest.json` - Plugin metadata
- `package.json` - Dependencies
- `tsconfig.json` - TypeScript configuration
- `esbuild.config.mjs` - Build configuration
- `INSTALLATION.md` - Complete installation instructions

---

Made with ❤️ for Obsidian Bases users
