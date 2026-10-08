---
name: ig-reel
description: Plan Instagram Reels / YouTube Shorts from a topic. Produces a consistent character/style prompt, scene-by-scene scripts with AI image/video generation prompts, on-screen text, audio picks, caption, hashtags and production tips. Use when the user runs /ig-reel or asks for reel/short ideas, scripts or AI video prompts.
argument-hint: <topic, e.g. "funny 3d pixar bala ganesh and mushika reels">
---

# /ig-reel — Reel planner

Topic: $ARGUMENTS

If the topic is empty, ask the user what the reel should be about (offer 2–3 example topics) and stop.

## What to produce

Reply in chat (markdown), in this order:

1. **Style prompt** — one reusable paragraph to append to every generation prompt so characters stay consistent: art style (e.g. 3D Pixar-style), lighting, palette, detailed character descriptions (look, outfit, signature traits), `9:16 vertical`.
2. **3–4 reel concepts**, each with:
   - A catchy title and target length (8–20s).
   - A shot table: `Time | Shot | Prompt / Action`. One row per 2–5s clip; each prompt is ready to paste into an AI video tool (Sora, Veo, Kling, Runway, Pika) and ends with `...` meaning "+ style prompt".
   - Optional short dialogue lines (note voice style).
   - **On-screen text** (hook in the first 2 seconds).
   - **Audio** suggestion (trending-style track or SFX).
3. **Caption + hashtags** — one ready-to-post caption with emojis and 10–15 relevant hashtags (mix of broad and niche).
4. **Production tips** — character consistency (reference image first), stitching clips in CapCut/Instagram editor, voice ideas, export 1080×1920 at 24–30fps, burned-in captions.
5. End with a one-line offer: more ideas, full dialogue, or a regional-language version.

## Guidelines

- Keep humour warm and family-friendly. For religious or cultural figures (deities, saints, festivals), keep it affectionate and devotional — gentle mischief and cuteness, never mockery.
- Don't use real people's likeness, or copyrighted characters by name, in generation prompts; describe the *style* instead ("Pixar-style", not a specific film's character).
- If the user names a language, write the dialogue, on-screen text and caption in that language (hashtags may stay mixed).
- Don't claim to have generated video or images — this skill outputs scripts and prompts only.
