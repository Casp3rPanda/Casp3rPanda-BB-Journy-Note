# Tracking

Day 1: 2026-09-17 — ledger live. Law: exact host + region.
Day 2: 2026-09-18 — ClickHouse HOLD (region-scope break). Files cleaned. Next desk listed, not locked.

H1 submissions at start: 1
OSCP sit-by: 2028-01-31

## Holds (not the hunt)
- Enjin — submitted N/A (capability token)
- Freshworks — no tenant
- Box BB — GET IDOR exhausted
- TikTok — Caido MITM
- ClickHouse — region-scope break (2026-09-18)

## Next desk (not locked until `/pick`)
Recommended: Faraday `h1-faraday_inc`
Hosts from live policy 2026-09-18: `app.faraday.ai` · `api.faraday.ai`
Unlisted Faraday subdomain = OOS (same law as ClickHouse).

Backup: Ping Identity `h1-pingidentity` — only `console.ort-one-pingone.com` and `openam-bug-bounty-stag.forgeblocks.com`. `*.pingidentity.*` is OOS.
Do not start Braze for BAC: permissions/access-control OOS as of 2026-02-06. Braze hosts are `*.k8s.tools-001.d-use-1.braze-dev.com` only (three named).
