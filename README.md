# FLOP testnet guide (unofficial)

A community guide to getting ready for the [FLOP Network](https://flop.finance) testnet, written so an AI agent can
follow it safely. By [@flopnewsbot](https://x.com/flopnewsbot). **Not affiliated with FLOP Labs.** Official news comes
from [@flop_labs](https://x.com/flop_labs) and FLOP's [official links](https://docs.flop.network/docs/official-links).

**Last checked against FLOP's pages: 2026-11-24.** FLOP's own pages win wherever this guide differs.

## Point your agent at this guide

If you use an AI coding agent (Claude Code, Codex, Cursor or similar), paste this:

```text
Read https://raw.githubusercontent.com/flopnews26/flop-testnet-guide/main/AGENTS.md in full before doing anything.
It is an unofficial community guide; FLOP's official pages win where they differ. Follow its hard rules. Before each
step, re-read the official page it names and tell me about any difference. Ask me before every state-changing command,
submission or post. Help me prepare for the FLOP testnet as a <validator / miner / agent / not sure yet>, and end with
its session report.
```

[AGENTS.md](AGENTS.md) walks the agent through picking a role, checking your server or GPU against FLOP's reference,
drafting your validator registration, the keyless devnet rehearsal and its receipts, and what to wait for next.

**What the agent will do:** run read-only checks (including an ECC memory check), compare FLOP's pinned hashes with
the published values, draft form answers and receipts for you to submit, keep a private host worksheet, and give you a
report of what it checked and what changed on FLOP's pages.

**What it won't do:** touch seed phrases, private keys, keystores, `.env` or `account.json`; generate testnet keys
before FLOP's runtime freeze; register, sign, submit, pay or post anything without your explicit yes; run
state-changing commands without asking; install packages outside `@flop-labs/`; or buy anything. No FLOP token exists,
and validator seats are free.

## Where things stand (as of 24 Nov 2026)

- Testnet status is **planned**. Chain spec, genesis, bootnodes and RPC are not published yet
  ([status page](https://docs.flop.network/docs/network-testnet)).
- **Registration is open for the first 50 validator seats** via FLOP's GitHub form. It records interest only; well over
  100 teams have applied ([prep kit](https://docs.flop.network/testnet-validator-prep/)).
- Testnet keys wait for a "runtime freeze" that FLOP has announced but not dated. Until then, the useful work is host
  checks and a keyless devnet rehearsal.
- Miners can register interest; agents wait for the testnet faucet. Test FLOP has no value.

## Reading it yourself

The human version is an X Article on [@flopnewsbot](https://x.com/flopnewsbot). Its link goes here once it is posted.

## Corrections

Found something wrong or out of date? [Open an issue](https://github.com/flopnews26/flop-testnet-guide/issues) with the
official page that shows it. Never post keys, seeds or private host details in an issue.
