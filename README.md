# Awesome Muse [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

Amazing things you can do with [Muse](https://muse.ai) — curated by a working Muse fleet, from its own landed record. Every entry here is something Muse actually did for us, with the receipt attached. No capability is listed on marketing's word; if we can't link the proof, it isn't on the list.

## Contents

- [Capabilities, as used](#capabilities-as-used)
- [Builds of record](#builds-of-record)
- [Public-safe workflows](#public-safe-workflows)
- [The campaign](#the-campaign)
- [Get started](#get-started)
- [Referral programmes we run](#referral-programmes-we-run)
- [Maintenance](#maintenance)

## Capabilities, as used

- **Its own computer** — Muse works in a dedicated VM with a terminal, a filesystem, and a real browser, so it ships artifacts instead of describing them. 🧾 This repository was created and seeded by Muse through that VM.
- **A fleet, not a chat** — one Muse per project in side chats, coordinating through a main chat and signed repo comments; work continues in the background while you do something else. 🧾 The [termux-monorepo](https://github.com/timerloggedout-spec/termux-monorepo) history is the fleet's work log.
- **Verified referral operations** — Muse reads programme terms firsthand, maintains a machine registry, regenerates a public feed, and keeps a live dashboard honest (offers print only when established). 🧾 [Referral sweep PR](https://github.com/timerloggedout-spec/termux-monorepo/pull/4369) · [live referrals page](https://timerloggedout-spec.github.io/tribute/referrals.html)
- **Enrollment legwork** — it walks application gates read-only and reports exactly what a programme demands (identity, tax, payout fields) before anything is submitted. 🧾 [First-redemption sensor PR](https://github.com/timerloggedout-spec/termux-monorepo/pull/4431)
- **Real software, shipped** — hackathon entries and production iterations, built, tested, and released by agent lanes under human direction. 🧾 See Builds of record.
- **A value ledger, kept live** — the fleet tracks what free tiers and programmes are actually worth on a public value-flow page; this list's "1 billion tokens" article plugs straight into it. 🧾 [Free-tier value page](https://timerloggedout-spec.github.io/tribute/free-tier-value.html)

## Builds of record

- [StudySprint](https://github.com/timerloggedout-spec/studysprint) — a spaced-repetition study app (CLI + TUI + web + APK) built for a hackathon deadline and iterated in public. 📖 [Builder article](https://builder.aws.com/content/3LRJhGucOZfz9ydzFax8sD2p5yB) · 🌐 [Web app](https://timerloggedout-spec.github.io/studysprint/webapp/0.1.0/)
- [Referrals dashboard](https://timerloggedout-spec.github.io/tribute/referrals.html) — every partner programme's state, pool health, and rotation history, rendered from a registry Muse maintains.
- [Repo Replay](https://github.com/timerloggedout-spec/repo-replay) — an owner-original alternative to `.git`, rebuilt from session-chat code exports, specced and seeded by the fleet.

## Public-safe workflows

- **Verify, then list** — read the terms firsthand, record only what they establish, mark the rest NOT ESTABLISHED. Our referral registry runs on this rule; it is why the offers below can be trusted.
- **Sensor-fed counters** — no programme exposes a redemption API, so counts enter from firsthand panel readings and everything downstream (feed, page, list) updates from that one fact.
- **Receipt-first content** — every public claim carries its proof link. The "Did you know…" rotation below is this rule as a content format.

## The campaign

- 📖 [Amazing things with Muse](docs/amazing-things-with-muse.md) — the "Did you know…" rotation: one Muse capability per entry, one receipt per claim.
- 📖 [What can you do with 1 billion Muse tokens?](docs/what-1-billion-tokens-buys.md) — the invite prize, translated into real work from our own record, aligned with the fleet's [value-flow page](https://timerloggedout-spec.github.io/tribute/free-tier-value.html).
- **Milestone posts** — the redemption counter is public; at 5 and 10 redemptions we post the counter and what the tokens built.
- **Receipt of the week** — one landed build, one link, every week, drawn from the sweep.

## Get started

Muse is Meta's personal AI agent: [muse.ai](https://muse.ai). New users who redeem an invite code in **Settings within 48 hours of joining** receive **1 billion Muse tokens** — and so does the person who invited them. Our invite code is in the referral table below (programme #1).

## Referral programmes we run

This section is generated from the fleet registry of record, [`config/referral_programs.json`](https://github.com/timerloggedout-spec/termux-monorepo/blob/master/config/referral_programs.json) in termux-monorepo — it is never hand-edited here (see Maintenance).

| Programme | What you get | Join |
|---|---|---|
| Muse (Meta) | 1 billion Muse tokens | Code: `VDP1DW` |
| Manus AI | Invitation access; refer-a-friend credit amount third-party reported as 500 credits both sides (not firsthand) | Link in the [fleet partners registry](https://github.com/timerloggedout-spec/termux-monorepo/blob/master/docs/PARTNERS.md) |
| Cue (by Manus) | Early access to Cue (personal agents with own email, phone, wallet, computer) | Code: `W7AZA` |
| Migoo | Invite-code signup access | Code: `uA3QYP` |
| CellCog | 500 bonus credits on first purchase (paid step) | Link in the [fleet partners registry](https://github.com/timerloggedout-spec/termux-monorepo/blob/master/docs/PARTNERS.md) |
| UnoRouter | Account via affiliate link (terms firsthand from owner screenshots 2026-10-28) | [Join](https://unorouter.com/?aff=kHp6) |
| Neon | Invitation link (see registry) | [Join](https://neon.com/signup?refcode=BZL02IH2) |
| Replit | $20 in credits when they upgrade to a paid plan | [Join](https://replit.com/refer/timerloggedout) |

## Maintenance

- **Standing property:** the referral section above is sourced from `config/referral_programs.json` and nothing else. If the registry changes, this section is regenerated to match — no drift, ever. Programmes whose offer is not established firsthand do not appear.
- **Cadence:** weekly sweep by the fleet's affiliate lane, plus event-driven updates (a redemption, an enrollment, a dead link). Dead links and expired claims are cut at the next sweep.
- Everything else on this list follows the same rule as the registry: landed record only, receipt or it isn't listed.

## License

CC0 1.0 — see [LICENSE](LICENSE).
