## About

A Claude skill that generates a detailed, formal executive briefing document to help you prepare for job interviews. Just provide a company name, website URL, and a link to the job description — the skill handles the research and formatting.

## What it does

Produces a 5–7 page briefing covering company overview, leadership, culture, competitive landscape, business risks, tailored interview questions, and additional resources (podcasts, keynotes, blog posts, recent news).

## Usage

1. Copy the prompt below into Claude (or wherever you keep reusable skills).
2. Fill in `<current job title>` and `<current employer>` with your own details.
3. Provide the target company's name, URL, and a link to the job description.
4. Claude will generate the brief as a Word document (`.docx`) named `<Company Name> Executive Brief`.

## Skill

```markdown
# Company Briefing Report — Interview Prep Skill

**Add a company name and job description to generate a detailed executive briefing document to prepare for job interviews.**

## Prompt

> You are an expert corporate researcher. I currently work as a `<current job title>` at `<current employer>`. Help me prepare for job interviews. I need a detailed formal briefing document to prepare for the interview cycle — the ideal length is 5–7 pages. I would like to be able to just provide the company name and URL, as well as a link to the job description, for you to get started. The output should be delivered as a Word document (.docx). The filename should be "`<company>` Executive Brief."
>
> While other sections that you think are relevant may be included, it is mandatory that you include the following sections in the brief, which should be well-formatted:

### Company Overview

This should include the following sections:

- **What They Do**
- **Funding Rounds and potential exit timeline**, or **Financial Overview** (if public)
- **Leadership**
- **Corporate Culture**
- **Value to the Marketplace**
  - Problem they are solving
  - Product Set
  - Solutions
  - Industries
  - Customer Stories

### Competitive Landscape

This section should cover the competitors in the sector and how they stack up against the company.

### Risks to Their Business

Please highlight any potential risks, including, but not limited to, supply chain, customer mix, and shifts in technology.

### Questions to Ask

Provide five tailored questions I should be asking in the interview.

### Questions to Expect

**Recruiter**
Please include 3–5 questions I might expect from the recruiter screen.

**Hiring Manager**
Please include 3–5 questions I might expect during an initial meeting with the hiring manager.

### Additional Resources

Please include:

- Podcasts, especially those interviewing their leaders
- Keynotes on YouTube
- Blog posts
- Recent news and product launches
```

## Placeholders

- `<current job title>` — e.g. "Field Sales Representative"
- `<current employer>` — e.g. "Google Cloud"
- `<company>` — filled in automatically per use, based on the target company you provide

## Requirements

- Output is generated as a Word document (`.docx`), named `<Company Name> Executive Brief`.
- Prioritize resources like the company website, 10k filings, earnings calls, press releases, and news articles.

## Changelog

See [CHANGELOG.md](./CHANGELOG.md).
