# People First Design — Core Principles (Expanded)

> **Not legal advice.** These are practical, human-centered guidelines for building respectful websites, apps, and software.

This document expands the **Core Principles** from the README into actionable guidance, examples, and quick checklists.

---

## 1) UX before metrics, and far before profits

### What it means
User experience is the primary constraint. Metrics and revenue matter, but they must not be improved by making the product confusing, coercive, or unpleasant.

This doesn’t mean “ignore sustainability.” It means:
- Don’t trade away trust and usability for short-term gains.
- If you must tighten things due to real financial risk, do it transparently and revert once stable.

### Practical rules
- **Default to helpful**: the simplest path should be the best path.
- **Measure friction as a cost**, not a lever.
- **If a change improves metrics but worsens user outcomes**, treat it as a failed change.

### Do
- Keep flows short and predictable (sign-up, checkout, settings, export, deletion).
- Make pricing and limits clear upfront.
- Optimize performance and accessibility before “growth experiments.”
- Use metrics that represent user success: task completion, time-to-success, retention driven by value (not lock-in).

### Avoid
- “Engagement” tactics that trap users (infinite loops, nagging, manipulative streaks).
- Hiding key features behind confusing steps to increase conversions.
- Designing for the dashboard instead of the user.

### Example: good vs bad
- **Good**: “Upgrade” is visible, but the free path remains functional and easy.
- **Bad**: Basic functionality is intentionally slow/annoying unless the user pays.

### Quick checklist
- [ ] Can a user complete the main task in a straightforward way?
- [ ] Is any friction intentional? If yes, is it for safety/clarity—not conversion?
- [ ] Do your metrics include user outcomes (not just clicks)?
- [ ] Would you feel comfortable explaining this change to users publicly?

---

## 2) No dark patterns

### What it means
No manipulative interfaces that pressure, mislead, or trick users into actions they didn’t intend.

A simple test:
> If a reasonable user would feel annoyed or deceived after realizing what happened, don’t do it.

### Common dark patterns to avoid
- **Guilt buttons**: “No thanks, I hate saving money”
- **Fake urgency**: “Only 1 left!” when untrue or unverifiable
- **Confusing opt-outs**: “Uncheck to opt out” with double negatives
- **Hidden costs**: fees revealed at the final step
- **Forced continuity**: trials that are hard to cancel
- **Sneaky defaults**: pre-checked consent, pre-checked marketing
- **Disguised ads**: content that looks like UI/system messages
- **Obstruction**: cancellation or deletion hidden behind hoops

### Do
- Make choices symmetrical: *Accept* and *Decline* should be equally clear.
- Use plain labels: “Cancel subscription,” “Delete account,” “Export data.”
- Confirm destructive actions, but don’t punish users for choosing them.

### Avoid
- Making the “good for you” choice visually weak or hard to find.
- Using shame, fear, or urgency to drive clicks.
- Building flows that rely on user confusion.

### Quick checklist
- [ ] Are choices presented fairly (visual weight, wording, placement)?
- [ ] Is consent explicit and reversible?
- [ ] Is cancellation as easy as sign-up?
- [ ] Could this UI be defended as “honest” in one sentence?

---

## 3) Top Tier Privacy

### What it means
Collect the **minimum** data required, protect it well, and explain it clearly.

Privacy is not only legal compliance—it’s respect.

### Data minimization (default stance)
- Don’t collect data “just in case.”
- Prefer aggregated/anonymous signals where possible.
- Avoid sensitive data unless absolutely necessary.

### Transparency (plain language)
Users should understand:
- **What** you collect
- **Why** you collect it
- **How long** you keep it
- **Who** gets access (including vendors)
- **How** to delete/export it

### Controls users should have (when applicable)
- View their data
- Export their data (common format)
- Delete their data (with verification)
- Manage consent (analytics, marketing, personalization)

### Security basics (minimum expectations)
- HTTPS everywhere
- Encrypt sensitive data at rest
- Least-privilege access for staff
- Log access to sensitive systems
- Have a breach response plan (even a simple one)

### Quick checklist
- [ ] Is every collected field necessary for functionality?
- [ ] Can users request deletion and get a clear result?
- [ ] Is the privacy explanation readable without legal knowledge?
- [ ] Do third parties receive user data? If yes, is it clearly disclosed?

---

## 4) Respect attention

### What it means
Don’t treat attention as a resource to extract. Interrupt only when necessary and do it politely.

### Acceptable interruptions (examples)
- Cookie consent (when required)
- Security alerts (suspicious login, password compromise)
- Critical system status (downtime, breaking changes)
- Legal document updates (when relevant and meaningful)

### Avoid
- Autoplay audio/video
- Popups that block reading on page load
- Repeated nags after dismissal
- Notifications designed to cause anxiety or urgency
- Infinite scroll without stopping cues (especially for kids)

### Better patterns
- Use inline banners instead of modal popups.
- Allow “Not now” or “Remind me later” where appropriate.
- Provide notification controls (type, frequency, quiet hours).

### Quick checklist
- [ ] Does this interruption help the user *right now*?
- [ ] Can the user dismiss it easily and permanently (if appropriate)?
- [ ] Would the product still work if this interruption didn’t exist?
- [ ] Are notifications opt-in (or minimally opt-out) and configurable?

---

## 5) Clarity over cleverness

### What it means
Prefer understandable UI over “creative” UI. Users should not need to decode your intent.

### Writing rules (UI copy)
- Use concrete verbs: “Save,” “Delete,” “Export,” “Pay,” “Cancel”
- Keep labels consistent across the product
- Explain consequences near the action (especially destructive ones)
- Avoid slang, sarcasm, or ambiguous jokes in critical flows

### Interaction rules
- Buttons should look like buttons.
- Links should look like links.
- Don’t hide essential actions behind unfamiliar icons without labels.
- Prefer standard UI patterns unless there’s a strong reason not to.

### Good vs bad microcopy
- **Good**: “Delete account (permanent)”
- **Bad**: “Poof! Make it disappear”

### Quick checklist
- [ ] Can a new user understand the page in 5–10 seconds?
- [ ] Are primary actions obvious and consistently placed?
- [ ] Are error messages actionable (what happened + how to fix)?
- [ ] Could a screen reader user navigate this without guesswork?

---

## Suggested “People First” self-review (lightweight)

Use this before shipping a feature:
1. **Intent**: What problem does this solve for the user?
2. **Honesty**: Is the UI truthful and non-manipulative?
3. **Control**: Can the user change their mind or undo actions?
4. **Privacy**: Did we add any new data collection? Is it necessary?
5. **Attention**: Did we add interruptions? Are they justified?
6. **Clarity**: Could someone unfamiliar complete the task without help?

---

## Related docs
- See `README.md` for the summary principles and project overview.
- See `/examples` for concrete patterns to copy or avoid.
- See `verified.md` for verification/badge information (if applicable).