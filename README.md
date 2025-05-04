# 🎵 MP3 Player with word-by-word live transcript
> ❤️ Spotify Lyrics App · **Mix any MP3 with ElevenLabs JSON transcripts to create a word-by-word synced lyrics file — just like Spotify Lyrics, but offline.** Play it in `player.html` with live highlighting, volume control, and optional audio effects like nightcore, slow + reverb, and more. You can even decode and edit your custom `.songlyrics` files anytime.<br>
> Demo:<br>
> * Player: https://realaurora-stw.github.io/song-player/player
> * Mixer: https://realaurora-stw.github.io/song-player/mixer
> * Decode: https://realaurora-stw.github.io/song-player/decode <br>
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
<img src="https://sdmntprnorthcentralus.oaiusercontent.com/files/00000000-da14-622f-9888-408f6976bb71/raw?se=2025-05-04T05%3A48%3A11Z&amp;sp=r&amp;sv=2024-08-04&amp;sr=b&amp;scid=4de52f3a-31b9-5d19-98b0-2cd1c313b4b0&amp;skoid=de76bc29-7017-43d4-8d90-7a49512bae0f&amp;sktid=a48cca56-e6da-484e-a814-9c849652bcb3&amp;skt=2025-05-03T19%3A35%3A30Z&amp;ske=2025-05-04T19%3A35%3A30Z&amp;sks=b&amp;skv=2024-08-04&amp;sig=y8CTi0AWrIsNC9KT4tkifwqsj4ypo6gY0hbqeaApYpw%3D" alt="Generated image"/>![image](https://github.com/user-attachments/assets/9434a3f3-d07d-4537-b4a0-5cf3fba1e665)
