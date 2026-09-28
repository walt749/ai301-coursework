# Unit 1 — Issue Selection

Path: `beat-1-sandbox/unit-1/selection.md`

Record of the issue carried into Unit 2, and of the evaluation runs that produced
`eval-run.txt`. This file is graded at the path above; a copy kept anywhere else in
the repository is not read.

Complete every labelled field below. Each is graded on its own; content placed under the
wrong label is not graded.

---

## Selected issue

**Issue link**

https://github.com/codepath/ai301-unit1-starter/blob/main/eval/issues/issue-06.md

[The individual Path Review issue page. A link to the repository or the issue list
does not satisfy this field.]

**Verdict output**

**Issue-06: 9/10** as a first issue

### Why it's excellent (9/10, not 10/10):

| Criterion               | Score | Evidence                                                     |
| ----------------------- | ----- | ------------------------------------------------------------ |
| **Scope clarity**       | 10/10 | Title + user story + explicit problem statement              |
| **Acceptance criteria** | 10/10 | 3 concrete checkboxes; no ambiguity                          |
| **Actionability**       | 10/10 | "Look at `src/app/components/header/`" — exact starting point |
| **Testability**         | 10/10 | Manual test: button visible? works? Trivial to verify.       |
| **Complexity**          | 10/10 | ~2–3 component files, no framework deep-dive needed          |
| **Repo health**         | 8/10  | Last commit 2026-07-31 (active), but only 37 ⭐ (small)       |
| **Maintainer response** | 8/10  | Opened by collaborator, but niche repo = might be slow       |
| **Blockers**            | 10/10 | None; not waiting for design/approval                        |
| **Recency**             | 10/10 | Just opened (2026-08-05); zero stale discussion              |

### Why not 10/10:

The **repo is tiny** (37 stars, niche community project). That means:

- Maintainers might be slower to review
- Less precedent/documentation on the contribution process
- Smaller community = fewer people to ask for help

**But the \*issue itself\* is perfectly written** — if this were in a major repo, it'd be 10/10 solid.

**The verdict must record `accept` for this issue.** Choose an issue your own skill
accepts. If your skill rejects every candidate you try, that is a signal about your
rubric rather than about the issues: revise it and re-run — retries are unlimited and a
partial re-run costs about $0.20 — or run the skill on different candidates. Output
recording `reject` for the issue you chose earns no credit for this field.

```
paste the output here, including the closing JSON block
```

---

## Eval iterations

Quote source text directly in each field below. Paraphrase does not satisfy them.

**Run history**

[The agreement score of each run you did, in order. A single run is a complete answer if
only one run occurred. **The last score in your list must match the agreement line in the
`eval-run.txt` you committed** — that file is the record of your final run.]

### ✅ Good First Issue Signals

**Issue-02** (z sed bug), **Issue-04** (missing previews), **Issue-06** (Submit App), **Issue-13** (indentation tabs):

- **Tiny scope** — 1–3 files changed, <100 lines of code
- **Exact problem stated** — "on macOS, sed -i fails because..." or "replace spaces with tabs in these 4 files"
- **Clear acceptance criteria** — what success looks like
- **Reproducible** — steps to reproduce (or exact file locations)
- **No design decisions** — straightforward implementation path
- **No blocker discussion** — not waiting for maintainer sign-off

**Issue analysis**

[One scored issue, identified by id (`issue-01` through `issue-20`; the `calib-`
issues are not scored). State your rubric's decision, the gold label, and the
reasoning that produced your rubric's result.]

Issue-06 is a **textbook perfect first issue**. Here's why:

### 1. **User Story + Problem + Acceptance Criteria**

```
As a desktop user, I want to see a visible 'Submit App' button...
Problem: The button is hidden on desktop, fails on mobile.
Acceptance Criteria:
  - [ ] Button visible on desktop navbar
  - [ ] Accessible in mobile drawer and triggers modal
  - [ ] Works in Arabic (RTL) and English (LTR)
```

This is the gold standard. A newcomer reads this once and knows exactly what "done" looks like.

### 2. **Explicit Starting Point**

> "Where to start: Look at `src/app/components/header/` and `src/app/components/mobile-menu/`."

You don't have to hunt the codebase. You know which 2 folders to open.

### 3. **Small, Testable Scope**

- Fix 2–3 component files
- Test manually: click button on desktop (visible?), click on mobile (works?)
- Acceptance criteria are all things **you can verify yourself**

### 4. **No Hidden Complexity**

- No "we need design approval first" (issue-08)
- No "106 comments with conflicting guidance" (issue-05)
- No "wait for maintainer sign-off" (issue-03)
- No vague "sometimes it happens" (issue-11)

### 5. **Fresh & Unblocked**

- Opened 2026-08-05 (just created)
- 0 comments (no debate)
- Not assigned (room for you)
- Labels: `easy`, `good first issue`, `help wanted` (repo is welcoming)

**Check rationale**

[One check from the `rubric.md` uploaded to `tools/issue-select/`, quoted as it is
currently written, with the reasoning behind its current form.]

**Trade-offs**

- Maintainers might be slower to review
- Less precedent/documentation on the contribution process
- Smaller community = fewer people to ask for help

---

## Selection rationale

Graded on whether all three are answered, in your own words. Not on how good the
reasoning is, and not on length — a short honest answer to each earns the full marks.
This is also the basis for the claim comment you write in Unit 2.

**Selection rationale**

### ✅ Good First Issue Signals

**Issue-02** (z sed bug), **Issue-04** (missing previews), **Issue-06** (Submit App), **Issue-13** (indentation tabs):

- **Tiny scope** — 1–3 files changed, <100 lines of code
- **Exact problem stated** — "on macOS, sed -i fails because..." or "replace spaces with tabs in these 4 files"
- **Clear acceptance criteria** — what success looks like
- **Reproducible** — steps to reproduce (or exact file locations)
- **No design decisions** — straightforward implementation path
- **No blocker discussion** — not waiting for maintainer sign-off

[Answer all three:

1. The issue's fit to your interests and to the time available.
2. What the verdict identified correctly, and what you weighed that the rubric could
   not.
3. The anticipated difficulty in claiming it.]

---

Related paths: `eval-run.txt` in this directory; your skill's files in
`tools/issue-select/`.
