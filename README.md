# Wahaj Ahmed

Full-stack engineer in Islamabad, Pakistan. I build React and Node systems that
hold up past 100,000 users, and I work remotely with teams anywhere.

**[wahaj-portfolio-one.vercel.app](https://wahaj-portfolio-one.vercel.app)**
· [LinkedIn](https://www.linkedin.com/in/wahajahmed-ftw/)
· wahajahmed55@live.com

Open to engineering roles and freelance work. Islamabad is UTC+5, which is
about five hours of overlap with CET and a full working day with the Gulf.

---

### What I build

**Full-stack product engineering.** React and Next.js in front, Node.js and
GraphQL behind it. Client-facing dashboards and admin panels, shared component
libraries documented in Storybook, and end to end delivery from design through
deployment.

**APIs and service architecture.** GraphQL and REST inside microservice
architectures, standardized response shapes and reusable middleware, scalable
schemas and consistent data contracts, role-based authorization with JWT and
Clerk.

**Performance and reliability.** Code splitting, lazy loading and render
optimization. TanStack Query caching. Lighthouse and Core Web Vitals work.
Structured logging with request correlation, and incident investigation that
goes to root cause rather than to a workaround.

**Cloud and AI in production.** AWS Lambda, SQS and S3 with DynamoDB and
PostgreSQL. Scheduled pipelines and pre-signed URL delivery. MCP servers that
put internal data inside a customer's Claude, behind OAuth and company, sector
and per-user entitlement checks.

---

### Selected work

**Scheduling at scale.** A full-stack scheduling system for an enterprise
tutoring platform serving over 100,000 students per district, with scheduling
errors down 90%. Report exports kept timing out at the API Gateway, which no
query tuning could fix because the gateway timeout is a platform limit rather
than a slow query. So exports left the request path entirely: a cron job builds
the file every two hours and writes it to S3, and the client gets a pre-signed
URL instead of a payload.

**An incident worth writing down.** Around 4,500 teachers were due payment and
about thirty were paid nothing, with no error logged anywhere. The update
function completed without writing. The real problem was that there was no
process-level error capture, so the failure had nowhere to land. Capture went in
first, before any fix; the next run revealed DynamoDB throttling writes because
the index's provisioned capacity was too low for payday load. The thirty were
paid manually and the provisioning was raised. What stayed with me was the
prevention, not the fix.

**AI in production.** For a market-intelligence platform serving institutional
investors: a weekly Trigger.dev job that fans out into parallel tasks and
compiles leadership metrics into charts with one-line summaries written by Claude
Haiku, chosen deliberately because one-liners do not need a frontier model. Plus
a production MCP server with seven tools that puts published research inside the
customer's own Claude, where entitlements are the hard part.

**This profile's one public repo** is my portfolio, built as an engineering
document: every figure is a hand-projected isometric SVG generated from a small
maths module, every animation is CSS, and there is no canvas or animation
library anywhere. It scores 100 on Lighthouse desktop and 98 mobile, with zero
layout shift, and every route is prerendered at build.

---

### Stack

**Languages** TypeScript · JavaScript · Python · Java · SQL
**Frontend** Next.js · React · TanStack Query · Tailwind · shadcn/ui · Storybook
**Backend** Node.js · Express · GraphQL · Spring Boot · Flask · Django · MCP · Claude API
**Data** PostgreSQL · Supabase · MongoDB · MySQL · DynamoDB · Prisma · Mongoose
**Infra** AWS Lambda · SQS · S3 · Trigger.dev · Jenkins · SonarQube · Vercel
**Auth** JWT · Clerk

---

Most of my work is closed source, so this profile is deliberately small. The
portfolio is the code I can show, and it is the same standard I build to for
clients.
