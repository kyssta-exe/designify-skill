# designify

A portable agent skill for Codex, Claude Code, OpenCode, Cursor, Gemini CLI, GitHub Copilot, and other tools that support the open Agent Skills format.

This skill teaches coding agents how to design and build websites that feel premium, human-made, responsive, and production-ready instead of generic or AI-generated.

## What this skill does

- enforces strong layout discipline and realistic web bounds
- pushes agents toward premium, authored, non-generic design decisions
- adds motion rules for tasteful, performant animation
- improves futuristic styling without turning the site into glow spam
- forces responsive behavior, section purpose, and hierarchy checks
- includes reusable review checklists and prompt templates

## Repository layout

```text
designify-skill/
├── README.md
├── LICENSE
├── PUBLISHING.md
└── designify/
    ├── SKILL.md
    ├── references/
    │   ├── ANTI_AI_DESIGN_FAILURES.md
    │   ├── MOTION_SYSTEM_GUIDE.md
    │   ├── RESPONSIVE_BOUNDS.md
    │   ├── SECTION_PATTERNS.md
    │   ├── STYLE_BOOTSTRAP.md
    │   └── WEBSITE_REVIEW_CHECKLIST.md
    └── assets/
        ├── design-direction-template.md
        └── website-request-template.md
```

## Install locally for common agents

Project-local examples:

- **Codex / Cursor / Gemini CLI / GitHub Copilot / Universal agents**: copy `designify/` into `.agents/skills/`
- **Claude Code**: copy `designify/` into `.claude/skills/`
- **OpenCode / OpenClaw**: copy `designify/` into `skills/`

## Install through the Skills CLI after publishing

Once this repository is on GitHub, install it with a command like:

```bash
npx skills add https://github.com/kyssta-exe/designify-skill --skill designify
```

## Notes

This repository keeps the skill instruction-only. No executable scripts are required.
