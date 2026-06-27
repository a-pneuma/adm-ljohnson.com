---
title: "Why I'm Building This"
date: 2026-06-25
summary: "On documentation, portfolios, and why this site exists in the first place."
tags: ["meta"]
draft: false
---

I've spent a long time fixing things, configuring things, and explaining things to
clients, and almost none of that work has ever existed anywhere outside a ticket
system or an e-mail chain. Solve a tricky Exchange on-prem routing issue once, and
there's a real chance I'll solve a slightly different version of the same problem
eight months later, having fully forgotten the first time.

That's reason one for this blog. It's documentation for myself as much as anyone else.

## The Documentation Problem

Every sysadmin has a version of this story: a problem gets solved under pressure, the
fix works, and the actual *reasoning* behind it evaporates the moment the ticket
closes. Six months later, something similar breaks, and there's a faint, frustrating
memory of having dealt with this exact flavor of weird before, with none of the useful
detail attached.

Writing things down properly, not just "did this, fixed it." but *why* it broke and
*why* the fix worked, is the actual skill. This site is partly just me forcing myself
to practice that skill consistently instead of only when a client's paying for it.

## The Portfolio Problem

A resume is a list of claims. "Experienced with Azure, Fortinet, CMMC compliance"
doesn't show anyone how I actually think through a problem, what my troubleshooting
process looks like, or what I do when the documentation doesn't cover the situation
in front of me.

A detailed, honest breakdown of a real project does that. So this is also,
unapologetically, a portfolio, built the way I'd want to evaluate someone else's work
if I were hiring.

## Building Something From Scratch

This blog itself is the first project worth writing about. A Debian VPS, Hugo, Caddy,
hand-rolled styling, a custom logo, and a command-palette search feature I had no
strict *need* to build, except that it seemed like a genuinely good way to learn
something new.

{{< figure src="01-hugo-build-output.png" alt="Terminal output of a successful Hugo build" caption="The build that kicked this whole thing off." >}}

There were a handful of real mistakes along the way, an SSH key typo, a permissions
issue that 403'd the whole site, a placeholder domain that quietly redirected visitors
somewhere else entirely. I'm planning to write about those too, since the failures are
usually more instructive than the parts that worked on the first try.

## What You'll Find Here

Going forward, expect a mix of:

- **Homelab projects** — Proxmox, Docker, Kubernetes, DevOps, Networking, self-hosted services, and the inevitable troubleshooting that comes with running your own infrastructure
- **Microsoft 365 & Azure deep-dives** — the kind of tenant-level weirdness that doesn't show up in the official docs
- **Networking notes** — Fortinet, Cisco, and whatever firewall is causing problems that week
- **CMMC & NIST compliance** — making sense of frameworks that drive our industry forward *(sometimes backwards)*
- *Whatever else* crosses my desk and seems worth writing down properly

If any of it saves you a few hours of troubleshooting, that's a bonus. Mostly, I'm just here to write
about the things I love and keep better notes than I have been.
