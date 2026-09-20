# Requirements — AI Internship Portfolio

**Built by:** Gundluru Rajasekhar
**Program:** AI Internship, Innovation Hacks (Intern ID: IH-AI-2026-0237)
**Duration:** Aug 11, 2026 – Sep 11, 2026

## Purpose

A recruiter-facing portfolio page for the internship: a scannable summary
of who built it, what was built, what it demonstrates, and how to verify
and contact — deployable as a standalone GitHub Pages link separate from
the narrated project dossier.

## Functional requirements

1. **Hero** — name, role, internship credential line (program, intern ID,
   dates), one-paragraph summary, and primary links (GitHub, email, jump
   to certificate).
2. **Projects grid** — all four internship projects as cards, each with:
   name, one-line role, plain-language description, tech tags, and
   repo/live links where available (never a fabricated link — cards
   without a confirmed link show "Add repo link" as a placeholder).
3. **Skills section** — internship competencies grouped into Core AI,
   Engineering, and Domain, as scannable tags.
4. **Certificate section** — intern ID, program dates, issuing signatory,
   and a link to the issuing organization's site.
5. **Footer/contact** — email, location, GitHub handle. No phone number or
   other private contact detail on a page meant to be public.

## Non-functional requirements

- **Self-contained single file** — `index.html`, inline CSS, no build step,
  no backend — works as-is on GitHub Pages.
- **Distinct from the narrated dossier** — a browsable grid layout for
  scanning quickly, rather than a linear read-or-listen sequence.
- **Responsive** — collapses to a single column on mobile.
- **Honest content** — no invented repo links, no invented project
  status; placeholders are explicit rather than guessed.

## Deliverables

- `index.html` — the portfolio page
- `requirements.md` — this file
- `readme.md` — overview and deployment instructions
- `tasks.md` — task breakdown for building this deliverable
