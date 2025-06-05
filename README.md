# Static Website Architecture – A Professional Case Study

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![AWS Architecture](https://img.shields.io/badge/Cloud-AWS-orange?logo=amazonaws&logoColor=white)](https://aws.amazon.com/)
[![Made with Markdown](https://img.shields.io/badge/Format-Markdown-000000?logo=markdown)](portfolio-case-study.md)
[![Status: Completed](https://img.shields.io/badge/Status-Completed-brightgreen)]()
[![Author: Rishwanth](https://img.shields.io/badge/Author-Rishwanth-lightgrey)](https://rishwanth.com)


...

This repository presents a real-world architectural breakdown of how I approached designing and deploying a scalable, cost-efficient website for a small-to-mid scale business use case. The project reflects my role as a **Solutions Architect**, with decisions grounded in business requirements, traffic expectations, and operational budgets.

---

## Problem Statement

> "The ask was simple — build a website. The solution needed to be anything but."

Most small businesses think a basic website is enough. But when you're designing with **scale**, **availability**, and **cost-awareness** in mind, the architecture becomes a strategic lever.

This case study answers:
- How do we design for now **and** for growth?
- When does shared hosting break down?
- What are your AWS-backed alternatives?
- How do you choose the right deployment option?

---

## Key Artifacts

This repository includes:

| File/Folder                    | Description                                                                 |
|-------------------------------|-----------------------------------------------------------------------------|
| `portfolio-case-study.md`     | Full blog post content as published on [rishwanth.com](https://rishwanth.com/post/static-website-architecture) |
| `architecture-decision-record.md` | Architecture tradeoffs, cost breakdowns, and justifications for AWS services |
| `discovery-questionnaire.md`  | Professional questionnaire to uncover project scope, traffic, and budget    |
| `diagrams/`                   | Architecture diagrams (draw.io + PNGs) for each solution path               |

---

## ⚙️ Architecture Options Explored

| Architecture         | Use Case                      | Scalability | Monthly Cost |
|----------------------|-------------------------------|-------------|---------------|
| Shared Hosting       | Entry-level brand site        |  Low       | $2–10         |
| S3 + CloudFront      | Static, modern business site  |  Very High | <$1           |
| Lightsail + WordPress| Low-maintenance CMS setup     |  Medium    | $5–10         |
| Elastic Beanstalk    | Fully managed WP w/ scaling   |  High      | $30–50        |
| EC2 + RDS            | Full infrastructure control   |  High      | $20–60        |

Each option comes with an **architecture diagram**, a **cost analysis**, and a **justification memo** in the repo.

---

## Architecture Diagrams

All diagrams are in `/diagrams/` (both `.drawio` and `.png`):

- `s3-cloudfront.drawio` – Static website on S3 + CDN
- `lightsail-wordpress.drawio` – WordPress on Lightsail
- `beanstalk-arch.drawio` – Auto-scaled infra using Beanstalk
- `ec2-rds.drawio` – Custom setup using EC2, RDS, Load Balancer

---

## Highlights from the Case Study

- Emphasis on **asking the right discovery questions** before development begins
- Real-world example of how **bandwidth limitations** affect shared hosting
- Cost breakdowns for low-traffic vs scalable setups
- CDN and image optimization via **S3 + CloudFront**
- Tradeoffs between **managed vs manual infrastructure**

---

## Live Blog

Read the full case study on my blog:  
👉 [rishwanth.com/post/static-website-architecture](https://rishwanth.com/post/static-website-architecture)

---

## 📬 Contact

If you're building cloud-native platforms or re-architecting legacy systems, I'm happy to collaborate or consult.

📧 **Email:** [rishwanth.perumandla@hotmail.com](mailto:rishwanth.perumandla@hotmail.com)  
🌐 **Portfolio:** [rishwanth.com](https://rishwanth.com)  
📂 **All Projects:** [github.com/RishwanthPerumandla](https://github.com/RishwanthPerumandla)

---

## 🏷️ Tags

`#solutions-architecture` `#aws` `#cloud-native` `#website-scalability` `#case-study` `#professional-architecture`

