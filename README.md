# GiftWise — Project Proposal

Design, Build, Ship · MPCS 51238 · Autumn 2026 · Yiting Chen

A single-page proposal for AI-powered holiday gift discovery, verified price comparison, and historical price context. **This repository is the proposal assignment, not the GiftWise application.**

## Submission links

- Live proposal: https://giftwise-project-proposal.vercel.app
- GitHub repository: https://github.com/YitingChen-coder/GiftWise-Project-Proposal

## Preview
Open `index.html` directly, or run `python3 -m http.server 8000` and visit http://localhost:8000. No package installation, framework, build step, external font, or runtime service is required.

## Sources and scope
- Official requirements: instructor's “Design, Build, Ship - Week 5 - Project Proposal.pdf”.
- Project decisions: student-provided GiftWise implementation brief and approved plan.
- Three interview excerpts: faithful English translations of Chinese interview records supplied by the student. The third excerpt is shortened with an ellipsis. No interviewee identities or quantitative validation are inferred.
- All application integrations and roadmap functionality are planned, not operational. Provider documentation has been researched, with primary links on the page; no API access has been tested. Keepa requires a subscription and is not a confirmed free-tier solution. No-cost historical-price provider access remains a principal v1 risk.
- Original assignment deadline: November 3, 2026, 5:30 PM. No extension approval is claimed.

## Deployment
After student copy review, deploy this directory using the student's own Vercel account: choose the Other/static preset, no build command, and serve the repository root. Alternatively use an authenticated `vercel` CLI and `vercel --prod`. Do not use an anonymous expiring deployment. No API keys are needed.

Deployment status: production deployment READY on November 8, 2026, using the student’s authenticated Vercel account `chenyiting0521-3362`, workspace `cs-0c90`. The student explicitly authorized deployment after the preview and revision rounds. Anonymous HTTP verification returned 200 and the response matched `index.html` byte for byte. This was an account-backed production deploy, not a temporary anonymous deploy. Repository documentation is excluded from the hosted files by `.vercelignore`.

## Rubric coverage
- One-sentence problem and audience: introduction.
- Three potential-user interviews: The people.
- AI focus and rationale: The focus.
- Weekly roadmap and explicit v1/v2 scope: The plan.
- Planned stack, MCP servers, CLIs and rationale: The blueprint.
- Static single HTML: `index.html` with embedded styling and artwork.
- Iterative work: actual Git history; each meaningful step pushed to GitHub.
- Own-account Vercel hosting: deployed and HTTP/content verified.
- Review: preview supplied, revisions completed, and student explicitly authorized deployment. No claim that the student has personally read every line; a final read-through before Classroom submission is recommended.
- Browser-based visual device checks remain unverified because the browser runtime was unavailable.
