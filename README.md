# Stickman — How Did We Get Here?

A reusable **VideoExpress historical explainer agent** for entertaining, researched, **3–5 minute** videos that trace an object, invention, idea, or institution from its origins to today.

## The v2 style

**Expressive 2D stickmen in richly detailed historical worlds.** Every human is a stickman, while vehicles, machinery, architecture, props, and environments are carefully illustrated and appropriate to the era. Stories prioritize cause and effect, verified surprises, failures, and pivotal turning points—not arbitrary date lists.

**Default format:** ~4 minutes, 16:9 landscape, integrated VideoExpress narration, Beau Whitaker voice if available. Vertical 9:16 can be requested.

Each episode uses a **20–30 second curiosity hook**, a brief subscribe reminder after a midpoint reveal, and a closing invitation to subscribe, suggest future subjects in the comments, and return for the next story.

**Reusable voiceover scripts:** Every episode preserves its exact narration and voice/take metadata before generating audio, enabling repairs and alternate voices. **Cover images:** Every episode gets 4–6 suggested 16:9 thumbnail concepts and, when authorized and available, separately generated candidates.

## Files

- [VOICEOVER_SCRIPT_POLICY.md](VOICEOVER_SCRIPT_POLICY.md) — canonical narration script, metadata, voice-swap and recovery rules.
- [THUMBNAIL_GUIDE.md](THUMBNAIL_GUIDE.md) — 4–6 thumbnail concepts, compelling headlines, detailed prompts, and image delivery checks.

- [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) — complete v2 production agent: research, story arc, visual bible, detailed prompt formula, continuity, rendering, quality gates, runtime checks, and safeguards.
- [STICKMAN_WARDROBE_GUIDE.md](STICKMAN_WARDROBE_GUIDE.md) — approved clothing style, era-specific wardrobe examples, image prompt suffix, and continuity rules.
- [EPISODE_TEMPLATE.md](EPISODE_TEMPLATE.md) — reusable fact ledger, milestone grid, narration timing, character/object/environment masters, shot record, image/motion prompt schema, and final checklist.
- [examples/history-of-the-car.md](examples/history-of-the-car.md) — pilot episode outline and three fully written scene prompt examples. This is a **planning example**, not a rendered video or fully fact-checked final script.

## How to use

1. Open [SYSTEM_PROMPT.md](SYSTEM_PROMPT.md) in a supported browser-capable agent with access to VideoExpress.
2. Supply a topic such as **“How did we get here? The car.”**
3. The agent researches the topic, chooses meaningful milestones, drafts narration, plans the scene continuity, generates illustrated assets, uses VideoExpress integrated narration, assembles the video, and checks the measured runtime.
4. When browser access is unavailable, the agent should produce a clearly labeled planning package rather than claim a video was made.

## Origin and repository independence

This repository is an independent customization inspired by [ai-playbooks/videoexpress-stickman-story-agent](https://github.com/ai-playbooks/videoexpress-stickman-story-agent). It is **not represented as an official GitHub fork**. All v2 changes are confined to this repository; upstream remains untouched.
