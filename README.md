# Beyond Pixells — Estate Status

Free, serverless uptime monitoring for every live Beyond Pixells property:
flagship landings, client gym systems, and the Gym OS platform. Runs entirely
on **GitHub Actions + Issues + Pages** via [Upptime](https://upptime.js.org) —
₹0/month, no server to maintain.

- **Status page:** https://somilsharma2000.github.io/beyond-pixells-status/
- **Checks:** every 5 minutes (Uptime CI workflow)
- **Alerts:** a GitHub issue is auto-opened on any failure and closed on recovery
- **History:** 90-day response-time graphs, committed to this repo as data

The lead-capture API is intentionally not monitored here yet (returns 402
while Base44 integration credits are exhausted — would show permanent red);
the agent's daily estate review covers it. See `.upptimerc.yml` for details.

Managed by the Beyond Pixells agent. Research record: `docs/research/tools_monitoring.md`
in the [beyond-pixells](https://github.com/somilsharma2000/beyond-pixells) repo.
