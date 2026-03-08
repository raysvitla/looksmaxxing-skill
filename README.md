# QOVES Facial Aesthetics & Style Advisor

**An AI skill / knowledge base for evidence-based facial aesthetics, hairstyle selection, grooming, and style advice.**

Built from **153 QOVES Studio YouTube video transcripts** covering facial analysis, attractiveness research, and optimization strategies.

---

## What is This?

This repository contains a structured knowledge base extracted from [QOVES Studio](https://www.youtube.com/@QOVESStudio)'s public YouTube content. It's designed to be used as:

1. **An OpenClaw/Claude skill** — AI assistants can read these files to provide personalized style and aesthetics advice
2. **A reference guide** — Humans can browse the markdown files for research-backed insights
3. **A learning resource** — Study the science of facial attractiveness and style optimization

---

## Knowledge Base Structure

```
qoves-skill/
├── SKILL.md                          # Main skill instructions (for AI agents)
├── README.md                         # This file
├── LICENSE                           # MIT License
├── knowledge/
│   ├── hairstyles-guide.md          # Hairstyle selection based on 6 facial features
│   ├── mens-specific.md             # Male facial aesthetics and grooming
│   ├── face-shapes.md               # Face shape guide (oval, round, square, etc.)
│   ├── facial-proportions.md        # Golden ratio, thirds, fifths
│   ├── grooming-essentials.md       # Skincare, facial hair, eyebrows, hair care
│   ├── style-principles.md          # Fashion and style optimization
│   ├── attractiveness-science.md    # Research-backed attractiveness principles
│   └── common-mistakes.md           # What to avoid
└── reference/
    └── video-index.md               # Index of all 153 QOVES videos processed
```

---

## How to Use

### As an OpenClaw/Claude Skill

1. **Copy the `qoves-skill` folder** to your OpenClaw workspace or Claude project directory.
2. **Reference `SKILL.md`** in your agent's instructions or project context.
3. **Ask questions** like:
   - "What hairstyle should I get based on my face?"
   - "How do I choose a hairstyle for a square jawline?"
   - "What makes a male face attractive?"
   - "Analyze this photo and suggest grooming improvements."

The AI will read the appropriate knowledge files and provide evidence-based, actionable advice.

---

### As a Human Reference

Just browse the `knowledge/` folder markdown files. Each file is structured for easy reading:

- **Hairstyle advice?** → `hairstyles-guide.md`
- **Men's grooming and aesthetics?** → `mens-specific.md`
- **General attractiveness science?** → `attractiveness-science.md`
- **Proportions and analysis?** → `facial-proportions.md`

---

## Key Insights (Highlights)

### Hairstyles

The "6 features" framework for choosing hairstyles:
1. **Hairline** (shape and density)
2. **Facial symmetry** (asymmetric faces → asymmetric hair)
3. **Forehead shape** (upright vs. sloped)
4. **Facial width** (use layers to narrow)
5. **Jawline** (defined jaw → show it off with short/up styles)
6. **Hair quality** (grow as long as you can without losing quality)

→ **Forget generic "face shape" advice.** Your specific features matter more.

---

### Men's Facial Aesthetics

The **6 features that make men handsome** (ranked by research):
1. **Chin size** (length + width)
2. **Chin projection** (forward prominence — recession is worse than protrusion)
3. **Jawline** (gonial angle + jaw width)
4. **Facial width-to-height ratio** (moderate is best)
5. **Eyebrow thickness** (one of the top 3 masculinity signals)
6. **Lower third prominence** (jaw + chin dominance)

**The #1 non-surgical optimization:** **Lose body fat.** (Reveals all facial features.)

---

### Attractiveness Science

**Core principles:**
- **Averageness** (normal features) + **masculinity/femininity** (sex-typical traits) = attractive
- **Symmetry** signals genetic quality
- **Neoteny** (youthful features) is attractive, especially in women
- **Sexual dimorphism** (masculine features in men, feminine features in women) enhances attractiveness
- **Context matters:** Preferences vary by culture, relationship type, and individual

---

## Attribution

**All content is based on publicly available material from QOVES Studio.**

- **YouTube:** [@QOVESStudio](https://www.youtube.com/@QOVESStudio)
- **Website:** [QOVES.com](https://qoves.com)

This knowledge base was created by extracting and structuring insights from 153 QOVES Studio video transcripts (auto-generated English subtitles). 

**Purpose:** Educational use, aggregation of public research, and AI skill development.

**We do not claim ownership** of QOVES Studio's content. All credit goes to QOVES Studio for their research and educational videos.

---

## Disclaimer

- **Educational use only:** This is not medical or professional aesthetic advice.
- **Research-based, not prescriptive:** Attractiveness is subjective and context-dependent. Use this as a guide, not a rulebook.
- **No affiliation:** This project is not affiliated with, endorsed by, or sponsored by QOVES Studio.

---

## How This Was Built

1. **Downloaded** 153 QOVES Studio video transcripts using `yt-dlp` (auto-generated English subtitles)
2. **Cleaned** VTT files to plain text (removed timestamps, duplicates)
3. **Analyzed** and categorized content by topic
4. **Synthesized** into structured markdown knowledge files
5. **Packaged** as an OpenClaw skill + GitHub repo

**Tech stack:**
- `yt-dlp` for transcript download
- Bash/sed/awk for cleaning
- Claude (Anthropic) for analysis and synthesis
- Markdown for documentation

---

## Contributing

Contributions welcome! If you:
- Find errors or outdated info
- Want to add new QOVES Studio content
- Have suggestions for better organization

Open an issue or submit a pull request.

---

## Changelog

### v1.0 (March 2026)
- Initial release
- 153 QOVES Studio videos processed
- 8 core knowledge files
- Complete hairstyle guide
- Men's facial aesthetics guide
- Attractiveness science compendium

---

## License

**MIT License**

You're free to:
- Use this knowledge base
- Modify it
- Distribute it
- Build on it

**Conditions:**
- Attribute QOVES Studio for the original content
- Attribute this repository if you redistribute

See `LICENSE` file for full details.

---

## Links

- **QOVES Studio YouTube:** https://www.youtube.com/@QOVESStudio
- **QOVES Website:** https://qoves.com
- **OpenClaw:** https://openclaw.com
- **This Repository:** https://github.com/[YOUR_USERNAME]/qoves-facial-aesthetics-skill

---

## Star this repo if you find it useful! ⭐

Built with ♥ by the OpenClaw community.
