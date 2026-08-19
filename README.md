## About

A Claude skill that generates a detailed, formal executive briefing document to help you prepare for job interviews. Just provide a company name, website URL, and a link to the job description — the skill handles the research and formatting.

## What it does

Produces a 5–7 page briefing covering company overview, leadership, culture, competitive landscape, business risks, tailored interview questions, and additional resources (podcasts, keynotes, blog posts, recent news).

## Usage

1. Open [`SKILL.md`](./SKILL.md) and copy the fenced code block — that's the full skill, ready to paste as-is.
2. Add it to Claude:
   - **Claude.ai / Claude apps:**
     ```
     Settings → Capabilities → Skills → paste or upload
     ```
   - **Claude Code / API:**
     ```
     Save it as SKILL.md in your skills directory (e.g. .claude/skills/ for a project, or your global skills path).
     ```
3. Provide the target company's name, URL, and a link to the job description.
4. Claude will generate the brief as a Word document (`.docx`) named `<Company Name> Executive Brief`.

## Placeholders

- `<current job title>` — e.g. "Field Sales Representative"
- `<current employer>` — e.g. "Google Cloud"
- `<company>` — filled in automatically per use, based on the target company you provide

## Requirements

- Output is generated as a Word document (`.docx`), named `<Company Name> Executive Brief`.
- Prioritize resources like the company website, 10k filings, earnings calls, press releases, and news articles.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md).
