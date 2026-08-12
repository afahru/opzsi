# OPZSI — Corporate Website

> **Enterprise Technology Consultancy**  
> Engineering systems. Enabling outcomes.

[![Website](https://img.shields.io/badge/Website-opzsi.com-111827?style=flat-square)](https://opzsi.com)
[![Status](https://img.shields.io/badge/Status-Live-16a34a?style=flat-square)](https://opzsi.com)
[![Deployment](https://img.shields.io/badge/Deployment-GitHub%20Pages-181717?style=flat-square&logo=github)](https://pages.github.com/)

The official corporate website for **OPZSI (Optima Zetta Inovasi)**, an engineering-led enterprise technology consultancy.

This repository is intentionally public as part of OPZSI's engineering portfolio, demonstrating how a modern corporate website can be designed, versioned, deployed, and maintained using a lightweight engineering workflow.

---

## About OPZSI

**OPZSI** is an enterprise technology consultancy focused on designing, modernizing, and evolving technology systems for organizations.

Our capabilities include:

- Enterprise Technology Consulting
- Microsoft 365 & SharePoint
- Power Platform
- Cloud & Platform Engineering
- Application Development
- Systems Integration
- Technology Modernization

> Small by design. Deep by expertise.

---

## Website

**Production:**  
https://opzsi.com

The website is designed to represent OPZSI as a **boutique enterprise technology consultancy**, rather than a generic agency or template-driven business website.

Design principles:

- Minimal
- Technical
- Corporate
- Understated
- Content-led
- Performance-conscious
- Accessibility-conscious
- Responsive
- No dependency on visual trends or excessive animations

---

## Engineering Philosophy

The website itself is treated as an engineering project.

Rather than using a traditional CMS or pre-built corporate template, the site is intentionally built as a lightweight static application.

### Principles

**Static First**

No unnecessary backend or database.

**Version Controlled**

All website changes are managed through Git.

**Automated Deployment**

Changes should move from source control to production through an automated deployment pipeline.

**Security by Design**

Security headers, HTTPS, dependency minimization, and least-privilege practices are considered part of the implementation.

**Performance**

Minimal JavaScript, optimized assets, and a lightweight page structure help keep the site fast.

**Maintainability**

The codebase should remain understandable and easy to modify without introducing unnecessary framework complexity.

---

## Architecture

Current architecture:

```text
                         ┌──────────────────┐
                         │     Developer    │
                         └────────┬─────────┘
                                  │
                                  │ Git
                                  ▼
                         ┌──────────────────┐
                         │     GitHub       │
                         │    Repository    │
                         └────────┬─────────┘
                                  │
                                  │ Deployment
                                  ▼
                         ┌──────────────────┐
                         │   GitHub Pages   │
                         └────────┬─────────┘
                                  │
                                  │ HTTPS
                                  ▼
                         ┌──────────────────┐
                         │    opzsi.com     │
                         └──────────────────┘
