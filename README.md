# Anthony Nader

I'm not a software engineer by training. I come from finance and operations, and I build the way engineers would want a business builder to: tested, measured and reviewed.

I build with AI to be more useful where I work, so every tool has to move revenue, margin, cost or time. Given the choice, I would rather have AI write me a Python tool that does the job than have AI do the job itself. Models are not yet dependable enough to be trusted with the numbers. Code can be read, tested and rerun, and it gives the same answer every time.

These repos are sanitised samples of real work on synthetic data. Each README says where the method breaks.

## Three uses I've found for AI

- **Screen.** Cut thousands of records to a shortlist a leader can act on. Lever: revenue and time.
- **Analyze.** Size a deal, a spend line or a risk before anyone commits, with figures computed in code. Lever: margin, cost and risk.
- **Automate.** Run the recurring briefs, triage and dashboards a leader judges value by; a person approves anything irreversible. Lever: time and risk.

## Background

- **Private equity.** Chief of staff at a lower-middle-market energy PE firm; I lead its AI work, and every tool is scored on margin or time saved before it is built.
- **Epic Systems.** Worked on a hospital system's Epic implementation.
- **ExxonMobil Low Carbon Solutions.** Interviewed 200+ people to map cost tracking for Department of Energy grant compliance.

Most projects come from Dandoun Group, which I started to build with AI and solve problems I kept seeing in my network.

## Projects

| Project | What it does | Use | Lever it pulls | Where AI sits |
|---|---|---|---|---|
| [farmland-acquisition-map](https://github.com/anader298/farmland-acquisition-map) | Finds, values and screens Illinois farmland from free public records before it reaches market. Full build: 529,213 parcels; repo uses synthetic data. | Screen | Revenue: off-market targets with owners named. Cost: free public records instead of paid data. | Build time only. No model in the repo; every value is a median or formula in Python. |
| [pit-wall](https://github.com/anader298/pit-wall) | Profiles the family businesses behind a racing paddock, sizes B2B deals between them (low, base, high; five-year NPV) and gates outreach. | Analyze | Commercial: who sells to whom, and deal size. Demand: what each family business buys. Supplier: a supplier or second source inside the paddock. | Build time. Live, a model drafts outreach; here a template does. Code sizes deals and blocks drafts citing unverified figures. |
| [chief-of-staff-agent](https://github.com/anader298/chief-of-staff-agent) | Three briefs a day; an hourly watcher over four mailboxes and a calendar. Drafts replies but cannot send alone. | Automate | Time: the inbox and day triaged before a leader opens them. Risk: nothing leaves unapproved. | Run time: Claude Code steered by markdown. A tested hook and a mail-tool check block any send without fresh approval. |
| [diligence-rooms](https://github.com/anader298/diligence-rooms) | A password-gated research room on a counterparty and its people before a meeting, plus a live meeting companion. | Analyze | Commercial: negotiation prep on the counterparty. Risk: figures rechecked live in the meeting. | Both. Agents build the room. At run time the companion calls Claude (Gemini for speech-to-text); the server recomputes any model calculation. |
| [wedding-guest-platform](https://github.com/anader298/wedding-guest-platform) | Per-family invitation links, RSVPs, helper and owner pages, Excel in and out. | Automate | Time: guest lists and RSVPs run from one place instead of chased by hand. | Build time only. Nothing in the product calls a model. |

## How I build

Method, and what I don't do well yet: [how-i-build-with-ai](https://github.com/anader298/how-i-build-with-ai). Case studies with results and limits: [dandoungroup.com/case-studies](https://dandoungroup.com/case-studies/)
