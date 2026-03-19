# IBOC Course Website — Project Instructions

## About This Project
UCLA Anderson MGMT 298 course website for Professor Andrea Eisfeldt (PhD Finance).
Built with Jekyll + GitHub Pages using the `just-the-docs` remote theme with UCLA branding.
Sister site to the FinTech course: https://andrea-eisfeldt-finance.github.io/fintech-course/

## Session Start
- When starting a new session, check the auto memory files and summarize the last 2-3 items we were working on so we can pick up where we left off.

## Site Conventions
- Theme: `remote_theme: just-the-docs/just-the-docs` (never use `theme:`)
- Color scheme: UCLA — blue #2774AE, gold #FFD100, dark blue #003B5C
- Deploy: legacy GitHub Pages build (no workflow file)
- Always test links use the baseurl `/iboc-course`

## Course Structure
- 10 weeks, Thursdays 4:10-7pm PT
- Three modules: Fixed Income (Weeks 1-3), Derivatives (Weeks 4-6), Currencies (Weeks 7-9), Capstone (Week 10)
- 6 graded assignments (3 Individual HWs, 3 Group Strategy Proposals)
- Group Best Idea Presentation (Week 10) — groups present their best strategy proposal
- Final exam in finals week

## Content Style
- Tone: polished, professional, academically rigorous — this is a top MBA program
- Be precise with financial terminology; never simplify in a way that sacrifices accuracy
- Emphasize links to current market events, real data, and practitioner perspectives
- Include references to Bloomberg, FRED, OECD, and other professional data sources
- Weekly articles from Bloomberg, WSJ, FT, and academic journals

## Workflow
- Don't ask yes/no permission questions — just proceed
- Keep momentum, don't over-explain

## Technical Notes
- pptx files: extract via `unzip -p file.pptx ppt/slides/slide*.xml | sed 's/<[^>]*>//g'`
- docx files: convert via `textutil -convert txt file.docx`
- GitHub Pages: use `remote_theme` not `theme` in _config.yml
- Mac is Intel x86_64, not ARM
- No Homebrew installed

## Git & Deploy
- Repo: andrea-eisfeldt-finance/iboc-course (to be created)
- Push changes to `main` branch; GitHub Pages auto-deploys
- Commit messages should be concise and descriptive
