# Cyberbullying Awareness Portal (Attaa)

> Arabic-language (RTL) awareness portal about cyberbullying risks for children, built under Attaa (Digital Giving Initiative, sponsored by Saudi Arabia's Ministry of Communications and Information Technology). Educates parents through guides, risk articles, parental-control setup instructions, videos, and surveys.

## Links

- Archived snapshot (2021-03-03): [https://web.archive.org/web/20210303144514/https://cyberbullying.attaa.sa/](https://web.archive.org/web/20210303144514/https://cyberbullying.attaa.sa/)
- Original (offline): [https://cyberbullying.attaa.sa/](https://cyberbullying.attaa.sa/)
- Parent initiative: [https://attaa.sa/](https://attaa.sa/)

## What it contains

- **Parents' guide**: downloadable PDF on opportunities and risks children face online.
- **Editorial section** (`/digital-world`): "My child and the digital world."
- **Risk library** (6 articles): what cyberbullying is, educating your child, parent-child dialogue, handling complaints, cyber vs. physical bullying, when your child bullies others.
- **Statistics band**: global exposure figures with cited sources.
- **Parental-control guides** per platform: PlayStation, Xbox, Nintendo, Android, Apple, Windows.
- **Video library**: YouTube embeds plus "Anti-bullying Squad" series.
- **Survey CTA**: Google Forms questionnaire on gaming-disorder prevalence.
- **Partners page** and shared Attaa navigation (events, e-learning, webinar, content library, podcast, login via `attaa.sa`).



## Frontend developer role

- Implemented full RTL Arabic layout: typography, spacing, and reading order verified for right-to-left.
- Built article-card grids, statistics band, platform-icon guides, video library, and survey/partner sections from content specs.
- Added accessibility touches: font-size toggle (A+/A-), readable contrast, keyboard-reachable navigation.
- Integrated YouTube embeds and external Google Forms CTA without breaking layout or performance.
- Wired auth-adjacent entry points (login redirect to `attaa.sa`) and shared-initiative navigation.
- Handled asset pipeline under `/assets/frontend/img/...` and kept pages light for parent audiences on varied devices.



## Tech signals

- Custom Frontend JavaScript app with webpack bundler and PHP backend.
- RTL layout, font-size controls, CMS-style article routing, YouTube + Google Forms integrations.

