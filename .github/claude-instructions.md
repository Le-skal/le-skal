# GitHub Claude Instructions for le-skal Repository

## Repository Overview

**Profile/portfolio repository** (special GitHub repo matching username) serving as Raphael Martin's (Skal's) professional profile page at https://github.com/le-skal.

**Purpose:** Showcase Data Engineering and AI/ML expertise with links to external projects.

**Key Facts:**
- Single-file repository containing only README.md
- Pure Markdown documentation, no code
- No build process, dependencies, or tests

## Repository Structure

```
/
├── .git/                  # Git repository metadata
├── .github/              # GitHub configuration directory
│   └── claude-instructions.md  # This file
└── README.md             # Profile page content
```

### Key Files

**README.md** - Profile page containing:
- Personal intro (Paris, France)
- Background in Data Engineering & AI/ML
- Technical skills: Python, SQL, TypeScript/JavaScript, GCP, n8n, and more
- Links to external projects (data pipelines, ML experiments, tools)
- Portfolio link: [martin-raphael.deepskal.com](https://martin-raphael.deepskal.com/)
- Contact info

## Making Changes

### Editing the Profile (README.md)

**Guidelines:**
1. **Preserve Formatting:** Maintain emoji bullets, markdown headers, and existing style
2. **Section Structure:** Header, About Me, Expertise (bulleted), Repositories (categorized links), Learning Goals, Contact
3. **Repository Links Format:**
   ```markdown
   - #### Project Title
     🔗[le-skal/repo-name](https://github.com/le-skal/repo-name)
       Brief description.
   ```
4. **Professional Tone:** This is a public professional portfolio — keep language direct and authentic, no fluff

### Validation

**No build/test required.** Only validate:
- Markdown syntax correctness
- Links properly formatted
- Consistent formatting (-, #### for subsections)

**Preview markdown rendering if possible before committing.**

## GitHub Actions Workflows

**Note:** This repository does not contain `.github/workflows/` directory or workflow files.

## Git Operations

**Default Branch:** `main`

Standard git commands work normally:
```bash
git --no-pager status     # Check status
git --no-pager diff       # View changes
cat README.md             # View content
```

## What This Repository Does NOT Have

**To save exploration time, this repository has NO:**
- Source code files (.js, .py, .java, .ts, etc.)
- Build configs (package.json, Makefile, etc.)
- Dependencies (package-lock.json, requirements.txt, etc.)
- Test files or frameworks
- CI/CD config files (.github/workflows/*.yml in repo)
- Linting config
- Docker files
- IaC files (.tf, CloudFormation)
- Scripts directory

## Troubleshooting

**Q: How do I build/test?**
A: Nothing to build/test. This is documentation-only.

**Q: Where are the project files?**
A: This is a profile repo. Projects referenced are external repos under le-skal.

**Q: Changes not showing on profile?**
A: Ensure changes are committed to the `main` branch. GitHub displays README.md from main on the profile page.

## Key Reminders

1. **Trust These Instructions:** Repository thoroughly analyzed. Search only if instructions are incomplete or incorrect.
2. **Documentation-Only:** No build files, tests, or source code exists.
3. **No Validation Pipeline:** No build failures, tests, or linting. Only validate markdown formatting.
4. **Preserve Professional Tone:** Public-facing professional profile — keep it direct and authentic.
5. **External Projects:** Listed projects are references only. Don't modify external repos.
6. **Minimal Changes:** Make surgical edits. Preserve structure and style.
7. **No Dependencies:** No packages, runtimes, or environment setup needed.

## Content Summary

**Professional Background:** Data Engineering & AI/ML, currently apprentice at L'Agefi (Groupe Bey Medias), studying at ECE Paris (Bachelor Data & IA), accepted to Mastère Data Engineering & IA at EFREI Paris starting September 2026
**Skills:** Python, SQL, TypeScript, JavaScript, Java, Bash
**Expertise:** GCP (BigQuery, Cloud Run), n8n workflow automation, Salesforce integrations, NLP pipelines, Power BI, Gemini/OpenAI APIs, React/Next.js
**Projects Listed:** Data pipelines, ML experiments, automation tools, personal portfolio (deepskal.com)
**Contact:** Portfolio at martin-raphael.deepskal.com

## Files in Repository

**/ (root):**
- README.md (markdown profile page)

**/.github/:**
- claude-instructions.md (this file)

---

**Last Updated:** March 2026
**Repository URL:** https://github.com/le-skal/le-skal