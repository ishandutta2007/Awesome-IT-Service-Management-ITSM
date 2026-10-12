# Awesome-IT-Service-Management-ITSM

# Top IT Service Management (ITSM) Tools Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Incident Management, Service Catalogs & ITIL-Aligned Workflows*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **IT Service Management (ITSM) Tools**. These tools help IT teams manage incidents, service requests, changes, problems, and assets — aligning with ITIL practices to deliver reliable services, maintain configuration management databases (CMDBs), and enforce SLAs across enterprise environments.

**Examples** include Salesforce IT Service, ServiceNow IT Service Management, Jira Service Management, Freshservice, BMC Helix ITSM, Ivanti Neurons for ITSM, Cherwell Service Management, SolarWinds Service Desk, SysAid, and ManageEngine ServiceDesk Plus (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom ITIL workflows, and transparent asset management — ideal for IT departments, MSPs, and developers building data-sovereign service management platforms.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Salesforce IT Service](https://www.salesforce.com/)**  
  IT service management within Salesforce Service Cloud with incident management, service catalogs, and ITIL-aligned workflows integrated with CRM data. Rated a Leader in the ISG Buyers Guide for ITSM Platforms 2026 .

- **[ServiceNow IT Service Management](https://www.servicenow.com/)**  
  Enterprise ITSM platform with the largest market presence and highest satisfaction score in G2's Spring 2026 Enterprise Grid Report . Features incident, problem, change, and configuration management with CMDB.

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  ITSM solution from Atlassian with 4.3-star rating on G2, 95% of users rating it 4 or 5 stars . Deep integration with Jira, Confluence, and DevOps toolchains.

- **[Freshservice](https://www.freshworks.com/freshservice/)**  
  Cloud-based ITSM platform rated Exemplary in ISG Buyers Guide 2026 . Features Freddy AI Copilot (add-on) for ticket summarization and response suggestions .

- **[BMC Helix ITSM](https://www.bmc.com/)**  
  Enterprise ITSM platform rated a Leader in ISG Buyers Guide 2026 . Formerly Remedy, with strong automation and multi-cloud support.

- **[Ivanti Neurons for ITSM](https://www.ivanti.com/)**  
  ITSM platform with endpoint and asset management integration. Formerly Cherwell Service Management before acquisition .

- **[Cherwell Service Management](https://www.cherwell.com/)**  
  ITSM platform with strong workflow management for IT change controls, now part of Ivanti portfolio .

- **[SolarWinds Service Desk](https://www.solarwinds.com/)**  
  ITSM platform integrated with SolarWinds monitoring tools for IT operations alignment.

- **[SysAid](https://www.sysaid.com/)**  
  ITSM platform with AI-powered ticket routing and asset management capabilities.

- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/)**  
  ITSM platform available cloud and on-premises with ITIL processes, asset management, and project module. Rated Exemplary in ISG Buyers Guide 2026 .

## Open-Source GitHub Projects

- **[iTop](https://github.com/Combodo/iTop)**  
  Complete open-source, web-based IT service management platform with fully customizable CMDB, helpdesk, and document management. ITIL-compliant with incident, problem, change, and configuration management. AGPL-3.0 licensed, actively developed since 2009 with 314 years of estimated effort . Features graphical impact analysis, CSV import, consistency audit, and data synchronization .

- **[GLPI](https://github.com/glpi-project/glpi)**  
  Leading open-source ITSM and asset management suite combining helpdesk ticketing with full CMDB — hardware inventory, software licensing, contracts, and financial tracking. GPL-3.0 licensed . Handles incidents, problems, changes, and service requests. The closest open-source equivalent to ServiceNow for teams needing both ITSM and asset management in one platform .

- **[Zammad](https://github.com/zammad/zammad)**  
  Modern open-source helpdesk with ITIL-aligned ticketing, SLA management, knowledge base, and time accounting. AGPL-3.0 licensed . Multi-channel inbox covering email, phone, Twitter, Facebook, Telegram, WhatsApp, and SMS. Elasticsearch-powered full-text search. Cleanest UI among open-source options, though requires 4-8 GB RAM .

- **[OTOBO](https://github.com/RotherOSS/otobo)**  
  Open-source fork of OTRS Community Edition — full ITIL-compliant service management with incident, problem, and change management, SLA enforcement, service catalogs, and CMDB. GPL-3.0 licensed . Best for IT departments needing formal ITIL processes with 50+ agents. Migration path from OTRS available .

- **[Znuny](https://github.com/znuny/Znuny)**  
  Active fork of OTRS Community Edition with ITIL-aligned features: incident, problem, change management, service catalog, CMDB, and SLA management tied to service classes. Best for large IT departments with formal escalation chains .

- **[Chatwoot](https://github.com/chatwoot/chatwoot)**  
  Open-source customer engagement suite with omnichannel shared inbox (live chat, email, WhatsApp, Facebook, Instagram, Telegram, SMS). MIT licensed, 28k+ GitHub stars . While primarily customer-facing, useful for IT teams handling conversational support alongside ticketing.

- **[FreeScout](https://github.com/freescout-helpdesk/freescout)**  
  Lightweight self-hostable Help Scout alternative running on 1-2 GB RAM. Shared inbox, conversation threading, customer profiles, knowledge base, and customer portal. AGPL-3.0 licensed with paid Modules marketplace for advanced features . Best when email is primary support channel and server resources are constrained.

- **[osTicket](https://github.com/osTicket/osTicket)**  
  One of the oldest open-source support ticket systems (first release 2013), widely deployed at scale. Email-to-ticket conversion, department routing, SLA plans, canned responses, client portal, and knowledge base. GPL-2.0 licensed . Limitation: email ticketing system, not full ITSM platform — no change management or CMDB .

- **[LibreDesk](https://github.com/abhinavxd/libredesk)**  
  Modern self-hosted customer support desk distributed as single Go binary. SLA management, automation rules, CSAT surveys, auto-assignment, webhooks, and AI-assisted responses — all in free AGPL-3.0 version . Low resource usage (512 MB RAM). Built by Zerodha Tech team.

- **[REI3](https://github.com/REI3/REI3)**  
  Open-source ticket and request management with simple or complex workflows, clear ownership and ticket status overview. MIT licensed .

### Additional Strong Open-Source Options

- **[Helpy](https://github.com/helpyio/helpy)** — Open-source customer support platform with ticket routing and multi-channel intake .
- **Monitoring Integration** — Zabbix, Prometheus, Grafana for alert-to-ticket workflows.
- **CMDB Tools** — iTop, GLPI for configuration management databases.
- **Knowledge Management** — BookStack, Outline for IT documentation and runbooks.

**Frameworks for building custom systems**: Combine **GLPI** or **iTop** for ITSM and CMDB, **Zammad** or **LibreDesk** for service desk, **OTOBO** for full ITIL compliance, and **Grafana + Prometheus** for monitoring integration to build a complete self-hosted ITSM stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- ITSM tools must comply with data protection regulations (GDPR, CCPA), industry standards (SOC 2, ISO 27001), and ITIL framework alignment where applicable.
- Self-hosted open-source solutions require proper security hardening, high-availability design, and ongoing maintenance.

---

**Made for IT service managers, service desk leads, infrastructure teams, and developers building ITSM platforms.**  
Let's make IT service management more open, ITIL-aligned, and developer-friendly.
