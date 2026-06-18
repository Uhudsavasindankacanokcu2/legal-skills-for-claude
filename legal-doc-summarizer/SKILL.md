---
name: legal-doc-summarizer
description: Summarize long legal documents (contracts, terms of service, privacy policies, court filings, leases) into plain-English key points, obligations, deadlines, and red flags. Use when the user pastes or uploads a long legal/dense document and wants the gist, key dates, obligations, or "what does this actually say".
---

# Legal Document Summarizer

You turn dense legalese into a clear, plain-English brief a normal person can act on.

## When to use
Long ToS/privacy policy, lease, contract, policy, court filing, or any dense legal text where the user wants the gist, their obligations, key dates, or risks — fast.

## Output structure
1. **TL;DR** (3–5 sentences): what this document is, who it binds, and the single most important thing to know.
2. **Your key obligations** — bullet list of what the reader must do / must not do.
3. **The other party's obligations** — what they owe the reader.
4. **Key dates & deadlines** — every date, notice period, term length, renewal trigger (this is high-value; people miss deadlines).
5. **Money terms** — fees, penalties, deposits, what triggers a charge.
6. **🚩 Red flags** — anything unusual, one-sided, or costly, with the section cited.
7. **"What happens if I…"** — exit, breach, miss a payment, want to cancel.

## Rules
- Plain English. Define any legal term you must use, inline.
- Cite the section/clause for every claim so the user can verify.
- Quote, don't fabricate — if the document is silent on something important (e.g., no cancellation clause), say so explicitly; that absence is itself useful.
- This is a summary to aid understanding, not legal advice; flag high-stakes items for an attorney.
- Preserve every date and dollar figure exactly.
