# Job Search & LinkedIn Agent Kit

A bilingual kit (English + Bahasa Indonesia) for an AI agent that helps you search for jobs and update your LinkedIn profile. Works in Muse and in Grok Bot.

## English

This skill helps you land more jobs. It finds and verifies openings that are still live, tailors applications in your voice, and upgrades your LinkedIn so recruiters can find you — while you stay in control of every send.

Nothing is submitted, posted, or published without your approval, and the agent must never invent achievements, titles, dates, or metrics.

### Files

- `SOUL.md` — identity, values, voice, hard rules, full workflow, memory guidance, and an example first message. Use this as the persona or long instructions.
- `system-prompt.md` — a shorter, copy-paste system prompt that works on its own, plus starter prompts you can paste.
- `SKILL.md` — an Agent Skills-format playbook (`name: job-search-linkedin`). Install it by dropping this folder or `SKILL.md` into the platform's skills directory, or by pasting it as a skill.
- `id/` — Bahasa Indonesia versions of the same files (`id/SOUL.md`, `id/system-prompt.md`, `id/SKILL.md` with `name: job-search-linkedin-id`, and `id/README.md`).

### How to use it

**In Muse:** paste `SOUL.md` into the agent's persona or instructions. If the product also has a system-prompt field, paste the prompt block from `system-prompt.md` (the part between the horizontal rules). Install the skill by dropping this folder or `SKILL.md` into the skills directory, or paste it as a skill. Attach your resume, then start with one of the starter prompts.

**In Grok Bot:** paste `SOUL.md` as the bot's instructions or soul, and optionally paste the prompt block from `system-prompt.md` as the system prompt. Install `SKILL.md` by dropping it into the skills directory or pasting it as a skill. Attach your resume in the first message, then use a starter prompt such as "Audit my LinkedIn: [url]" or "Find me remote [role] roles."

Do not put passwords or session cookies in these files or in chat. Leave Open to Work and live profile edits untouched until you give an explicit yes for that change.

## Bahasa Indonesia

Skill ini bantu kamu dapat lebih banyak peluang kerja. Agennya mencari dan memverifikasi lowongan yang masih buka, merancang lamaran dengan gaya bahasamu, dan merapikan profil LinkedIn supaya lebih mudah ditemukan rekruter — tetap kamu yang putuskan setiap kali ada yang mau dikirim.

Tidak ada yang di-submit, diposting, atau diterbitkan tanpa persetujuanmu, dan agen tidak boleh mengarang pencapaian, jabatan, tanggal, atau angka.

### File

- `SOUL.md` — identitas, nilai, gaya bicara, aturan keras, alur lengkap, panduan memori, dan contoh pesan pertama. Pakai sebagai persona atau instruksi panjang. Versi Bahasa Indonesia: `id/SOUL.md`.
- `system-prompt.md` — system prompt yang lebih singkat, bisa ditempel sendiri, plus prompt pemula. Versi Bahasa Indonesia: `id/system-prompt.md`.
- `SKILL.md` — playbook berformat Agent Skill (`name: job-search-linkedin`). Instal dengan memasukkan folder ini atau `SKILL.md` ke direktori skills platform, atau tempel sebagai skill. Versi Bahasa Indonesia: `id/SKILL.md` (`name: job-search-linkedin-id`).
- `id/` — folder lengkap versi Bahasa Indonesia, termasuk `id/README.md`.

### Cara pakai

**Di Muse:** tempel `SOUL.md` (atau `id/SOUL.md`) ke persona atau instruksi agen. Kalau ada field system prompt, tempel blok prompt dari `system-prompt.md` atau `id/system-prompt.md` (bagian di antara garis horizontal). Instal skill-nya dengan memasukkan folder atau file `SKILL.md` / `id/SKILL.md` ke direktori skills, atau tempel sebagai skill. Lampirkan resume, lalu mulai dengan salah satu prompt pemula.

**Di Grok Bot:** tempel `SOUL.md` atau `id/SOUL.md` sebagai instruksi atau soul bot, dan boleh tempel blok prompt dari `system-prompt.md` atau `id/system-prompt.md` sebagai system prompt. Instal skill dengan memasukkan `SKILL.md` atau `id/SKILL.md` ke direktori skills, atau tempel sebagai skill. Lampirkan resume di pesan pertama, lalu pakai prompt pemula, misalnya "Audit LinkedIn-ku: [url]" atau "Carikan lowongan [peran] remote."

Jangan taruh password atau cookie sesi di file-file ini atau di chat. Biarkan Open to Work dan suntingan profil live utuh sampai kamu memberi ya yang tegas untuk perubahan itu.
