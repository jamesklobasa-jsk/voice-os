---
name: voice-os-extraction
description: |
  Extract, encode, and apply a person's Voice OS from raw writing samples.
  Produces a portable voice codex that transforms any AI-generated content
  into the person's authentic voice — not generically human, but specifically them.
version: 1.0.0
platforms: [macos, linux]
metadata:
  hermes:
    tags: [voice, copywriting, direct-response, marketing, ai-content]
    category: creative
---

# Voice OS Extraction

A methodology for encoding someone's authentic voice so AI-generated content
can be transformed to sound like them — not generically human, but specifically them.

---

## The 6 Layers of Voice

Every voice has six distinct layers. Miss any of them and the output will be close but not right.

**Layer 1: Identity Position**
Who are you in the writing? Are you the protagonist confessing, or the expert advising?
This is the single most defining element — and it's not a writing rule, it's a worldview.

**Layer 2: Mechanics**
Rhythm, sentence length, punctuation rules, formatting. The "how it looks on the page" stuff.
Most rewriter tools only capture this layer.

**Layer 3: Vocabulary**
Two sides: what you USE and what you NEVER USE. The banned list is often
MORE defining than the positive list.

**Layer 4: Audience Awareness**
Who exactly you're writing to. Their fears, their inner critic, what makes them engage.

**Layer 5: Signature Moves**
Structural patterns you reach for: the three-beat list, the quiet reveal, the vulnerability close.

**Layer 6: Owned IP**
Real named stories, named frameworks, verbal tics. These CANNOT be generated — they must be
extracted from the person's own content. The most important and most overlooked layer.

---

## When To Use This Skill

- User wants to extract their own Voice OS
- User wants to transform AI content into their voice
- User wants to build a reusable voice file for ongoing use

---

## Step 1: Extract the Voice OS

Tell Hermes:
> "Extract my Voice OS from this content." Then dump all your writing.

Hermes will run the extraction protocol across all 6 layers and produce a structured
Voice OS `.md` file saved to your local machine.

**Accept any input:**
- Emails, social posts, voice memo transcripts, podcast transcripts
- Messages, Slack/DMs, blog posts, video scripts, rough notes
- Minimum viable input: ~1,500 words of their own writing

**Also ask (optional but powerful):**
1. 3 words that describe your style
2. 3 words you'd NEVER want used about your writing
3. One sentence on who your audience is and what they fear

---

## Step 2: Transform Content Into Their Voice

Tell Hermes:
> "Transform this content into my voice." Then paste the AI content.

Hermes will apply the stored Voice OS file to rewrite the content.

**Transformation checklist:**
1. Strip all Banned List phrases (Section 9 of the Voice OS file)
2. Rebuild rhythm using the mechanics (Section 2)
3. Replace vocabulary with their words (Section 3)
4. Apply their structural moves (Section 4)
5. Add their emotional signature (Section 5)
6. Check register for the format (Section 10)
7. Read it aloud — if it sounds written, fix it

---

## Output: The Voice OS File

A structured markdown document covering all 12 sections:

1. Core Identity Position
2. Rhythm & Sentence Mechanics
3. Vocabulary Fingerprint
4. Structural Moves
5. Emotional Signature
6. Audience Relationship
7. Named Frameworks & Owned Language
8. Stories Vault
9. Banned List
10. Register Dial
11. Voice Test (proof-of-concept paragraph)
12. Transformation Instructions

Save as `yourname-voice-os.md`. Works in any AI — Claude, ChatGPT, Gemini, anything.

---

## Pitfalls

- **Don't ask for a fixed number of samples.** "Dump everything" converts better than "give me 3 emails." Lower friction = higher follow-through.
- **The banned list is more defining than the positive list.** Always build it.
- **Layer 6 (Owned IP) cannot be generated.** Extract it from content; never fabricate.
- **The register modulates; the voice doesn't.** Same identity position across all formats — only pace and urgency change.
- **Polish is the enemy of authentic voice.** Rougher and more human beats clean and generic.
