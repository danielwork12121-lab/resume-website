# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Technical recruiters and hiring managers screening for Summer 2027 SWE / ML internships, usually arriving from a resume link, LinkedIn, or GitHub and deciding within about ten seconds whether to read further. Secondary: engineers doing a deeper pre-interview read; hackathon and research collaborators.

## Product Purpose

A single-page personal site for Zilin "Daniel" Li (CS + Math, Georgia Tech, expected May 2030). Success means a recruiter leaves believing three things in order: he ships real products that people pay for, he can code and reason at a level beyond his year, and he is an interesting person to work with.

## Positioning

The lead claim is shipped, used, paid-for work, not coursework: co-founded Hachi (300+ paying users, $800+ revenue in month one), top 2% of 14,022 at the ByteDance TRAE hackathon, top 18 of 2,589 at Tencent's game challenge, two live demos. Research (first-author Springer AIET 2024 paper, Best Session Presenter, a co-first-author paper under review at IEEE ICDE 2026) supports the products claim rather than leading it. The page itself is a demonstration: one hand-written HTML file, no framework, no build step, with a live opt-in guide character written in vanilla JS.

## Operating Context

Read on a laptop or phone in a screening pass, often alongside a PDF resume and a GitHub profile. Must survive link previews (Slack, iMessage, LinkedIn), fast skimming, keyboard navigation, and reduced-motion settings. Deployed as a static file (Vercel).

## Capabilities and Constraints

- One file, `index.html`, hand-written HTML/CSS/JS. No framework, no build step. Keep it that way.
- Bobbie, the opt-in animated guide, stays and should be easier to discover than today (decided: keep and promote). Its tour, perch anchors, and dialogue are content, not decoration.
- All facts, numbers, dates, links, and copy are real and must not be altered or invented. Ask before changing a claim.
- Contact: zli3381@gatech.edu, LinkedIn, GitHub. Hachi has no public link (mainland China hosting).
- Undecided: whether to add a downloadable PDF resume link (asset not in repo).

## Brand Commitments

Standing visual preference (decided during the redesign round): the existing page is the visual identity, not something to replace. Preserve the near-black ground with mint accent, the serif display face against sans body and mono labels, the sidebar-plus-main composition, the research figure, the statistics row, and Bobbie. Work is refinement toward a richer, more premium feel that stays calm at first glance: spacing, borders, type hierarchy, interaction states, subtle surface variation, alignment, restrained motion. Craft references, for level not imitation: rauno.me (micro-interaction precision), brittanychiang.com (recruiter readability and hierarchy), paco.me (restraint and typographic discipline). Rule: detail without distraction. Avoid decorative noise, heavy animation, gradients, glass, floating effects, large empty areas, card lifting, or drifting toward a generic developer portfolio.


Name as written: Zilin "Daniel" Li. Voice: direct, specific, lightly witty (Bobbie carries the wit; the resume copy stays plain). Headshot asset is embedded in the page. No logo.

## Evidence on Hand

All content in `index.html`: education, research and publications, four projects with links, engineering roles, applied AI and data internships, leadership, skills. The fig. 1 canvas is a real reference to the time-series paper. No testimonials, no press, no case studies; do not fabricate any.

## Product Principles

1. Proof before claims: every section leads with an outcome a recruiter can verify.
2. The page is a work sample: craft in the code and the interface is part of the argument.
3. Ten-second legibility, then depth: skimmable at the top, detailed below.
4. Personality is earned, not sprinkled: one distinctive element (Bobbie) rather than many flourishes.
5. Nothing fake: real numbers, real links, real dates.

## Accessibility & Inclusion

WCAG 2.1 AA target: contrast, visible focus, keyboard-operable tour, reduced-motion respected, no horizontal scroll at 320px and up.
