# FL-01: Workflow Audit

**Name:** Ali
**Phase:** Setup
**Date:** July 2026

---

## 1. Task Classification

| # | Task | Classification | Rationale |
|---|---|---|---|
| 1 | Writing Express route handlers | Collaborate with AI | Boilerplate-heavy, but auth/logic edge cases need my judgment |
| 2 | Debugging race conditions (e.g. authUser null init) | Just me | Requires understanding runtime state, AI guesses wrong without full context |
| 3 | Writing TanStack Query hooks (useQuery/useMutation) | Delegate with review | Pattern is repetitive, I verify caching/invalidation logic after |
| 4 | CORS/env config debugging | Collaborate with AI | Fast to search but I need to understand *why* it broke, not just paste fix |
| 5 | LinkedIn captions about my learning journey | Delegate with review | AI drafts fast, but I edit tone — must sound like me, not generic AI voice |
| 6 | Sakoon Al Quran video captions | Collaborate with AI | Structure is fixed (hook→arc→CTA) but emotional tone is something I calibrate |
| 7 | NTU exam prep (networking, cybersecurity concepts) | Just me | Understanding > memorizing; using AI to explain everything atrophies recall for exams |
| 8 | Writing README/documentation for projects | Delegate with review | Low-stakes, structure is standard, I just verify accuracy |
| 9 | Deciding architecture for new feature (e.g. LMS auth flow) | Collaborate with AI | I want a second opinion but final call is mine — my system, my constraints |
| 10 | Formatting/cleaning commit messages to Conventional Commits | Fully automate | Zero judgment needed, purely mechanical |
| 11 | Researching a new library/API before using it | Delegate with review | AI summarizes fast, I verify against actual docs before trusting |
| 12 | Reviewing my own code for bugs before a PR | Collaborate with AI | Second pair of eyes catches things I miss, but I decide what's a real issue |
| 13 | Translating technical concepts into Urdu-friendly explanations | Just me | Requires cultural/linguistic judgment AI often gets stiff or wrong |
| 14 | Scheduling/posting Instagram content (7-9PM PKT slot) | Fully automate | Pure logistics, no judgment |
| 15 | Deciding what to learn next (DSA vs ML vs more MERN) | Just me | Strategic, personal — outsourcing this defeats the point of the audit |

---

## 2. Toolkit Setup

- [x] Claude account
- [x] ChatGPT account
- [x] Anthropic Academy — enrolled in *AI Fluency: Framework & Foundations*, Module 1 complete

*(Screenshots attached separately: Academy progress, Claude Project configuration)*

---

## 3. Claude Project — Custom Instructions

```
I'm Ali, a 2nd-4th semester BSCS student at NTU Faisalabad, interning at
FlyRank on the MERN stack (MongoDB, Express, React, Node, TypeScript,
TanStack Query, session-based auth).

Current goals: mastering full-stack MERN → DSA → ML, aiming for a
high-level software engineering career. I also run a Quran website and
an Islamic content Instagram page (Sakoon Al Quran).

Tone: direct, dense, expert-level. No filler, no unsolicited safety
lectures. Code should be production-ready, clean, follow SOLID/DRY.
I'm an active learner — explain the "why" briefly when it's non-obvious,
skip it when it's routine.
```

---

## 4. Three Target Tasks (for FL-02 through FL-04)

| Task | Success Definition |
|---|---|
| Writing TanStack Query hooks | AI-generated hook works with zero manual edits to query keys/invalidation logic on first try, 80%+ of the time |
| LinkedIn caption drafting | Draft requires ≤2 rounds of edits before it sounds authentically like me (not generic AI tone) |
| Debugging race conditions / auth bugs | AI correctly identifies root cause (not just symptom) in ≤2 prompts, verified by me fixing and bug not recurring |