# Academic Skills

Reusable Codex skills for discovering academic opportunities, preparing applications, and drafting research outreach.

## Apply to Scandinavia

This skill collection is shared by **Apply to Scandinavia**.

Follow our Telegram channel: [Apply to Scandinavia](https://t.me/applytoscandinavian).

## Skill catalog

| Category | Skill | Purpose | Deliverable |
| --- | --- | --- | --- |
| Discovery | [Find master's programs](skills/discovery/find-masters-programs/SKILL.md) | Research programmes, eligibility, tuition, deadlines, and scholarships | Sourced Excel workbook |
| Discovery | [Find academic supervisors](skills/discovery/find-academic-supervisors/SKILL.md) | Identify and verify research-fit supervisors and collaborators | Sourced Excel shortlist and coverage |
| Applications | [Tailor academic CV](skills/applications/tailor-resume/SKILL.md) | Adapt every applicable CV section for master's, PhD, or postdoctoral applications | Complete tailored academic CV |
| Outreach | [Draft PhD supervisor emails](skills/outreach/draft-phd-supervisor-emails/SKILL.md) | Prepare personalized initial and follow-up drafts | Word document with drafts and source notes |

## Suggested workflows

- Master's applications: find programmes, then tailor the CV to each selected programme.
- PhD applications: find supervisors, tailor the CV to the opportunity, then draft outreach using the verified shortlist.
- Postdoctoral applications: tailor the CV to a specific research posting. Supervisor discovery can also support collaborator research; the email skill is specifically for PhD inquiries.

## Installation

Download or clone this repository. Copy each desired skill folder into your Codex skills directory, typically `~/.codex/skills/` (Windows: `%USERPROFILE%\.codex\skills\`). Copy the folder containing `SKILL.md`, not the enclosing category folder. If `CODEX_HOME` is configured, use its `skills` directory. Review existing versions before replacing them.

Category directories organize this repository; installed skills are individual folders:

```text
skills/
  find-masters-programs/SKILL.md
  find-academic-supervisors/SKILL.md
  tailor-resume/SKILL.md
  draft-phd-supervisor-emails/SKILL.md
```

## Example requests

- `Use $find-masters-programs to find programmes in my selected countries using my CV and transcript.`
- `Use $find-academic-supervisors to find researchers matching my CV and research interests.`
- `Use $tailor-resume to adapt my academic CV to this PhD posting, including Research Experience.`
- `Use $draft-phd-supervisor-emails with my CV and supervisor workbook to prepare email drafts.`

Supply the inputs requested by each skill. Do not commit candidate CVs, transcripts, contact lists, generated drafts, or application documents to this repository.

## Requirements and boundaries

These are instructions for an agent, not standalone executable applications. Discovery and outreach verification require live browsing. Spreadsheet and Word deliverables require suitable authoring tools; academic CV file generation requires tools for the requested format. Individual skills define their required inputs and verification steps.

Keep claims grounded in evidence. Distinguish verified facts, inferred fit, and unknowns. No skill guarantees admission, funding, supervision, or hiring. Drafting does not authorize sending emails or submitting applications.

## Maintaining the collection

See [CONTRIBUTING.md](CONTRIBUTING.md) for structure and review guidance. Skill names are stable invocation identifiers, even when the display title differs: `tailor-resume` is the academic CV skill.

## License

No reuse license has been selected yet. Add one before offering explicit redistribution or modification permissions.
