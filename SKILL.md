---
name: product-demo-launch-video
description: Use when the user wants a launch video, product demo video, announcement clip, "launch trailer", or a short (15–45s) video showing what their app/tool does — for X/Twitter, Product Hunt, a landing page hero, or a README. Also use to plan, script, storyboard, critique, or render such a video, or to study why a reference launch video is so engaging.
---

# Product demo launch video

A short, wordless-but-readable launch video that makes people *feel* the product before they understand it. The house reference is kyzo's "One" launch (31.5s, 573k views, 4K/60, zero hard cuts). `reference-one.md` (same folder) has its second-by-second breakdown. Read it before storyboarding.

The whole skill comes down to one sentence: **one continuous camera, one beat grid, one sentence per feature, and the real UI doing the real thing at the speed of a keystroke.**

## Why the reference works

These are the mechanisms, ranked by how much they carry. Each one is a rule.

### 1. It never cuts. The camera travels.
Scene detection finds **zero hard cuts** in 31 seconds, even at a 5% threshold. Every change is a camera move (zoom, pan, push-in, pull-out) or a morph: one element becomes the next. The logo grid collapses into blue blocks, which scatter into dots, which become the corner brackets around the headline. The camera then pans right to the screen edge where the product actually lives. It zooms into one row, out to the phone, back to the list, and into the inbox. The mascot grows until it becomes the end-card logo.
- Why it matters: a cut is a moment where the viewer can leave. A continuous camera feels like one thought, and the eye is always tracking *something*, so it never resets.
- Rule: every transition must be a move or a match/morph. If you can't connect A to B, re-order the scenes until you can. Cut only to change worlds (live-action to UI), and even then dissolve through a shared shape.

### 2. Sound is half the video, and it is designed, not added.
The audio is a score built for the picture, not a stock track laid under it. Measured:
- **Beat grid.** It runs at 120 BPM (a beat every 0.5s), and the visuals are locked to it. Four logos swap on four consecutive beats (0.46, 0.95, 1.46, 1.95s). Keycaps hit on beats, and the answer gets confirmed one beat after the press.
- **It opens on near-silence and isolated hits.** The crest factor is 27 in the first 2s: single sharp transients over nothing. Every logo arrives as its own *event*. Loudness then climbs steadily from about -31 to -12 dB over ~7s, so the build is felt rather than announced.
- **Every UI action has its own tiny sound.** Clusters of onsets 70ms apart are the terminal typing, text streaming and keys being pressed. These are soft, high, crisp ticks (energy above 4kHz rises to 25% during the keystroke section). The UI sounds like a beautiful mechanical keyboard, so interactions are *heard* as tactile and satisfying.
- **The sound follows the emotional arc.** It is bright and clicky during the mess and the speed section (spectral centroid about 2–2.5kHz). It turns warm and low during "See every agent" and "Something's still waiting" (centroid around 900Hz, sub-200Hz energy roughly doubles). At "Nothing needs you" the **stereo field opens wide** (side/mid ratio jumps from about 0.3 to 0.6): the sound literally exhales when the tension resolves. The end is the warmest, lowest moment (centroid around 700Hz), then a fade to silence under the held end card.
- **It is tonal and consonant.** The dominant pitches (~110, 147 and 220 Hz, i.e. A2, D3 and A3) suggest a calm A/D tonal centre with no clashing tones. It's pleasant, never aggressive "hype" music.
- Why it matters: viewers can't name any of this, but they feel it. Clicks make actions tactile. The arc in the timbre tells the emotional story underneath the visuals. The widening at the end creates relief.
- Rules:
  - Pick or commission the track first, then cut picture to it, and write the storyboard in beats.
  - Give every visible action (key, check, panel open, camera whoosh, dot turning green) its own soft micro-sound, each mixed quietly with care, never stock "swoosh" presets at full volume.
  - Map the sound to the story: bright and percussive for the problem and speed, warm and low for tension, wide and open for relief.
  - Begin with space (silence plus hits). End with a fade under a held card.
  - Use consonant, calm tonality, not EDM-trailer energy.
  - Check it on headphones *and* on a phone speaker.

### 3. Show the input, not just the output.
Big physical keycaps (⌥, ⌥⌥, 1, K, 2, space, ↵) pop up in the lower left at the instant they're "pressed", and the UI reacts within one beat. Voice input shows as words streaming into a pill with a red waveform.
- Why it matters: a viewer can't feel speed from a result alone. They feel it from **input → instant response**. The keycap turns the viewer into the user.
- Rule: render every user action as a visible input (keycap, cursor click, voice waveform). Never let UI change without a visible cause. Keep response latency on screen to ≤1 beat.

### 4. One verb-led sentence per feature, set against the product.
Headlines: "Every agent. One inbox." / "Answer in a keystroke." / "Press ⌥⌥ to talk." / "See every agent." / "Take it with you anywhere." Each is 2–5 words, starts with an imperative verb, and sits large on the left, with the live UI on the right. A small secondary line appears only when it's needed ("One routes the message to the right agent.", "On your Mac and your VPS.").
- Words animate in one or two at a time, rising from slightly below and slightly smaller ("Answer" then "in a" then "keystroke."), timed to the beat. Reading pace equals music pace.
- Rule: features are verbs the viewer gets to do. No feature names, no adjectives ("powerful", "seamless"). Text-left/product-right is the default composition. Headline type is about 6–8% of frame height, and nothing else is that big.

### 5. A tiny emotional story: tension, release, relief.
Under the feature tour sits a plot about *waiting*:
"Agent needs you" (a want) → answering is effortless (release) → "Something's still waiting. And you're away from your Mac." (a fresh tension) → the phone buzzes, one tap: "Run it" (resolution) → every status dot turns green → "Nothing needs you. Suspiciously quiet." (relief plus a joke) → "Never keep an agent waiting." (the promise).
- Why it matters: a list of features is a spec sheet. One recurring tension (here, an agent blocked on you) that each feature removes gives the viewer a reason to watch until the end.
- Rule: find the product's **one recurring pain**. Make each feature defuse it a bit more. End on its absence, shown as an empty or calm state. The tagline restates that absence as a promise.

### 6. The opening borrows scale, then shrinks it.
The video opens on the four tools the viewer already uses, each on an epic nature/cosmic plate (geode macro, Earth from orbit, jungle canopy, rocket launch) for one beat each. Then it hard-flattens to a plain grid where those same tools are scattered across terminals on Mac and VPS. That's the mess.
- Why it matters: in 2 seconds it says "this is for you" (I use those) and "this is big", and then shows the problem as visual clutter rather than describing it.
- Rule: open with something the viewer recognizes (their tools, their workflow) on a beat-cut montage. Show the problem as **visual multiplicity** (too many windows, tabs, terminals) before the product appears. No product in the first ~3 seconds.

### 6b. Every image is chosen for meaning, not filled.
The four opening plates aren't generic "epic B-roll". Each one is a quiet visual pun on its brand:
- **Claude Code** is on an amber/orange **geode**: Claude's warm terracotta palette, and layered, crystalline thinking.
- **Codex (OpenAI)** is on **Earth from orbit**: global, ubiquitous, planet-scale.
- **OpenCode** is on a sunlit **jungle canopy**: open, organic, community-grown.
- **Grok (xAI)** is on a **rocket launch**: a nod to Musk and SpaceX.

The viewer may not consciously decode them, but each feels *right*, and the few who do decode them feel rewarded. That's the "attention to detail" signal that makes people share. The end plate (sunflowers, golden hour) follows the same logic: it *is* the outcome "nothing needs you, go outside".
- Rules:
  - For every image, ask: "why *this* one for *this* thing?" If the answer is "it looks cool", find one where the answer is a meaning (brand color, founder lore, product metaphor, the outcome).
  - Match each plate's colour to its brand's palette.
  - Use stills or slow-drift footage at the highest resolution you can source. Nothing compressed or stocky.

### 6c. Craft density: the detail is the message.
Count the deliberate touches in 31 seconds:
- the bracket motif that survives three scenes
- ⌥⌥ shown as two keycaps
- "esc to undo" with a thin progress line
- "3 of 3"
- the 9:41 lock screen
- realistic agent names and tasks
- a status dot pulsing as it turns green
- the mascot peeking from *behind* the pill
- the brighter canvas dissolving into sky
- a joke in the empty state

None of them are needed to understand the product. Together they say "the person who made this cares about details", which is exactly the trust a user wants from a tool they'll live in.
- Rules:
  - After the beat sheet works, do a **detail pass**: for each beat, add one touch that rewards a second viewing (a micro-state, a sound, a motif callback, a realistic string).
  - Aim for one new touch per 1–2 seconds.
  - Never add a touch that slows the beat.

### 7. It bookends in the real world.
It opens on nature footage and closes on a golden-hour sunflower field with the logo, tagline and URL. The calm ending matches the emotional payoff (nothing needs you, go outside).
- Rule: the end-card plate should *mean* the outcome. For a productivity tool that's calm or freedom. For a speed tool, motion. Hold it about 3s with the music tailing off. The audio in the reference fades out at 28.5s and the card holds to 31.5s.

### 8. Restraint in the visual system.
The palette is warm off-white canvas, near-black UI panels, one accent blue (dots, brackets, active states), and green/yellow reserved for status meaning. It uses one sans family. A faint grid is visible only during the "mess" section. The UI panels are tilted in subtle 3D perspective when the camera pushes in, so they feel like objects rather than screenshots.
- Rule: one accent color, used only for "attention here". Status colors mean status and nothing else. Dark UI on a light canvas (or the inverse) so the product pops. Add subtle depth (perspective tilt, soft shadow) on push-ins.

### 9. Personality in one place.
A small cloud mascot with two eyes peeks out from the screen edge to say "Agent needs you". It shows up again on the empty inbox and in the logo. The empty state's copy is a joke ("Suspiciously quiet.").
- Rule: give the product one recurring character or one voice. Spend humor exactly once, on the relief beat.

### 10. Real product, real-looking data.
The tasks feel real ("Add a pricing page to the site", "Migration 0042 adds an index on orders… dry run took 3 seconds", "push to prod"), with real agent names (claude-7, codex-12, opencode-3) and real locations ("api · on remote vps"). The phone shows a lock screen at 9:41 with a real notification.
- Rule: no lorem ipsum, no "Task 1". Write the fake data so a target user nods. Specific beats generic every time.

## Procedure

1. **Gather**: product name, the one recurring pain, 3–5 features, the platform (Mac, web, CLI, mobile), the target viewer's existing tools, URL, and any mascot or logo. Ask for screen recordings or the ability to run the app. Ask only for what's missing.
2. **Write the spine**: pain sentence → 3–5 verb headlines (2–5 words each) → the absence-of-pain line → tagline (the promise, ≤5 words). Read them in order. They should tell the story with no visuals at all.
3. **Pick the track**: 110–128 BPM, builds by about 6s, no vocals. Set the length in beats: 30s ≈ 60 beats at 120 BPM. Budget it like this:
   - Hook/montage: 4–6 beats
   - Mess: 4–6 beats
   - Thesis line: 2–3 beats
   - Each feature: 6–10 beats
   - Payoff/empty state: 4–6 beats
   - End card: about 6 beats
4. **Storyboard as a beat sheet**: a table with columns `beat | camera | on-screen text | UI state | input shown | SFX`. For each row, name the **bridge** to the next row: which element morphs, or where the camera travels. Any row without a bridge is a cut, and you need to fix it.
4b. **Meaning pass and detail pass.**
   - Justify every image's meaning in one clause, and add brand-matched plates for any tools or logos shown.
   - Add one rewarding detail per 1–2s.
   - Write a sound cue list: for each beat, what is heard, how bright or warm it is, and how wide.
5. **Show the beat sheet to the user** before producing anything, using the `red-pen` skill per the user's global CLAUDE.md.
6. **Produce**, picking the lightest path that achieves continuous camera moves:
   - **Remotion** (React to MP4) or a scripted HTML/GSAP scene captured at 60fps. This is best when you rebuild the UI as components, because you get perfect timing, morphs and perspective. Default to it.
   - Screen-recording tools with auto-zoom (Screen Studio-style) plus an editor, when the real app must be shown live.
   - Render at 4K/60 if possible, or at least 1080p60. Export H.264 with the AAC audio track.
7. **Verify**: extract a contact sheet (below), watch it muted (does the story still read?), then watch it with sound (are the hits on the beat?). Run the checklist.

## Checklist (all must pass)
- [ ] Zero hard cuts, except at most one world-change, which is dissolved through a shared shape
- [ ] Every state change lands on a beat or half-beat; SFX fill the subdivisions
- [ ] Every UI change has a visible input (keycap, click, voice)
- [ ] Every headline is ≤5 words and verb-led, with no adjectives or feature names
- [ ] The product doesn't appear before ~3s; recognizable context comes first
- [ ] One recurring tension, resolved, ending on a calm or empty state
- [ ] One accent color; status colors only mean status
- [ ] All fake data is specific and plausible
- [ ] Every image has a stated meaning (brand color, lore, metaphor, outcome), with no generic B-roll
- [ ] Every visible action has its own soft micro-sound
- [ ] The audio timbre follows the arc: bright for the problem and speed, warm for tension, wide for relief, fade at the end
- [ ] The detail pass is done: about one rewarding touch per 1–2s
- [ ] The end card has logo + ≤5-word promise + URL, held about 3s, with audio tailing off
- [ ] The muted viewing still tells the story; total length 20–40s

## Studying a new reference
When the user brings another video they love, measure it before theorizing:
```bash
V=video.mp4; S=<scratchpad>/ref
ffprobe -v error -show_entries format=duration:stream=width,height,r_frame_rate -of compact $V
ffmpeg -v error -i $V -vf "select='gt(scene,0.1)',showinfo" -f null - 2>&1 | grep -o 'pts_time:[0-9.]*'   # cut times
ffmpeg -v error -i $V -vf "fps=4,scale=480:-1,tile=4x4:padding=4" $S/sheet_%02d.jpg                     # 4s per sheet
ffmpeg -i $V -af silencedetect=n=-35dB:d=0.3 -f null - 2>&1 | grep silence_                               # audio in/out
```
For beats, compute spectral-flux onsets with numpy (the gaps between onsets give you the BPM). Then read the sheets and fill a breakdown in the same format as `reference-one.md`.
