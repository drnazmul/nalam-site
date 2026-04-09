# Dr. Nazmul Alam — Business & Personal Brand Roadmap
## Last Updated: April 2026

---

# PART 1: VISION & POSITIONING

## Brand Identity
- **Name:** Dr. Nazmul Alam
- **Domain:** nalam.ca
- **Email:** nazmul@nalam.ca
- **Tagline:** LC-MS Expert | Green Analytical Chemistry
- **LinkedIn:** linkedin.com/in/nazmul-alam
- **YouTube:** @nazmulalamphd
- **ORCID:** 0000-0002-6442-3569

## Brand Color Palette
- Background: Warm cream (#FAF7F2)
- Primary accent: Terracotta/burnt orange (#D4632A)
- Secondary accent: Sage green (#6B8F71)
- Tertiary accent: Gold (#C69B3C)
- Text: Dark (#1A1A1A)
- Muted text: (#8C8478)
- Cards: White (#FFFFFF) on cream
- No blue anywhere. Editorial, modern, Carrd-inspired feel.

## Core Positioning
I bridge the gap between academic chemistry and industrial reality. 14 years across government, cosmeceuticals, and drug discovery. Practical insights, real data, and honest advice for chemists at every career stage.

## Corrected Career Timeline (use everywhere)
1. **NADES Research Collaborator** — Sunway University & USM, Malaysia (Current)
2. **Scientist** — Dalriada Drug Discovery, Canada
3. **LC-MS/MS Scientist | Project Manager** — Deciem (The Ordinary), Canada (Wrike implementation, Wrike Elite 100 Award 2024, raw material qualification)
4. **Postdoctoral Researcher** — Ontario Ministry of Environment, Canada
5. **PhD Analytical Chemistry** — University of Waterloo, Canada (under Prof. Janusz Pawliszyn, inventor of SPME)

## Expertise Tags (for landing page and LinkedIn)
LC-MS/MS, Green Analytical Chemistry, SPME, Mass Spectrometry, NADES Research, Method Validation (ICH), Raw Material Qualification, FDA / Health Canada / cGMP, Project Management, Cosmeceutical Analysis

---

# PART 2: TECH STACK (all free)

## Overview
| Tool | Purpose | Cost |
|------|---------|------|
| nalam.ca | Primary domain, personal brand hub | Already owned (renew before May 19, 2026!) |
| Cloudflare | DNS management, email routing, website hosting (Pages) | Free |
| Kit (ConvertKit) | Email list, form capture, PDF delivery | Free (up to 10,000 subscribers) |
| Cloudflare Pages | Static site hosting for landing page | Free |
| Gmail | Email backend (send as nazmul@nalam.ca via Cloudflare routing) | Free |
| Calendly | Meeting scheduling (free tier) | Free |
| Google Sheets | CRM / lead tracking | Free |
| Google Drive | PDF hosting for guide delivery | Free |
| Gumroad | Paid product sales (future) | Free until first sale, then 10% per transaction |
| Zoom / Google Meet | Video calls | Free |

## Email Setup (Completed)
- Cloudflare Email Routing: hello@nalam.ca and nazmul@nalam.ca forward to Gmail
- Gmail "Send As": configured to send from nazmul@nalam.ca via smtp.gmail.com with App Password
- SPF record in Cloudflare DNS: `v=spf1 include:_spf.mx.cloudflare.net include:_spf.google.com ~all`
- DMARC record in Cloudflare DNS: `v=DMARC1; p=none; rua=mailto:nazmul@nalam.ca` (Name: _dmarc)
- Note: "via gmail.com" label will show in recipients' inbox. This is a cosmetic limitation of the free setup. Goes away only with Google Workspace ($6/mo) or Zoho Mail.

## Landing Page Setup
- HTML file hosted on Cloudflare Pages (not Workers)
- Upload as a folder (not loose file) or zip to Cloudflare Pages
- To update: go to Workers & Pages > Pages tab > your project > "Create new deployment" > upload updated folder
- Kit form embedded in HTML via form action URL
- Photo: save as photo.jpg in same folder as index.html, replace avatar div with img tag

## Kit Form Setup
1. Go to kit.com > Grow > Landing Pages & Forms
2. Create New > Form > Inline style
3. In Settings, find Form Action URL (looks like: `https://app.kit.com/forms/XXXXXXX/subscriptions`)
4. Paste this URL into index.html where it says YOUR_FORM_ID
5. Turn OFF double opt-in: Settings > Subscriber Settings > disable "Require email confirmation"
6. Set up incentive email in the form settings to deliver the PDF download link
7. Kit sending email: nazmul@nalam.ca (verify in Kit account settings)

## Calendly Setup
- Account email: nazmulche@gmail.com (to match Google Calendar)
- Display name: Dr. Nazmul Alam
- Reply-to email: nazmul@nalam.ca
- Event type: 30-minute Career Strategy Call
- Do NOT put Calendly link on public landing page (see Part 5 for placement strategy)

## Domain Renewal Warning
nalam.ca expires May 19, 2026. Auto-renew is OFF. Turn it on immediately in Namecheap or manually renew. If this domain expires, everything breaks.

---

# PART 3: CONTENT STRATEGY

## LinkedIn Content Pillars
1. **Green Analytical Techniques (40%)** — SPME, NADES, green metrics, method development with sustainability lens
2. **Industry-Academia Bridge (25%)** — career insights, regulatory perspectives, what industry needs vs. what academia produces
3. **Sustainable Chemistry Education (20%)** — teaching, mentorship, making sustainability quantitative
4. **Malaysian/ASEAN Context (15%)** — palm oil sustainability, green chemistry talent gap, regional opportunities

## Posting Schedule
- 3-4 posts per week
- Best days: Tuesday through Thursday
- Best time: 8-11 AM target audience timezone
- Never post more than once per day, minimum 12 hours between posts
- Tuesday: 20% higher engagement than Friday

## Content Rules (2026 LinkedIn Guidelines)
- Hook must fit within 210 characters ("See More" cutoff)
- No banned words (see full list in LinkedIn project instructions)
- No em dashes (use commas, periods, colons)
- No markdown formatting (no asterisks, no ## headers)
- No rhetorical questions
- No semicolons
- 0-3 hashtags at end, separated by line break
- End with specific, answerable question (not "What do you think?")
- No engagement bait
- External links in first comment only (reduce reach 30-60% if in post body)
- Respond to every comment within first 60 minutes (Golden Hour)
- Add follow-up comment 8 hours after posting to reactivate distribution

## Next LinkedIn Post (Ready to Publish)
Topic: PhD resume problem (highest emotional pull from career guide)
Hook: "45% of Global 500 employers rate the average PhD resume as 'far below average.'"
Full draft saved in conversation history. Post on Tuesday or Wednesday, 8-10 AM.

## Future Content from Career Guide (6 weeks of posts)
Each section of the career guide becomes a standalone LinkedIn post:
1. PhD resume transformation (with translation table)
2. Salary comparison: Canada vs. the world
3. A day in the life: pharma QC vs. food vs. cosmetics vs. environmental
4. The 5-channel job search strategy
5. Certifications worth pursuing at each career stage
6. When chemists leave the bench (and where they go)

---

# PART 4: REVENUE ASSETS (ranked by demand)

## Asset 1: LC-MS/MS Method Development Training (HIGHEST DEMAND)
- **Market evidence:** Companies pay US$500-2,000 per seat. CfPIE has waitlists. Phenomenex charges €510/person for one-day seminars. University of Tartu MOOC attracted 999 participants from 95 countries.
- **Your edge:** LC-MS/MS at Deciem for cosmeceutical products. Nobody teaches from the cosmeceutical/personal care perspective.
- **Format:** Video course (screen recordings over slides and chromatograms)
- **Price:** US$149-249 individual, US$499-999 team licenses
- **Platform:** Gumroad
- **Build timeline:** Month 3-5 (after validating with LinkedIn content and email list)
- **Pre-work:** Post LC-MS/MS tips on LinkedIn months 1-3. Track which subtopics get most engagement. Those become course modules.

## Asset 2: Raw Material Qualification Consulting (SECOND HIGHEST)
- **Market evidence:** Global cosmetic raw material market: US$39.8B in 2026, projected US$65.2B by 2035. Regulatory complexity intensifying globally.
- **Your edge:** Deciem experience + Malaysia location (same timezone as Asian suppliers) + green chemistry knowledge
- **Target clients:** Small/mid-size cosmetic brands, new brands sourcing from Asia, contract manufacturers
- **Deliverables:** Raw material qualification SOP templates, supplier assessment checklists, CoA review, consulting calls
- **Price:** $150-250/hour consulting
- **Build timeline:** Opportunistic from month 1. Do not actively market. Pursue when conversations arise naturally.

## Asset 3: Green Analytical Chemistry Reference Guide (MODERATE)
- **Role:** Lead magnet and authority builder, not primary revenue product
- **Format:** PDF reference guide compiled from LinkedIn posts over 6 months
- **Price:** $49-99 (or free as lead magnet)
- **Build timeline:** Month 6+ (compile existing content)

## Asset 4: LinkedIn Content Engine (FOUNDATIONAL)
- **Role:** Powers everything else. Zero direct revenue. Essential infrastructure.
- **Action:** Post consistently. Build audience. Drive to Kit landing page.

## Career Coaching Products (validated by viral post)
- **Tier 1 (C$29-49):** "PhD-to-Industry Resume Kit" — templates, before/after examples, translation table workbook, video walkthrough. Build once, sells repeatedly.
- **Tier 2 (C$149-249):** 90-minute "Resume and Interview Intensive" — live resume review, top 3 bullet rewrites, mock STAR interview. Start with this. Zero upfront creation needed.
- **Tier 3 (C$499-799):** 4-week "Industry Transition Program" — weekly 1-on-1 calls covering resume, job search, interview, salary negotiation. Small cohort (5-8 people). Launch after Tier 2 testimonials.

---

# PART 5: THE 10 FREE CALLS SYSTEM

## Preparation
Create a Google Sheet with columns:
- Name
- Degree Level
- Country
- Current Situation (their one-sentence DM)
- Date of Call
- Top 3 Pain Points (fill after call)
- Willingness to Pay (gut read: high/medium/low)
- Follow-up Action

## 30-Minute Call Structure
- **Minutes 1-5:** Ask them to describe their situation. Where are they? What have they tried? What is the blocker?
- **Minutes 5-15:** Review their resume or LinkedIn profile (ask them to send before the call). Give 3 specific, actionable fixes on the spot.
- **Minutes 15-25:** Walk through job search strategy. Identify which of the 5 channels they are missing. Give a 2-week action plan.
- **Minutes 25-30:** Two closing questions:
  1. "What would have made this conversation even more useful?"
  2. "If I offered a deeper 4-week program covering resume rewrite, interview prep, and job search strategy, is this something you'd invest in?"
- Do not pitch. Do not name a price. Listen. Write it down after the call.

## Calendly Link Placement (Important)
- Do NOT put Calendly on public landing page (attracts random time-wasters)
- Place in Kit incentive email after PDF download link: "Want personalized guidance? Book a free 30-min call: [Calendly link]"
- Place in LinkedIn comment replies to qualified people (manually, case by case)

## Post-Call Sequence
- **Week 1-2:** Complete all 10 calls. Fill tracking spreadsheet.
- **Week 3:** Review data. Find the pattern. Which pain point dominated? Which segment showed highest urgency? How many said yes to "would you invest?"
- **Week 4:** Build first paid offer based on data. Start with Tier 2 (90-minute Intensive, C$149-249). Sell to the 10 call participants first.
- **Week 5-6:** Collect 2-3 testimonials. Add to landing page. Write LinkedIn post with anonymized success story. Drive traffic to landing page.

---

# PART 6: EMAIL LIST GROWTH STRATEGY

## Current Lead Magnet
The Chemistry Career Guide (40-page PDF) — salary data, 4 sectors compared, PhD-to-industry roadmap.

## How It Works
1. LinkedIn post drives traffic to nalam.ca
2. Visitor enters email in Kit form on landing page
3. Kit captures email and sends incentive email with PDF download link
4. Subscriber is now on your permanent email list
5. Future broadcasts reach all subscribers at once

## Scaling the Resource Library
**Now (Approach A):** One guide. Promote it. Collect emails. Welcome email delivers Chemistry Career Guide PDF.

**Later with 2-3 guides (Approach B):** Change landing page to general offer: "Join 500+ chemists getting free resources on LC-MS/MS, green chemistry, and career strategy." Welcome email delivers links to all guides:
1. The Chemistry Career Guide
2. LC-MS/MS Method Development Cheat Sheet
3. Green Metrics Quick Reference

Form URL and landing page stay the same forever. Only the welcome email evolves.

---

# PART 7: LINKEDIN COMMENT REPLY GUIDELINES

## Principles
- Respond within 60 minutes (Golden Hour)
- Add value in every reply (no "thanks!" or single-word responses)
- Reference specific sections of the guide when relevant
- Offer Calendly link only to qualified individuals, not publicly
- If someone asks for the download link, reply with nalam.ca directly (people miss the first comment)

## Reply Templates by Comment Type

**Academic/Faculty commenting:**
Thank them. Reference a specific section relevant to their students. Offer to answer student questions.

**Graduate/Student commenting:**
Give 1-2 specific, actionable next steps based on their degree level and location. Reference relevant guide sections.

**"How do I download?" comments:**
Reply with nalam.ca link directly. Note the specific section most relevant to them.

**"I wish this existed for [other field]" comments:**
Acknowledge the demand signal. Note the overlap with your guide. File for future product ideas. Do not act on it now.

**PhD/Postdoc in transition:**
Provide specific advice. Reference resume translation table. Offer Calendly link if they seem serious and qualified.

---

# PART 8: WHAT NOT TO DO

- Do not build a course before validating with live calls
- Do not build a community or membership (no audience size yet)
- Do not launch a full multi-page website (one landing page is enough)
- Do not announce a business publicly on LinkedIn (academic career protection)
- Do not seek a decorative corporate title (CSO at a company you don't work for damages credibility)
- Do not use a Gmail address on professional pages (use nazmul@nalam.ca)
- Do not add a CRM until you have 100+ paid customers
- Do not spread across multiple identities at once (LC-MS expert first, other offerings later)
- Do not put Calendly link on public landing page
- Do not spend time on platform shopping instead of creating content and responding to leads

---

# PART 9: PRIORITY TIMELINE

## This Week
- [x] Email setup (Cloudflare routing + Gmail Send As)
- [ ] Landing page live on nalam.ca via Cloudflare Pages
- [ ] Kit form connected with incentive email delivering PDF
- [ ] Respond to all LinkedIn comments within 60 minutes
- [ ] Send Calendly link to meeting request via DM
- [ ] Turn on auto-renew for nalam.ca domain
- [ ] Add SPF and DMARC records in Cloudflare DNS

## Week 2
- [ ] Complete first free career strategy call
- [ ] Post PhD resume LinkedIn post (draft ready)
- [ ] Update LinkedIn Featured section with nalam.ca link
- [ ] Update LinkedIn About section with nalam.ca link

## Week 3-4
- [ ] Complete all 10 free calls
- [ ] Fill tracking spreadsheet
- [ ] Review patterns from calls
- [ ] Build first paid offer (Tier 2: 90-minute Intensive)
- [ ] Collect 2-3 testimonials

## Month 2-3
- [ ] Begin posting LC-MS/MS tips on LinkedIn
- [ ] Create LC-MS/MS Method Development Cheat Sheet (one-page PDF lead magnet)
- [ ] Add to Kit welcome email alongside career guide
- [ ] Track which LC-MS/MS subtopics get most engagement

## Month 3-5
- [ ] Build LC-MS/MS course module by module (3-5 video modules)
- [ ] Set up Gumroad product page
- [ ] Launch course to email list
- [ ] Price: US$149-249 individual, US$499-999 team

## Month 6+
- [ ] Compile LinkedIn green chemistry posts into reference guide
- [ ] Switch landing page to Approach B (resource library model)
- [ ] Evaluate raw material qualification consulting demand
- [ ] Consider "Physical Sciences Career Guide" if chemistry version reaches 500+ downloads

---

# PART 10: KEY METRICS TO TRACK

| Metric | Where to Check | Target (Month 1) | Target (Month 3) |
|--------|---------------|-------------------|-------------------|
| Email subscribers | Kit dashboard | 50 | 300 |
| LinkedIn post impressions | LinkedIn analytics | 5,000/post | 10,000/post |
| Free calls completed | Google Sheet | 10 | 15 |
| Paid clients | Google Sheet | 0 | 5 |
| Revenue | Gumroad/Stripe | $0 | C$500-1,000 |
| Landing page visits | Cloudflare Pages analytics | 100 | 500 |

---

# PART 11: FUTURE SIGNALS TO WATCH

- **Parisa Rouzbazar's comment:** Market for career transition extends beyond chemistry. "Physical Sciences Career Guide" covering physics, materials science, and chemistry = larger addressable audience. Act when chemistry guide hits 500+ downloads.
- **Bob Stanley (Head of Faculty):** Academic connections sharing your guide with students = potential for university workshop or guest lecture partnerships.
- **Raw material sourcing conversations:** Monitor LinkedIn DMs for brands asking about ingredient sourcing from Asia. Each conversation validates Asset 2 (consulting).
- **LC-MS/MS engagement:** Track which subtopics get saved/shared most on LinkedIn. These become course modules.

---

*This document is the single source of truth for the nalam.ca business system. Update it as decisions are made and milestones are reached.*
