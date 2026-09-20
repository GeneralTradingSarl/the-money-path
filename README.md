# The Money Path

**Designing, securing and auditing a Stripe integration that deserves to run in production.**

A practitioner's handbook by [Ismaël Ladjohounlou](https://github.com/GeneralTradingSarl). 126 pages, 18 chapters, 6 appendices, 72 review points. Free to read.

### [Download the PDF](The-Money-Path.pdf)

---

A payment system does not fail loudly. It fails in a way that looks exactly like success, for months, until someone finally counts the money.

Stripe protects the card data. What your own code does with the payment, and what it gives the customer afterwards, is still your responsibility, and that is where most integration failures come from. This book is organised around the thing you are actually protecting: the path the money takes.

## What is inside

**Part one, the ground rules**
1. The Shared Responsibility Model
2. Eligibility: who Stripe can and cannot serve
3. Choosing an integration shape

**Part two, the regulatory surface**
4. PCI DSS 4.0.1 in practice
5. Strong Customer Authentication and 3D Secure
6. The payment page: TLS, CSP and e-skimming

**Part three, the server side**
7. Keys, secrets and blast radius
8. The money path: server-authoritative payments
9. Webhooks: the load-bearing wall
10. Fulfilment and data consistency
11. Rate limits, errors and resilience

**Part four, fraud, risk and disputes**
12. Radar and transaction risk
13. Disputes, chargebacks and evidence

**Part five, platforms and marketplaces**
14. Connect: account types and liability

**Part six, operating the integration**
15. API versioning and SDK discipline
16. Environments, sandboxes and testing
17. The go-live checklist
18. The security review grid

**Appendices**
A. Test cards and simulated outcomes · B. Content Security Policy directives · C. Webhook events that matter · D. Reference implementation (TypeScript, Next.js App Router, PostgreSQL) · E. Glossary · F. Sources

## Who it is for

Engineers shipping their first paid product. Technical leads inheriting an integration someone else wrote. Consultants asked to review a codebase and say whether it is safe to put behind real money. Founders who need to understand what they are signing up for before they sign.

Code examples assume TypeScript on a Node runtime. The principles in parts one, two, four and six are language independent.

## How it is written

Every normative statement is traceable to a primary source listed in appendix F: Stripe's documentation, Stripe's published engineering guidance, the PCI Security Standards Council and the text of the relevant European regulation. Four marks run through the book: **RULE** for a non-negotiable, **TRAP** for a pattern that looks correct and is not, **PRACTICE** for something that costs a little now and saves a great deal later, **CONTEXT** for the history behind a decision.

Thresholds, API versions and prices change. Check every figure against the current source. The reasoning around them has a longer shelf life.

## Errata and questions

Open an issue. Corrections with a primary source attached are especially welcome and go into the next edition.

## Work with me

I build and review payment integrations, automation and trading systems.

- Portfolio: https://ismael-portfolio-liard.vercel.app/en
- All my work: https://github.com/GeneralTradingSarl
- Email: general.trading.bot.2025@gmail.com

## Notice

Copyright © 2026 Ismaël Ladjohounlou. All rights reserved. The PDF may be downloaded and read freely; it may not be resold or republished as your own.

Nothing here is legal or compliance advice. Stripe, Radar, Connect, Checkout, Elements, Link, Terminal, Sigma and Issuing are trademarks of Stripe, Inc. This book is an independent work and is not endorsed by, affiliated with or sponsored by Stripe, Inc.
