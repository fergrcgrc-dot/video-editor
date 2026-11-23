# Video Editor

Video pipeline built with Claude Code: script → voice → animated scenes → render.

## Structure

```
video editor/
 scripts/   # video scripts
 voice/     # voice files (ElevenLabs)
 videos/    # finished videos
```

## Tools

| Tool | Role | Notes |
|---|---|---|
| [HyperFrames (HeyGen)](https://github.com/heygen-com/hyperframes) | Animates every scene | Free, open source (Apache 2.0). Skills installed in `.agents/skills/` (symlinked in `.claude/skills/`) |
| [ElevenLabs](https://elevenlabs.io) | Voice | Limited free tier, paid plans above ([pricing](https://elevenlabs.io/pricing)). Model `eleven_v4`, voice "Liam" |
| [FFmpeg](https://ffmpeg.org) | Renders the video | Free, open source |

## Install

```bash
npx skills add heygen-com/hyperframes
```

Reference versions: HyperFrames CLI 0.9.72, FFmpeg 6.0, ElevenLabs `eleven_v4`.
