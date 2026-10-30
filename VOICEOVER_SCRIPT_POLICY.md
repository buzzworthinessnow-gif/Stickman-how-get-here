# Voiceover Script Preservation — 16:9 Long-Form Episodes

**Mandatory:** Save the exact complete narration script before voice generation for every episode, regardless of length, including opening hook, history, transitions, optional midpoint subscribe reminder, and closing subscribe/comment invitation. The saved text is the canonical source for the narrator and for later recovery or voice changes.

## Per-episode files

- `episodes/<episode-id>/voiceover-script.md`: exact spoken words and punctuation, title, version, status, optional timing markers, and separately marked non-spoken pronunciation notes.
- `episodes/<episode-id>/voiceover-metadata.md`: voice name/provider, script version, language, delivery settings where available, word count, target and measured audio duration, VideoExpress project/asset IDs or references, and alternate takes.
- Optional `episodes/<episode-id>/voiceover-versions/`: approved script revisions. Never silently overwrite the prior version.

Save in the authorized VideoExpress project when supported **and** commit Markdown copies to this GitHub repository when GitHub write access is available. Verify each saved file before creating narration. If saving is blocked, provide a copyable/downloadable script and clearly state it was not saved to GitHub.

## Voice changes and recovery

1. Keep the original approved script unchanged when selecting a different narrator.
2. Generate a newly labeled audio take with the new voice; retain old audio takes and their asset references.
3. Measure new narration length and realign or adjust visuals to the new audio duration while checking the **5-minute maximum, with no minimum**. Plan for the shortest complete origins-to-present story, typically 3–4 minutes when warranted. Never trim, split, speed-change, rewrite, or regenerate completed narration merely to hit a target. If a completed take exceeds 5 minutes, report the conflict and ask how to proceed; any authorized script change must be a separately approved version.
4. Never overwrite existing audio or final videos without authorization. Keep narration as the only intelligible speaking voice unless the user explicitly asks for character dialogue.
5. If the video has overlapping dialogue, mute generated scene audio while preserving narration, or regenerate the affected visual clips silently.
6. Never infer an exact historical script from a mixed export when the canonical saved script exists.

## Script template

```markdown
# Voiceover — <Episode Title>
Episode ID: <id>
Version: v1
Narrator: <voice>
Planned total video length: <subject-driven estimate; typically 3–4 minutes, maximum 5:00, no minimum>
Opening hook: approximately 5–10 seconds, included in total

## Exact spoken narration
<all words exactly as submitted to TTS, including intro, midpoint CTA, ending>

## Pronunciation / pacing notes (not spoken)
<optional>

## Audio takes and revisions
<voice, version, asset ID, duration, date if known>
```

**This policy governs future productions; it does not retroactively recover scripts from existing videos.**
