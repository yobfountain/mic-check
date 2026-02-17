# Mic Check

A tool to help you get comfortable freestyling. Press the play button. Wait for the intro, then freestyle lyrics that end with the current rhyme prompt.

## Potential Roadmap

### Gameplay & Practice

- **Multiple Beats / Song Library** — Currently there's only one backing track hardcoded at 90 BPM. Supporting multiple songs with different tempos and vibes would add variety and let users practice at different speeds.
- **Difficulty Levels** — The rhyme dictionary has ~111 words across 4 families. Easier modes could show longer preview windows or simpler words, while harder modes could use less common words, shorter bars, or faster BPM.
- **Freestyle Recording & Playback** — Use the browser's MediaRecorder API to capture the user's mic input so they can listen back to their freestyle over the beat.
- **Expanded Rhyme Dictionary** — Only 4 rhyme families exist (-ee, -ove, -oo/-ew, -and). Adding more families and less common words would keep prompts fresh.

### Feedback & Progression

- **Session Stats / Scoring** — Track metrics like bars completed, streaks, sessions over time. Even simple stats would give users a sense of progression.
- **Beat Countdown / Visual Metronome** — The progress bar exists but a more prominent visual beat indicator (flash on each beat) would help users stay on rhythm.

### UX Improvements

- **Keyboard / Touch Controls** — Spacebar toggles play, but adding more hotkeys (skip, restart, volume) and better mobile touch targets would improve usability.
- **Dark Mode** — Useful for practice environments with low lighting (stages, studios).
- **Responsive / Mobile-First Redesign** — The CSS caps at 500px max-width. A more flexible responsive layout would work better across devices.
- **Offline / PWA Support** — Since the app is simple static files with one audio track, wrapping it as a Progressive Web App would let users practice without an internet connection.
