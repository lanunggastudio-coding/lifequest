# LifeQuest

**Interactive Life & Career Navigation Platform** by [Medinovatech](https://medinovatech.com)

Live: https://lifequest.medinovatech.com

## What is LifeQuest?

LifeQuest helps Indonesian high school students, university freshmen, and young professionals discover their purpose, design a meaningful career path, and build the skills needed to get there.

Unlike traditional tryout/bank-soal platforms, LifeQuest is a **Life & Career Navigation Platform** — starting from *who you want to help*, not which major to pick.

## MVP Features (v1.0)

- **RIASEC Assessment** — 36 questions, 6 dimensions (Realistic/Investigative/Artistic/Social/Enterprising/Conventional), normalized 0–100
- **Archetype Generation** — 12 unique archetypes from top-2 RIASEC codes (e.g. IS → Sang Penyembuh, IE → Sang Pendiri Visioner)
- **Mission Builder** — Target (who) + Problem (what) + Approach (how) → personalized mission statement
- **Career Explorer** — 30 careers across 5 categories, match scored by RIASEC+mission alignment
- **Results Dashboard** — radar chart, top 5 careers, skill roadmap, shareable mission statement

## Career Score System

| Score | Meaning |
|-------|---------|
| **AI Risk** | Probability of significant automation by 2035. Lower = safer. |
| **Growth** | Projected demand over next 10 years. Higher = more opportunities. |
| **Human Advantage** | How much empathy, judgment, creativity matter. Higher = harder to automate. |
| **Impact** | Social/economic impact potential. |

## Tech Stack

- Vanilla HTML/CSS/JS (single-file SPA, zero dependencies)
- localStorage persistence (no login required)
- Figtree font (Google Fonts)
- nginx on Ubuntu VPS, SSL via acme.sh/Let's Encrypt

## Roadmap

| Phase | Features | Timeline |
|-------|----------|----------|
| v1.0 MVP | RIASEC + Mission Builder + Career Explorer | Q3 2026 |
| v1.1 | Portfolio Builder + Project Templates | Q4 2026 |
| v1.2 | Learning Path Generator + Course Links | Q1 2027 |
| v2.0 | UTBK/SNBT Admission Simulator + IRT Scoring | Q2 2027 |
| v2.5 | Mentor Matchmaking + Community Forum | Q3 2027 |
| v3.0 | AI-Adaptive Recommendations + 1000 Careers | Q4 2027 |

## RIASEC Dimensions

| Code | Bahasa Indonesia | Description |
|------|-----------------|-------------|
| R | Realistis | Practical, technical, hands-on |
| I | Investigatif | Analytical, scientific, research |
| A | Artistik | Creative, expressive, design |
| S | Sosial | Helping, teaching, collaborative |
| E | Wirausaha | Leading, business, persuasive |
| C | Konvensional | Organized, systematic, data-driven |

---

Made with purpose by **Lanungga Studio** · [medinovatech.com](https://medinovatech.com)
