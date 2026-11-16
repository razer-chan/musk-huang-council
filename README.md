# Musk × Huang Council

**English** | [简体中文](README.zh-CN.md)

An Agent Skill for Claude. Once installed, you can ask about life, career, learning and startups, and get answers grounded in what Elon Musk and Jensen Huang have said in public.

Every point links to the original video at the right timestamp, so you can check it yourself.

> This is a third-party compilation. It has no connection to either man or their companies and is not endorsed by them. The content is paraphrase, not their words.

## What it does

- Answers "how do they see this" and gives sources.
- Shows where the two disagree, and where each has changed his mind.
- Covers the costs they have admitted to, and what most people should not copy.
- Keeps "what they said" separate from the assistant's own advice.

## What it does not do

- It does not role-play either man in the first person or invent words for them.
- It does not assess stocks or give investment advice.
- It does not cover product specifications, company news or political positions. Those are not in the index.

## Things to ask

- I want to quit my job and start a company, but I'm scared. What would they say?
- AI is moving so fast. Is it still worth learning to code?
- I'm doing several things at once and don't want to drop any. What now?
- Run a round table for me: is a PhD worth it?
- Musk says work will be optional within a few years. Should I believe that?

It answers in the language you ask in. The index carries each point in both English and Chinese.

## Install

### Claude Code

Clone the repository into your personal skills folder:

```bash
git clone https://github.com/razer-chan/musk-huang-council ~/.claude/skills/musk-huang-council
```

Then just ask. If the skill does not show up in a session that was already running, run `/reload-skills`.

### Claude apps (web and desktop)

1. Download `musk-huang-council.zip` from the Releases page of this repository.
2. In Claude, go to Customize → Skills, click +, choose Create skill → Upload a skill, and upload the zip.
3. Switch the skill on.

Code execution and file creation need to be enabled in settings. Menu names may change; Claude's official help is the reference.

## What is inside

| File | Contents |
|---|---|
| `SKILL.md` | The skill itself: when to use it, how to answer, and a few lines not to cross |
| `references/index.md` | 180 viewpoint entries in 15 topics, in English and Chinese |
| `references/tensions.md` | Disagreements, changes of mind, costs, and what not to copy |
| `references/principles.md` | Ten principles that run through both |
| `references/method.md` | How the index was made and how far to trust it |

The fifteen topics: choosing a direction, how to think, mistakes and feedback, how to learn, education and college, work intensity and its cost, resilience, risk and startups, priorities, AI and the future of work, getting things done, teams and hiring, money, meaning and optimism, and how far to trust their predictions.

## How reliable is it

- The raw material is 1,056 transcripts of their public videos from 1998 to 2026, about 7.18 million words.
- For every entry, a script went back to the transcript and confirmed that the sentence is there.
- Who is speaking and whether the paraphrase is fair are reading judgements, and may be wrong.
- 55% of the transcripts were never read. They are mostly product launches, earnings calls and political rallies.

Details are in [`references/method.md`](references/method.md).

## Notices

- This repository contains no video transcripts. The original videos belong to their makers.
- The points in the index are the compiler's paraphrases. To quote either man, go to the original video.
- Both are extreme survivors, and what worked for them may not suit you. Nothing here is career, financial, legal or medical advice.

## Corrections

If a speaker is wrong, a paraphrase is distorted, a year is off or a link is dead, please open an issue and give the entry code (for example `FB-02`).

## License

The text and structure of this repository are released under the MIT License. See [`LICENSE`](LICENSE).
