# Legal Skills for Claude ⚖️

**Turn Claude into a contracts assistant.** A pack of [Claude Skills](https://docs.claude.com/en/docs/claude-code/skills) that review, summarize, and draft business agreements — in plain English, with the risky clauses flagged and cited.

For founders, freelancers, and small businesses who sign contracts without a lawyer on retainer.

---

## ✨ What's inside (free core)

| Skill | What it does |
|-------|--------------|
| **contract-reviewer** | Paste any contract → clause-by-clause **risk report from your side**, plain-English explanations, and suggested redlines. Catches one-sided liability, auto-renewals, IP grabs, and more. |
| **legal-doc-summarizer** | Long ToS/lease/policy/filing → TL;DR, **your obligations, key dates & deadlines, money terms, red flags** — every claim cited to its section. |
| **agreement-drafter** | Describe the deal → clean, balanced first-draft **NDA / contractor / service agreement / ToS**, with a "before you send" checklist. |

Each skill is a single `SKILL.md` — drop it in `~/.claude/skills/` and Claude uses it automatically.

---

## 🚀 Quick start
1. Copy a skill folder into `~/.claude/skills/`.
2. Ask Claude: *"Review this contract — I'm the contractor. What should I push back on?"*
3. Get a real, cited risk breakdown.

---


---

## 👀 See it in action

**You paste a clause from a contract you're about to sign** (you're the freelancer/vendor):

```
Section 9. Limitation of Liability. In no event shall Client be liable to
Contractor for any damages. Contractor shall indemnify and hold harmless
Client from any and all claims, losses, and liabilities arising from the
services, without limitation. This Agreement shall auto-renew for successive
12-month terms unless terminated with 90 days' written notice.
```

**Claude returns** (contract-reviewer skill, reviewing from YOUR side):

---

**Verdict:** 🔴 **Several one-sided terms — push back before signing.** Three clauses shift all risk to you.

| Clause | Tier | What it means for YOU | Suggested change |
|--------|------|----------------------|------------------|
| §9 Liability (one-way) | 🔴 High | Client owes you *nothing* for any damages — even if they cause them. Totally one-sided. | Make it **mutual**: cap both sides' liability at fees paid in the prior 12 months. |
| §9 Indemnity (unlimited) | 🔴 High | You cover *all* claims "without limitation" — potentially far more than the contract is worth. | Limit to **third-party claims arising from your breach**; exclude Client-caused issues. |
| §9 Auto-renew + 90-day notice | 🟡 Watch | You're locked in yearly unless you remember to cancel 90 days early. Easy to get trapped. | Shorten to **30 days' notice**, or add a renewal reminder obligation. |

**Top 3 things to negotiate (copy-paste redlines):**

1. **Mutual liability cap:**
   > "Neither party shall be liable to the other for indirect or consequential damages. Each party's total liability shall not exceed the fees paid under this Agreement in the twelve (12) months preceding the claim."

2. **Limited, mutual indemnity:**
   > "Each party shall indemnify the other against third-party claims arising from the indemnifying party's breach of this Agreement or infringement of third-party IP."

3. **Reasonable termination:**
   > "Either party may decline renewal with thirty (30) days' written notice before the end of the then-current term."

**The framing to send them:** *"I'd like these to be mutual rather than one-directional — standard market terms that protect both of us. Happy to keep everything else as-is."* (Mutual + market-standard lands far better than "I don't like this.")

*Contract analysis to help you negotiate — not legal advice. For a high-value deal, have an attorney review the final language.*

---

> The skill **quoted the actual clause** for every flag and never invented a risk. It reviewed from *your* side — the same clause is graded differently depending on which party you are.

---

## 💎 Pro pack — 6 skills

**[Legal Skills Pro →](GUMROAD_LINK_HERE)** adds:
- **clause-library** — instant access to balanced, ready-to-paste versions of common clauses (liability cap, mutual indemnity, termination-for-convenience…)
- **negotiation-helper** — turns "this clause is bad" into the exact counter-language to send
- **compliance-checker** — flags missing GDPR/privacy/consumer-law basics in your ToS & policies
- Priority updates + new skills

**One-time payment. No subscription.** [Get the Pro pack →](GUMROAD_LINK_HERE)

---

## ⚖️ Important
These skills help you **understand, review, and draft** agreements — they are **not legal advice** and Claude is not your lawyer. For high-stakes or jurisdiction-specific matters, have a licensed attorney review before you sign. The skills cite clauses and flag missing terms; they never invent legal facts.

---
⭐ **Star this repo** if it saved you a lawyer's hourly rate on a first pass. New free skills added regularly.

*Made for the Claude Skills ecosystem.*

## 🔗 More Claude Skill Packs

- 💸 [Finance Skills](https://github.com/Uhudsavasindankacanokcu2/finance-skills-for-claude) — cash flow, runway, invoices, budgets, pricing
- 🧑‍💼 [Recruiting & HR Skills](https://github.com/Uhudsavasindankacanokcu2/recruiting-skills-for-claude) — JDs, resume screening, interviews
- 🛒 [E-commerce Seller Skills](https://github.com/Uhudsavasindankacanokcu2/ecommerce-skills-for-claude) — listings, reviews, ad spend
