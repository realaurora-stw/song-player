# 🎵 MP3 Player with word-by-word live transcript
> ❤️ Spotify Lyrics App · **Mix any MP3 with ElevenLabs JSON transcripts to create a word-by-word synced lyrics file — just like Spotify Lyrics, but offline.** Play it in `player.html` with live highlighting, volume control, and optional audio effects like nightcore, slow + reverb, and more. You can even decode and edit your custom `.songlyrics` files anytime.<br>
> ⌛ This project took over **30 hours** to code from scratch! If you like it, please consider starring the repo or forking it to modify it however you like! :)<br>
> * 🌐 Main Site: [http://auroraverse.shop](http://auroraverse.shop/)
> * ▶️ Player: [http://auroraverse.shop/player](http://auroraverse.shop/player)
> * ➰ MP3 Mixer: [http://auroraverse.shop/mixer](http://auroraverse.shop/mixer)
> * 🛠️ Decode Songlyrics: [http://auroraverse.shop/decode](http://auroraverse.shop/decode)
> * ⚠️ Open Source Beta - Report bugs or feedback to [GitHub Issues!](https://github.com/realaurora-stw/song-player/issues)

## 🧪 How to Use

1. 🎧 Download your song as an MP3
2. 🗣️ Upload the MP3 to [https://elevenlabs.io/app/speech-to-text](https://elevenlabs.io/app/speech-to-text)
3. 📤 Export the transcript as **JSON** — **do not** check "include speakers"
4. 🧪 Open `mixer.html` and upload **both** the MP3 and the JSON file
   → You’ll get a `.songlyrics` download
5. 🎬 Open `player.html`, load the `.songlyrics`
   → Done. Word-by-word playback.
## 📁 Files
- `player.html` = MP3 Player
- `mixer.html` = Mix MP3 + JSON for .songlyrics
- `decode.html` = Decode .songlyrics and get MP3 and JSON downloads
## ⚡ Features
- Word-by-word live lyrics
- Speed up or slow down songs
- Persistent Volume Slider
- Play/Pause button
- Infinite loops of songs
- Download finished "Remixes" of songs (e.g. nightcore or slowed down songs)
- Light/Dark mode (Dark mode by default)
- Keyboard shortcuts (left arrow = go back 5 seconds, right arrow = go foward 5 seconds, space/k = pause, up/down = adjust volume, m = mute/unmute)
