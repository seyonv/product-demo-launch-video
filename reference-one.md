# Reference breakdown: "One" launch (kyzo, x.com/ky__zo/status/2107549434280284460)

- 31.55s, 3840×2160, 60fps, 573k views / 2.6k likes in the first days
- Music only, no voiceover; the music runs to 28.5s and the end card holds silent to 31.5s
- 120 BPM (onsets every 0.50s from 0.46s); 0 hard cuts at a 5% scene threshold
- Post copy: "meet One, the new way for talking with your agents", then 3 bullets (inbox / voice / iPhone) and "most joyous product I've built so far"

| t (s) | beats | Camera / bridge | On-screen text | What it does |
|---|---|---|---|---|
| 0.0–0.5 | 1 | static macro plate (geode) | — | silence and then a hit, so the first frame is already beautiful |
| 0.5–2.5 | 4 | one plate per beat: geode, Earth, jungle, rocket; corner brackets frame each logo | Claude Code / Codex / OpenCode / Grok | "your tools", given epic scale; the brackets are the visual motif that carries through |
| 2.5–3.0 | 1 | plates flatten to a white canvas; the blue brackets stay as the bridge | — | world change, from epic to work |
| 3.0–5.0 | 4 | grid canvas fills with tool chips + terminal prompts (`you@mac:~/web$ claude`, `ssh vps`, `codex`…), with fast typing ticks | — | the mess: many agents across many machines, shown rather than said |
| 5.0–5.7 | 1.5 | blue blocks wipe over the chips and shatter into dots | — | morph: clutter becomes particles |
| 5.7–6.8 | 2 | dots converge into the four corner brackets around the headline | Every / agent. One / inbox. (word-by-word) | thesis; the brackets from beat 1 return |
| 6.8–7.6 | 1.5 | headline exits and the camera pans right to the screen edge | — | reveals where the product lives (a pill docked at the screen edge) |
| 7.6–8.6 | 2 | mascot peeks from behind the pill; a status dot turns yellow | Agent needs you | the tension starts: a want, delivered by a character |
| 8.6–9.4 | 1.5 | ⌥ keycap, then ⌥⌥; the panel springs open | — | input shown first, response within one beat |
| 9.4–11.0 | 3 | push-in with 3D tilt on the panel; text left | Answer in a keystroke. | keys 1 → check → "Answer sent · esc to undo"; K → next agent; 2 → check; K |
| 11.0–13.0 | 4 | panel for opencode-3, "Onboarding copy is in. Three screens, tests green." | (same) | space → type "push to prod" (typing ticks) → ↵ → sent, "3 of 3" |
| 13.0–15.5 | 5 | ⌥⌥ keycap; a dark pill grows; waveform turns red | Press ⌥⌥ to talk. / One routes the message to the right agent. | words stream in: "Make the orders page faster" → "✓ Sent to @codex-9 · remote vps" |
| 15.5–19.0 | 7 | the pill expands into the agent list (morph) | See every agent. / On your Mac and your VPS. | spinners flip to green one row per half-beat; one row (Database Migration) stays yellow |
| 19.0–20.5 | 3 | camera dives into the yellow row; the list falls away | Something's still waiting. / And you're away from your Mac. | the new tension |
| 20.5–22.0 | 3 | iPhone slides in: lock screen 9:41, notification "An agent needs your answer" | (same) | world extension, still in a continuous frame |
| 22.0–23.5 | 3 | phone opens to the question "Run it on production now?" | Take it with you anywhere. | tap "Run it" → ✓ "Answer sent"; the row's dot turns green with a pulse |
| 23.5–24.5 | 2 | pull back to the full list, all green; a cursor clicks the inbox icon | — | resolution |
| 24.5–26.0 | 3 | push-in on the inbox card | Inbox — Nothing needs you. Suspiciously quiet. Questions and finished work land here. | relief plus the one joke |
| 26.0–27.0 | 2 | the card dissolves away, leaving only the mascot; the canvas brightens into sky | — | morph: mascot becomes the logo, UI becomes the world |
| 27.0–31.5 | 9 | sunflower field at golden hour, slow drift | One / Never keep an agent waiting. / getone.one | promise plus URL; the tagline animates word-by-word, then holds; music fades out at 28.5 |

## Motifs that thread through it
- **The bracket/dot shape.** It frames the logos, survives the world change, becomes particles, frames the thesis, and turns into status dots. One shape carries the eye across ~8s and three "scenes".
- **Status dots.** Blue spinner means working, yellow means needs you, green means done. The whole emotional arc can be read from dot colors alone.
- **The mascot.** It appears three times: delivering the problem, on the empty state, and as the logo. It's the same object each time.
- **Left text / right product.** This is held from 9s to 24s, so the eye knows where to read and where to watch.

## Opening plates and what each one means
- **Claude Code**: amber geode. Claude's warm orange palette, plus crystalline, layered structure.
- **Codex**: Earth from orbit. OpenAI at global scale.
- **OpenCode**: jungle canopy. Open source, organic.
- **Grok**: rocket launch. xAI and SpaceX lore.
- **End card**: sunflower field at golden hour. The outcome (calm, go outside).

## Audio, measured in 2s windows
| window | what's happening | centroid | sub-200Hz share | stereo width | character |
|---|---|---|---|---|---|
| 0–2s | logo hits | 1.9kHz | 0.03 | 0.17 | near-silence plus isolated transients (crest 27) |
| 2–6s | the mess, terminals | 2.0–2.1kHz | 0.09–0.17 | 0.16–0.31 | bright typing ticks, build |
| 8–10s | keystroke answers | 2.5kHz | 0.22 | 0.28 | brightest moment, key clicks |
| 14–20s | voice, see every agent, still waiting | 0.9–1.0kHz | 0.31–0.41 | ~0.32 | warm, low, grounded |
| 24–28s | "Nothing needs you", logo | 1.0–1.3kHz | 0.27–0.52 | **0.59–0.62** | stereo opens wide: the exhale |
| 28–31.5s | end card | 0.7kHz | 0.56 | 0.41 | warmest, fades out at 28.5s |

Dominant pitches are around 110, 147 and 220 Hz (A2/D3/A3), so the tonality is calm and consonant.

## Typography & motion details
- Headlines: one heavy grotesk, tight tracking, black on warm off-white (white on dark scenes).
- Word reveal: each word or pair rises a few px from below and grows from about 85% to 100% size while fading in, one beat per chunk. Mid-reveal, the words sit visibly on different baselines, and that motion is part of the charm.
- Camera: eased (slow in, slow out), never linear. Push-ins add a slight perspective tilt to the UI panel.
- Keycaps: large, dark, rounded, with a soft shadow, bottom-left. They pop in on the beat and repeated presses show as two caps (⌥⌥).
- Confirmation states: an inline check plus "esc to undo" plus a thin progress line, so even the undo is part of the speed story.
