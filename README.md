# Rescorer

Line up a scene from YouTube with a song from YouTube, then mix their audio live.

**Use it:** https://valagit12.github.io/rescorer/

- Paste a scene link and a song link, hit **Load**.
- Mark the hit point in the scene and in the song; the song follows the scene from there.
- Nudge the timing in 0.05s / 0.5s steps while it plays.
- Ride the scene and song volume faders live (or with the keyboard).
- **Record moves** captures your fader rides so they replay on the next pass.
- **Copy link** saves the whole setup (videos, cues, mix, recorded moves) in a URL.

Keys: `Space` play/pause · `C` play from cue · `Q`/`A` scene vol · `W`/`S` song vol · `1`/`2` mute · `←`/`→` nudge (`Shift` = 0.5s) · `R` record · `L` link

Single static `index.html`, no build step. Uses the YouTube IFrame Player API.
