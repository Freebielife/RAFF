# RAFF verification — 2026-11-24

- Template 1.3.0, source 65780137fa12eda7500f48d29c5b261411305274.
- HTML: 456769 bytes; SHA-256 `62c43123767677f205de90463b34311eba7dd409816c4f9f23f16a316eb6d647`.
- Verified token address, decimals 9 and three direct TON pools via successful
  TonAPI JettonSwap actions; configuration and source URLs in project.json.
- First local collector completed with no failed sections. 100 holder addresses,
  496 verified swaps, 15 accepted burn notifications, 62 indexed pools.
- History is partial and incremental, not a complete annual archive.
- Python: 17 tests passed. Node: 15 tests passed, plus JS syntax validation.
- Browser: desktop viewport 1363px, mobile iframe viewport 390px; no horizontal
  overflow. RU/EN and TON/USD controls, top-10/top-20 expansion, four common badge
  filters and five watermarks per buy/sell card were exercised.
- Fixed inherited daily-burn field mismatch (`project` -> `tokenAmount`);
  browser showed 2,006.2 RAFF across 8 transactions in the sampled 24h window.
- Embedded CSS/JS/art, no external rendering resources and no broken internal
  anchors. Remote data and wallet lookup require network.
- HTTP checks of configured static links: docs/link-checks.json. Telegram/X
  returned HTTP 403 from the execution host; the Telegram channel association
  was checked through its public official directory and channel in web search.
- Locks/staking have no verified integration; amounts remain unavailable.
- TON Storage/Resistance Tools publication has not been performed.
- GitHub 30-minute fallback cron configured; scheduled execution not yet observed.
- Cloudflare shared scheduler registration not verified; live registry untouched.

GitHub Actions push run [45359582748](https://github.com/Freebielife/RAFF/actions/runs/45359582748) completed successfully, including collection, build, verification and snapshot publication. Refreshed HTML/data commit: `8eac02c`. Final snapshot has no section errors. Scheduled cron and Cloudflare dispatch remain unobserved.
