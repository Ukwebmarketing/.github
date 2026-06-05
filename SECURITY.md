# Security Policy

UK Web Marketing operates managed website infrastructure for UK businesses. If
you've found a security issue affecting any of our systems, this document tells
you how to report it and what we'll do.

---

## Reporting a vulnerability

**Email:** [security@ukwebmarketing.com](mailto:security@ukwebmarketing.com)

PGP encryption is not required. If you'd prefer to encrypt, request a public
key in the first message and we'll respond with one.

When you report, please include:

1. **A description** of the issue
2. **Affected surface** — domain, repo, endpoint, or service name
3. **Steps to reproduce** (or proof-of-concept code/URL)
4. **Suggested fix or mitigation** if you have one
5. **Your contact** for follow-up + how you'd like to be credited

Do **not** open a public GitHub issue for security reports. The advisory tab on
any repo or the email above are the only acknowledged channels.

---

## What we commit to

- **Acknowledge** every report within **24 hours** (working days; weekends may
  push to Monday morning)
- **Triage + initial response** within **72 hours**
- **Fix or document mitigation** within **7 days** for confirmed issues
- **Credit** the reporter in the fix commit + release notes unless they request
  anonymity

---

## Scope

In scope:

- All websites under [ukwebmarketing.com](https://ukwebmarketing.com) and its
  subdomains
- Any client site we host (please email rather than disclosing to the client
  directly — we'll co-ordinate)
- All public repositories under this organisation
- Our API endpoints + edge functions
- Our outbound email (Resend) and transactional flows

Out of scope:

- Third-party services we use (report to them: Vercel, Stripe, Resend, Cloudflare)
- Denial-of-service attacks of any kind
- Social engineering of staff or clients
- Physical access attacks
- Issues that require a man-in-the-middle on the reporter's own network

---

## Safe harbour

We will not pursue legal action against researchers who:

- Make a good-faith effort to follow this policy
- Do not access, modify or exfiltrate data beyond what's needed to demonstrate
  the issue
- Do not disclose publicly before we've shipped a fix or 90 days have passed,
  whichever comes first
- Do not attempt to extort or otherwise weaponise the finding

---

## Bug bounties

We do not currently run a paid bug-bounty programme. We do credit reporters
publicly (with their consent) and will write a recommendation on LinkedIn or
similar for serious + ethically-disclosed findings.

---

_This policy applies to all repositories under the `ukwebmarketing` GitHub
organisation, operated by **TicketWave HQ Ltd**, UK Companies House
[17143167](https://find-and-update.company-information.service.gov.uk/company/17143167)._
