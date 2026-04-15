# Publishing guide

## 1) Push this repository to GitHub

Suggested repository name:

- `designify`

## 2) Keep the skill folder name stable

The published skill name is defined in `designify/SKILL.md` frontmatter:

```yaml
name: designify
```

Do not change the folder name and the frontmatter name independently unless you want to create confusion for installers.

## 3) Verify the frontmatter

Make sure `designify/SKILL.md` keeps valid YAML frontmatter with at least:

```yaml
name: designify
description: Build premium, human-made websites with disciplined layout, tasteful animation, futuristic restraint, and strong responsive execution.
```

## 4) Publish and test install

After the repository is public, test with:

```bash
npx skills add https://github.com/kyssta-exe/designify-skill --skill designify
```

## 5) Test in agents

Suggested checks:

- ask the agent to create a futuristic landing page
- ask the agent to redesign a generic AI-looking site
- ask the agent to add tasteful motion without hurting performance
- ask the agent to review a page for responsive and hierarchy issues

## 6) Improve discoverability

In your GitHub description and README, mention:

- premium website design
- anti AI-generated look
- motion / animation standards
- futuristic website design
- responsive layout discipline
- Codex, Claude Code, Cursor, Gemini CLI, Copilot compatibility

## 7) Keep future updates backward-compatible

Try to preserve:

- skill name
- overall folder structure
- reference file names when possible

That makes updates easier for users who already installed the skill.
