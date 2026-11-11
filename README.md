# Rescorer

Line up a scene from YouTube with a song from YouTube, then mix their audio live.

**Use it:** https://valagit12.github.io/rescorer/

- Paste a scene link and a song link, hit **Load**.
- Editor timeline with a video track (scene) and an audio track (song). Drag either clip to move it; clips snap to each other's hit markers, edges and the playhead.
- Mark the hit in the scene and in the song, then **Line up the hits** (or drag until they snap).
- Ride the scene and song faders live. **Record moves** captures your rides onto each clip so they replay and travel with the clip.
- **Save** keeps every version of your edit in this browser; **Saved edits** reopens any of them. Undo/redo with Ctrl/Cmd+Z.
- **Copy link** puts the whole edit in a URL.

Single static `index.html`, no build step. Uses the YouTube IFrame Player API.
