<h1 align="center">Djulian Pohlmann Mazzardo</h1>

<h3 align="center">Technical Lead | Infrastructure Modernization | Performance Engineering | Application Security | AI Automation</h3>

<p align="center">
  📍 Barcelona, Spain &nbsp;|&nbsp; 💼 19+ years in software &nbsp;|&nbsp; 🗣️ Portuguese (native), English (C1), Italian (B1), Spanish (A2)
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/djulianm" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-djulianm-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://github.com/djulianm" target="_blank"><img src="https://img.shields.io/badge/GitHub-djulianm-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="mailto:djulianmazzardo@gmail.com"><img src="https://img.shields.io/badge/Gmail-djulianmazzardo-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"></a>
  <a href="https://bitbucket.org/djulian_mazzardo" target="_blank"><img src="https://img.shields.io/badge/Bitbucket-djulian__mazzardo-0052CC?style=for-the-badge&logo=bitbucket&logoColor=white" alt="Bitbucket"></a>
</p>

---

## About me

Technical Lead at **[Visca Web](https://www.linkedin.com/company/visca-web/)** in Barcelona, where I design scalable systems, modernize cloud infrastructure and lead engineering on high-traffic web platforms.

I started in tech as a teenager fixing computers in my father's store, and I've been building software professionally since **2007**. Along the way I worked on enterprise integrations for **BRF (Sadia and Perdigão)**, built SaaS products for healthcare, and today I lead infrastructure, security and AI automation work.

**What I bring to a team:**

- **Cloud cost optimization:** cut infrastructure spend by **92%** (from €13k to €1k per month) through a large-scale migration with zero downtime.
- **Performance engineering:** reduced TTFB by **90%** (from 2s to 200ms) across 10+ production environments.
- **DevOps and developer experience:** automated, branch-based staging environments that boosted QA and sprint velocity by **60%**.
- **Application security:** patched critical RCEs across the whole fleet within days and built my own vulnerability scanners.
- **AI engineering:** autonomous agents that turn tickets into ready-to-review pull requests, plus AI-powered internal tools.
- **Technical leadership:** principal technical advisor to the CTO. Led a cross-functional team of 5 (backend, frontend, product), including hiring, 1:1s and performance reviews. Owns architecture decisions and technical due diligence for M&A.

> **Last 3 years:** 730+ pull requests and 5,000+ contributions across 25+ production repositories (mostly private).

---

## Key achievements

| Area | Impact |
| --- | --- |
| **Infrastructure modernization** | Led the migration of Symfony/WordPress infrastructure from AWS (EC2, RDS, Lambda) to containerized Docker/Dokploy deployments on OVH, cutting monthly costs by **92% (from €13k to €1k) with zero downtime** while improving performance and availability. [Read the story](https://lnkd.in/e6aHUp7n) |
| **Disaster recovery** | Designed a **multi-cloud failover and failback pipeline** between OVH and AWS EC2: MySQL and file backups to S3, automated restore into Dokploy stacks and **Cloudflare DNS cutover**. Added a dashboard with a real-time go/no-go verdict per site (DNS state, standby health, backup freshness), presented the plan to leadership and instituted **recurring recovery drills**. |
| **Multi-cloud deployment** | Built a **provider-agnostic deploy pipeline** (a common base with AWS Beanstalk and OVH implementations) with dynamic per-environment Varnish configuration, decoupling deployment logic from any single cloud vendor. |
| **Monolith decoupling** | Led a 4-person team through a multi-phase removal of a legacy shared library and CMS dependency chain from a multi-site WordPress portfolio, with **change sets touching over 1M lines**. |
| **Security patching** | When a critical PHP RCE (CVSS 9.2) was disclosed, led the **emergency upgrade to PHP 8.4 across 14+ production repositories in under a week**, including framework and dependency upgrades. |
| **Performance** | Implemented **Varnish Cache** layers on 10+ production sites: **TTFB from 2s to 200ms** and lower backend load. |
| **Core Web Vitals** | Improved LCP, FCP, CLS and accessibility on high-traffic sites (render-blocking assets, hero image preloading, critical CSS). Removed N+1 queries and about 15k redundant request parses per page load, made critical CSS generation faster by reusing a single Puppeteer browser, and added **Chrome UX Report** monitoring with trend alerts. |
| **Observability** | Built a **self-hosted observability stack** (Grafana, VictoriaMetrics, Tempo, Grafana Alloy, OpenTelemetry) that replaced New Relic Infrastructure and APM, bringing monitoring costs from **$200/month to $0**. It covers host and per-container metrics plus PHP APM with distributed traces, slow-query and error breakdowns, all deployed as code with Dokploy. Proactive monitoring and query optimization reduced downtime by **90%**. |
| **DevOps and DX** | Built automated **branch-based staging environments** on AWS, raising sprint velocity and QA efficiency by **60%**. Containerized legacy apps with Docker and CircleCI pipelines. |
| **AI automation** | Built an **autonomous Asana to Pull Request agent**: it reads specs from Confluence, analyzes the repos, extracts Figma designs via **MCP**, and delivers a PR plus a live staging environment for review, at **about $1 to $3 per task**. Introduced **AI code review on PRs in early 2024**. |
| **AI-powered tools** | Built an **AI Image Studio** that replaced the manual design workflow for homepage banners and featured images (generation, scheduling, WebP export), and AI assistants embedded in a SaaS product. |
| **Engineering analytics** | Built an internal dashboard for sprint metrics (velocity, misestimated and unplanned work, AI usage), automated Confluence documentation sync, and centralized AWS EC2 start/stop scheduling to cut idle costs. |
| **SaaS and payments** | Shipped billing and growth features for a lead generation SaaS: **Stripe** subscriptions, Apple Pay and Google Pay, saved cards, CRM sync with ActiveCampaign, and large-scale lead scraping pipelines with proxy usage monitoring. |
| **Content engineering and SEO** | Automation for high-volume CMS migrations and SEO integrity tooling, with **20%** less crawl budget waste. |
| **Technical M&A** | Led technical due diligence and handover for acquisitions and sales of high-traffic web assets. |

---

## Side projects

| Project | What it does |
| --- | --- |
| **WordPress Vulnerability Scanner** (PHP) | Internal security auditing tool with **25+ CVE checkers** for WordPress core and plugins: RCE, SQL injection, auth bypass, privilege escalation, and `.git` or credential file exposure. Uses passive version fingerprinting and false positive guards. |
| **Batch domain analysis** (Go) | High-throughput crawler with pluggable **Go detectors for PHP engine CVEs** and WordPress core vulnerabilities, used for internal security audits. |

---

## Experience

| Role | Company | Period |
| --- | --- | --- |
| **Technical Lead** | Visca Web, Barcelona | Sep 2022 to present |
| DevOps / Backend Developer | Visca Web, Barcelona | Aug 2020 to Sep 2022 |
| Web Technician (Jenkins, Selenium, Capistrano, Salesforce) | Randstad España, Barcelona | Feb 2020 to Aug 2020 |
| Back-end Developer (ColdFusion, MySQL, workflow automation) | Livonius Assessoria e Parcerias de Seguros | Jun 2016 to Jan 2024 |
| Full-Stack Developer and IT Infrastructure Manager | ClicMed, SaaS for medical clinics (EHR, scheduling) | Jun 2015 to Sep 2022 |
| PHP Developer (Zend Framework, MySQL) | Clariai Sistemas | Dec 2016 to Aug 2020 |
| Web Consultant for BRF (Sadia and Perdigão): SAP, e-commerce and web portal integrations | GrupoW Softwares para Internet | Sep 2007 to Jun 2015 |

🎓 **Master's in Cybersecurity**, OBS Business School, Barcelona (starting April 2027)
<br>
🎓 **Technologist in Management Processes**, Universidade do Contestado (2011 to 2014)

---

## Tech stack

**Languages and frameworks**
<br>
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=flat-square&logo=laravel&logoColor=white)
![Zend](https://img.shields.io/badge/Zend_Framework-68B604?style=flat-square&logo=zend&logoColor=white)
![Symfony](https://img.shields.io/badge/Symfony-000000?style=flat-square&logo=symfony&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Go](https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![ColdFusion](https://img.shields.io/badge/ColdFusion-0A6EB4?style=flat-square&logo=adobe&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=flat-square&logo=wordpress&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![jQuery](https://img.shields.io/badge/jQuery-0769AD?style=flat-square&logo=jquery&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat-square&logo=bootstrap&logoColor=white)

**Cloud, infrastructure and DevOps**
<br>
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white)
![OVH](https://img.shields.io/badge/OVHcloud-123F6D?style=flat-square&logo=ovh&logoColor=white)
![Varnish](https://img.shields.io/badge/Varnish_Cache-0D2F59?style=flat-square&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)
![VictoriaMetrics](https://img.shields.io/badge/VictoriaMetrics-621773?style=flat-square&logo=victoriametrics&logoColor=white)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-425CC7?style=flat-square&logo=opentelemetry&logoColor=white)
![Cloudflare](https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Dokploy](https://img.shields.io/badge/Dokploy-111827?style=flat-square&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white)
![Nginx](https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white)
![CircleCI](https://img.shields.io/badge/CircleCI-343434?style=flat-square&logo=circleci&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=flat-square&logo=jenkins&logoColor=white)
![Capistrano](https://img.shields.io/badge/Capistrano-CC0000?style=flat-square&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![CI/CD](https://img.shields.io/badge/CI%2FCD-4B5563?style=flat-square&logo=githubactions&logoColor=white)

**Databases**
<br>
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![SQL Server](https://img.shields.io/badge/SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)

**AI and tooling**
<br>
![AI Agents](https://img.shields.io/badge/AI_Agents-111827?style=flat-square&logo=openaigym&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-6B7280?style=flat-square&logoColor=white)
![Asana](https://img.shields.io/badge/Asana-F06A6A?style=flat-square&logo=asana&logoColor=white)
![Confluence](https://img.shields.io/badge/Confluence-172B4D?style=flat-square&logo=confluence&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=flat-square&logo=figma&logoColor=white)
![Puppeteer](https://img.shields.io/badge/Puppeteer-40B5A4?style=flat-square&logo=puppeteer&logoColor=white)
![Playwright](https://img.shields.io/badge/Playwright-2EAD33?style=flat-square&logoColor=white)
![Lighthouse](https://img.shields.io/badge/Lighthouse-F44B21?style=flat-square&logo=lighthouse&logoColor=white)
![Stripe](https://img.shields.io/badge/Stripe-635BFF?style=flat-square&logo=stripe&logoColor=white)
![Salesforce](https://img.shields.io/badge/Salesforce-00A1E0?style=flat-square&logo=salesforce&logoColor=white)

**Practices:** SOLID, Clean Architecture, Performance Tuning, Core Web Vitals, Caching Strategies, Observability, Vulnerability Management, Disaster Recovery, ITIL, Agile/Scrum

---

## Right now

- Leading infrastructure, performance and scalability initiatives at Visca Web
- Building AI agents that automate the path from spec to production-ready pull request
- Expanding my security tooling: CVE detection, vulnerability management and fast fleet-wide patching
- Deepening my knowledge of software architecture, DevOps and applied AI
- Starting a **Master's in Cybersecurity** at **OBS Business School** (Barcelona) in **April 2027**

---

## Let's talk

I'm always open to exchanging ideas, whether it's **discussing a project**, **collaborating on open-source**, talking about **infrastructure, performance, security or AI automation**, or just helping out with a tricky technical problem.
Reach me on **[LinkedIn](https://www.linkedin.com/in/djulianm)** or by email at **[djulianmazzardo@gmail.com](mailto:djulianmazzardo@gmail.com)**.

<details>
<summary>GitHub stats</summary>
<br>
<p align="left">
  <img width="48%" src="https://github-readme-stats.vercel.app/api?username=djulianm&theme=react&show_icons=true&count_private=true" alt="GitHub stats" />
  <img width="48%" src="https://github-readme-stats.vercel.app/api/top-langs?username=djulianm&theme=react&layout=compact&langs_count=6" alt="Top languages" />
</p>
</details>
