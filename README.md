# closebot vs botpress: which fits GoHighLevel and HubSpot agencies, and what each plan really costs

Somebody searching this comparison usually has the same problem in the background: leads are sitting in a CRM, replies are too slow, and there's a budget line for "AI" that needs to turn into booked calls. Then two very different tools show up in the same shortlist.

CloseBot and Botpress both get filed under AI agents, and both can chat with a lead. After that, they stop resembling each other. One is a sales setter wired into your CRM. The other is a build-anything agent platform, mostly aimed at support and internal automation. Picking the wrong one doesn't usually show up as a broken product. It shows up six weeks later as a half-built bot nobody wants to maintain.

Here's the honest split.

## Two platforms, two different jobs

CloseBot does one thing: it qualifies inbound leads and puts meetings on the calendar, on text channels, inside the CRM you already use. HighLevel and HubSpot are native integrations; Salesforce, Podio and custom stacks are covered too. It also runs standalone without a CRM at all.

It's text-only. No voice, no video, and no support-desk ambitions. CloseBot's own material is blunt about that: it's built for lead qualification and booking, not customer service tickets.

Botpress is the opposite shape. It's a platform for building agents: a visual flow builder (Studio), code-level access through its ADK and API, a helpdesk product (Desk), WhatsApp and Viber channels, webchat, and voice on the enterprise tier. Teams use it for support automation, internal tools, intake workflows, and, yes, sometimes lead capture.

So the overlap is narrower than the search suggests. If your goal is "replies in seconds, qualified, booked on a calendar", you're comparing a purpose-built tool against a general-purpose one. If your goal is "a bot that answers 40 support questions and hands off to a human", CloseBot was never in that race.

## Side-by-side on the things that decide it

|  | CloseBot | Botpress |
| --- | --- | --- |
| Primary job | Lead qualification, follow-up, appointment booking | General AI agent and support automation |
| Where it lives | Inside HighLevel, HubSpot, Salesforce, Podio, custom stacks, or standalone | Botpress workspace, deployed to webchat, WhatsApp, Viber, Messenger, voice (Enterprise) |
| Pricing unit | Monthly platform fee + messages | Monthly platform fee + conversations |
| Free tier | 1 agent, 1 seat, 100 messages/month | 25 conversations/month, 3 seats, 3 AI agents |
| Entry paid price | $64/month (business), $397/month (agency) | $150/month billed annually (Plus) |
| Agency/reseller model | White-label portal, per-message costs you mark up and rebill | Whitelabel webchat on Plus; no native rebilling layer |
| Voice | Not offered | Enterprise tier |
| Voice/video channels | Text only | Text, voice on Enterprise |
| Compliance angle | HIPAA on the Growth plan, 99.99% uptime infrastructure | HIPAA BAA and data residency options listed on higher tiers |
| Languages | CloseBot advertises 40+ | Botpress positions translation and multilingual flows across its product |
| Setup style | Objective-based drag-and-drop "job flows", no prompting required, testing portal | Visual flow builder plus code cards, variables, integrations, API/ADK |
| Best fit | Agencies and businesses that sell appointments | Teams that need to automate conversations broadly |

Read that table twice before you sign up for anything. Most of the disappointment in this category comes from buying a general platform for a specific job, or a specific tool for a general job.

## The pricing models do different things to your invoice

CloseBot charges per message. Botpress charges per conversation, and that's a real difference in behavior, not just vocabulary.

On Botpress, a conversation is any exchange with at least two messages from the end user in the billing month. The included volumes are 25 on Free, 250 on Plus, and 1,500 on Team. When you go over, the page shows a pack of 100 extra conversations for $65 on Plus ($0.65 each) or $50 on Team ($0.50 each). Packs are added automatically at 95% of quota and don't roll over at month end. AI usage is bundled into the plan now, which is a change from the older model where LLM spend was billed separately at cost. Botpress also notes that workspaces created before May 14, 2026 keep the previous pricing, so the numbers on the page don't apply to every existing account you'll talk to.

On CloseBot, a message is one segment unless you're using the Agent Node with tools and unlimited instruction size, in which case you're billed in tokens and can burn more than one segment per message. Business plans include message costs in the base price with a ceiling; going over draws from a wallet. The free plan includes 100 messages a month and charges $0.08 per message past that. Agency accounts are billed a flat per-message rate that they can rebill at their own markup.

Which model is cheaper depends entirely on conversation length. Support chats tend to run long with many messages, which favors per-conversation pricing. Lead qualification is usually a short, tight exchange: a handful of questions, a booking, done. That's where a low per-message cost wins, and it's also why CloseBot's free tier is usable for testing with real leads rather than just a demo sandbox.

Three things are worth flagging before you build a business case on either pricing page:

- CloseBot does not offer refunds, but every paid plan comes with a 7-day trial, and the free plan stays free as long as you stay under 100 messages.
- CloseBot expects you to bring your own AI provider keys in V2, so Anthropic or OpenAI token costs are a separate line item. That's the trade for not being locked to CloseBot's model choices.
- Botpress's conversation packs don't expire until month end, and unused conversations in a pack disappear.

## CloseBot plans in full

These are the plans currently shown on CloseBot's pricing page, plus the stepped business tiers still documented in its help center.

| Plan | What you get | Price | Billing | Get started |
| --- | --- | --- | --- | --- |
| Free | 1 agent, 1 user seat, 100 messages/month, 1 MB upload storage, unlimited account connections | $0 | Always free | [ Start on CloseBot's free plan](https://app.closebot.com/a?fpr=li87) |
| Core (Business) | Business agents for your own pipeline, human support, 15+ templates, add extra seats ($5 each), storage and agents as add-ons | $64/month, or $640/year upfront (about $53/month effective) | Monthly or annual | [ Compare CloseBot's business plans](https://app.closebot.com/a?fpr=li87) |
| Core (Agency) | Unlimited agents and sources, white-label client portal, rebill all costs, client wallets and markup, 1 seat included | $397/month, about $331/month effective on annual billing | Monthly or annual | [ Check CloseBot's agency plan and rebilling](https://app.closebot.com/a?fpr=li87) |
| Growth | SLAs, HIPAA compliance, quarterly audits, 99.99% priority uptime, priority support, high volume | Custom quote | Custom, via sales | [ Ask about CloseBot's Growth plan](https://app.closebot.com/a?fpr=li87) |

One wrinkle worth knowing: CloseBot's help center still lists stepped business tiers at $197/month for 3 job flows, $297/month for 10, and $397/month for unlimited job flows. The current plans page presents business pricing as a base of $64 that scales with monthly message volume instead. Treat the older tier list as a map of what scaling looks like, and confirm the exact number in the app before you commit. Same applies to the per-message agency rate: the plans page FAQ states $0.012 per message, while some older CloseBot posts and support articles cite $0.006. The pricing page is the one to trust until you see your own invoice.

## Botpress plans in full

Botpress doesn't have an affiliate link in this article, so these are listed for comparison only.

| Plan | What you get | Price |
| --- | --- | --- |
| Free | 25 conversations/month, 3 seats, 3 AI agents, Help Center, community support, no top-ups or overages | $0 |
| Plus | 250 conversations/month, extra packs of 100 for $65, 3 seats, unlimited AI agents, WhatsApp, whitelabel webchat, custom Help Center domain, live chat support | $150/month billed annually |
| Team | 1,500 conversations/month, extra packs of 100 for $50, unlimited seats, Teams and routing, RBAC, team analytics, real-time collaboration | $750/month billed annually |
| Built For You | Botpress's team builds and maintains your agents for you, custom conversation volume | $1,650/month |
| Enterprise | Dedicated support, uptime SLA, security review, custom storage, voice channel, custom data retention | Custom |

Free storage on Botpress is tight: 100 MB vector, 100 MB file, 1,000 table rows. Plus moves to 1 GB and 10 GB, Team to 5 GB and 50 GB, and there's a $40/month storage add-on that adds 100,000 rows, 1 GB of vector storage, and 10 GB of file storage. If your knowledge base is a few hundred PDFs, price that add-on in from the start.

## The agency question: white label and rebilling

If you're an agency selling AI to clients, this is usually the deciding factor, not features.

CloseBot's agency plan is built around the reseller workflow. You get a white-label client portal, client wallets funded by Stripe that pay straight to you, rebillable per-message costs, seats at $5 each that you can mark up too, and per-client reporting. The pitch is simple: your clients see your brand, your usage costs become your margin, and you set the markup. CloseBot also says the business plan won't show you any of the rebilling or white-label tooling, so an agency that starts on business will end up migrating.

Botpress's agency story is thinner. Whitelabel webchat is included on Plus, so you can remove Botpress branding from the widget, and there's no per-seat cost on Team, which helps if you want to give clients logins. What's missing is the rebilling layer: no client wallets, no usage markup mechanism, no built-in portal designed for resale. You can absolutely sell Botpress-based agents to clients, and plenty of teams do, but the billing and margin infrastructure is your problem. If that sentence sounds fine, Botpress is a legitimate option. If you want the platform to handle the client billing mechanics, CloseBot is the one that was designed for it.

## Implementation, testing, and what breaks first

CloseBot's builder is objective-based. Instead of writing prompts, you define goals: qualify this lead, collect these fields, book this calendar slot. The AI works through them and adapts. There's a testing portal to preview responses and see which properties, lists, or calendars will get updated before anything goes live, persona A/B testing, a human takeover pause on any conversation, and Smart FAQ, which flags questions the agent couldn't answer so you answer once and CloseBot follows up with every lead who asked. Everything in the UI is also available through the API.

Botpress gives you more raw capability and more ways to get lost. The visual builder handles nodes, variables, and AI tasks; code cards handle the rest; the ADK and API cover advanced cases. Users on G2 consistently describe it as flexible and genuinely no-code friendly for standard flows, then mention the same friction points: documentation gaps, a learning curve that runs toward a month for complex builds, and workflow logic that gets tangled as bots grow. Multiple reviewers specifically ask for better visibility into AI usage costs.

Rough rule from the reviews: CloseBot's quality tracks the quality of the flow you build. One G2 reviewer summed it up as poorly designed pipelines and follow-up logic just scaling faster. Botpress's quality tracks how much time you're willing to spend learning the platform.

## Channels, compliance, and languages

CloseBot runs on all text channels inside your CRM: SMS, email, live chat, Facebook Messenger, Instagram, WhatsApp where your CRM supports it. Conversations stay in the CRM, data is held there, and the HubSpot app listing confirms the app uses HubSpot webhooks and API calls rather than storing contact data elsewhere. HIPAA compliance sits on the Growth plan. CloseBot advertises 40+ languages and notes that if Claude and ChatGPT handle your language, so will the agents, since it uses the same underlying models.

Botpress covers webchat, WhatsApp, Viber, Messenger, and email-style channels, with voice on Enterprise. It lists a formal BAA for HIPAA, custom data retention and residency policies, and DPA documentation on higher plans, which matters if you're selling into procurement. If voice is on your roadmap, close the comparison here: CloseBot doesn't do it, and Botpress does on Enterprise.

## What the ratings actually say

On G2, CloseBot holds 4.8 out of 5 across roughly 190 reviews, with reviewers consistently pointing at ease of use and fast setup. Botpress sits at 4.5 out of 5 across 512 reviews, praised for flexibility, integrations, and the visual builder, and criticized most often for documentation.

Neither number should decide anything on its own. CloseBot's review base is smaller and skews toward agencies and local-service businesses, which is exactly the audience the product targets. Botpress's base is bigger and more varied, so it includes enterprise support teams with requirements CloseBot doesn't serve. Compare the reviews from people who do your job, not the averages.

## So which one should you actually pick

Pick CloseBot if the goal is booked appointments and your leads live in HighLevel, HubSpot, or a similar CRM. It's the shorter path: fewer moving parts, a free plan you can test with real leads, and an agency tier that handles client billing and branding if you're reselling. The trade-offs are real, though: text only, no support-desk features, no refunds, and you bring your own model keys.

Pick Botpress if you're building agents for support, internal operations, or multi-channel experiences, or if you need voice, WhatsApp, an open builder with code access, and enterprise compliance paperwork. The trade-offs are a steeper learning curve, documentation gaps that users complain about regularly, conversation-based billing that punishes long chats less and short bursts more, and no native reseller billing layer.

Two specific cases settle fast. If you're an agency whose offer is "we'll answer and book your leads in 30 seconds", that's CloseBot's whole product, and Botpress means building it yourself. If your offer is "we'll automate your support desk across WhatsApp and voice", Botpress is the platform and CloseBot simply isn't an option.

A last note on sequencing, since this trips up a lot of teams: decide the job first, then the platform. The cost difference between the two pricing models at your actual volume is usually smaller than the cost of rebuilding the wrong bot three months in.

[👉 See CloseBot's current plans and start with the free tier](https://app.closebot.com/a?fpr=li87)
