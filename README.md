# Awesome-Email-Marketing-Newsletter-Automation

## Top Email Marketing & Newsletter Automation Ecosystem

**Curated List of SaaS Platforms & Open-Source GitHub Projects**  
*Focused on Campaign Sending, Subscriber Segmentation & Self-Hosted Automation*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Email Marketing & Newsletter Automation**. These tools help organizations build subscriber lists, send campaigns, and automate welcome sequences—covering everything from creator-focused newsletter platforms to full lifecycle automation suites with behavioral triggers.

**Examples** include Mailchimp, ActiveCampaign, Brevo, Klaviyo, MailerLite, ConvertKit (Kit), GetResponse, Campaign Monitor, Constant Contact, and open-source alternatives like Mautic, Listmonk, and Keila (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted email marketing, open-source newsletter senders, and community-driven automation—ideal for organizations seeking data sovereignty and avoiding per-subscriber pricing that punishes list growth. The open-source landscape splits into **full automation platforms** (Mautic, Helio) for visual journeys, and **high-performance senders** (Listmonk, Keila) that prioritize deliverability and throughput over complex branching .

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Mailchimp](https://mailchimp.com/)** | Industry-standard email marketing with automation flows (up to 200 on Standard/Premium), predictive segmentation, and a familiar editor. Free plan capped at 500 contacts/1,000 sends; Essentials automation limited to 4 steps. Phone support reserved for Premium ($350/month at 500 contacts) . | Essentials: from **$13/month** (500 contacts); Standard: ~$20/month; Premium: ~$350/month  | **Free**: 500 contacts, 1,000 sends/month, 4-step automation; **14-day trial** for paid tiers . |
| **[Brevo](https://www.brevo.com/)** | Low-cost email/SMS platform with a genuine free plan (300 emails/day, unlimited contacts). Standard tier unlocks **unlimited automation workflows** at ~$31.50/month (annual) for 1,000 contacts—half the cost of ActiveCampaign Plus . | Starter: **$9/month** (~$15.30 annual at 1,000 contacts); Standard: ~$31.50/month (annual, unlimited automation)  | **Free**: 300 emails/day forever, unlimited contacts, 2,000 unique contacts in automation . |
| **[ActiveCampaign](https://www.activecampaign.com/)** | Automation-first platform with deep behavioral triggers and CRM. **Hidden costs**: contact overages, dedicated IP ($95–150/month), SMS credits, inbox preview, and annual price increases. Negotiation can cap increases at 3% . | Starter: **$15/month** (annual, 1,000 contacts); Plus: ~$49/month  | Free trial available; no permanent free tier . |
| **[Klaviyo](https://www.klaviyo.com/)** | E-commerce-focused automation with deep Shopify integration, predictive analytics, and revenue attribution. Free plan: 250 profiles, 500 emails/month. Marketing plan from $20/month (500 profiles) . | Free: **$0** (250 profiles, 500 sends); Marketing: **$20/month** (500 profiles)  | **Free**: 250 profiles, 500 emails/month, basic templates, 60 days email support . |
| **[MailerLite](https://www.mailerlite.com/)** | **Major restructuring June 2026**: paid plans moved to Comfort/Power. **Free plan limited to 3 automations, 3 forms, 1 landing page**. Comfort unlocks 50 automations, 10 forms, and preference center; Power removes all limits. No opting out of new structure . | Free: **$0** (1,000 subscribers, 3 automations); Comfort/Power: quote-only  | **Free**: 1,000 subscribers, 12,000 emails/month, 3 automations, 3 forms . |
| **[Kit (ConvertKit)](https://convertkit.com/)** | Creator-first platform with generous free tier: **up to 10,000 subscribers** with unlimited emails, forms, and landing pages—but only **one automation**. Creator ($39/month at 1,000 subs) unlocks visual automations and integrations . | Free: **$0** (10,000 subscribers, 1 automation); Creator: **$39/month** (1,000 subs)  | **Free**: 10,000 subscribers, unlimited broadcasts/forms/landing pages, 1 automation, Kit branding . |
| **[GetResponse](https://www.getresponse.com/)** | Email marketing with landing pages, webinars, and AI course creator. **14-day trial** unlocks premium features; free plan thereafter has limits (1,000 unique landing page visitors/month, badge on emails, no dynamic segments) . | Free: **$0** (limited); Starter: quote via pricing page; **18% discount** for 12-month prepay  | **Free**: basic email, limited landing pages/automation; **14-day premium trial** . |
| **[Campaign Monitor](https://www.campaignmonitor.com/)** | Polished campaign creation for agencies and teams. **No permanent free plan**—Lite includes monthly sends capped at ~5x contacts; Essentials unlocks unlimited sends. Drag-and-drop website builder is a $10/month add-on on Lite/Essentials . | Lite: **$47/month** (1,000 contacts); Essentials: **$74/month** (1,000 contacts, unlimited sends)  | **30-day trial**: up to 500 contacts and 500 emails (not a free plan) . |
| **[Constant Contact](https://www.constantcontact.com/)** | SMB-focused with events, social posting, and phone support below top tier. Plans scale by contacts: Lite ($12/month) has 1 automation template, 1 user; Standard ($35) adds 3 templates and 3 users; Premium ($80) unlocks custom automations, unlimited users, and 500 SMS . | Lite: **$12/month**; Standard: **$35/month**; Premium: **$80/month**  | **No permanent free plan**; trial and guarantee terms may apply . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Mautic](https://github.com/mautic/mautic)** | [![Stars](https://img.shields.io/github/stars/mautic/mautic?style=social&color=white)](https://github.com/mautic/mautic/stargazers) | **The most powerful open-source marketing automation platform.** GPL-3.0, PHP. **~11k GitHub stars**, actively maintained. **Visual campaign builder with conditional branching**, lead scoring, dynamic content, and multi-channel touchpoints beyond email. Native integrations with WordPress, Salesforce, and major CRMs. **Self-hosted edition is unrestricted and free**. Heavier to run than simple newsletter tools—requires proper server resources and has a steeper learning curve . **Best for teams wanting HubSpot-style automation depth without per-contact fees.** |
| **[Listmonk](https://github.com/knadh/listmonk)** | [![Stars](https://img.shields.io/github/stars/knadh/listmonk?style=social&color=white)](https://github.com/knadh/listmonk/stargazers) | **The most popular open-source newsletter and mailing list manager.** AGPL-3.0, Go. **~24k GitHub stars**, highest health score in 2026 comparisons. **Single binary deployment** with PostgreSQL as the only dependency. High-performance architecture sends millions of emails from your own SMTP relay. Supports both transactional and bulk campaigns, public API for integrations, and dynamic templates. **Trade-off: no built-in drip sequences or behavioral triggers**—you write automation against the API and run it from cron . **Best for developers wanting a fast, lightweight newsletter sender with full relay flexibility.** |
| **[Keila](https://github.com/pentacent/keila)** | [![Stars](https://img.shields.io/github/stars/pentacent/keila?style=social&color=white)](https://github.com/pentacent/keila/stargazers) | **Modern EU-based newsletter tool with GDPR-first design.** AGPL-3.0, Elixir/Phoenix. **~2.2k GitHub stars**, actively maintained. **Polished interface**—the most modern UX among open-source email tools. Sends through SES, SendGrid, Mailgun, Postmark, or any SMTP. **One welcome email per signup form**; multi-step automations are on the roadmap but not shipped as of late 2026. Segments can filter on opens and clicks. Docker image available . **Best for EU teams prioritizing data sovereignty and a clean interface over complex automation.** |
| **[Helio](https://github.com/achref-soua/helio)** | [![Stars](https://img.shields.io/github/stars/achref-soua/helio?style=social&color=white)](https://github.com/achref-soua/helio/stargazers) | **Ambitious open-source marketing platform with AI copilot and visual journeys.** TypeScript/Python/PostgreSQL. **React Flow journey canvas** → validated DAG → durable Temporal workflows (survives `kill -9`). Segment builder with nested AND/OR. Block-based email templates with `{{token|fallback}}` personalization and RFC 8058 one-click unsubscribe. **AI copilot** drafts segments, journeys, and on-brand emails from a sentence. **MCP server** for external AI agents. One-click importers for HubSpot/Mailchimp/Klaviyo exports. **Status: v0.6.0 (2026)**—multi-channel and growth tooling are on the roadmap . **Best for teams wanting a modern, AI-native open-source alternative to Mailchimp with real automation depth.** |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[phpList](https://github.com/phpList/phplist3)** | [![Stars](https://img.shields.io/github/stars/phpList/phplist3?style=social&color=white)](https://github.com/phpList/phplist3/stargazers) | **Veteran open-source newsletter tool, actively maintained since 2000.** AGPL-3.0, PHP. Handles lists, campaigns, bounce processing, and **basic scheduled autoresponders**. Extremely mature and stable with low resource footprint. **UI is dated** and advanced features require plugins . **Best for non-profits and community organizations wanting proven reliability with basic automation.** |
| **[NetSendo](https://github.com/NetSendo/NetSendo)** | [![Stars](https://img.shields.io/github/stars/NetSendo/NetSendo?style=social&color=white)](https://github.com/NetSendo/NetSendo/stargazers) | **Self-hosted professional email marketing with SMS, CRM, and AI integrations.** Laravel/Vue/Docker. Features email and SMS workflows, CRM pipelines, analytics, live visitor tracking (via Laravel Reverb WebSocket), and optional AI keys for OpenAI/Claude/Gemini . **Best for teams wanting a full-stack email + SMS + CRM platform in one self-hosted package.** |

**Frameworks for building custom systems**: Choose **Mautic** for the deepest open-source automation with visual branching and lead scoring , **Listmonk** for the fastest, most reliable newsletter sender with full relay flexibility , **Keila** for EU data sovereignty and a polished modern UI , and **Helio** for an AI-native platform with durable Temporal journeys —all without per-subscriber pricing that scales against you.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Email marketing platforms handle subscriber PII and sending reputation; enforce double opt-in, clear unsubscribe mechanisms, and compliance with CAN-SPAM, GDPR, and applicable anti-spam regulations. **Self-hosted sending requires proper domain authentication (SPF, DKIM, DMARC) and IP warm-up**—misconfiguration leads to deliverability failures.
- **SaaS pricing changes frequently and hidden costs compound.** MailerLite restructured all paid plans in June 2026 with no opt-out—free plans now cap at 3 automations and 3 forms . ActiveCampaign's add-ons (dedicated IP $95–150/month, SMS credits, inbox preview) and annual price increases can significantly raise total cost without negotiation . Campaign Monitor has **no permanent free plan**—the 30-day trial is not a free tier, and Lite's send cap requires upgrading to Essentials for unlimited sends . **Open-source tools have different trade-offs**: Listmonk and Keila lack built-in drip sequences (Listmonk requires cron/API automation; Keila has one welcome email only) , while Mautic and Helio provide full visual automation at the cost of heavier infrastructure .

---

**Made for growth marketers, newsletter operators, and developers building email marketing infrastructure.**  
Let's make email marketing and newsletter automation more open, deliverable, and subscriber-friendly.
