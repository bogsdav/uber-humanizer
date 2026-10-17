# Uber-humanizer

A Claude skill. Draft, humanize, rewrite, edit, proofread, diagnose, or match voice in prose while preserving meaning and facts. Exclude code, schemas, exact quotations, and locked text from stylistic edits.

## What's inside

- `uber-humanizer/SKILL.md`
- `uber-humanizer/adapters/chatgpt.md`
- `uber-humanizer/adapters/claude.md`
- `uber-humanizer/adapters/gemini.md`
- `uber-humanizer/references/patterns-and-repairs.md`
- `uber-humanizer/references/quality-checks.md`
- `uber-humanizer/references/source-notes.md`
- `uber-humanizer/references/voice-and-channel-presets.md`
- `uber-humanizer/standalone-instructions.md`
- `uber-humanizer/tests/acceptance-tests.md`
- `uber-humanizer/validation-summary.md`

## Install

### Claude app (claude.ai, desktop, mobile)

1. Download this repo as a ZIP (**Code > Download ZIP**) and unzip it.
2. Zip the `uber-humanizer` folder on its own, so the ZIP contains `uber-humanizer/SKILL.md`.
3. In Claude's settings, open the Skills section, upload that ZIP, and turn the skill on.

### Claude Code

```bash
git clone https://github.com/bogsdav/uber-humanizer.git
mkdir -p ~/.claude/skills
cp -r uber-humanizer/uber-humanizer ~/.claude/skills/
```

Restart Claude Code. The skill loads automatically when a request matches its description.

## Try it

- "Make this blog post sound less robotic without changing the facts."
- "Proofread this email and match the voice of the sample I pasted."
- "Diagnose what makes this paragraph read as AI-written."

## License

MIT. See [LICENSE](LICENSE).
