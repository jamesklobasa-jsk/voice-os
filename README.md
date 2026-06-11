# Voice DNA

**Extract your exact voice. Make any AI sound like you — specifically you.**

Not generically human. Not "less robotic." *You.* Your frameworks, your IP, your quirks, your favourite sayings, your stories, your language, your rhythm. More YOU than you. 

---

## The Problem

Every AI writing tool tries to make content sound human. None of them make it sound like *you specifically*.

That's the gap Voice DNA fills.

---

## How It Works

**One time:** Dump everything you've ever written into Claude or ChatGPT with the Voice DNA extraction prompt. Get back a portable `.md` file — your Voice DNA.

**Every time after:** Open any AI, paste your Voice DNA file + the content you want transformed. Done.

No app. No login. No subscription. Works in Claude, ChatGPT, Gemini — any AI, forever.

---

## What Gets Captured (The 6 Layers)

Most AI tools only capture surface-level style. Voice DNA goes deeper:

| Layer | What It Captures |
|-------|-----------------|
| **Identity Position** | Are you the protagonist or the advisor? Do you confess first or instruct first? |
| **Mechanics** | Rhythm, sentence length, punctuation patterns, formatting habits |
| **Vocabulary** | Words you use, words you never touch, your plain English level |
| **Audience Awareness** | Who you write to, what they fear, what makes them engage |
| **Signature Moves** | Structural patterns you reach for — the three-beat list, the quiet reveal |
| **Owned IP** | Your real named stories, frameworks, verbal tics. These can't be generated — only extracted. |

---

## Quick Start

### Step 1 — Extract Your Voice DNA

1. Open [Claude](https://claude.ai) or [ChatGPT](https://chat.openai.com)
2. Copy the prompt from [`voice-dna-prompt.md`](./voice-dna-prompt.md)
3. Paste it into a new chat
4. Dump everything underneath it: emails, posts, transcripts, messages, anything you've written
5. Hit send
6. Save the output as `yourname-voice-dna.md`

**Minimum viable input:** ~1,500 words of your own writing. More = better.

### Step 2 — Use Your Voice DNA

Open a new AI chat and start with:

```
Here is my Voice DNA file. Use it to transform the content I give you 
into my exact voice. Do not summarise, change the meaning, or add ideas. 
Just rewrite in my voice.

[Paste your Voice DNA file]

[Paste the AI content you want transformed]
```

That's it.

---

## Files in This Repo

| File | What It Is |
|------|-----------|
| [`voice-dna-prompt.md`](./voice-dna-prompt.md) | The extraction prompt — copy, paste, dump your writing, get your Voice DNA |
| [`example-output.md`](./example-output.md) | A sample completed Voice DNA file so you know what to expect |
| [`hermes-skill/SKILL.md`](./hermes-skill/SKILL.md) | Hermes Agent skill — for users running [Hermes Agent](https://hermes-agent.nousresearch.com) |

---

## Hermes Agent Users

If you run [Hermes Agent](https://hermes-agent.nousresearch.com), drop the `hermes-skill/SKILL.md` file into your skills directory and Hermes handles the full extraction and storage workflow natively.

See [`hermes-skill/SKILL.md`](./hermes-skill/SKILL.md) for setup.

---

## Tips

- **The banned list is more revealing than the positive list.** What you never say defines your voice faster than what you do say.
- **Owned IP (Layer 6) cannot be generated.** Only extracted. Real named stories and frameworks are the most important layer — and the most overlooked.
- **Dump everything.** Don't curate. The AI finds the patterns. More input = more accurate Voice DNA.
- **The register modulates; the voice doesn't.** Your casual post and your sales email should sound like the same person — just at different speeds.

---

## License

MIT — use it, share it, build on it.

---

*Built from the JK Voice Codex framework — June 2026*
*Voice DNA v1.0*
