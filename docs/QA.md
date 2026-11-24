# RAFF verification — 2026-11-24

- Template 1.3.0, source 65780137fa12eda7500f48d29c5b261411305274.
- HTML: 378133 bytes; SHA-256 `f0efc5fb6f48efd1a3980ac7685409c587aa1b92c0d7dbc75a569a68344c84f4`.
- Verified token address, decimals 9 and three direct TON pools via successful
  TonAPI JettonSwap actions; configuration and source URLs in project.json.
- First local collector completed with no failed sections. 100 holder addresses,
  257 verified swaps, 15 accepted burn notifications, 62 indexed pools.
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
