# Haze — a personal music player

A single HTML file. No install, no account, nothing leaves your browser. Open it, drop in your music, and go.

## Getting started

- **Add music**: drag & drop `.mp3` / `.mp4` files onto the drop zone, or click it to browse.
- **Connect a folder**: click **📁 folder** to pick a whole folder at once (subfolders included). Click **rescan** anytime to pull in new files you've added to that folder. *Chrome/Edge only* — and it only stays connected for the current tab; reload the page and you'll need to reconnect.
- Click any track in the playlist to play it. Click the **✕** on a track to remove it. **clear** wipes the whole playlist.

## Playback controls

| Button | What it does |
|---|---|
| ⏯ (center, gradient circle) | Play / pause |
| ⏮ | Previous track (or restart current track if you're more than 3 seconds in) |
| ⏭ | Next track |
| 🔀 Shuffle | Toggles shuffled play order |
| 🔁 Repeat | Cycles through **off → repeat all → repeat one**. When it's on "repeat one," a small **"1"** badge lights up on the button so it's obvious which mode you're in |

**Keyboard shortcuts** (work anywhere except while typing in a text field):
- `Space` — play/pause
- `←` / `→` — previous/next track

**Seek bar & volume**: drag the top slider to jump around in a track; the volume slider is below the play controls.

## Lyrics

Click **Lyrics** to open the panel.
- Drop a `.lrc` file with the *same filename* as a song (e.g. `song.lrc` next to `song.mp3`) and the current line highlights and auto-scrolls as it plays.
- No `.lrc`? The player checks the mp3's own tags for embedded lyrics and shows those as plain text if found.
- A 📝 next to a track's duration in the playlist means it has lyrics attached.

## The Studio panel

Click **Studio** to open it. Everything here is real audio processing, not decoration.

- **Equalizer** — 5-band graphic EQ (60Hz–12kHz), drag each vertical slider.
- **Echo** — Mix, Time, and Feedback controls.
- **Reverb** — Mix level and room Size (short/medium/long).
- **Preamp** — overall gain trim, useful if boosting the EQ makes things too loud.
- **Crossfade** — toggle on, set a length (1–10s), and consecutive audio tracks blend into each other instead of cutting. Doesn't apply to video files.
- **Color Theme** — 5 palettes (Dream Pop, Midnight Neon, Sakura, Solar Flare, Mono). Changes the whole look, including the visualizer colors.
- **Visual Style** — 4 different looks for the main visualizer: Haze (glow + particles), Bars, Wave (oscilloscope), Radial.
- **Background** — Stars or Orbs drifting behind the whole page, reacting to the bass. Or turn it Off.
- **Stereo Width** — narrow toward mono or exaggerate the stereo image.
- **Sleep Timer** — pick 15/30/45/60 minutes; volume fades out gently in the last 20 seconds, then playback pauses.
- **Speed** — playback rate 0.5x–1.5x (this changes pitch too, like a turntable).
- **Presets** — quick-apply combos for the EQ/echo/reverb: Flat, Bass Boost, Vocal, and Haze (the dream-pop preset). **Reset all** puts everything back to defaults.

## A couple of hidden extras 🤫

Since this is your own copy, no harm in writing these down so you don't forget them:

- Type the word **"haze"** anywhere (not while typing in a field) for a little surprise.
- The Konami code (**↑ ↑ ↓ ↓ ← → ← → B A**) does something fun to the visualizer.
- Click the **"Haze"** title at the top **7 times quickly** to unlock two secret presets.

## Good to know

- Nothing is uploaded anywhere — your files stay as local blob references in the browser tab.
- Reloading the page clears your playlist and any connected folder — this is intentional (no background storage), but it does mean you'll re-add your music each session.
- The reverb is algorithmically generated (not a sampled room), so it leans more "plate/spring" than "real hall" in character.
