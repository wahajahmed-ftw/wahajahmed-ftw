<p align="center">
  <img src="https://wahaj-portfolio-one.vercel.app/opengraph-image" alt="Wahaj Ahmed, full-stack engineer" width="840">
</p>

<p align="center">
  <a href="https://wahaj-portfolio-one.vercel.app"><b>Portfolio</b></a>
  &nbsp;·&nbsp;
  <a href="https://www.linkedin.com/in/wahajahmed-ftw/">LinkedIn</a>
  &nbsp;·&nbsp;
  <a href="mailto:wahajahmed55@live.com">wahajahmed55@live.com</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Islamabad-UTC%2B5-15171C?style=flat-square" alt="Islamabad, UTC+5">
  <img src="https://img.shields.io/badge/Overlap-5h%20CET%20%C2%B7%20full%20day%20Gulf-565B64?style=flat-square" alt="Timezone overlap">
  <img src="https://img.shields.io/badge/Open%20to-roles%20%26%20freelance-2B49CF?style=flat-square" alt="Open to roles and freelance">
</p>

---

I build React and Node systems that hold up past 100,000 users. Most of my work
is closed source, so this profile is small on purpose. The portfolio below is
the code I can show, and it is the same standard I build to for clients.

## Shipped

| Work | What it involved | Outcome |
| --- | --- | --- |
| **Enterprise scheduling platform** | Full-stack scheduling for a tutoring platform. Report exports kept dying at the API Gateway, so they left the request path entirely: cron builds the file to S3, the client gets a pre-signed URL. | 100K+ students per district, scheduling errors **down 90%** |
| **Payday incident** | About 30 of 4,500 teachers were paid nothing, with no error logged anywhere. Error capture went in before any fix; the next run exposed a throttled DynamoDB index. | **All 30 paid**, and the silent-failure class closed |
| **AI for institutional investors** | Weekly Trigger.dev job fanning out into parallel tasks with Claude Haiku summaries, plus a production MCP server behind OAuth and per-user entitlements. | **7 tools live**, weekly digest to a dozen inboxes |
| **Front-end performance** | Route-level code splitting, lazy loading, render optimization, then a TanStack Query caching and invalidation pass. | **3.5s → 1.8s** load, Lighthouse **65 → 92** |
| **Shared component library** | Consolidated duplicated modals, form fields and tables into one documented library. | Feature cycles **30% faster**, duplication down 20% |

## What I work on

**Full-stack product engineering** — React and Next.js in front, Node.js and GraphQL behind it. Dashboards, admin panels, component libraries, and delivery from design through deployment.

**APIs and service architecture** — GraphQL and REST inside microservices, standardized response shapes, reusable middleware, and schemas that keep both sides honest.

**Performance and reliability** — Code splitting, caching strategy, Core Web Vitals, structured logging with request correlation, and incidents traced to root cause rather than patched at the symptom.

**Cloud and AI in production** — Lambda, SQS and S3 pipelines, and AI features built with the same care as the rest of the system: work off the request path, access checked first, models sized to the job.

## Tech stack

**Depth**

![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=for-the-badge&logo=nodedotjs&logoColor=white)
![GraphQL](https://img.shields.io/badge/GraphQL-E10098?style=for-the-badge&logo=graphql&logoColor=white)

**Frontend**

![Tailwind CSS](https://img.shields.io/badge/Tailwind-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=for-the-badge&logo=reactquery&logoColor=white)
![shadcn/ui](https://img.shields.io/badge/shadcn%2Fui-000000?style=for-the-badge&logo=shadcnui&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-FF4785?style=for-the-badge&logo=storybook&logoColor=white)

**Backend & data**

![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?style=for-the-badge&logo=supabase&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![Prisma](https://img.shields.io/badge/Prisma-2D3748?style=for-the-badge&logo=prisma&logoColor=white)

**AWS**

![Lambda](https://img.shields.io/badge/Lambda-FF9900?style=for-the-badge&labelColor=232F3E)
![S3](https://img.shields.io/badge/S3-FF9900?style=for-the-badge&labelColor=232F3E)
![SQS](https://img.shields.io/badge/SQS-FF9900?style=for-the-badge&labelColor=232F3E)
![DynamoDB](https://img.shields.io/badge/DynamoDB-FF9900?style=for-the-badge&labelColor=232F3E)

**Delivery**

![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Jenkins](https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white)
![SonarQube](https://img.shields.io/badge/SonarQube-4E9BCD?style=for-the-badge&logo=sonarqubeserver&logoColor=white)

**AI in production**

![Claude API](https://img.shields.io/badge/Claude_API-D97757?style=for-the-badge&logo=claude&logoColor=white)
![MCP](https://img.shields.io/badge/MCP-1F2937?style=for-the-badge)
![Trigger.dev](https://img.shields.io/badge/Trigger.dev-3B82F6?style=for-the-badge)

**Also work with** — Python, Java, Spring Boot, Flask, Django, MySQL, Mongoose, JWT, Clerk. Depth lives in the TypeScript, React and Node column; the rest is working fluency.

<details>
<summary><b>The portfolio repo, and why it is worth opening</b></summary>

<br>

[**wahaj-portfolio**](https://github.com/wahajahmed-ftw/wahaj-portfolio) is built
as an engineering document rather than a showreel, under constraints I set on
purpose:

- **No canvas, no WebGL, no animation library.** Every figure is an SVG isometric projection generated from a small maths module (`src/lib/iso.ts`), and every animation is CSS.
- **Zero JavaScript for the visuals.** All four diagrams are server-rendered SVG. With scripting disabled the page still renders its text, figures and scroll reveals.
- **Measured, not estimated.** Production Lighthouse: 100 desktop, 98 mobile, 0 cumulative layout shift, 0ms total blocking time, every route prerendered at build.

The parts worth reading are the projection module, the hero figure's single
7-second CSS clock that choreographs a causal request round trip, and the
scroll-driven scenes that are state machines rather than scroll-jacking.

</details>
