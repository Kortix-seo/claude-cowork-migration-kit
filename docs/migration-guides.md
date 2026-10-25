# The order an open-source Claude Cowork migration runs in

This repository, `Kortix-seo/claude-cowork-migration-kit`, is a kit for a team leaving Claude Cowork for Kortix, the open-source AI Operating System: the timeline of the September 2026 merge, a checklist, and the order the work runs in.

## What the exports carry, and what they leave

Anthropic gives back a bulk account export, a memory export, and Enterprise Cowork transcripts through the Compliance API. None of them carries a project's instructions, connector setup, skills or schedule in a form another platform can import. The [migration walk-through](https://opensourceclaudecowork.com/migrate-from-claude-cowork) starts from that gap and rebuilds one job at a time.

## The sequence

Capture each job's instructions, connector and cadence, and commit the capture before anything is rebuilt, so every later step reads from a file you own. Rebuild one job, move its memory into files beside it, reconnect the tools, schedule it as a trigger, then run one real task and merge the result. One isolated sandbox per session. Each session has its own isolated machine and branch.

## What to compare before picking a target

Compare where the capability runs: a desktop, your own infrastructure, or a vendor's cloud. The [alternatives roundup](https://opensourceclaudecowork.com/claude-cowork-alternatives) sorts the open field that way. Kortix is built for the second placement. Run it on Kortix Cloud, in your VPC, or on your own on-prem network. Self-host is free.

The kit's `docs/` holds the timeline, the checklist and the audit trail that go with this order.
