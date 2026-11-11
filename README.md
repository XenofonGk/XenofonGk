# Xenofon Gkioka

**Full-stack developer in Toronto. React, TypeScript, C#/.NET.**\
Open to full-stack roles in Canada and the EU.

I build software and I run it. My APIs run on a home server set up the way production is set up: no open ports, signed images, alerts on my phone, and backups I have actually restored.

**[xgbuilds.dev](https://xgbuilds.dev)** · [LinkedIn](https://www.linkedin.com/in/xenofon-gkioka/) · [ksenofwn58@gmail.com](mailto:ksenofwn58@gmail.com)

## Try it live

- **TaskManager API**: ASP.NET Core, EF Core and PostgreSQL. Writes need an API key. Contract tests run on every push.\
  [Open Swagger](https://tasks.xgbuilds.dev/swagger) · [code](https://github.com/XenofonGk/DotNet/tree/main/WebAPI/TaskManagerAPI)
- **Resume Classifier**: a scikit-learn model served with FastAPI. It sorts resume text into 5 job families and gives a confidence score.\
  [Open it](https://resume-classifier.xgbuilds.dev) · [code](https://github.com/XenofonGk/ai-programming-tools/tree/main/AI%20Resume%20Classifier%20%28NLP%20%2B%20ML%29)
- **Train Yard validator**: C compiled to WebAssembly. Your browser runs the same code the test suite runs.\
  [Run it in the browser](https://xgbuilds.dev/projects#train-yard) · [code](https://github.com/XenofonGk/train-yard-manager)
- **azclean.gr**: a client site for a cleaning business in Athens. React and Vite, plus the domain, DNS and search indexing.\
  [azclean.gr](https://azclean.gr)

## Selected projects

- **[ai-eng](https://github.com/XenofonGk/ai-eng)**: would your tests notice if the lines you just changed were wrong? It mutation-tests only the lines a diff touches. On 59 real zod bug fixes, reverted one at a time, it flagged the changed lines as weakly tested in 27 (45.8%). Zod's own test suite caught 0.
- **KykloC**: a field-service app for cleaning businesses and trades. Appointments, VAT invoicing, customers and recurring jobs in one place. React 19, TanStack Start, Tailwind, Supabase. A prototype; the code is private.\
  [Case study](https://xgbuilds.dev/projects/kykloc)
- **[AgentMesh](https://github.com/XenofonGk/AgentMesh)**: a self-hosted control plane for AI coding agents across Claude, Gemini, DeepSeek, Grok and Ollama. A credential proxy means the agent process never sees your API keys. TypeScript, Next.js, Fastify, Docker. In development.
- **[aoda-scan](https://github.com/XenofonGk/aoda-scan)**: a CLI that crawls a whole site and grades it against WCAG 2.1 AA and Ontario's AODA. A fault in a shared component becomes one fix, not fifty findings.
- **Home server**: Cloudflare Tunnel, Caddy, OpenTofu, Prometheus, Grafana and restic. Deploys are pull-based and check each image's signature first. It hosts the two live APIs above.

In progress: **[PixelForge](https://github.com/XenofonGk/PixelForge)**, a C++17 photo editor with no outside libraries. It is a practice project: I add one feature a day, and daily tests check each step.

## Work

- **Software Engineer Intern, Mercell** (Copenhagen, Jun–Aug 2026). Shipped the Document Library micro-frontend to production on a platform with 800,000+ users (React, TypeScript, Module Federation, NX). Built an accessible file-uploader library used by 3+ product teams. Cut accessibility violations in shared UI components by over 60%.
- **Web Developer, freelance and volunteer** (2021–present). Client sites [azclean.gr](https://azclean.gr) and [beautybybeautia.pages.dev](https://beautybybeautia.pages.dev). Volunteer WordPress site for the Kenyan non-profit [WAY Empowerment](https://wayempowerment.com).
- **Junior Software Developer, Spinworks** (Athens, Aug 2021–Aug 2022). B2B e-commerce with Symfony and OroCommerce.
- **Campus Coordinator (elected), Seneca Student Federation** (2026–present).

**Education:** Seneca Polytechnic, Ontario College Diploma in Computer Programming (expected April 2027).

## Stack

- **Frontend:** TypeScript · React · Next.js · TanStack Start · Tailwind
- **Backend:** C# · ASP.NET Core · EF Core · Python · FastAPI · PHP · Symfony
- **Data:** PostgreSQL · SQL Server · Supabase
- **Ops:** Docker · GitHub Actions · Cloudflare · OpenTofu · Prometheus · Grafana
- **Testing:** Jest · React Testing Library · axe-core · Playwright
