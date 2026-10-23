## Hi, I'm Triết (Đởm Quang Minh Triết)

Fourth-year **Information Systems** student at the University of Science, VNU-HCM (GPA 8.24/10), based in Ho Chi Minh City.  
I build **backends for real e-commerce businesses**: order and inventory engines, payment webhooks and the data pipelines behind them.  
Open to Backend Developer internships and graduate roles in Ho Chi Minh City, growing toward **Data Engineering**.

---

### What I'm building

**IMYSM Studio** · [imysmstudio.com](https://imysmstudio.com) · *Full-stack Developer (part-time), 08/2026 – now*  
Bilingual (VI/EN) e-commerce platform and admin system that replaced Haravan for a Vietnamese fashion startup. Source is private (company code).
- Transactional order creation with **FIFO batch costing** for accurate COGS
- **VietQR / SePay** bank transfers auto-confirmed through **HMAC-verified webhooks**, with Zalo notifications
- **Row-Level Security** on Supabase PostgreSQL for role-based access
- Idempotent **ETL migration** from Haravan (6,281 historical orders, 11,392 transaction rows) with an exceptions queue
- Daily **Meta Ads ETL** (Graph API → PostgreSQL) for ROAS/CTR/CPC dashboards; reconciles with the cost ledger within 1%

**BrownVN** · [brownvn.com](https://brownvn.com) · *Freelance, 01/2026 – now*  
Bilingual (VI/EN) storefront and admin dashboard built and run solo: 13 admin modules, ~71 REST endpoints, FIFO inventory, COD / bank / PayPal checkout, GHN shipping and financial reports.

---

### Some of my Academic projects

| Project | What I did | Stack |
|---|---|---|
| [Voucher Marketplace](https://github.com/DomTriet/voucher-marketplace) · e-commerce course project ([demo](https://ec-nhom3.vercel.app)) | Team of 4: backend + Next.js frontend, layered API, PayPal/Stripe sandbox | Next.js, Express/TypeScript, Drizzle ORM, Supabase Auth |
| [HomeStay Dorm](https://github.com/DomTriet/homestay-dorm-management) · dormitory management | Backend developer (team of 4): analysis & design, room/bed search, rental requests, viewing bookings, CI fixes to pass a 70% Jest coverage gate | Angular, TypeScript, Node.js, Express, Supabase |
| [Hospital Data Security on Oracle](https://github.com/DomTriet/oracle-admin-hospital-security) | Built the core of Subsystem 1 (team of 5): Oracle admin app for users, roles, grants/revokes with `WITH GRANT OPTION` and column-level privileges | C# WinForms, Oracle (RBAC, VPD, OLS, FGA) |

---

### Tech stack

**Backend** &nbsp; Node.js · Express · REST APIs · Zod · Webhooks (HMAC)  
**Databases** &nbsp; PostgreSQL · SQL Server · Supabase (Auth, RLS) · Oracle · SQL migrations & transactions  
**Data** &nbsp; ETL pipelines · Python · pandas · PyTorch · Meta Graph API · Google Sheets API  
**Frontend** &nbsp; React · Angular · TypeScript · Vite · Tailwind CSS  
**Tooling** &nbsp; Git · GitHub Actions · Jest · Playwright · Vercel · Railway

### Certifications

[Microsoft SQL Server Professional Certificate](https://www.coursera.org/account/accomplishments/specialization/1UMZ56BSDU99) (Microsoft) ·
[Python for Everybody Specialization](https://www.coursera.org/account/accomplishments/specialization/I9EJ1SMUDCQ2) (University of Michigan) ·
[SQL Window Functions for Analytics](https://www.coursera.org/account/accomplishments/verify/KOU4P5JTOOZE) (Coursera) ·
[Programming with JavaScript](https://www.coursera.org/account/accomplishments/verify/YQZQUB2K0YSA) (Meta)

### How I work

I write the specification, design the schema and architecture, and use Claude Code as a pair programmer; every change goes through my review and automated and smoke tests before it ships.

---

🌐 [Portfolio](https://domtriet.github.io) · 📫 domquangminhtriet17@gmail.com · [LinkedIn](https://www.linkedin.com/in/domquangminhtriet)
