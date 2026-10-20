# Sim Company Tower — Remotion project

```
npm install
npx remotion studio
npx remotion render src/index.ts Main out/video.mp4
```

- Composition ID: `Main` (1920×1080, 30fps). Duration and all timing come from the SRT (`src/script.ts`, same text as `public/script.srt`).
- Put the voiceover at `public/voiceover.mp3` to hear it in Studio (flag: `src/audio/PreviewAudio.tsx`). It is not mixed into renders by default.
- SFX live in `public/sfx/` (regenerate with `npm run sfx`).
- Colors, fonts, easings and springs: `src/theme.ts`.
