# Product feature with video

- Use iframe to play external videos
- Use video tag if included in source code
  - Can add various attributes like video sound, playback, loop, controls, etc.
- Use libraries like video.js to customize the video player
- mp4 is supported by modern browsers, but large size
- webM is also supported, light weight
- The strategy is to use them together. if WebM is not supported, fallback to MP4
