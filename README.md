# Awesome-Support-Ticket-Case-Management

# Awesome Support Ticket & Case Management

> A curated list of top Support Ticket and Case Management platforms — both SaaS/Hosted commercial solutions and open-source alternatives for managing customer inquiries, incidents, and service requests.
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Zendesk Support](#zendesk-support)
  - [Freshdesk](#freshdesk)
  - [Zoho Desk](#zoho-desk)
  - [Jira Service Management](#jira-service-management)
  - [ServiceNow Customer Service Management](#servicenow-customer-service-management)
  - [Help Scout](#help-scout)
  - [LiveAgent](#liveagent)
  - [HappyFox](#happyfox)
  - [Kayako](#kayako)
  - [Deskpro](#deskpro)
- [Open-Source Software](#-open-source-software)
  - [Zammad](#zammad)
  - [Znuny](#znuny)
  - [OTOBO](#otobo)
  - [FreeScout](#freescout)
  - [Frappe Helpdesk](#frappe-helpdesk)
  - [Libredesk](#libredesk)
  - [Helpy](#helpy)
  - [ITFlow](#itflow)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Support Ticket and Case Management platforms. These are not open-source but are included as reference points for feature comparison.

### Zendesk Support
**Type:** Enterprise support suite with deep configurability  
Zendesk is the long-standing enterprise standard for support ticketing, offering omnichannel routing, SLA policies, and analytics. Its strength is configurability—large operations can build complex workflows—but teams typically assign an administrator to maintain that configuration [citation:8]. Its AI agents are included on Suite and Support plans billed on resolution outcomes, with Copilot as a separate per-agent line at $50/agent/month [citation:8]. Best suited for organizations with dedicated support operations staff.

### Freshdesk
**Type:** Accessible support with fast time-to-value  
Freshdesk is the more common choice for teams that need to go live quickly from an email-only setup [citation:3]. It offers omnichannel support, SLA management, and AI (Freddy) with 50+ prebuilt workflows for retail/e-commerce use cases [citation:8]. Pricing starts at $19/agent/month, with a free tier for small teams [citation:8]. The trade-off is less deep configurability than Zendesk, but significantly lower administrative overhead.

### Zoho Desk
**Type:** Budget-friendly support within Zoho ecosystem  
Zoho Desk offers a free edition for three users and starts at $7/user/month [citation:8][citation:12]. It leads small business reviewers on ticket visibility mentions (134 vs Freshdesk's 59), with automation rules and routing from shared inboxes cited as strengths [citation:3]. Customization ceiling is tied to the wider Zoho suite, and AI is a metered add-on [citation:8]. Best for teams already in the Zoho ecosystem or wanting a capable free tier.

### Jira Service Management
**Type:** ITSM-aligned support within Atlassian ecosystem  
Jira Service Management (formerly Jira Service Desk) brings support ticketing into the Atlassian ecosystem, integrating natively with Jira Software, Confluence, and Bitbucket [citation:4]. It is rated 4.5/5 across 668 reviews, with strengths in agile service management and developer collaboration [citation:4]. Best for software teams that already use Jira for development work and want support requests to flow into the same system.

### ServiceNow Customer Service Management
**Type:** Enterprise CSM within ServiceNow platform  
ServiceNow CSM delivers frictionless customer experiences on the ServiceNow platform, rated 4.3/5 across 149 reviews [citation:4]. It is enterprise-priced and requires significant configuration, with reviewers noting it "sometimes offers too much and you can get lost in the forest" [citation:9]. Best for large enterprises already invested in ServiceNow for ITSM or ITAM that want customer service on the same platform.

### Help Scout
**Type:** Email-first support with conversation feel  
Help Scout provides shared inboxes for customer support teams with a focus on email-first conversations. Pricing benchmarks show a $0 entry tier with a median of $54/month and top tier at $90/month [citation:5]. The interface is designed to feel like email rather than a ticketing system, making it accessible for smaller teams.

### LiveAgent
**Type:** Multichannel help desk with competitive pricing  
LiveAgent offers ticketing, live chat, and call center features. Pricing benchmarks show an entry of $15/month, median $50, and top tier $85 [citation:5]. Positioned as a competitive option for smaller teams wanting multichannel support without enterprise complexity.

### HappyFox
**Type:** Configurable help desk for operations teams  
HappyFox provides ticketing, automation, knowledge management, and multichannel support [citation:10]. Its strength is configurable routing and ticket fields without abandoning standard help desk workflows like macros and canned responses [citation:10]. Pricing benchmarks show an entry of $24/month, median $62, and top tier $99 [citation:5]. A practical trade-off is that the configuration surface is wide, so teams without an admin owner may need time to define custom fields and automation rules [citation:10].

### Kayako
**Type:** Support platform with premium top-tier pricing  
Kayako offers ticketing and customer support. Pricing benchmarks show a $1 entry, $500 median, and $10,000 top tier—the highest top-tier list price among tracked products [citation:5]. Best suited for organizations that have specifically evaluated and committed to its workflow model.

### Deskpro
**Type:** Help desk with self-hosted and cloud options  
Deskpro provides help desk ticketing, live chat, and knowledge base capabilities. It is often evaluated alongside Kayako and HappyFox for mid-market support teams. Available as both cloud-hosted and self-hosted, making it a consideration for organizations with data residency requirements.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Support Ticket and Case Management tools. The open-source ecosystem offers mature alternatives for organizations prioritizing data control and no per-seat licensing.

### Zammad
**Stack:** Ruby on Rails / PostgreSQL / Elasticsearch | **License:** AGPL-3.0
Zammad is a modern, open-source, web-based helpdesk and customer support system that streamlines communication between businesses and customers [citation:2]. It provides an intuitive interface for managing support tickets, tracking issues, and automating workflows. Features include multi-channel communication (email, chat, phone, social media), ticket assignment and prioritization, and built-in reporting and analytics [citation:2]. Listed in Awesome Selfhosted as an "easy to use but powerful open-source support and ticketing system" [citation:11]. Self-hosted with full control over data and customization.
**Best for:** Organizations wanting a polished, modern helpdesk with multi-channel support and full data sovereignty, accepting the operational overhead of self-hosting Ruby/PostgreSQL/Elasticsearch.

### Znuny
**Stack:** Perl / MySQL/PostgreSQL | **License:** GPL-3.0
Znuny is an open-source ticketing and ITSM platform forked from OTRS, providing helpdesk and product support capabilities [citation:7]. Features include fast service request creation via call center agents, customer email, customer portal, and other channels; snippets/templates for faster responses; customer self-service interface; FAQ/knowledgebase; personalized service with booked services visible during ticket processing; and SLAs for service quality control [citation:7]. It is fully customizable, available on-premise or cloud, and community-driven with 30K+ GitHub commits and 200K+ forum posts [citation:7]. Current LTS is 6.5.26, with 7.3.8 as the latest stable [citation:7].
**Best for:** IT and service teams wanting an OTRS-style service desk with strong SLA management and deep customization, backed by an active community.

### OTOBO
**Stack:** Perl / MariaDB/MySQL/PostgreSQL/Oracle | **License:** GPL-3.0
OTOBO is a flexible web-based ticketing system used for customer service, help desk, and IT service management, listed in Awesome Selfhosted [citation:11]. It is a fork of OTRS maintained by Rother OSS, continuing the codebase with ITSM packages available free. Features include ticket management, service desk, incident/problem/change management, self-service portal, and knowledge management.
**Best for:** Organizations wanting an OTRS-style service desk without license fees, with a path to vendor support if needed.

### FreeScout
**Stack:** PHP / Laravel / MySQL | **License:** AGPL-3.0
FreeScout is an email-based customer support application, help desk and shared mailbox explicitly positioned as an alternative to Zendesk and Help Scout [citation:11]. It provides shared inboxes, assignment, private notes, and a familiar email-like interface. Deployable on standard PHP/MySQL hosting with a web installer. Some advanced modules are paid add-ons.
**Best for:** Technical teams with a spare VPS or shared hosting wanting a free-forever shared mailbox with help desk features, accepting paid modules for advanced functionality.

### Frappe Helpdesk
**Stack:** Python / Frappe Framework / Vue | **License:** AGPL-3.0
Frappe Helpdesk is helpdesk software that helps streamline a company's support, offering easy setup, a clean user interface, and automation tools to resolve customer queries efficiently [citation:11]. Built on the Frappe framework (same ecosystem as ERPNext), it provides clean shared support queues with assignments and SLAs. Docker deployment is available.
**Best for:** Teams already in or considering the Frappe/ERPNext ecosystem, wanting helpdesk functionality with SLA support integrated with broader business operations.

### Libredesk
**Stack:** Go / PostgreSQL | **License:** AGPL-3.0
Libredesk is a modern customer support desk distributed as a single binary application [citation:11]. It provides shared inboxes for email and live chat, with assignment and a modern UI. Deployable via Docker or prebuilt binary with PostgreSQL. Positioned as a lightweight, modern open-source alternative to commercial support desks.
**Best for:** Teams wanting a modern, lightweight open-source shared inbox with email and live chat, accepting a younger ecosystem.

### Helpy
**Stack:** Ruby on Rails | **License:** MIT
Helpy is a modern, open-source helpdesk customer support application with knowledgebase, community discussions, and support tickets integrated with email [citation:15]. It provides a JSON API for integrations. The project was created nearly 6 years ago and last updated 9 months prior to the listing, so maintenance status should be verified before adoption [citation:15].
**Best for:** Teams wanting an MIT-licensed helpdesk with community features and knowledge base, verifying current maintenance activity before production use.

### ITFlow
**Stack:** PHP / MySQL | **License:** Open Source
ITFlow provides client IT documentation, ticketing, invoicing, and accounting specifically for MSPs (Managed Service Providers) [citation:11]. It combines helpdesk ticketing with the documentation and billing workflows that MSPs need, making it a specialized alternative to general-purpose help desks.
**Best for:** MSPs wanting an open-source platform that combines ticketing with client documentation and invoicing, rather than a standalone help desk.

---

## 📊 Comparison at a Glance

| Software | License | Stack | Multi-Channel | SLA | Self-Hosted | Best For |
|----------|---------|-------|---------------|-----|-------------|----------|
| **Zendesk** | Proprietary | Cloud | ✅ | ✅ | ❌ | Enterprise configurability |
| **Freshdesk** | Proprietary | Cloud | ✅ | ✅ | ❌ | Fast time-to-value |
| **Zoho Desk** | Proprietary | Cloud | ✅ | ✅ | ❌ | Budget + free tier |
| **Jira SM** | Proprietary | Cloud/DC | ✅ | ✅ | (DC) | Atlassian dev teams |
| **ServiceNow CSM** | Proprietary | Cloud | ✅ | ✅ | ❌ | ServiceNow enterprises |
| **Help Scout** | Proprietary | Cloud | ✅ | (Limited) | ❌ | Email-first conversations |
| **Zammad** | AGPL-3.0 | Ruby/Postgres | ✅ | ✅ | ✅ | Modern self-hosted helpdesk |
| **Znuny** | GPL-3.0 | Perl | ✅ | ✅ | ✅ | OTRS-style ITSM |
| **OTOBO** | GPL-3.0 | Perl | ✅ | ✅ | ✅ | OTRS fork + ITSM |
| **FreeScout** | AGPL-3.0 | PHP/MySQL | (Email) | (Add-on) | ✅ | Zendesk/Help Scout alt |
| **Frappe Helpdesk** | AGPL-3.0 | Python/Frappe | (Check) | ✅ | ✅ | ERPNext ecosystem |
| **Libredesk** | AGPL-3.0 | Go/Postgres | (Email+chat) | (Check) | ✅ | Modern lightweight inbox |
| **ITFlow** | Open Source | PHP/MySQL | (Check) | (Check) | ✅ | MSP ticketing + invoicing |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Support Ticket or Case Management tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem offers strong options: **Zammad** is the most modern and polished self-hosted helpdesk, **Znuny** and **OTOBO** carry the OTRS legacy with deep ITSM customization, and **FreeScout** is the most accessible entry point for teams wanting a Zendesk/Help Scout alternative on modest infrastructure. For MSPs specifically, **ITFlow** combines ticketing with client documentation and invoicing.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
