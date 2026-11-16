# How this index was made, and how far to trust it

Compiled in November 2026.

## Raw material

- Transcripts of public videos of the two men: 1,056 files, about 7.18 million words, from 1998 to 2026. They include interviews, podcasts, commencement speeches, conference conversations, product launches and earnings calls.
- Most are YouTube auto-captions, with no punctuation, no speaker labels and some mis-heard words. A minority are human-made transcripts.
- Musk's posts and replies on X were also searched by keyword.

This repository contains no transcripts. The original videos belong to their makers. The index gives only links and timestamps.

## Steps

1. **Full scan.** A script read every transcript and pulled out 984 passages using keywords around advice, first principles, feedback, suffering, usefulness, learning, education, and AI and work.
2. **Close reading.** The 710 most relevant passages were read from start to finish by AI reading agents, which judged who was speaking and what was said. Seven full transcripts, including five commencement speeches, were read through by the compiler.
3. **Selection and paraphrase.** 180 places that best represent the two men's views were chosen and written up as short points, first in Chinese and then in English.
4. **Machine check.** Each time the index is generated, a script goes back to the transcript and finds the sentence each entry refers to. Entries that cannot be found are left out, and the timestamp is taken by the script.

## What is guaranteed, and what is not

**Guaranteed**: at the place each entry points to, the transcript really contains the corresponding sentence.

**Not guaranteed**:

- **The speaker.** Auto-captions carry no speaker labels, so who is speaking is a reading judgement. For entries marked A the surrounding context was read; for B only the adjacent lines. During compilation at least one case was found and corrected where an interviewer's restatement had been taken for the man's own words. Others may remain.
- **The accuracy of the paraphrase.** The points are summaries, not translations. Shades of tone and qualification are lost.
- **The year.** Some catalogue dates are upload dates. Known problems are noted in the index. There may be others.
- **Whether what they said is true.** Only the fact that they said it was checked, not whether it was correct.
- **Exact alignment with the video.** Timestamps come from transcripts, and some podcast versions run a minute or two apart from the video.

## What is not covered

- 55% of the transcripts had no keyword hits and were never read. They are mostly product launches, earnings calls and political rallies.
- Topics were chosen for growth and life choices. Products, technical detail, company operations, politics and geopolitics are not here.
- Their predictions were not catalogued systematically. The PR topic holds only a few examples chosen to make a point.
- Nothing said after November 2026 is included.

## Common traps in this kind of material

- A video with one of their names in the title is not necessarily them speaking. Explainer videos are often a narrator paraphrasing.
- In panels and joint interviews, another guest's or the host's words are easily credited to them.
- The same event often exists as several uploads, so part of the impression that "he has said this many times" comes from duplicates.
- Their accounts of the same thing change between occasions. See section 3 of `tensions.md`.

## Reporting an error

Open an issue in the repository with the entry code (for example FB-02) and what is wrong: wrong speaker, distorted paraphrase, wrong year, or dead link.
