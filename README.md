# ai sales agent cost: what you actually pay per month, per message, and per booked appointment

Most people searching for AI sales agent cost get handed a range so wide it's useless: $50 a month on one page, $200,000 on the next. Both numbers are real, they just describe completely different things.

Here's the split that actually matters. There's the platform fee, which is what vendors advertise. There's the usage layer — AI replies, tokens, credits, minutes — which is what shows up on the second invoice. And there's the cost per booked appointment, which is the only number that tells you whether any of it was worth paying for.

CloseBot is a useful case study for working through all three, because its pricing page publishes plan prices and per-message costs side by side rather than hiding the second half behind a sales call.

## The three price bands, and where each one lives

Coffee's 2026 pricing guide puts AI sales agents into three tiers, and the boundaries are consistent across most of the vendor pages we looked at:

| Band | Typical 2026 price | What you're actually buying |
| --- | --- | --- |
| CRM copilots | $30–$150 per user / month | Suggestions, summaries, data entry for human reps |
| Task bots | $50–$500 per month | Lead qualification, outreach sequences, booking |
| Autonomous SDR platforms | $900–$10,000+ per month | Full prospecting and follow-up without a human |

CloseBot sits in the task-bot band: platform fee from $0 to $397 a month, then a per-message element depending on which track you're on. If your mental budget started at "$900 because that's what an AI SDR costs," you're shopping one band above where most small teams and agencies actually land.

Voice-first agents are priced differently again — per minute rather than per message. Retell publishes per-minute rates starting at $0 with no monthly minimum. That's not a better or worse model, it's just a different unit, and mixing the two up is how cost comparisons go sideways.

## Why the sticker price is never the bill

Every vendor quote we found for 2026 comes with the same warning attached. Coffee's guide cites real-world spend running about 30% above sticker prices from credit overages, per-seat compounding, and integration work, and notes that true Year 1 total cost of ownership typically lands at 1.4–1.6x the initial vendor quote.

Instantly's pricing breakdown is blunter about the mechanism: unmonitored credit pools turn a predictable $500 monthly tool cost into a $2,000 invoice during a campaign surge. They also flag the expiry trap, where monthly plan credits lapse two months after purchase, penalising anyone who sized their tier against peak volume instead of average.

So when you're comparing an AI sales agent's cost, the question isn't "what's the monthly fee." It's:

- Is usage metered separately, and at what unit price?
- What happens exactly at the limit — throttling, or a per-unit overage charge?
- Do unused units roll over, expire, or vanish?
- Are seats, storage, and CRM connections billed on top?
- Can you plug in your own model API key to control the biggest variable cost?

That last one is where CloseBot has a firm, deliberate answer.

## What a "message" actually costs

Two per-message numbers get quoted for CloseBot, and they apply to different people.

**Free plan: $0.08 per message over the cap.** The free tier includes 100 AI replies a month. Go past that and you pay as you go at $0.08 each — which, incidentally, is worth doing the maths on. At 1,000 messages a month, staying on the free plan costs $72 in overages. The paid business tier starts at $64 with a 500-message pool. The upgrade is often cheaper than the overage.

**Agency track: a flat $0.012 per message, rebillable.** CloseBot removed the old model where agencies paid $0.006 per message plus their own OpenAI token fees. Under that arrangement, a top agency CloseBot documented paid $1,173 to OpenAI and $521 to CloseBot in October 2025 — $1,694 total. Under the new flat rate, the OpenAI bill drops to $0 and the same volume costs about $1,042. CloseBot's own figure for the saving is 38%.

Business plans work the opposite way: message costs are included in the base price rather than metered on top.

Two caveats worth knowing before you build a budget:

> One message equals one segment — unless you switch on the Agent Node's "unlimited potential" setting (lots of tools, unlimited instruction size), at which point billing moves to token costs and a single message can consume several segments.

And there's no bring-your-own-key option. CloseBot's stated reason is security compliance, and it means your model spend is baked into the plan rather than something you can optimise separately. If you want to control AI costs by swapping models yourself, this is the wrong architecture for you.

## The full CloseBot price list

Here's what the plans page currently shows, all four tiers:

| Plan | Core configuration | Price | Billing | Get it |
| --- | --- | --- | --- | --- |
| **Free** | 1 agent, 1 user seat, 100 monthly AI replies, 1 MB knowledge storage, unlimited account connections | $0 | Forever, no credit card | Start on the free plan |
| **Core (Business)** | Message costs included in the base price, monthly reply pool starting at 500, 15+ templates, human support; add users at $5/seat, storage from $0.10–$3.00 per MB/month | From $64/mo USD monthly, or $53/mo billed as $640/yr | Month to month, 7-day trial | Check the Core business pricing |
| **Core (Agency)** | Unlimited agents across unlimited sources, white-label client portal, re-bill all costs, usage at a flat $0.012/message; additional seats $5 | $397/mo USD monthly; annual billing works out around $331/mo | Month to month, 7-day trial | See the Agency plan in detail |
| **Growth** | SLAs, HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, 50+ templates | Custom quote | Contracted | Request a Growth tier quote |

The business track is modular rather than fixed: the plans page has a volume selector running from 100 messages up to 100K+, and the monthly price rises with the reply pool you choose. A third-party review published in August 2026 lists the ladder as roughly $64 at the entry pool, $84 for 1,000 messages, $109 for 2,000, $176 for 5,000, $454 for 20,000, and $806 for 50,000. Treat those mid-tier figures as one reviewer's reading of the slider rather than a price list CloseBot publishes in text — but the shape of the model is clear. Bigger pool, better per-message rate.

Extra costs that don't appear in the headline number: additional user seats are $5 each on both paid tracks, and business storage add-ons run $0.10 to $3.00 per MB per month depending on how much you need. One MB is roughly 1,000 pages of text, so most small operations never touch this line.

## Worked example: the same lead volume, three ways

Assume you're handling 2,000 inbound AI replies a month.

- **Free plan.** 100 included, 1,900 at $0.08 = $152 in overages, plus no live chat support, job flows capped at 5 actions, and access to only 2 AI providers. Cheapest on paper, worst on capability.
- **Business track.** Around $109/month at that volume per the third-party ladder, with message costs included. Roughly $43 less than free-plan overage, with the free tier's feature locks removed.
- **Agency track.** $397/month flat plus $0.012 × 2,000 = $24 in usage, which you rebill. Higher entry price, but it's the only one of the three where the subscription is designed to be resold.

Only one of these is a "cheap AI sales agent" and only one is a business model. They're frequently the same search.

If you'd rather not guess at your volume before signing up, the free plan and the paid trials are the honest way to size it. 👉 Try CloseBot free and count your actual replies for a month.

## Cost per booked appointment is the number to defend

Instantly's formula is the cleanest one published: **(software cost + infrastructure cost + data cost) ÷ total meetings booked**, applied monthly rather than annually, so a slow quarter doesn't get averaged away.

CloseBot's contribution to that equation is straightforward: platform fee plus per-message cost. It is not a closed-loop revenue system. It qualifies, follows up, and books.

What the vendor claims on top of that, in its own marketing: over 1 million booked appointments, roughly 150K daily messages, 99.99% uptime, and 1,000+ agencies on the platform. Those are company-published numbers, not audited ones. The independent signals that exist: a 4.8/5 rating on G2, and a third-party review of CloseBot for GoHighLevel users that scores value for money at 4.0/5 while flagging that per-message fees between $0.012 and $0.08 "create variable monthly costs at high volume." That's the same critique everyone in this category earns.

Worth holding against the benchmark: a fully loaded US SDR costs $110,000–$160,000 in year one once salary, benefits, payroll taxes, recruiting, onboarding, and a per-rep tech stack are counted (SalesHive's figure, cited in Instantly's guide). If your AI agent stack runs $1,700–$6,700 a year on a flat-fee-plus-credits model, as Instantly estimates, you don't need a heroic conversion rate to justify it. You need the follow-up to actually happen.

## If you resell AI, the cost line flips into a revenue line

This is the part of AI sales agent cost that agency owners care about, and it's where CloseBot's pricing model is the most distinctive thing about it.

On the $397/month agency track, you pay a flat $0.012 per message and you re-bill it. You set your own markup, your clients top up a wallet that pays into your Stripe account, and the difference is your margin. The same mechanism applies to seats, storage, and — if you choose — AI token costs.

The scale of the spread is the whole point. CloseBot says polled agencies bill an average of $500 per client per month. Against $64 a month plus $0.012 per message, the platform fee is a rounding error in the client invoice. That's also why the "cheapest platform" question is often the wrong one for an agency: a $64 tool with no rebilling is more expensive than a $397 tool with it.

One vendor-published case study describes an agency selling CloseBot builds for $5,000 in setup plus $500/month ongoing. Different operator, different market, but it shows the ceiling isn't the license.

If your model is building AI setters as a productised service, 👉 look at the agency track's rebilling setup before you compare it to anything per-seat.

## Discounts and trials: what's real

CloseBot publishes one official discount code and says so explicitly: **CLOSEBOT100OFF**, which takes $100 off your first payment and works on both Business and Agency plans. Everything else circulating on coupon aggregators is either an expired partner code or scraped clickbait.

The bigger structural saving is annual billing: two months free, which brings Core to $53/month when billed as $640/year. On the agency track, third-party reviews put the annual equivalent at around $331/month.

Then the three things that are not negotiable, straight from the plans page:

- **No refunds.** None. That's why the free plan and the 7-day trial exist.
- **7-day trial on any paid plan**, including Agency — enough to test white-labelling and re-billing before you're charged.
- **No lock-in.** Plans outside Growth run month to month; upgrade, downgrade, or cancel any time.

A 7-day trial and a free-forever plan under 100 messages are a legitimate way to answer "what does this cost me" with your own numbers. 👉 Start the trial and run it against real leads.

## How the per-unit costs compare across 2026 options

Different units, so read the right column carefully:

| Tool | Pricing model | The unit you're actually paying for |
| --- | --- | --- |
| CloseBot | $0–$397/mo platform + usage | AI replies ($0.012 agency, $0.08 free overage) |
| Fin for Sales | $9.99 per qualified lead | Outcomes, where you define "qualified" |
| Microsoft Copilot for Sales | $50/user/mo standalone, plus credits at $0.01 | Seats, then Copilot Credits per task |
| Instantly | Flat $47 / $97 / $358 + credits from $9 | Leads and AI replies at 5 credits each |
| Lemlist | $55–$109 per seat | Human seats |
| GoHighLevel native AI | Up to $0.02 per message | Messages inside the CRM |

The pattern: per-outcome pricing punishes you when qualification is subjective; per-seat pricing punishes you as headcount grows; per-message pricing punishes you when volume spikes. CloseBot sits on the third and competes with GoHighLevel's own conversational AI at roughly 40% less per message — $0.012 versus up to $0.02 — which is the comparison that matters if GoHighLevel is already your CRM.

And budget for the CRM itself. CloseBot is a brain that sits on top of one; the GoHighLevel or HubSpot subscription is a separate line item that a review of the system puts at $97/month and up for the entry tier. A solo operator wanting 1,000 AI messages a month is realistically looking at two subscriptions, not one.

## Who shouldn't pay for this at all

An independent 2026 evaluation of CloseBot is unusually specific about where it doesn't fit, and it's worth repeating rather than smoothing over:

- Businesses that already answer every inbound lead within two minutes. The AI's whole value proposition is response speed you already have.
- Sales requiring custom proposals, scope negotiation, or multi-party deal closing. It qualifies and books; humans close.
- Operators with no time to maintain an accurate knowledge base. Weak inputs scale fast, in the wrong direction. As one G2 reviewer quoted in a competitor comparison put it: if your pipeline, messaging, offer, and follow-up logic are sloppy, the AI just scales that sloppiness faster.
- Anyone treating it as a DM tool. CloseBot has no native Instagram or WhatsApp connection of its own — it answers whatever channels are already wired into your CRM.

The flip side is the same review's "best for" list: GoHighLevel operators with slow lead response, agencies re-billing AI qualification to client accounts, service businesses that get inquiries after hours, and teams whose conversion goal is a booked calendar slot.

## FAQ

**How much does CloseBot cost per month?**
Free forever at $0 for up to 100 AI replies. The Core business tier starts at $64/month with message costs included, dropping to $53/month on annual billing ($640/yr). The agency tier is $397/month flat with rebillable usage at $0.012 per message, around $331/month equivalent annually. Growth is custom-quoted.

**Is there a free trial?**
Two, effectively: a free-forever plan capped at 100 messages and a 7-day trial on any paid plan, Agency included. No refunds, so use the trial window properly.

**Do I pay separately for the AI model or API tokens?**
Not on CloseBot. The company moved agencies from a $0.006-per-message-plus-your-own-OpenAI-key model to a flat $0.012 per message, and it doesn't allow bring-your-own-key for security reasons. Your model spend is inside the plan price.

**What's the cheapest legitimate way to test an AI sales agent?**
The free tier, with an honest count of how many replies you actually need. If you cross roughly 800 messages a month, the $0.08 free-plan overage puts you above the entry paid tier anyway. 👉 Compare the free and paid tiers side by side.

**Is an AI sales agent cheaper than hiring?**
The labour math isn't close — $110K–$160K for a fully loaded SDR in year one against a few thousand a year for a task-bot stack. The real question is coverage: your human rep works eight hours, and most inbound leads don't.
