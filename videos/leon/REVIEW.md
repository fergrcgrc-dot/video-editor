# León · 10 s vertical — review

**Script (scripts/leon.txt):** "León. Dos mil años de historia. Una catedral hecha de luz. Tapas gratis con cada caña. Ven a vivirla."
Voice: ElevenLabs `eleven_v4`, voice "Fer" (cloned), Spanish. Word timings from ElevenLabs character alignment (voice/leon_words.json), offset +0.25 s.

## Creative calls
- 4 scenes on real Wikimedia Commons photos: Roman wall (0–3 s) · cathedral stained glass (3–5 s) · Barrio Húmedo (5–7 s) · Casa Botines at night (7–10 s).
- Hook at frame 0: "LEÓN" already on screen. Closing title lands at ~7.95 s and holds 2 s.
- Transitions, each with a cause: vertical whip (wall → cathedral), light flood on "luz" (cathedral → tapas), blur swap (tapas → Botines).
- Captions: one group of 1–3 words at a time, active word in amber #FFB547, inside the 9:16 safe zone (bottom ≤ y 1248).
- No music (film under 15 s).

## Measured
- `check`: 0 errors. Kept on purpose: `contrast_aa_failure` at exactly 5.0 s (white flash frame on "luz", caption fading in, 1 frame); `timeline_track_too_dense` (4–8 clips per scene file).
- Render: 1080×1920, 30 fps, 10.0 s, h264 + AAC. Voice mean −22.8 dB, peak −1.1 dB. Speech pauses line up with caption group changes (±0.1 s). Sound was measured, not heard.

## Weakest shot / next
- Photo credits over the bright Botines facade are hard to read (small, decorative). With more time: a darker backing for the credit line, and a food close-up for "tapas".

## Photo credits
Rafa Esteve (CC BY-SA 4.0) · Zarateman (CC0) · Javier Villasclaras (CC BY 3.0) · Fernando (CC BY-SA 4.0) — Wikimedia Commons.
