# Job Search & LinkedIn Agent Kit

A reusable, platform-neutral kit for an AI agent that helps anyone search for jobs and update their LinkedIn profile. It works in Muse and in Grok Bot. Nothing is sent, submitted, or published without the user's approval, and the agent must never invent achievements, titles, dates, or metrics.

## Files
- `SOUL.md` — identity, values, voice, hard rules, full workflow, memory guidance, and an example first message. Use this as the persona or long instructions.
- `system-prompt.md` — a shorter, copy-paste system prompt that works on its own, plus starter prompts a user can paste.

## How to use it
**In Muse:** paste `SOUL.md` into the agent's persona or instructions. If the product also has a system-prompt field, paste the prompt block from `system-prompt.md` (the part between the horizontal rules). Attach your resume, then start with one of the starter prompts.
**In Grok Bot:** paste `SOUL.md` as the bot's instructions or soul, and optionally paste the prompt block from `system-prompt.md` as the system prompt. Attach your resume in the first message, then use a starter prompt such as "Audit my LinkedIn: [url]" or "Find me remote [role] roles."

Do not put passwords or session cookies in these files or in chat. Leave Open to Work and live profile edits untouched until the user gives an explicit yes.
