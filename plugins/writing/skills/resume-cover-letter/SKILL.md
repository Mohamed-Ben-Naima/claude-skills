---
name: resume-cover-letter
description: "Write a resume / CV or cover letter tailored to a specific role. Handles regional format differences (AU/NZ, US, UK), ATS-friendly formatting, achievement-focused bullets, and cover letter structure. Use whenever the user mentions a job application, resume, CV, cover letter, career document, applying for a role, or needs help framing their experience for a specific job."
---

# Resume and Cover Letter Writer

Produces job application documents: a resume/CV, a cover letter, or both. Every output is tailored to a specific role at a specific company — generic documents are not useful.

## Before You Start

The candidate's background is already loaded below in **Candidate Profile**, so do not re-ask for it. Gather only:

1. **Target role** — job title, company name, and the job listing or description (paste or URL)
2. **Mode** — "resume", "cover-letter", or "both" (default: ask)
3. **Angle** — which domain to lead with for this role: software, cloud/DevOps, DevSecOps, network, or cybersecurity. Infer it from the listing; confirm if unclear.

Defaults, unless the role says otherwise: **one page, single column, English, ATS-safe.** Many Tunisian employers and some international ones (e.g. Harvest, Medius) reject non-English CVs, so English is the default and French is used only when the offer or its form is French.

If the user provides a job listing, extract its key requirements and mirror its language for skills and responsibilities. Tailor every line to that role; a generic document is not useful.

---

## Candidate Profile — Mohamed Ben Naima

**Contact:** Mahdia, Tunisia · +216 25 577 542 · Medbennaima2021@gmail.com · linkedin.com/in/mohamed-ben-naima · github.com/Mohamed-Ben-Naima · portfolio mohamed-ben-naima.netlify.app · open to a 6-month PFE (end-of-studies) internship from January 2027, and to software, cloud and security roles including remote and relocation (Canada, Switzerland, Japan).

**Education:** ESPRIM Monastir, Engineering Degree in Cybersecurity and Cloud Computing, 2024–2027 (ranked first in class — state this once, in Education only). ISIMa Mahdia, BSc in Software Engineering, 2021–2024, highest honours.

**Evidence base (only these facts; nothing invented).** Pick the ones that fit the role and lead with the strongest:
- **Alfa Computers & Consulting** (freelance, accounting ERP in C#/.NET 9, clean layered architecture): owns five modules — the RBAC permission matrix (rights per module), the administration console (signed backups and verified restores), a print-template designer, the licensed installer, and an MCP server that lets an AI assistant read the accounts and suggest journal entries for an accountant to approve. Added a quality gate that blocks any commit whose build or tests fail.
- **Polymaille / Microtiss** (software engineer intern, Spring Boot + Angular garment ERP): owned the Stock and Sales modules end to end over a relational database; ran an OWASP Top 10 review before go-live and fixed the session-token handling.
- **MedLink** (ESPRIM team of 6, Agile, healthcare portal API): owns the authentication module — Keycloak backend-for-frontend, CSRF and session handling, password reset, MFA; works in the team's GitHub Actions pipeline (CodeQL, Trivy, Gitleaks, OWASP ZAP).
- **Hermes** (MERN e-commerce, moving to multi-tenant SaaS): React/TypeScript on Node/Express; built its DevSecOps pipeline in Jenkins as code (lint, secret scanning, unit and integration tests, deploy by digest).
- **Sentinel** (secured banking platform on a microservices architecture, team of 5): designed service isolation and safe inter-service communication, packaged services in Docker, built the observability layer (Prometheus, Grafana, Loki) and the SOC (Wazuh, pfSense/VLAN).
- **Data Center Casablanca** (GNS3 Tier III network): dual-provider BGP, paired cores with HSRP, pfSense HA pair, 14 VLANs behind default-deny, bastion with MFA, Zabbix/Grafana, mapped to ISO 27001.
- **HQ** (personal, multi-agent AI orchestration): TypeScript/Fastify; a coordinator agent splits work across specialised agents, every tool call through an authenticated proxy, nothing runs without human approval.
- Do **not** use the DAB project.

**Certifications:** Certified Red Team Operations Management (CRTOM, 2026), Certified LLM Security Professional (CLLMSP, 2026), Cisco CCNA 200-301 (in progress).
**Awards and leadership:** 2nd and 4th at Polytech Sousse CTF, 2nd at Insight CTF, 2nd at Clean & Green hackathon 2025, runner-up at ESPRIT Projects Ball 2025; co-founded Hunters Club (20+ members), led the Cyber & Cloud committee of DevTalents (30+ members).
**Languages:** English (professional, TOEIC upper B2), French (fluent), Arabic (native), German (basic).

### The one rule that overrides everything: no invented facts

Never invent or inflate a metric, a technology, a date, or a responsibility. Use only what is in the evidence base above. Where there is no real number, use a qualitative outcome rather than a made-up figure. If a role wants something not in the evidence base, say so and leave it out; do not paper over the gap. This rule beats any "add numbers" advice further down this skill.

### Voice and humanisation (so it does not read as AI-written)

- Plain, natural first person. No corporate filler, no breathless adjectives.
- Structure each bullet as problem → action → result.
- No em dashes anywhere. No bullets that open with a bold label like "**Impact:**".
- Lead with architecture and system-design decisions (a trade-off made, a structure chosen), not low-level bug fixes.
- Name explicit module ownership (for example the Alfa RBAC matrix), do not be vague about what he owned.
- Trim minutiae: no test counts, no "the reviewer asked me to", no incident-by-incident detail. Keep the real keywords for ATS.
- Mirror the job listing's own wording for skills and tools where he genuinely has them.

---

## Resume / CV

### Regional Format Differences

| Element | AU/NZ | US | UK |
|---------|-------|----|----|
| Name | CV or resume (both accepted) | Resume | CV |
| Length | 2-3 pages standard | 1 page (<10 years exp), 2 max | 2 pages standard |
| Photo | No | No | No |
| Date of birth / age | No | No | No |
| Nationality / visa | Include if relevant (common in AU/NZ) | No (discrimination risk) | Include visa status if applicable |
| Referees | "Available on request" is outdated — omit entirely, or list 2 if specifically requested | Omit | Omit |
| Address | City/state only (no street) | City/state only | City only |

### Section Order

Adjust based on seniority and what sells the candidate best:

**Entry-level / graduate (0-3 years):**
1. Contact details
2. Professional summary (3-4 lines)
3. Education
4. Experience (internships, part-time, volunteer)
5. Skills
6. Certifications / projects

**Mid-career (3-10 years):**
1. Contact details
2. Professional summary
3. Experience
4. Skills
5. Education
6. Certifications

**Senior / executive (10+ years):**
1. Contact details
2. Executive summary
3. Key achievements (optional highlight section)
4. Experience
5. Board / advisory roles (if applicable)
6. Education
7. Professional memberships

### Writing Achievement Bullets

Use CAR format: **Challenge** (context/problem), **Action** (what you did), **Result** (measurable outcome).

Every bullet should answer: "So what? What changed because of this?"

**Too generic:**
> Managed social media accounts and created content for the company.

**Right approach (CAR):**
> Rebuilt the social media strategy for a stagnant B2B account (Challenge), shifting from product-focused posts to customer case studies with a consistent weekly publishing schedule (Action), growing LinkedIn engagement 340% and generating 12 qualified leads in the first quarter (Result).

Prefer a measurable result where a real one exists, but never invent one (see "no invented facts" above). For this candidate most outcomes are qualitative (what was owned, built, or secured), and that is fine. Acceptable result types when the number is genuine:
- Percentages (increased, reduced, improved by X%)
- Dollar amounts (managed $X budget, saved $X, generated $X revenue)
- Volume/scale (team of X, X users, X transactions per day)
- Time (reduced from X weeks to Y days, delivered 2 weeks ahead of schedule)
- Rankings/ratings (achieved #1, rated 4.8/5, top 10%)

When the user does not have specific numbers, ask if they can estimate. If not, use qualitative results: "significantly reduced", "consistently exceeded targets", "recognised by leadership for".

### Action Verbs

Choose verbs that match the type of contribution:

| Category | Verbs |
|----------|-------|
| Leadership | Led, directed, managed, oversaw, mentored, championed, established |
| Creation | Developed, designed, built, launched, created, implemented, introduced |
| Improvement | Increased, improved, streamlined, optimised, reduced, enhanced, modernised |
| Analysis | Analysed, evaluated, assessed, identified, researched, investigated |
| Communication | Presented, negotiated, facilitated, coordinated, advised, authored |
| Technical | Engineered, automated, configured, deployed, integrated, migrated, architected |

Avoid weak openers: "Responsible for", "Helped with", "Assisted in", "Involved in", "Participated in". These describe proximity, not contribution.

### ATS-Friendly Formatting

Applicant Tracking Systems parse resumes before humans see them. Follow these rules:

- Use standard section headings: "Experience", "Education", "Skills" — not creative alternatives like "Where I've Made an Impact"
- No tables, columns, or text boxes — ATS reads left-to-right, top-to-bottom
- No headers or footers — ATS often ignores these entirely
- No images, icons, or graphics
- Use standard fonts (Calibri, Arial, Garamond, Georgia)
- File format: PDF unless the listing specifically requests .docx
- Include keywords from the job listing naturally in context — not keyword-stuffed in a hidden block
- Spell out acronyms on first use, then abbreviate: "Search Engine Optimisation (SEO)"

### What to Omit

- "References available upon request" — assumed and wastes space
- Objective statements — replaced by professional summaries years ago
- Every job since high school — include only relevant roles (last 10-15 years)
- High school education (if you have a degree)
- Hobbies/interests — unless directly relevant to the role or culture
- Salary expectations — never on the resume itself
- Reasons for leaving previous roles

### Professional Summary

3-4 lines at the top. Not a personality description — a positioning statement.

**Too vague:**
> Motivated professional with strong communication skills and a passion for technology seeking a challenging role.

**Right approach:**
> Operations manager with 8 years in logistics and supply chain for mid-market retailers. Track record of reducing fulfilment costs (cut 22% at current role) while maintaining 99.4% on-time delivery. Looking to bring that operational discipline to a high-growth e-commerce environment.

Formula: [Role identity] + [years/domain] + [signature achievement or strength] + [what you're looking for].

---

## Cover Letter

### Structure

Three to four paragraphs, under one page. Every paragraph earns its place.

**Paragraph 1 — Opening hook:**
Why this role, why now, why you noticed. Reference something specific about the company or role. No "I am writing to express my interest in the position of..." — that is the most wasted sentence in job applications.

**Paragraph 2 — Why you (the match):**
Two to three specific examples of how your experience maps to their requirements. This is not a resume summary — pick the two strongest matches and give brief context. Use language from the job listing.

**Paragraph 3 — Why this company (the fit):**
Show you have done your homework. Reference their product, mission, recent news, company culture, or a specific project. Explain why this matters to you personally. Generic flattery ("I admire your innovative approach") does not count.

**Paragraph 4 — Close:**
Clear call to action. "I'd welcome the chance to discuss how my experience in X could support your team's work on Y. I'm available for a conversation at your convenience." Confident, not desperate.

### Length and Format

- Under one page, always
- Same header/font as the resume for visual consistency
- Address to a named person where possible (check LinkedIn, company website). "Dear Hiring Manager" as a last resort
- AU/NZ: sign off with "Kind regards" (proposals/applications) or "Cheers" (if tone is casual)
- US/UK: "Sincerely" or "Kind regards"

### Tone Matching

Read the job listing and company website to calibrate tone:

| Company type | Tone | Example phrasing |
|-------------|------|-------------------|
| Startup / tech | Conversational, direct | "I've spent the last 3 years building exactly this kind of thing" |
| Corporate / enterprise | Professional, measured | "My experience in enterprise integration aligns closely with your stated objectives" |
| Government / public sector | Formal, criteria-driven | "I address each of the key selection criteria below" |
| Creative agency | Personality forward | "Your work on the X campaign is what made me pay attention" |
| Non-profit | Mission-aligned | "I've followed your work in X for several years and share your commitment to Y" |

### Common Mistakes

- **Rehashing the resume.** The cover letter adds context and personality — it does not repeat bullet points.
- **Generic openings.** "I am excited to apply for..." tells the reader nothing. Open with something specific.
- **No company reference.** If you could send the same letter to 50 companies, it is too generic.
- **Underselling or overselling.** State what you have done, factually. No "I'm the perfect candidate" and no "I know I don't have much experience but..."
- **Burying the lead.** If you have a direct connection to the role (you use their product, you know someone there, you have deep domain expertise), say it in the first line.

### Cover Letter Example

**Too generic:**
> Dear Hiring Manager,
>
> I am writing to express my interest in the Marketing Manager position. I have 5 years of marketing experience and am a strong communicator with excellent organisational skills. I believe I would be a great addition to your team.

**Right approach:**
> Hi Sarah,
>
> Your job listing mentioned you are looking for someone to rebuild the content strategy from the ground up — that is exactly what I did at Redgum Digital over the past two years, taking their blog from 400 monthly visitors to 12,000 and making it their primary lead channel.
>
> The two things that stood out in the listing were the focus on SEO-driven content and the need to work closely with the sales team on case studies. At Redgum, I built both of those functions: a keyword-driven editorial calendar that targeted commercial intent terms, and a case study pipeline where I partnered with account managers to document client wins monthly. Five of those case studies became our top-converting landing pages.
>
> I have been following [Company]'s expansion into the SME market since the product launch in October. The positioning challenge — making enterprise-grade software feel approachable for smaller teams — is something I find genuinely interesting, and it is the kind of messaging work I do best.
>
> I would welcome the chance to talk through how I could help build out your content operation. Happy to chat whenever suits.

---

## Special Circumstances

### Career changers

Lead with transferable skills, not job titles. The professional summary should bridge the gap: "Project manager transitioning from construction to software delivery — 6 years of managing cross-functional teams, budgets, and tight deadlines." Emphasise skills that translate directly.

### Employment gaps

Do not hide them or get creative with dates. If there is a gap, briefly explain it in the cover letter (caring responsibilities, study, travel, health — one sentence is enough). On the resume, list any relevant activity during the gap: freelance work, volunteering, courses, personal projects.

### Overqualified

The cover letter must address the obvious question: "Why do you want this role?" Be direct about your motivation. Scaling back for work-life balance, pivoting into a new area, genuinely interested in the company — whatever the reason, name it.

### Underqualified

Focus on adjacent experience and learning velocity. Show you have done something similar at a smaller scale or in a different context. The cover letter should acknowledge the stretch honestly while demonstrating you have closed similar gaps before.

### Multiple roles at the same company

List the company once with each role as a sub-entry showing clear progression. This signals growth and loyalty.

---

## Output Format

Default deliverable: a **one-page PDF** built from HTML, not markdown. The CV must be ATS-safe and fit on exactly one page.

Build pattern (adapt to the environment; do not ship a fixed script):
1. Generate a single self-contained HTML page: standard font (Arial), navy section headings with a thin bottom border, single column, standard headings (Summary, Education, Experience, Projects, Skills, Certifications). No tables, columns, icons, images, headers or footers.
2. Render it to A4 PDF with headless Chromium / Playwright (`print_background`, `prefer_css_page_size`). Tune the base font size (roughly 9.0–9.3pt) so it fills one page without spilling to a second.
3. Verify before delivering: `pdfinfo` to confirm **Pages: 1**, and `pdftotext -layout` to confirm every keyword and heading extracts cleanly and in order (that is what the ATS reads). Fix and re-render if it spills over or a section is missing.
4. Deliver the PDF to the user. Keep the HTML so later tweaks are one small edit and re-render, not a rebuild.

Where PDF rendering is not available in the environment, fall back to clean markdown and say so.

For "both" mode, deliver the resume first, then the cover letter, in the same response. The cover letter uses the same header and font as the CV, stays under one page, follows the four-paragraph structure above, and adds context rather than repeating CV bullets.
