# B2B Outbound Software Pricing Index (2026 Open Dataset)

An open, human-verified dataset of primary-source pricing, credit rules, and modeled 10,000-lead monthly bills across **13 B2B outbound & GTM tools** — maintained by [**GTMFacts**](https://gtmfacts.com/).

- **Interactive Total-Cost Calculator**: [https://gtmfacts.com/calculator/](https://gtmfacts.com/calculator/)
- **Live JSON Pricing Feed**: [https://gtmfacts.com/api/v1/pricing.json](https://gtmfacts.com/api/v1/pricing.json)
- **Verified Pricing Changelog & RSS**: [https://gtmfacts.com/changelog/](https://gtmfacts.com/changelog/) ([RSS](https://gtmfacts.com/rss.xml))
- **LLM Reference Markdown**: [https://gtmfacts.com/llms-full.txt](https://gtmfacts.com/llms-full.txt)

---

## Why This Dataset Exists

Vendor pricing pages rarely reflect the real monthly cost of running B2B outbound at scale. Phone reveal credit multipliers (5x–10x), bounce verification, seat minimums, and secondary domain/mailbox infrastructure routinely add **35%–45%** on top of published headline prices.

Every entry here is verified directly from official vendor pricing pages with **$0 paid placements** and transparent modeling assumptions ([Methodology](https://gtmfacts.com/methodology/)).

---

## Audited Tools Summary (10,000 Leads / Month Benchmark)

| Tool | Role | Published Entry | Modeled 10k-Lead Bill | Primary Billing Catch |
| :--- | :--- | :--- | :--- | :--- |
| [Apollo.io](https://gtmfacts.com/tools/apollo/) | B2B database & sequencer | $49/seat/mo | **$237+/mo** | Mobile reveals use 8 credits. Add-on prices depend on the account, and some teams budget for external verification. |
| [Clay](https://gtmfacts.com/tools/clay/) | Data orchestration | $185/mo | **$706/mo est.** | Actions and Data Credits scale separately, so multi-step waterfalls burn both meters quickly. |
| [HeyReach](https://gtmfacts.com/tools/heyreach/) | LinkedIn outreach automation | $79/sender/mo | **$158/mo (2 senders)** | Dedicated residential proxy is included, but active outreach typically requires a separate LinkedIn Sales Navigator subscription per sender. |
| [Instantly](https://gtmfacts.com/tools/instantly/) | Cold email sequencer | $47/mo | **$107/mo** | Outreach sending and Lead Credits are separate subscriptions, and secondary domains/mailboxes are extra overhead. |
| [lemlist](https://gtmfacts.com/tools/lemlist/) | Multichannel sequencer | $69/mo | **$69–$327/mo** | Email-only allows unlimited users at $69/mo, but LinkedIn and calling switch to $109/seat/mo per rep. |
| [Lusha](https://gtmfacts.com/tools/lusha/) | Contact & phone database | $37.45/mo | **Quote required** | Phone numbers consume 5 credits each and entry tiers cap sharply below high-volume outbound needs. |
| [MillionVerifier](https://gtmfacts.com/tools/millionverifier/) | Bulk email verification | $39 / 10k | **$39 / 10k** | Minimal inbox-placement extras compared to ZeroBounce, but credits never expire and unknowns are refunded. |
| [NeverBounce](https://gtmfacts.com/tools/neverbounce/) | Automated list verification | $49/mo (10k) | **$49–$50 / 10k** | Pay-as-you-go credits expire after 12 months; Growth auto-sync bills monthly even in quiet sending months. |
| [Prospeo](https://gtmfacts.com/tools/prospeo/) | Email & mobile finder | $37/mo | **About $187/mo (one Pro seat, annual)** | The 10k benchmark uses one Pro seat. Multi-seat teams can pool credits, and phone reveals use more credits. |
| [RB2B](https://gtmfacts.com/tools/rb2b/) | US website visitor ID | $0 / $79/mo | **$149+/mo** | Starter ($79/mo) sends LinkedIn URLs to Slack only—business emails and CRM/Clay integrations require Pro ($149/mo+). |
| [Smartlead](https://gtmfacts.com/tools/smartlead/) | Cold email sequencer | $39/mo | **$94/mo** | Unlimited sender accounts are included, but secondary domains and Google/Microsoft mailboxes are billed separately. |
| [ZeroBounce](https://gtmfacts.com/tools/zerobounce/) | Email validation & deliverability | $39 / 2k | **$99–$129 / 10k** | PAYG 10k blocks run ~$129 (3.3x MillionVerifier); ZeroBounce ONE ($99/mo) is only cheaper if you use the bundled suite. |
| [ZoomInfo](https://gtmfacts.com/tools/zoominfo/) | Enterprise sales intelligence | Quote (~$15k/yr) | **$1,250+/mo** | No public list prices, mandatory 12-month upfront annual lock-in, and strict auto-renewal notice clauses. |

---

## Matched Full-Stack Monthly Benchmarks (10k Leads · 50k Sends · 3 Seats · Annual)

At a safe sending cadence of 40 sends/inbox/day, 50,000 monthly cold emails require **57 inboxes across 19 secondary domains ($219/mo infrastructure floor)** before software subscriptions or bounce scrubbing.

| Benchmark Stack | Software & Credits | Mailboxes & Verification | Total Monthly Estimate |
| :--- | ---: | ---: | ---: |
| **Lean Outbound Stack** (email-only) | $315/mo | $258/mo | **$573/mo** |
| **Clay + Multichannel** (+2 LinkedIn senders) | $918.42/mo | $258/mo | **$1,176.42/mo** |
| **ZoomInfo Enterprise** | $1,328/mo | $219/mo | **$1,547/mo** |

👉 Run custom volumes, monthly vs. annual billing, or 35% mobile phone reveals in the [Outbound Stack Cost Calculator](https://gtmfacts.com/calculator/).

---

## Key Head-to-Head Audits

- [Apollo.io vs ZoomInfo](https://gtmfacts.com/compare/apollo-vs-zoominfo/)
- [Clay vs Apollo.io](https://gtmfacts.com/compare/clay-vs-apollo/)
- [Instantly vs Smartlead](https://gtmfacts.com/compare/instantly-vs-smartlead/)
- [ZeroBounce vs NeverBounce](https://gtmfacts.com/compare/zerobounce-vs-neverbounce/)
- Alternatives: [Clay](https://gtmfacts.com/alternatives/clay/) · [Apollo.io](https://gtmfacts.com/alternatives/apollo/) · [ZoomInfo](https://gtmfacts.com/alternatives/zoominfo/) · [Instantly](https://gtmfacts.com/alternatives/instantly/)

---

## Files in This Repository

- `data/pricing.json` — Structured pricing tiers, credit allowances, billing units, and official URLs for all 13 audited vendors.
- `data/changelog.json` — 6 verified pricing, packaging, and credit-rule diffs.

## Contributing & Corrections

Spotted a vendor pricing change or credit-rule update? Open an issue here or submit a primary-source correction via [GTMFacts Changelog](https://gtmfacts.com/changelog/).

## License

Data and documentation are published under **CC BY 4.0** — free to reuse in research, spreadsheets, RevOps models, and articles with attribution to [GTMFacts](https://gtmfacts.com/).
