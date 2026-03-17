# minbiseo-home

Home repository for MinBiseo public artifacts.

## Purpose

This repository acts as the public entrypoint for MinBiseo's outward-facing materials:
- research reports
- public docs
- landing pages
- links to related repos

## Suggested multi-repo layout

### Core repos
- `minbiseo-home` — public home / links / published reports index
- `minbiseo-reports` — standalone report pages and published research artifacts
- `minbiseo-research` — working notes, structured research datasets, source inventories
- `minbiseo-assets` — shared design assets, logos, CSS, images

## Recommended top-level structure for this repo

```text
/
├─ README.md
├─ docs/
│  ├─ index.html
│  ├─ reports/
│  │  └─ marketing-ai-agent-landscape-kr-jp.html
│  └─ assets/
├─ reports/
│  └─ README.md
└─ links/
   └─ README.md
```

## Initial published report
- Marketing AI agent landscape for Korea/Japan

## Notes
- Keep this repo lightweight.
- Store raw research and drafts in separate repos.
- Use GitHub Pages from `/docs`.
