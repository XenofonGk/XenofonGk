# Xenofon Gkioka

**Full-stack developer · React, TypeScript, C#/.NET · Toronto** · open to full-stack roles in Canada and the EU

I build software and I run it. Most of what's below is live right now on a home server I set up the way production is set up: no open ports, signed images, alerts on my phone, backups I've actually restored.

[xgbuilds.dev](https://xgbuilds.dev) · [LinkedIn](https://www.linkedin.com/in/xenofon-gkioka/) · [ksenofwn58@gmail.com](mailto:ksenofwn58@gmail.com)

## Live right now

| | What it is | Try it |
|---|---|---|
| **TaskManager API** | ASP.NET Core + EF Core + PostgreSQL, key-protected writes, contract-tested on every push | [tasks.xgbuilds.dev](https://tasks.xgbuilds.dev/swagger) · [code](https://github.com/XenofonGk/DotNet/tree/main/WebAPI/TaskManagerAPI) |
| **Resume Classifier** | scikit-learn model served with FastAPI; sorts resume text into 5 job families with a confidence score | [resume-classifier.xgbuilds.dev](https://resume-classifier.xgbuilds.dev) · [code](https://github.com/XenofonGk/ai-programming-tools/tree/main/AI%20Resume%20Classifier%20(NLP%20%2B%20ML)) |
| **azclean.gr** | Client site for a cleaning business in Athens: React + Vite, domain, DNS, search indexing | [azclean.gr](https://azclean.gr) |
| **Train Yard validator** | C compiled to WebAssembly, the same code its test suite runs | [run it in the browser](https://xgbuilds.dev/projects/train-yard-manager) |

## Things I've built

- **[AgentMesh](https://github.com/XenofonGk/AgentMesh)**: a self-hosted control plane for AI coding agents across Claude, Gemini, DeepSeek, Grok and Ollama. A credential proxy means the agent process never sees your API keys. TypeScript, Next.js, Fastify, Docker.
- **[ai-eng](https://github.com/XenofonGk/ai-eng)**: would your tests notice if the lines you just changed were wrong? It mutation-tests only the lines a diff touches. On 59 real zod bug fixes, reverted one at a time, it flagged the changed lines as weakly tested in 27 (45.8%); zod's own test suite caught 0.
- **[aoda-scan](https://github.com/XenofonGk/aoda-scan)**: crawls a whole site and grades it against WCAG 2.1 AA and Ontario's AODA, rolling a fault in a shared component up into one fix instead of fifty findings.
- **Home server**: Cloudflare Tunnel, Caddy, OpenTofu, Prometheus, Grafana, restic. Pull-based deploys that verify each image's signature first.

## Work

- **Software Engineer Intern, Mercell** (Copenhagen, Jun–Aug 2026): shipped the Document Library micro-frontend to production on a platform with 800,000+ users (React, TypeScript, Module Federation, NX), built an accessible file-uploader library used by 3+ product teams, and cut accessibility violations in shared UI components by over 60%.
- **Junior Software Developer, Spinworks** (Athens, Aug 2021–Aug 2022): Symfony and OroCommerce B2B e-commerce.
- **Web Developer, freelance and volunteer** (2021–present): client sites [beautybybeautia.com](https://beautybybeautia.com) and [azclean.gr](https://azclean.gr); volunteer WordPress site for the Kenyan non-profit WAY Empowerment.
- **Campus Coordinator (elected), Seneca Student Federation** (2026–present).
- **Seneca Polytechnic**: Ontario College Diploma, Computer Programming (expected April 2027).

## Stack

TypeScript · React · Next.js · C# · ASP.NET Core · EF Core · Python · FastAPI · PHP · Symfony · PostgreSQL · SQL Server · Docker · GitHub Actions · Cloudflare · OpenTofu · Jest · React Testing Library · axe-core
