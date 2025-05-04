# 🎵 MP3 Player with word-by-word live transcript
> ❤️ Spotify Lyrics App · **Mix any MP3 with ElevenLabs JSON transcripts to create a word-by-word synced lyrics file — just like Spotify Lyrics, but offline.** Play it in `player.html` with live highlighting, volume control, and optional audio effects like nightcore, slow + reverb, and more. You can even decode and edit your custom `.songlyrics` files anytime.<br>
> * Player: http://auroraverse.shop/player
> * Mixer: http://auroraverse.shop/mixer
> * 🛠️ Decode Songlyrics: http://auroraverse.shop/decode
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
