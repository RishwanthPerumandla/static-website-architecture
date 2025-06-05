# Advanced Discovery Questionnaire – Website Architecture

**Prepared by:** Rishwanth Perumandla  
**Purpose:** To uncover both functional and non-functional requirements before architecting a scalable, performant, and secure website infrastructure.  
**Intended Use:** Solutions Architecture intake form for clients/startups/business stakeholders.

---

## Section 1 – Business Context

1. **What business problem is the website solving?**
   - Brand positioning / awareness
   - Service catalog and inbound lead generation
   - Funnel for product adoption / conversion
   - Thought leadership (blog, community, education)
   - Client onboarding or document management

2. **Who are the key stakeholders and decision-makers?**
   - C-level / Founder / Marketing / Engineering?

3. **What are the short-term (3–6 months) and long-term (12+ months) business goals for this platform?**
   - Include plans for international expansion, product launches, or multi-brand rollout.

4. **Are there any compliance or regulatory requirements?**
   - HIPAA / GDPR / SOC2 / PCI-DSS

---

## Section 2 – Audience, Traffic & Behavior

1. **Who is the primary audience?**
   - Geography, device breakdown (mobile/desktop), browser expectations, language/localization

2. **What is the estimated monthly traffic now and projected within 12 months?**

3. **Any seasonal/marketing events that could spike traffic?**
   - Black Friday, campaign launches, conference demos?

4. **What is the expected engagement behavior?**
   - Average session duration, scroll depth, repeat visits?

---

## Section 3 – Functional Requirements

1. **Pages/sections required:**
   - ☐ Landing Page(s)
   - ☐ About, Team, Careers
   - ☐ Services or Pricing
   - ☐ Blog or Knowledge Base
   - ☐ Contact / Lead Forms
   - ☐ Case Studies / Portfolio
   - ☐ Authentication (User login/registration)
   - ☐ Client dashboard or portals
   - ☐ API integrations

2. **Form functionality:**
   - Field-level validation, spam protection, conditional logic?

3. **Email workflows:**
   - Transactional? SMTP provider? Email forwarding? Auto-responders?

4. **CMS or Content Strategy:**
   - Content editing frequency and authorship roles?
   - Preference: Traditional CMS, Headless CMS, or Git-based markdown?

5. **Search, Filters, or Categorization?**

---

## Section 4 – Non-Functional Requirements

1. **Performance expectations:**
   - TTFB under 100ms? LCP < 2.5s? FID under 100ms?
   - Asset size constraints? Lazy loading images?

2. **SEO and social preview optimization:**
   - Structured data (schema.org)? Meta image automation?

3. **Internationalization:**
   - Static localized pages vs dynamic translation?

4. **Security Expectations:**
   - WAF, HTTPS, bot protection, rate limiting?
   - IAM roles for internal admin editors?

5. **Availability:**
   - Target SLA (e.g., 99.9%)?
   - Required regions for CDN or redundancy?

---

## Section 5 – Infrastructure & DevOps

1. **Do you require CI/CD pipelines for publishing?**
   - Manual trigger, GitHub Actions, GitLab CI?

2. **Will the app need to scale with traffic?**
   - Auto-scaling needed? Should the app degrade gracefully on resource constraints?

3. **Asset Hosting Strategy:**
   - Central image storage (S3)? CDN (CloudFront, Cloudflare)?

4. **Logging, Monitoring & Alerts:**
   - Required? Preferred provider (Datadog, CloudWatch, Sentry)?

5. **Backup Strategy?**
   - Frequency? Snapshot or versioned storage?

---

## Section 6 – Domain, DNS & Email

1. **Domain Management:**
   - Registrar (GoDaddy, Namecheap, AWS Route 53)?
   - Do you need DNS routing, subdomain mapping, vanity URLs?

2. **SSL:**
   - Custom cert or managed via ACM/Cloudflare?

3. **Email Hosting:**
   - Google Workspace, Zoho, AWS SES?

4. **Do you require SPF, DKIM, DMARC records configured?**

---

## Section 7 – Budget & Delivery

1. **Initial budget estimate:**
   - <$500, $500–$2K, $2K–$5K, $5K+

2. **Ongoing cloud budget (monthly):**
   - For compute, storage, email, monitoring

3. **Preferred engagement:**
   - One-time delivery vs Retainer/Long-term support?

4. **Timeline constraints:**
   - Launch dates tied to funding, product demo, trade show?

---

## Section 8 – Future-Readiness

1. **Is there an expected upgrade path?**
   - From static site to full-stack SaaS?
   - From blog to membership portal?

2. **Will the same stack serve mobile or desktop apps in the future?**

3. **Do you anticipate integrations with external systems?**
   - CRMs, APIs, inventory, authentication, internal tools?

---

## Final Notes

Use this document to guide early architecture sessions and define not just what needs to be built — but *why*. This ensures infrastructure, technology stack, and business goals are tightly aligned and allows for forward compatibility, observability, and performance under budget constraints.

---

**Prepared with Systems Thinking. Signed:**  
**Rishwanth Perumandla**  
Cloud & Solutions Architect  
[rishwanth.com](https://rishwanth.com)
