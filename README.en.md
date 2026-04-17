# Cognitive Dividend Skill

A ready-to-use AI skill toolkit — distilling the cognitive upgrade methodologies from *Cognitive Dividend* into 15 modular cognitive tools that can be triggered individually or composed together.

This is not a book summary page. The book is the source of these skills, not the main character of this page.

## What Problems Do These Skills Solve

- Feeling busy all the time but not producing much, with no idea where your attention is going
- Wanting to upgrade your thinking but not knowing where to start or how to practice
- Making gut-feeling decisions on complex problems, lacking structured analysis and systems thinking
- Getting stuck choosing between two options, not realizing there might be a third way
- Wanting to understand trends and potential energy, rather than staring only at immediate effort

## What Was Distilled

15 triple-verified skills extracted from *Cognitive Dividend* (Xie Chunlin, 2019), covering five dimensions:

- **Understanding Wealth**: `attention-management` (Attention Management), `time-merchant` (Four Time Merchant Modes), `compound-effect` (Compound Effect Design)
- **Understanding Yourself**: `nlp-levels` (NLP Six-Level Model), `metacognition-control` (Metacognition Three Stages), `multi-dimension-ability` (Multi-Dimensional Ability Building)
- **Understanding the World**: `potential-energy` (Potential Energy Differentials and Point-Line-Plane-Body), `mirror-world` (Mirror World and Four-Domain Space)
- **Thinking Power**: `brain-unseal` (Unsealing the Brain), `dialysis-prism` (Dialysis Prism), `structured-thinking` (Structured Thinking & MECE), `systems-thinking` (Systems Thinking)
- **Problem Solving**: `scientific-decision` (Four-Step Scientific Decision), `evolution-strategy` (Evolution Strategy), `innovation-method` (Innovation Methodology)

## Effect Examples

### Example 1: Facing a Complex Decision

**User Question**

> "I'm torn between two job offers — one pays more but is unstable, the other is stable but has a low ceiling. How do I choose?"

**Skill Judgment**

- Trigger `nlp-levels` to elevate the decision from the "behavior level" to the "identity level" and "vision level"
- Call `scientific-decision` to turn a multiple-choice question into a calculation using the four-step method
- If a long-term path is involved, supplement with `compound-effect` and `potential-energy`

**Response Example**

> Don't choose between two options — jump up a level first: Who do you want to become? The answer to that question will directly determine which option isn't even worth agonizing over. Then apply the four-step scientific decision method: clarify your purpose first (not "which job to pick," but "where do I want to be in five years"), exhaust all alternatives (not just these two offers), filter by conditions, and only then score and compare. Most indecision isn't because two options are equally good — it's because you're choosing at the wrong level.

### Example 2: Team Busy but Not Productive

**User Question**

> "My team is busy every day, but key projects never seem to move forward. What's going wrong?"

**Skill Judgment**

- Trigger `attention-management` to check for attention black holes
- Call `systems-thinking` to see if it's a structural problem rather than an individual one
- Supplement with `structured-thinking` to organize the chaotic information

**Response Example**

> First, determine which layer the problem is on: if everyone is busy but output falls short, it's most likely not a "not working hard enough" problem — it's an attention allocation problem. The three most common black holes are: reactive responding (message-driven work), context switching (frequent task-switching), and inefficient repetition (manually doing things that should be automated). Then look at the system structure: are incentives driving the wrong behaviors? Is the feedback loop reinforcing or balancing? The essence of most "busy but ineffective" situations is that the system structure sucks attention into low-leverage positions.

## How These Skills Were Generated

These skills were generated using the **cangjie-skill** RIA-TV++ pipeline, which consists of six stages:

1. **Whole-Book Understanding (Adler Analysis)** — Apply Mortimer Adler's analytical reading method: structure, interpretation, critique, and application. Produces `BOOK_OVERVIEW.md`
2. **Parallel Extraction** — Deploy 5 specialized extractors simultaneously (frameworks, principles, cases, counterexamples, terminology) to extract candidate methodology units from the text
3. **Triple-Verification Screening** — Each candidate must pass three checks: at least 2 independent supporting references in the book (cross-domain), ability to answer unstated new questions (predictive power), and non-obviousness (uniqueness)
4. **RIA++ Construction** — Structure verified content across six dimensions: R (Original Quote) / I (Rewrite in Own Words) / A1 (Book Case) / A2 (Future Trigger Scenario) / E (Executable Steps) / B (Boundaries & Blind Spots)
5. **Zettelkasten Linking** — Identify dependency, contrast, and composition relationships between skills. Generate `INDEX.md` and reference graph
6. **Stress Testing** — Design test cases including decoy questions for each skill. Failed skills are sent back for rework

## Generated by Cangjie Skill

This repository was generated by [cangjie-skill](https://github.com/kangarooking/cangjie-skill) — an open-source toolchain that distills books into executable AI skills.

cangjie-skill is based on the RIA-TV++ methodology, extracting methodologies, frameworks, and principles from books into atomic skills that can be directly invoked by AI agents in real-world scenarios.

## Repository Structure

```text
cognitive-dividend-skill/
├── README.md              ← You are here (Chinese)
├── README.en.md           ← English version
├── README.ja.md           ← Japanese version
├── LICENSE                ← MIT
├── BOOK_OVERVIEW.md       ← Stage 0 output: Full book Adler analysis
├── INDEX.md               ← Stage 3 output: Skill overview + reference graph
├── candidates/            ← Stage 1 output: Raw candidate units
├── rejected/              ← Stage 1.5 output: Rejected units + reasons
├── verified.md            ← 15 triple-verified units
└── */SKILL.md             ← 15 skills, each with test-prompts.json
```

## How to Use

1. Browse `INDEX.md` for the skill landscape and dependency relationships
2. Find the `*/SKILL.md` relevant to your current problem and use the trigger conditions and execution steps directly
3. Integrate skills into your agent framework, or use the prompts as standalone tools
4. Use `test-prompts.json` to verify that skills trigger in correct scenarios and do not trigger in incorrect ones

## Source

- Book: *Cognitive Dividend* (认知红利)
- Author: Xie Chunlin (谢春霖)
- Year: 2019

## More Skills

- [Buffett Letters Skill](https://github.com/kangarooking/buffett-letters-skill) — 20 investment judgment skills from Buffett's 60+ years of shareholder letters
- [Poor Charlie's Almanack Skill](https://github.com/kangarooking/poor-charlies-almanack-skill) — 12 decision and judgment skills from Charlie Munger's core thinking methods
- [No Rules Rules Skill](https://github.com/kangarooking/no-rules-rules-skill) — 10 organizational design skills from Netflix's freedom and responsibility culture
- [Duan Yongping Skill](https://github.com/kangarooking/duan-yongping-skill) — 15 business and investment skills from Duan Yongping's investment Q&A collection

## About the Author

**kangarooking** — AI blogger, indie developer. Creator of AI Top WeChat Official Account「袋鼠帝 AI 客栈」

Volcengine Navigation KOL, Baidu Qianfan Developer Ambassador, GLM Evangelist, Trae Kunming's First Fellow

| Platform | Link |
|----------|------|
| 𝕏 Twitter | https://x.com/aikangarooking |
| Xiaohongshu | https://xhslink.com/m/5YejKvIDBbL |
| Douyin | https://v.douyin.com/hYpsjphuuKc |
| WeChat Official Account | 袋鼠帝 AI 客栈 |
| WeChat Video Channel | AI 袋鼠帝 |

WeChat Official Account「袋鼠帝 AI 客栈」QR code:

![](https://raw.githubusercontent.com/kangarooking/cangjie-skill/main/assets/kangarooking-gzh.jpg)

## License

MIT. See [LICENSE](./LICENSE).
