# Awesome-Cloud-Infrastructure-Entitlement-Management

## Top Cloud Infrastructure Entitlement Management (CIEM) Platforms Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Cloud Permissions Analysis, Least-Privilege Automation, Identity Risk & Non-Human Identity Governance*  

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Infrastructure Entitlement Management (CIEM)**. These tools help security teams gain visibility into permissions assigned to human and non-human identities, detect excessive access, automate least-privilege enforcement, and identify privilege escalation paths across AWS, Azure, and GCP.



**Examples** include Sonrai Security, Ermetic (Tenable), Veza, ConductorOne, Grip Security, Palo Alto Prisma Cloud, Cyera, Microsoft Entra Permissions Management, Entitle, Astrix Security, Tenable CIEM, AuthZed Enterprise, Permiso Security, and Axonius (the category leaders).



**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom entitlement analysis, and transparent identity data — ideal for security teams that need full control over their cloud permissions pipeline without per-identity SaaS fees or vendor lock-in.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents



- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Sonrai Security](https://sonraisecurity.com/)**  

  Cloud Permissions Firewall and CIEM platform. Provides visibility into unused permissions, identities, services, and regions across AWS Organizations. Automates least-privilege enforcement with ChatOps on-demand permissions. **Proven results**: Global Atlantic achieved 100% least privilege across 60+ AWS accounts in six days, eliminating 199 unused human identities and 1,310 unused service identities . Named AWS Recommended & Trusted Security Partner .



- **[Ermetic (Tenable Cloud Security)](https://www.tenable.com/)**  

  **Best-in-class dedicated CIEM** with deepest cloud identity security capabilities. Provides granular CIEM analysis, automated least-privilege recommendations, cross-cloud identity correlation, and built-in just-in-time access provisioning. Acquired by Tenable. Choose Ermetic over Wiz if cloud identity and entitlement management is your primary security challenge .



- **[Veza](https://veza.com/)**  

  Unified access control platform for data governance, data access management, cloud entitlements, and privileged access. Builds an **Access Graph** cataloging all entities across identity providers, cloud providers, apps, and data systems. Features **Access Intelligence** (hundreds of out-of-the-box assessment queries), **Access Search** (Graph and Query Builder for "who has access to what"), **Access Reviews** (certification campaigns), and **Access Requests** (self-service with multi-party approval workflows) . **NHI Security**: Organizations typically have 10-45 non-human identity accounts per human user; Veza provides comprehensive visibility and governance for service accounts, API keys, and automated systems .



- **[ConductorOne](https://www.conductorone.com/)**  

  **Autonomous Identity Security platform for humans and AI agents.** Features universal identity graph across users, services, agents, and API keys; real-time activity monitoring; policy-as-code enforcement; AI agent fleet management with central governance controls; dynamic access provisioning based on trust and context; and lifecycle automations . **AI Agent Governance**: MCP self-service with policy-driven tool enforcement, automated approvals with human oversight for sensitive actions .



- **[Grip Security](https://www.grip.security/)**  

  SaaS Security Control Plane (SSCP) with **SaaS Identity Risk Management (SIRM)** framework. **Policy Center** provides no-code automation rules (e.g., "AI app + risk score > 80 + no SSO/MFA → initiate Identity Offboarding workflow"). **Customizable Workflows** with drag-and-drop interface for App Onboarding, Password Rotation, and Identity Offboarding . Discovers shadow SaaS, GenAI tools, dormant accounts, risky OAuth grants, and rogue IaaS tenants . Customer halved alert triage time by 50% .



- **[Palo Alto Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)**  

  CIEM module within Prisma Cloud CNAPP. Named a **Leader and Outperformer in CIEM by GigaOm** . Provides multi-cloud permissions management with graph visualization, AWS IAM Identity Center integration, and AWS tag support .



- **[Microsoft Entra Permissions Management](https://learn.microsoft.com/entra/permissions-management/)**  

  Microsoft's CIEM solution providing comprehensive visibility into permissions assigned to all identities (users and workloads), actions, and resources across Azure, AWS, and GCP. Detects, right-sizes, and monitors unused and excessive permissions for Zero Trust least-privilege access .



- **[Entitle](https://www.entitle.io/)**  

  **Just-in-Time (JIT) Access platform** that reduces elevated access by 91% while maintaining employee experience. Automates fine-grained temporary access to production and customer data with auto-revocation after duration, ticket resolution, or on-call rotation. Reduces access request support tickets by 85% . SOC 2 Type II compliant with cloud or self-hosted deployments .



- **[Astrix Security](https://astrix.security/)**  

  **Non-Human Identity (NHI) security pioneer** — API keys, service accounts, OAuth tokens, and AI agents. Discover, govern, and protect every agentic and non-human identity from provisioning to decommissioning. **Acquired by Cisco (May 2026)** with capabilities integrated across Cisco Security platform including Identity Intelligence, Secure Access, Duo, and Splunk . Raised $85M+ including $45M Series B .



- **[Tenable CIEM](https://www.tenable.com/)**  

  Cloud identity security for the identity-intelligent enterprise. Ermetic's CIEM capabilities integrated into Tenable's platform .



- **[AuthZed Enterprise](https://authzed.com/)**  

  Enterprise authorization platform built on **SpiceDB** (open-source). February 2026 release introduces **Postgres Foreign Data Wrapper** (experimental) allowing permission checks as SELECT statements, and **self keyword** in schema permissions for "user can view themselves" without extra relationships .



- **[Permiso Security](https://permiso.io/)**  

  Cloud-native identity security platform detecting threats across human, non-human, and agentic identities. Uses **2,500+ research-driven signals across 70+ identity partners** for overprivileged access, unused permissions, anomalous agent behavior, and high blast radius behavior in real time . **Acquired by Okta (August 2026)** to extend Okta's ITDR capabilities .



- **[Axonius](https://www.axonius.com/)**  

  Identity governance platform unifying human, NHI, SaaS, cloud, and on-prem identities. Shifts from static roles to **dynamic rules** for entitlement alignment. Features Profiles (define what access should look like), Rules (automatically align entitlements to lifecycle events), and Workflows (policy-driven access actions) .



## Open-Source GitHub Projects



### Multi-Cloud CIEM & Posture Assessment



- **[Prowler](https://github.com/prowler-cloud/prowler)**  

  **The most widely utilized open-source CIEM and cloud security assessment platform.** Covers **AWS, Azure, GCP, and Kubernetes** with hundreds of checks mapped to CIS benchmarks and NCSC Cyber Essentials 3.3 framework . **Benchmark performance**: Achieved **65% coverage** across 57 documented AWS IAM privilege escalation paths . Features custom policy creation, CLI-first scriptable, exportable detections (JSON, CSV, JUnit, HTML), and no vendor lock-in . **Open source**.



- **[Cartography (Lyft)](https://github.com/lyft/cartography)**  

  **Infrastructure graphing and querying platform.** Ingests cloud assets into a **Neo4j graph database** to enable cross-boundary queries . Provides the underlying data structure for advanced entitlement analysis — map identities, resources, and their relationships for "who can reach what" analysis. **Open source**.



- **[CloudQuery](https://github.com/cloudquery/cloudquery)**  

  **Open-source data movement framework** syncing cloud configurations into SQL databases (PostgreSQL, etc.) for complex relational analysis . First-class support for AWS, GCP, and Azure. Enables entitlement analysis through SQL queries on synchronized configuration data. **Open source**.



### AWS IAM Policy Analysis



- **[Cloudsplaining (Salesforce)](https://github.com/salesforce/cloudsplaining)**  

  **AWS IAM policy analysis tool** identifying least-privilege violations by parsing IAM policies to flag resource exposure and privilege escalation potential . Delivers findings via **risk-prioritized HTML report**. **Benchmark performance**: 35% coverage across AWS IAM privilege escalation paths . **Open source**.



- **[PMapper (Principal Mapper)](https://github.com/nccgroup/PMapper)**  

  **Privilege escalation pathfinding tool** using a **graph model** to analyze trust policies and resource-based policies . Answers "who can reach what" by simulating authorization decisions to find actual escalation routes. **Benchmark performance**: 33% coverage across AWS IAM privilege escalation paths . **Open source**.



### Policy Generation & Least-Privilege Automation



- **[policy_sentry (Salesforce)](https://github.com/salesforce/policy_sentry)**  

  **Preventative policy generation tool.** Allows engineers to declare required access levels via **YAML templates** to automatically generate least-privilege IAM policies, reducing reliance on dangerous wildcards . Implement in CI/CD pipelines to move from manual editing to automated, least-privilege policy creation . **Open source**.



### Additional Strong Open-Source Options



- **Multi-Cloud Assessment**: **Prowler** (broadest coverage, 65% privilege escalation coverage) .

- **Graph Analysis**: **Cartography** (Neo4j-based relationship mapping) .

- **SQL Analysis**: **CloudQuery** (sync to SQL for relational queries) .

- **AWS IAM Hygiene**: **Cloudsplaining** (risk-prioritized HTML reports) .

- **Privilege Escalation**: **PMapper** (graph-based pathfinding) .

- **Policy Generation**: **policy_sentry** (YAML → least-privilege policies) .



**Frameworks for building custom systems**: Follow the structured sequence recommended for effective entitlement programs : **Size the problem** with **Prowler** for breadth and **Cloudsplaining** for AWS IAM hygiene; **Identify paths** with **PMapper** for escalation routes; **Remediate non-human identities** first (highest unused permissions, lowest workflow disruption risk); **Automate generation** with **policy_sentry** in CI/CD pipelines. Add **Cartography** or **CloudQuery** for underlying graph/SQL analysis infrastructure.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CIEM platforms handle sensitive cloud identity and permission data; ensure proper access controls and compliance with organizational security policies.

- **Open-source reality**: The open-source ecosystem for CIEM is **mature at the discovery and analysis layers** but **lacks unified platform capabilities**. **Prowler** provides the broadest multi-cloud assessment with 65% privilege escalation coverage . **PMapper** and **Cloudsplaining** offer complementary AWS IAM analysis (33% and 35% coverage respectively) . **policy_sentry** enables preventative least-privilege policy generation . However, **commercial platforms** (Sonrai, Ermetic, Veza, ConductorOne, Grip) provide **automated remediation, just-in-time access, approval workflows, and unified multi-cloud governance** that open-source alternatives require significant integration and engineering investment to match. The open-source path is most viable for organizations with strong cloud security engineering capacity or for specific discovery/analysis use cases.



---



**Made for cloud security architects, IAM engineers, SOC analysts, and identity governance teams.**

Let's make cloud entitlement management more open, transparent, and least-privileged.
