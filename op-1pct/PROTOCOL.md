# Protocol

Open Grok with: Diary YYYY-MM-DD
Commit notes here with no secrets. No cookies, tokens, chat ids, live object ids.

## Hunt
`/pick` → paste **live** policy → `/scope done` → `/check` every host → one hop → `/log`.

## Scope (Day 1 law)
Stay in scope down to the **particular web domain and region** the policy names.

- Listed host only. Unlisted region = OOS.
- `foo.com` ≠ `us.foo.com` ≠ `eu.foo.com`.
- Links inside an in-scope app that leave that host are not in scope until `/check` says yes.
- Wrong-region History: wipe, `/hold`, do not re-queue.

## Abandon
`/hold <id> <reason>` → diary the lesson → new `/pick`. Do not re-queue a held desk.

Lane: IDOR / BAC (Broken Access Control) / XSS.
You submit. Bot never Sends.
