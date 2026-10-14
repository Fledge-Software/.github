# Fledge Software

**Develop fully and take flight.**

Software for the small businesses that hold a town together.

Fledge Software builds tools for one- to five-person service businesses: the
people who do the work themselves. We build the parts of the business that get
dropped when the day runs long.

> **Where we are:** everything below is in development. Nothing is generally
> available yet. We'll say so here when that changes.

## Fledge App

**One app a small business runs on, made of modules.**

Fledge App is the shell: sign-in, the business's people and roles, search,
settings and billing. The features live in modules. A business adds the modules
it needs and the owner decides who can use each one. Every module is its own
app in its own repository, served inside Fledge App under its own path, so each
one can be built, tested and shipped on its own.

### Modules in development

| Module | What it does |
| --- | --- |
| **Nest** | The free hub every business gets. Contacts, jobs on a pipeline, tasks, and table and board views. Customer data from integrations lands here, and the other modules read from it. |
| **Growth** | Automatic follow-up after every job, sent by text: review requests (**Reputation**), referral invites (**Referrals**), rebook reminders (**Retention**) and win-backs (**Recovery**). |
| **Connect** | The connecting part of a business: mail, calendar, team chat and booking. |
| **Desk** | Documents: docs, tables, canvases, databases and files. |
| **Rankings** | The business's website and how it shows up in local search. |
| **Reach** | Turns a business's videos into social posts. |

New modules start from a shared template that holds the module contract, so
each one plugs into Fledge App the same way.

## Fledge Charter

**Form a business and file its taxes, business and personal, without a lawyer
or an accountant.**

Charter is a separate app, not a Fledge App module. It handles entity formation
and EIN, ongoing compliance, information returns (1099, W-2) and income tax
filing through licensed partners. Fledge provides the tools, not legal or
accounting services. A newly formed business can then step straight into Fledge
App.

## Syrinx

**A browser you can add plugins to.** · [syrinxapp.dev](https://syrinxapp.dev) · [Source](https://github.com/Fledge-Software/Syrinx-app)

Syrinx is a web browser with vertical tabs and one command palette. Plugins
open as tabs beside your pages. It's written in Rust, and its interface is drawn
with GPUI.

- **Available now:** Windows 11, as weekly preview builds on the
  [releases page](https://github.com/Fledge-Software/Syrinx-app/releases).
- **Planned:** Windows, macOS and Linux, then iOS and Android.

**Plugins we're planning:**

- **Fledge:** your Fledge App, opened in the browser.
- **Notes:** note-taking.
- **Forge:** a code editor (IDE) built in Rust.

Because Syrinx is built in Rust, other Rust apps could become plugins without
giving up their performance.

Syrinx is open source under the [Mozilla Public License 2.0](https://github.com/Fledge-Software/Syrinx-app/blob/main/LICENSE).

## What we believe

- **A good business should not lose to a better-marketed one.** Most small
  service businesses don't have a growth problem. They have a follow-up
  problem, and follow-up is unpaid work that happens after a ten-hour day.
  Software is good at exactly that.
- **Say what the product does, and not more.** We publish what is built, what
  is being built, and what is only an idea, and we keep the three separate.
- **One price, no negotiation.** The owner of a two-truck operation pays the
  same as anyone else and doesn't have to talk to a salesperson to find out
  what that is.
- **We will not game a customer's reputation.** Review requests go to every
  customer, whatever they thought of the visit.

## Who we are

Founded in 2026 in Virginia and incubated by BuyIt Ventures.

- **Landon Boggs**, co-founder: product, design, operations and sales
- **Christian Arroyo**, co-founder: engineering, security and IT

## Get in touch

| | |
| --- | --- |
| General | [hello@fledgesoftware.com](mailto:hello@fledgesoftware.com) |
| Support | [support@fledgesoftware.com](mailto:support@fledgesoftware.com) |
| Legal and privacy | [legal@fledgesoftware.com](mailto:legal@fledgesoftware.com) |
| Hours | Monday to Friday, 8am to 6pm Eastern |

🌐 [fledgesoftware.com](https://fledgesoftware.com) · 🧭 [syrinxapp.dev](https://syrinxapp.dev)

<sub>Fledge Software, a DBA of BuyIt Ventures.</sub>
