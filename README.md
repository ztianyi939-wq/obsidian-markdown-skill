# Obsidian Markdown Skill

Create and edit Obsidian Flavored Markdown with wikilinks, embeds, callouts, properties, tags, comments, highlights, LaTeX, Mermaid, and footnotes.

This skill is useful when you want Codex or another compatible agent to produce Markdown that renders cleanly inside an Obsidian vault instead of plain generic Markdown.

## What it helps with

- Create Obsidian notes with YAML properties/frontmatter.
- Use `[[wikilinks]]` for vault-internal notes.
- Add embeds such as `![[image.png]]` or `![[Note#Heading]]`.
- Add Obsidian callouts such as `> [!note]`.
- Preserve Obsidian-specific syntax for tags, comments, highlights, Mermaid, and LaTeX.

## Install

Install with the Codex skill installer:

```powershell
python E:\Codex\.codex\skills\.system\skill-installer\scripts\install-skill-from-github.py --url https://github.com/ztianyi939-wq/obsidian-markdown-skill --path . --name obsidian-markdown --dest E:\Codex\.codex\skills
```

Or manually download this repository and place it at:

```text
E:\Codex\.codex\skills\obsidian-markdown
```

The final structure should contain:

```text
E:\Codex\.codex\skills\obsidian-markdown\SKILL.md
```

Restart Codex after installing.

## Usage

Example prompts:

```text
Use $obsidian-markdown to turn these notes into an Obsidian-ready Markdown file with properties, wikilinks, and callouts.
```

```text
Use $obsidian-markdown to create an Obsidian project note. Include title, date, tags, aliases, related wikilinks, and action items.
```

## Attribution

This skill is based on `obsidian-markdown` from [kepano/obsidian-skills](https://github.com/kepano/obsidian-skills).
