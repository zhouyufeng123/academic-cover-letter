# Academic Cover Letter Skill

A Claude Code skill that generates professional cover letters for computer vision / pattern recognition journal submissions.

## Supported Journals

| Journal | Strategy |
|---------|----------|
| IEEE TPAMI | Pattern-analysis framing, distinguish from TIP |
| IEEE TIP | Image-processing focus, distinguish from TPAMI |
| IJCV | Conference extension disclosure, journal-level contribution |
| Pattern Recognition | Broader scope, can include applications |

## What It Does

- Generates a complete cover letter with 5 structured paragraphs: hook, journal fit, conference extension (if applicable), contributions, and declaration
- Adapts tone and strategy based on target journal
- Ensures mandatory IEEE disclosure for conference extensions
- Includes hard metrics (PSNR, mAP, speedup) in contributions
- Flags common mistakes (filler phrases, vague claims, missing disclosures)

## Installation

### Option 1: Use the .skill file

Copy `academic-cover-letter.skill` to your Claude Code skills directory.

### Option 2: Manual setup

Copy `SKILL.md` and `references/` folder to your Claude Code skills directory:

```
your-skills-dir/
  academic-cover-letter/
    SKILL.md
    references/
      cv-venues.md
```

## Usage

Just ask Claude to write a cover letter. Examples:

```
帮我写一封投 TPAMI 的 cover letter，论文题目是 xxx
```

```
Write a cover letter for my TIP submission. The paper proposes a diffusion-based SR method achieving 32.1 dB PSNR.
```

```
我有一篇从 ECCV 2024 扩展的论文要投 IJCV，帮我写 cover letter
```

The skill will ask for any missing information (paper title, metrics, conference extension details, etc.) and generate a targeted cover letter.

## What You Need to Provide

| Field | Required |
|-------|----------|
| Paper title | Yes |
| Target journal | Yes |
| Core finding (1-3 sentences) | Yes |
| Technical contribution | Yes |
| Hard metrics | Yes |
| Conference extension? | If applicable |
| What's new vs conference? | If applicable |
| Corresponding author & affiliation | Yes |
| Suggested reviewers | Optional |

## Key Features

- **Journal-specific targeting**: Each journal has a distinct cover letter strategy
- **Conference extension disclosure**: Automatically includes mandatory IEEE disclosure when extending from a conference paper
- **Pitch, not summary**: Follows publisher guidelines (Springer Nature, Elsevier, IEEE) — the cover letter sells the paper, not repeats the abstract
- **Self-check**: 7-point validation after generation (opening test, journal fit, extension test, contribution test, declaration test, length test, filler test)

## Note

Top CV conferences (CVPR, ICCV, ECCV, NeurIPS, ICML) use OpenReview and do **not** require cover letters. This skill is for journal submissions only.

## License

MIT
