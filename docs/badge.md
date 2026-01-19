# People First Design Badge

This document expands on the **People First Design badge system** mentioned in the README, including what “Unverified” and “Verified” mean, how to use each badge, and how others can verify a badge ID.

> **Not legal advice.** This badge is not a legal certification and does not guarantee compliance with any laws.

---

## Overview

The People First Design badge is a lightweight, trust-based way to:

- Publicly state that you follow (or partially follow) the People First Design principles
- Provide a clear place where you explain *how* you follow them (with evidence)
- Let others verify whether your badge claim is **Verified** (issued) or **Unverified** (self-claimed)

There are two badge states:

1. **Unverified** — self-claimed, not reviewed/issued by this project
2. **Verified** — reviewed, issued an ID, and listed in `verified.md`

---

## Badge States

### 1) Unverified Badge (Self-Claim)

Use the **Unverified** badge if:

- You follow People First Design but have not applied for verification yet, or
- You don’t want to apply, but you still want to be transparent and accountable

**Unverified means:**

- No ID is issued by this project
- Your claim is not checked against the repository’s verification list
- People should treat it as a *good-faith statement*, not proof

**Requirements to use the Unverified badge**

If you display an Unverified badge, you must:

1. **Link back to this repository**
2. Provide a public page/section explaining:
    - Which principles you follow
    - Which principles you do **not** follow (if any)
    - Evidence/examples (screenshots, settings pages, privacy policy text, etc.)

**Recommended Unverified label text**

- “People First Design (Unverified)”
- “People First Design — self-attested”

---

### 2) Verified Badge (Issued + Listed)

Use the **Verified** badge only if you have been issued a badge ID and are listed in `verified.md`.

**Verified means:**

- You applied for verification
- You provided evidence
- You received a **badge ID**
- Your ID and details appear in `verified.md`

**Verified does not mean:**

- Perfect compliance forever
- A legal guarantee
- A security or privacy audit

Verification can be revoked or updated if a listing becomes misleading, outdated, or abused.

---

## Badge ID Rules (Verified Only)

If you use the **Verified** badge, you must clearly display your badge ID in a copyable format.

**You must:**

- Show the ID near the badge (same page/visible area when possible)
- Make it easy to copy/paste
- Link back to this repository
- Link to (or include) your evidence page/section

**Example (recommended format)**

```text
People First Design — Verified
Badge ID: PFD-0000
Verify: https://github.com/COOLmanYT/people-first-design/blob/main/verified.md
```

---

## How Verification Works (What Applicants Should Provide)

To apply for the Verified badge, you should prepare:

1. **Principles coverage**
    - Confirm you follow all principles **or** clearly state which ones you don’t
2. **Evidence**
    - Examples: UI screenshots, privacy settings, signup flow, consent dialogs, ad labeling, data export/delete flow, etc.
3. **Badge placement**
    - Show where the badge appears on your site/app
4. **ID display**
    - Confirm you will display your badge ID publicly and copyably
5. **Repository link**
    - Confirm you link back to this repo

The application link is referenced in the README.

---

## How to Verify a Badge (For Everyone)

To verify a **Verified** badge:

1. Copy the badge ID shown on the site/app (example: `PFD-0123`)
2. Open `verified.md`
3. Find the matching entry
4. Confirm the details match what the site/app claims (name/project/link)

If any of these do not match, treat the badge as **not verified**.

> If a site claims “Verified” but does not show an ID, it should be treated as **Unverified** at best.

---

## Correct Usage Guidelines

### Don’ts

- Don’t use the **Verified** badge without being listed in `verified.md`
- Don’t hide the badge ID (Verified) or make it hard to copy
- Don’t imply this badge is a legal certification or official compliance audit
- Don’t use the badge to justify harmful patterns (“we’re verified so it’s fine”)

### Do

- Keep your evidence page up to date when your product changes
- Be explicit about tradeoffs and exceptions
- Treat the badge as accountability, not marketing

---

## Suggested Badge Embed (Template)

Replace the placeholders with your actual URLs/ID.

### Unverified

```markdown
[![People First Design — Unverified](./path/to/pfd-unverified.svg)](https://github.com/COOLmanYT/people-first-design)

**People First Design (Unverified)**  
We follow People First Design principles. Evidence: https://example.com/people-first
```

### Verified

```markdown
[![People First Design — Verified](./path/to/pfd-verified.svg)](https://github.com/COOLmanYT/people-first-design)

**People First Design — Verified**  
Badge ID: `PFD-{example}`  
Verify: https://github.com/COOLmanYT/people-first-design/blob/main/verified.md  
Evidence: https://example.com/people-first
```

---

## Reporting Misuse

If you believe someone is misusing the badge (especially claiming **Verified** without a valid listing):

- Open an issue in this repository
- Include the site/app link, screenshots, and the claimed badge ID (if present)

---

## Changelog

This badge system is community-maintained and may evolve over time. If you have improvements (clearer requirements, better templates, stronger anti-misuse language), open a pull request.
