---
name: job-search-linkedin
description: Use when finding job openings, tailoring applications, or auditing, rewriting, and applying LinkedIn profile edits.
---

# Job search and LinkedIn updates

Follow this playbook whenever you help someone find roles, draft applications, or improve a LinkedIn profile. Stay consistent with this kit's SOUL and system prompt: honest, consent-first, and platform-neutral. Use web search, browsing, file reading, drafting, and screenshots — do not depend on one product's tool names. If the user only wants a shortlist, drafts, or an audit today, do that and do not force the rest.

## Hard rules

- Never invent professional achievements, employers, job titles, qualifications, dates, or performance metrics.
- Mark unknowns as `[ASK]` and resolve them before publishing that section.
- Do not change employment dates, job titles, employer names, privacy settings, or Open to Work visibility without explicit approval. Leave Open to Work untouched unless the user explicitly says you may change it.
- Do not send messages, apply to jobs, publish posts, or contact recruiters without approval for that specific item. A yes for one action does not cover the next.
- Do not reveal confidential business information, or anything the user said must stay off the public profile (confidential clients, paid promotions, side businesses).
- Do not replace photos or publish generated imagery without approval.
- Store logins only in a secure vault or password manager, never in chat or files.
- Keep LinkedIn's "notify network" (or equivalent) toggle off unless the user asks to announce updates.

## 1. Onboarding

Ask only for what is missing, all at once. Checklist:

- Resume or CV (a file is best)
- LinkedIn profile URL
- Portfolio or personal site, and any public work links they want used
- Target roles and seniority
- Locations, remote / hybrid / on-site preference, and whether they would relocate
- Salary floor and currency, if they have one
- Languages they work in
- Deal-breakers (companies, industries, visa needs, hours, travel)
- Things never to mention publicly
- Whether Open to Work may be touched at all (default: no)
- A preferred public contact email, if they want one on the profile

Acknowledge what you already have so they do not repeat themselves. Save confirmed preferences and rules.

## 2. Job search, verification, and shortlist

1. Search major boards, relevant niche boards (for example CryptoJobsList or Web3.career in Web3), company career pages, and official ATS listings.
2. Open each candidate link and verify it is still live. Drop expired, 404, or aggregator-only listings you cannot confirm on an official page.
3. Score fit against target role, seniority, location or remote preference, salary floor, and deal-breakers.
4. Deduplicate the same role when it appears on several boards.
5. Output a shortlist in this table. Do not apply or sign up while searching.

| # | Company | Role | Location / remote | Pay (if listed) | Link | Why it fits | Red flags |
|---|---------|------|-------------------|-----------------|------|-------------|-----------|
| 1 | | | | | | | |

6. Briefly note why other listings were dropped (expired, wrong location, wrong function, unofficial page).
7. Offer an optional recurring scan, and skip roles already shown.

## 3. Application drafts

For each role the user picks:

1. Draft a tailored cover note, Easy Apply answers, and/or a recruiter message in their voice, using only facts from their resume, profile, and what they have told you.
2. Use `[ASK]` for anything you would have to invent.
3. Show the draft and wait. Never submit or send without explicit approval for that specific role.
4. After they confirm a submission, log it (see Logging below).

Draft shape (adapt, do not pad): a one-line hook tied to the role, two or three true proof points, a clear close, and `[ASK]` for any gap.

## 4. LinkedIn audit, rewrite, then apply

**Audit.** Snapshot the current profile before editing: headline, About, experience, education, skills, Featured, Projects, recommendations, contact info, custom URL, and every language version. Do not edit yet.

**Rewrite.** Produce copy-ready materials and show them for review:

- Several headline options, with a recommended pick, within LinkedIn's character limit
- A concise About and a more detailed About, in their voice
- Stronger experience bullets; titles, employers, and dates stay unchanged unless they approve a correction
- Skills to remove (generic or outdated), skills to add (role keywords), and five to pin
- Featured, Projects, Education activities, and a custom URL suggestion — only from real work and real links they gave you
- A short audit of positioning, credibility, completeness, and discoverability, plus a simple plan

Write every language version. Mark unknowns as `[ASK]`. Do not touch the live profile until they approve.

**Apply approved edits**, one section at a time:

1. Keep "notify network" off.
2. Update every language version of that section before moving on.
3. Do not touch Open to Work, privacy, photos, or the banner unless they approved that specific change.
4. After each save, verify by re-reading the section or taking a screenshot.
5. Report what landed, what was left alone, and what is left to do.
6. If a custom URL change is approved, remind them to update old links on their CV and portfolio.

## 5. Logging

Keep a running log (in memory or a working file, never with passwords):

- Preferences, public-mention rules, and whether Open to Work may be touched
- Roles already shown, with enough detail to avoid repeats
- Drafts prepared, and applications submitted: company, role, date, link, status (drafted, applied, heard back, rejected, offer)
- Approved profile copy
- Outstanding `[ASK]` items and any dates or titles still waiting

## Output templates

**After a shortlist.** A one-line target reminder, the table above, a short "dropped and why" note, and a question about which roles to draft next. State clearly that nothing was applied.

**After a rewrite.** Status: draft, nothing applied yet. Then headlines, About, experience, skills, Featured/Projects, remaining `[ASK]` items, and the proposed apply order.

**After a live edit.** Section name, languages updated, notify-network still off, what changed, what was left alone, verification method (re-read or screenshot), and the next section awaiting approval.

## When to stop and hand to the user

- The site asks for a password, a captcha, or a two-factor code
- An unexpected confirmation or permission screen appears
- They have not yet approved a specific send, submit, post, or live edit
- The change would touch Open to Work, privacy, a photo, the banner, or the custom URL without a yes
- You would have to invent a fact, date, title, employer, or metric — use `[ASK]` instead
- The platform is rate-limiting or blocking further actions
