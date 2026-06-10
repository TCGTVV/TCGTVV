# Hi, I'm Leopold

SAP Business One Consultant on the way to an SAP S/4HANA Platform / Technical Architect role, somewhere at the intersection of deep SAP knowledge, modern software engineering, and Linux infrastructure.

What really drives me is curiosity. I genuinely love this field and I'm happiest when I'm learning something new about how systems work, then actually getting my hands dirty with it rather than just reading about it. I treat consulting like engineering work: reproducible setups, things kept under version control, clean migrations, and systems that the next person can actually maintain.

## What I do

I work as an SAP B1 consultant at rocon, handling implementations, version upgrades, and HANA/Linux migrations across customer environments. The day-to-day is a mix of technical troubleshooting, SQL Server and HANA tuning, e-invoicing topics (XRechnung, OZG-RE), coresuite customizing, and a fair amount of direct customer communication.

Outside of SAP, Linux and open source are where I'm most at home. Arch/CachyOS is my daily driver, I run a bit of self-hosted infrastructure, and I occasionally contribute upstream (for example to Infomaniak's kDrive client).

My background runs Fachinformatiker, then IT administration, then SAP consulting, and I'm finishing a dual-study B.Sc. in Wirtschaftsinformatik at IU International University of Applied Sciences in 2027.

## What I'm into right now

I'm digging deep into software and programming architecture at the moment, and learning a lot in the process. Design decisions, trade-offs, what makes a system hold up over time. It's the thread that connects my SAP work, my side projects, and where I want to take my career.

I also try to stay right at the front of what's happening in AI. I test pretty much every new tool that comes out, from agentic coding assistants to MCP-based setups, partly out of pure curiosity and partly because I want to understand where this is genuinely useful in real SAP and SME work, not just in demos.

On the SAP side, my near-term milestone is the C_TADM_23 certification (System Administration), which sits squarely on the road toward S/4HANA architecture.

## What I'm building

[SubTracked](https://github.com/TCGTVV/SubTracked) is my current main project and the one I put the most into. It's a local-first desktop app that tracks recurring payments and forecasts your account balances into the future, so it can warn you before an upcoming charge pushes a balance below its safety buffer or into the red. Built with Tauri 2 (a Rust core with the system WebView) and React 19 on strict TypeScript, it keeps everything locally in SQLite and runs an independent reminder loop in Rust so notifications still fire when the window is hidden. No account, no cloud, by design, because subscription and account data is private financial data. It's where the architecture thinking I keep going on about actually gets tested: a clean split between the Rust process and the frontend, tests on both sides, and CI with pre-commit quality gates.

[LifeBacklog](https://github.com/TCGTVV/LifeBacklog) is personal development run like a software project: epics, tickets, a WIP limit of 1, and Definition-of-Done criteria, all managed through the GitHub CLI and Issues. Basically an experiment in pointing an Informatik mindset at my own habits.

[arsnova.eu](https://github.com/TCGTVV/arsnova.eu) (a fork) is where I get hands-on with a modern Angular 21, tRPC, and Prisma TypeScript monorepo, including LSP-based tooling (Serena MCP) for symbol-level refactoring.

## Toolbox

SAP and data: SAP Business One, SAP HANA, SQL Server, coresuite, B1 upgrades and migrations.

Toward S/4HANA: system administration, platform and migration concepts, software architecture.

Dev and infra: Rust, Tauri, TypeScript, React, Angular, Node.js, SQLite, Docker, Git and GitHub Actions, Linux server administration.

AI tooling: agentic coding assistants, MCP servers, and whatever just shipped this week.

Workflow: Arch/CachyOS with KDE Plasma, open-source and self-hosted tooling wherever it makes sense.

## Languages

German (native), English (C1), Spanish (learning), Korean (learning).
