# Rescorer

Cut YouTube video and audio clips together on a timeline, line up the hits, and mix the audio live.

**Use it:** https://valagit12.github.io/rescorer/

- Add as many video and audio clips as you like; each new clip lands at the end of its track.
- Drag clips to move them, drag their edges to trim, split at the playhead (X), delete (Delete).
- Mark a hit on a clip (M) and line it up with the nearest hit on the other track (H), or drag until it snaps.
- Ride the video and audio faders live; Record moves captures your rides onto the clips.
- Save keeps every version of your edit in this browser; Saved edits reopens them. Undo with Ctrl/Cmd+Z.
- Share gives you a Watch link (just the finished edit with a play bar) and an Edit link (a copy in the editor). The edit is compressed into the link itself; nothing is uploaded.
- Works on phones, upright or sideways. Upright: picture on top, timeline below, Mix / Clip panels in thumb reach. Sideways: picture left, Mix / Clip right, full-width timeline along the bottom. Pinch to zoom, swipe to pan.

Single static `index.html`, no build step. Uses the YouTube IFrame Player API.
