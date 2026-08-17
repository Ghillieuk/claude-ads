# Ghillie Clothing — Meta Ads Performance Audit

Weekly automated audit log. Newest entries first.

---

## 2026-08-17 — Run skipped: Adspirer connector not enabled

**Status:** No data pulled. No changes made to the ad account (this audit is read-only regardless).

**What happened:** Same blocker as the previous run. This run checked the Adspirer MCP connector before pulling any data, per the standing verification step. `ListConnectors` shows the connector is installed on the account but still not enabled for this session (`enabledInChat: false`, `installState: unknown`), and a tool search found none of its tools (`get_connections_status`, `get_meta_campaign_performance`, `audit_conversion_tracking`) reachable. Since the run could not verify the Meta connection, it did not proceed to data pull, scoring, or dashboard regeneration — no numbers have been fabricated or estimated.

**What's needed to unblock next run:** Enable the Adspirer connector for this session/agent in the Claude connector settings (it currently shows as installed but toggled off for chat). This has now been the blocker for two consecutive weekly runs. Once enabled, the next scheduled run will verify the connection via `get_connections_status` and, if the Meta account (ad_account_id `2631295333650600`) is connected, proceed with the full audit and dashboard refresh.

No dashboard file (`meta-ads-dashboard.html`) has been created or modified this run, since there is no prior version to refresh and no fresh data to build one from.

---

## 2026-08-10 — Run skipped: Adspirer connector not enabled

**Status:** No data pulled. No changes made to the ad account (this audit is read-only regardless).

**What happened:** This run checked the Adspirer MCP connector before pulling any data, per the standing verification step. The connector is installed on the account but is not enabled for this session (`enabledInChat: false`, `installState: unknown`), so none of its tools (`get_connections_status`, `get_meta_campaign_performance`, `audit_conversion_tracking`) were available to call. Since the run could not verify the Meta connection, it did not proceed to data pull, scoring, or dashboard regeneration — no numbers have been fabricated or estimated.

**What's needed to unblock next run:** Enable the Adspirer connector for this session/agent in the Claude connector settings (it currently shows as installed but toggled off for chat). Once enabled, the next scheduled run will verify the connection via `get_connections_status` and, if the Meta account (ad_account_id `2631295333650600`) is connected, proceed with the full audit and dashboard refresh.

No dashboard file (`meta-ads-dashboard.html`) has been created or modified this run, since there is no prior version to refresh and no fresh data to build one from.

---
