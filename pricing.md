# SecureTransmit Pricing

Self-serve. Starts at $5/mo. No free tier.

SecureTransmit is currently in closed beta. Access is by approval and billing is paused for approved accounts. Public launch is coming. Request access at https://securetransmit.io/beta-access/

## Plans at a glance

| | Solo | Pro | Business | Enterprise |
|---|---|---|---|---|
| **Price** | $5 / mo (or $50 / yr) | $49 / mo | $249 / mo | From $5,000 / mo, annual, quoted |
| **Positioning** | For individuals and light usage | Where most real work happens | Team + compliance | Custom retention, SCIM, dedicated support |

## Volume & limits

| Feature | Solo | Pro | Business | Enterprise |
|---|---|---|---|---|
| Active workflows | 3 | 25 | Unlimited | Unlimited |
| Monthly transfer included | 100 MB | 10 GB | 100 GB | Custom |
| Monthly API requests | 10k | 100k | 1M | Custom |
| Overage pricing | Hard cap | $0.50 / GB, $5 / 100k req | Volume discount | Volume discount |

## Retention

| Feature | Solo | Pro | Business | Enterprise |
|---|---|---|---|---|
| File retention (default) | 7 days | 30 days | 90 days | Custom |
| Configurable retention windows | — | Paranoid on-ack only | 30d / 90d / 1y / on-ack | Fully custom (incl. delete-on-ack default) |
| Audit + hash retention | 1 year | Forever | Forever | Forever |

## Security architecture

| Feature | Solo | Pro | Business | Enterprise |
|---|---|---|---|---|
| Paranoid mode (ephemeral) | — | On-ack only | Full config | Full config |
| Island mode (outbound-only) | — | Yes | Yes | Yes |
| Built-in firewall (IP / creds) | Basic IP block | Full | Full | Full |
| Firewall (geo blocking) | — | — | Yes | Yes |

## Capabilities

| Feature | Solo | Pro | Business | Enterprise |
|---|---|---|---|---|
| Canonical URLs | 10 | 1,000 | 10,000 | Unlimited |
| Industrial webhook receive | 1 endpoint | 50 endpoints | Unlimited | Unlimited |
| Industrial webhook send | 1 destination | 50 destinations | Unlimited | Unlimited |
| AI enrichment (BYO token) | — | Yes | Yes | Yes |

## Team, admin & compliance

| Feature | Solo | Pro | Business | Enterprise |
|---|---|---|---|---|
| Team seats | 1 | 5 | 20 | Custom |
| Custom domains | 0 | 1 | 5 | Unlimited |
| SSO / SAML | — | — | Yes | Yes |
| SCIM, RBAC, audit log export | — | — | Add-on | Yes |
| Support | Community | Email | Priority (24h SLA) | Dedicated |

## Tier philosophy

**Pro is where most real work happens.** Swipe a card, production workflows, AI enrichment, Paranoid mode, Island mode — all there.

**Business adds team and compliance features.** SSO, geo-blocking, higher throughput, priority support. Plus full retention configurability.

**Enterprise starts at $5k/mo.** Custom retention, dedicated support, SCIM, audit log export. Founding rates available for design partners — contact us.

## FAQ

**Is there a free tier?** No, and we don't plan to add one. We don't run ads and we don't make money off your data — we make money from the monthly fee. Solo starts at $5/mo (or $50/yr).

**How does file retention work?** Every plan sets a default file retention window — 7 days on Solo, 30 on Pro, 90 on Business, fully custom on Enterprise. When that window expires, the file data is deleted. Audit records and SHA-256 hashes are retained separately (1 year on Solo, forever on Pro and up) so you can still prove what moved, even after the file is gone.

**What does "delete on ack" mean?** The moment the destination system acknowledges receipt, the file is deleted. No retention window, no waiting. The SHA-256 hash and the audit record stay forever. Breach exposes only in-flight data. Available on Pro and up; the default on Enterprise if you want it.

**How does Island mode interact with pricing?** Island mode is architectural, not metered. It's included on Pro and up at no extra charge. Partners push to SecureTransmit, your systems pull from SecureTransmit, and you close every inbound B2B port on your own firewall.

**Do AI tokens cost extra?** No. AI enrichment steps call your provider with your API key. Your provider, your account, your data policy, your bill for tokens. SecureTransmit doesn't resell AI or take a cut.

**What's a "founding rate" for Enterprise?** Our public Enterprise floor is $5k/mo. For a limited number of design partners willing to work closely with us, we negotiate a founding rate. That's a private conversation — contact us and tell us what you're building.

---

Canonical HTML pricing page: https://securetransmit.io/pricing/
