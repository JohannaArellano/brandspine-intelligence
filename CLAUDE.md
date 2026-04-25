# CLAUDE.md — The Brand Spine Intelligence OS

## About The Brand Spine
Brand strategy firm founded by Johanna Arellano. Serves service-based business owners who are generating revenue but lack a clear, ownable brand identity.

Website: www.thebrandspine.com
Primary operator: Johanna Arellano (jo@thebrandspine.com)
Collaborator: Brett Moore (brett@apexpodcast.co | GitHub: brettkmoore)

## What This Repository Is
This is the shared intelligence and content operations repository for The Brand Spine. It is NOT the website codebase. It contains:
- Research docs (keywords, ICP, market, geo/aeo)
- Content briefs, blog drafts, social content
- Session logs and strategic decisions

Do NOT deploy anything from this repo. It is documentation and content ops only.

## Repository Structure
/research/keywords      — keyword research tables with volume, intent, priority
/research/icp           — ideal client profile documentation
/research/market        — market and competitive research
/research/geo-aeo       — geographic and answer engine optimization research
/content/blog           — blog article drafts and final copy
/content/social         — social media content
/content/briefs         — content briefs (one per piece)
/strategy/sessions      — session logs (MANDATORY — see protocol below)
/strategy/decisions     — key strategic decisions and rationale

## Ideal Client Profile (Summary)
Service-based business owners — especially real estate agents, coaches, and consultants — who are generating revenue but feel invisible, generic, or unclear on their positioning. They know they need a brand but don't know what it should say or how to make it distinct.

## Brand Voice
Calm, grounded, direct. No hype, no urgency, no flattery.
Use language like: clarity, alignment, positioning, authority, identity, strategy, deliberate.
Avoid: game-changing, revolutionary, crush it, dominate, urgency stacking, performative warmth.

## SEO / GEO / AEO Priorities
- Long-tail keywords targeting service-based business owners
- Brand strategy for real estate agents, coaches, consultants
- Answer engine optimization: structure content to directly answer questions
- Geographic targeting relevant to Jo's primary markets

## Session Logging Protocol (MANDATORY)
Every working session MUST be logged. No exceptions.
x
Create a file in /strategy/sessions/ named:
YYYY-MM-DD_[contributor-initials]_[brief-topic-slug].md

Example: 2026-04-24_JA+BM_github-setup-and-content-infrastructure.md

Use the template in SESSION_LOG_TEMPLATE.md.
Commit the session log alongside any other changes made during the session.
Never skip a session log — this is the institutional memory of the operation.

## Research Documentation Standards
- Keywords: Markdown table format with columns: keyword | monthly volume | intent | priority | notes
- ICP: Update existing profile docs, do not create duplicates
- Market research: Date-stamp every entry, note the source
- Content briefs: One file per piece — target keyword, content angle, target audience segment, CTA, internal link opportunities

## Content Standards
- Audience: service-based business owners, professional reading level
- Structure for SEO: H1 > H2s > H3s where appropriate, meta description in brief
- Every piece should serve a keyword or answer a specific question
- Voice: Jo's — calm, direct, grounded authority (see Brand Voice above)

## What NOT To Do
- No duplicate research or ICP documents — update existing ones
- Never skip session logs
- Do not publish or deploy from this repo
- Do not modify CLAUDE.md without agreement from both Jo and Brett
- Do not store sensitive client data, contracts, or financial records here
- Do not create files outside the defined folder structure without noting the addition in a session log 
