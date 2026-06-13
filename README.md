# Uber Freight

Uber Freight is a digital freight brokerage platform providing 24/7 access to truckload freight with instant quoting and booking, real-time shipment visibility, lane management, and carrier network pricing. Its REST APIs enable shippers and TMS platforms to generate price quotes, tender loads, cancel tenders, and automate facility scheduling backed by a network of 50,000+ carriers across the U.S. and Europe.

**Website:** https://www.uberfreight.com/  
**Developer Portal:** https://developer.uberfreight.com/get-started  
**Status:** https://uber.statuspage.io/  
**Blog:** https://www.uberfreight.com/en-US/blog/  

## APIs

- **Loads API** — Generate price quotes, tender loads, cancel tenders (OAuth 2.0, freight.loads scope)
- **Scheduling API** — Automated dock appointment booking via Scheduling Standards Consortium (SSC) Technical Standard
- **Real-Time Tracking API** — Shipment visibility from pickup through delivery; embedded in Oracle TM, SAP, Blue Yonder, BluJay TMS integrations

## Repository Contents

| Path | Description |
|------|-------------|
| `apis.yml` | APIs.json 0.19 provider index |
| `plans/uber-freight-plans-pricing.yml` | Pricing plans and access model |
| `rate-limits/uber-freight-rate-limits.yml` | Rate limits and authentication details |
| `finops/uber-freight-finops.yml` | FinOps cost drivers and optimization tips |

## Access

API access requires registering an app at https://developer.uber.com/dashboard/ and emailing freight-api@uber.com to request the `freight.loads` scope. Uber responds within 1 business day.

---

Maintained by [Kin Lane](mailto:kin@apievangelist.com) via [API Evangelist](https://apievangelist.com).
