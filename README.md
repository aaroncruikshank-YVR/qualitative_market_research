# qualitative-market-research

A skill for Claude that teaches and supports the full lifecycle of qualitative market research: in-depth interviews (IDIs), focus groups, customer visits, and online research communities, in both online and offline modes. Designed for people new to qualitative research who want to learn how to do it.

Part of the CTRS Market Intelligence skill family, alongside `quant-market-research` and `competitive-intelligence`.

## What this skill covers

The full commercial qualitative research workflow:

1. **Deciding whether qual is the right tool** for a given business question.
2. **Choosing the method**: IDI, focus group, customer visit, or online community.
3. **Choosing the mode**: online (video), offline (in-person), or asynchronous (community, mobile ethnography).
4. **Recruitment and screening**: defining the population, writing the screener, working with recruiters, handling no-shows.
5. **Writing the discussion guide**: structure, time budgeting, IDI vs. focus group adaptations, worked examples.
6. **Moderation craft**: rapport, neutrality, probing, projective techniques, group dynamics, online adaptations.
7. **Analysis and coding**: framework-first coding, the "10 codes plus other" approach, inter-coder reliability, AI-assisted workflows.
8. **Reporting and insights**: the finding-evidence-implication structure, quote selection and editing, anonymization for B2B and small specialist markets.
9. **Ethics and validity**: informed consent, vulnerable populations, anonymization, the Lincoln-Guba trustworthiness criteria.

## Who this is for

People who are new to qualitative research and want to learn how to do it well. The skill assumes intelligence, not expertise. It walks through decision logic, provides worked examples, and flags the beginner mistakes that are easy to make and expensive to recover from.

It is also usable by experienced researchers as a structured reference and as a tool for briefing junior researchers.

## How to install

### In Claude Code or Cowork

Copy the entire `qualitative-market-research` folder into your skills directory:

- Claude Code: `~/.claude/skills/qualitative-market-research/`
- Cowork: drop the folder into your Cowork skills folder

After installation, the skill triggers automatically when you ask Claude about qualitative research topics. You can also reference it by name.

### As a packaged `.skill` file

This repo includes a packaged `qualitative-market-research.skill` file in `dist/` that can be installed directly via Cowork's "Save skill" UI or by dropping into the skills folder.

## Repo structure

```
qualitative-market-research/
├── README.md                       (this file)
├── LICENSE                         (MIT)
├── SKILL.md                        (skill entrypoint, workflow router)
├── references/                     (deep methodology, read on demand)
│   ├── research-design.md
│   ├── recruitment-and-screening.md
│   ├── discussion-guide.md
│   ├── moderation-craft.md
│   ├── mode-specifics.md
│   ├── analysis-and-coding.md
│   ├── reporting-and-insights.md
│   └── ethics-and-validity.md
└── evals/                          (test prompts used in development)
    └── evals.json
```

`SKILL.md` is the entrypoint Claude reads first. It contains the workflow router that points at the relevant `references/` file for each phase of the research lifecycle. Reference files are typically 200 to 400 lines each and cover one phase in depth.

## Citing or referencing

If this skill informs work you publish, a citation to CTRS Market Intelligence and a link back to this repo is appreciated but not required.

## Built with

- Anthropic's skill-creator framework
- Source material from Creswell's *Research Design*, Trochim's *Research Methods Knowledge Base*, Malhotra and Das, Burns and Bush, Kumar and Aaker, McQuarrie's *The Market Research Toolbox*, and current commercial qualitative practice
- Iterative review and testing across multiple representative beginner scenarios

## Contributions

If you find a mistake, have a suggestion, or want to extend the skill for a domain it does not yet cover well (medical, academic, niche B2B), open an issue or a pull request.

## License

MIT. See [LICENSE](LICENSE).
