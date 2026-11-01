<p align="center">
  <img src="./assets/banner.svg" alt="Awesome Marketing Analytics & Attribution Banner" width="100%" />
</p>

# 📈 Awesome Marketing Analytics & Attribution 🎯

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Marketing-Analytics-Attribution/stargazers"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Marketing-Analytics-Attribution?style=flat-square&logo=github" alt="GitHub Stars" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Marketing-Analytics-Attribution/network/members"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Marketing-Analytics-Attribution?style=flat-square&logo=github" alt="GitHub Forks" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Marketing-Analytics-Attribution/issues"><img src="https://img.shields.io/github/issues/ishandutta2007/Awesome-Marketing-Analytics-Attribution?style=flat-square" alt="Issues" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Marketing-Analytics-Attribution/blob/main/LICENSE"><img src="https://img.shields.io/badge/License-MIT-green.svg?style=flat-square" alt="License" /></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/flllowers/ishandutta2007?label=Follow" /></a>
</p>

> 🚀 **A curated directory of top SaaS platforms and open-source software for Multi-Touch Attribution (MTA), Bayesian Marketing Mix Modeling (MMM), Customer Journey Mapping, and First-Party Measurement Infrastructure.**

---

## 🔍 Overview & SEO Context 📊

Modern marketing measurement has entered a transformative era. Driven by third-party cookie deprecation, privacy frameworks (GDPR, CCPA, Apple ATT), and omnichannel fragmentation across ad networks, digital growth teams rely heavily on scientific measurement:

- **Multi-Touch Attribution (MTA)**: Deterministic, algorithmic (Markov Chain removal effects), and cooperative game theory (Shapley Values) allocating conversion credit across touchpoints.
- **Marketing Mix Modeling (MMM)**: Top-down Bayesian statistical causal inference evaluating media saturation (Hill functions), adstock decay, and incremental lift without user-level tracking.
- **Event Streaming & Customer Data Platforms (CDP)**: Warehouse-native first-party data collectors streaming behavioral clickstreams directly into Snowflake, BigQuery, ClickHouse, and Databricks.

---

## 📑 Table of Contents 📌

- [📊 Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [🏢 SaaS / Hosted Attribution Platforms](#-saas--hosted-attribution-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🤝 How to Contribute](#-how-to-contribute)
- [⭐ Star History](#-star-history)
- [💖 Support & Community](#-support--community)
- [⚠️ Disclaimer](#️-disclaimer)

---

## 📊 Sector Overview & Market Dynamics 🌐

The global marketing analytics and attribution software market is valued at approximately **$5.8 billion to $6.15 billion** (projected to reach over **$14 billion to $29 billion** by the mid-2030s at a **13%–17% CAGR**). 

The sector is **moderately to highly fragmented**: while enterprise cloud giants dominate broad digital analytics ecosystems, no single vendor captures a winner-take-all monopoly in cross-channel attribution, resulting in specialized fragmentation across B2B multi-touch revenue attribution (MTA), DTC e-commerce measurement, and Bayesian marketing mix modeling (MMM).

---

## 🏢 SaaS / Hosted Attribution Platforms ☁️

| Product | Pricing (Starting Tier) | Free Tier / Trial Limits | Company Scale (Valuation / Revenue) | Description |
| :--- | :--- | :--- | :--- | :--- |
| **[Google Analytics](https://analytics.google.com/)** | $50,000/year (GA 360 starting tier) | Free forever (Up to 10M events per exploration query, 1M BigQuery export events/day, 14-month data retention) | Alphabet subsidiary / $2.2T+ market cap ($350B+ revenue) | 📈 Web and app analytics with data-driven attribution models, funnel exploration, and integration with Google Ads for cross-channel measurement. |
| **[Adobe Analytics](https://business.adobe.com/)** | $2,000/month (~$24,000–$50,000+/year for Select tier) | No free tier or trial (Evaluation via scheduled enterprise sales demo only) | Adobe subsidiary / ~$215B market cap ($21B+ annual revenue) | 💼 Enterprise analytics with advanced attribution modeling, Marketing Channels, and integration across Adobe Experience Cloud. |
| **[Bizible (Adobe Marketo Measure)](https://business.adobe.com/)** | $1,666/month (~$20,000–$40,000+/year billed annually) | No free tier or trial (Evaluation via custom enterprise demo only) | Adobe subsidiary / Part of Adobe Experience Cloud ($215B market cap) | 🎯 B2B marketing attribution platform (acquired by Marketo/Adobe); tracks multi-touch attribution from first touch through closed-won revenue. |
| **[HubSpot Analytics and Attribution](https://www.hubspot.com/)** | $800/month (Marketing Hub Pro for contact attribution; $3,600/month for Enterprise multi-touch revenue attribution) | Free tools forever (300 marketing emails/month, 1,000 CRM contacts, 2 users, 1 deal pipeline; attribution gated) | Public (NYSE: HUBS) / ~$31B market cap ($2.6B+ ARR) | 🧲 Native analytics and attribution within HubSpot's CRM; connects marketing touchpoints to contact records and deals for multi-touch revenue attribution. |
| **[Amplitude](https://amplitude.com/)** | $0 base (Plus tier usage starts at $0 for initial volume, scaling with event volume) | Free forever (Up to 2,000,000 events/month, 10,000 session replays/month, unlimited seats, 1-year data retention) | Public (NASDAQ: AMPL) / ~$1.4B market cap ($290M+ ARR) | 🔍 Product analytics with attribution and journey analysis; connects marketing touchpoints to product behavior and retention. |
| **[Mixpanel](https://mixpanel.com/)** | $0 base (Growth tier starts around $100–$140/month past free allowances) | Free forever (Up to 1,000,000 events/month, 10,000 session replays/month, unlimited seats, 2-year data history) | Private / $1.05B valuation ($150M+ ARR) | ⚡ Product analytics with attribution capabilities; tracks user journeys and channel impact on conversion events. |
| **[Rockerbox](https://www.rockerbox.com/)** | $2,000/month ($24,000/year minimum contract) | No free tier or trial (Evaluation via guided consultative demo only) | Acquired by DoubleVerify for $82.6M (~$5M–$10M ARR) | 🛒 Marketing attribution platform for omnichannel brands; provides multi-touch attribution, marketing mix modeling, and incrementality testing. |
| **[Triple Whale](https://www.triplewhale.com/)** | $0/month (Free Tier; paid Foundation tier starts at $219/month based on GMV) | Free forever (First-click and last-click attribution via Triple Pixel, 10 seats, 12-month data retention, limited Moby AI) | Private / $55M total funding raised (~$21M–$34M ARR) | 🐋 E-commerce analytics platform with first-party attribution, blended ROAS, and AI-powered insights for DTC brands. |
| **[Dreamdata](https://dreamdata.io/)** | $0/month (Free Starter; paid Advanced tier starts at $750–$999/month) | Free forever (Up to 5 seats, 2 months active historical data, 3 stage models, 1 sync, 2 notifications) | Private / $65M total funding raised (~$1.5M–$3M ARR) | 🚀 B2B revenue attribution platform; connects marketing, sales, and CRM data to build multi-touch attribution models across the full go-to-market motion. |
| **[Attribution App](https://attributionapp.com/)** | $199/month (Shopify plan billed monthly up to 10k MTUs; Pro plan at $399/month) | 14-day free trial (Full feature access and multi-touch attribution up to 10,000 MTUs) | Private / Bootstrapped (~$880K ARR) | 📱 Marketing attribution platform for ecommerce and SaaS; provides multi-touch attribution, funnel analysis, and channel reporting. |

---

## 💻 Open-Source GitHub Projects 🛠️

Sorted descending by GitHub star count:

- **[PostHog](https://github.com/PostHog/posthog)** [![GitHub stars](https://img.shields.io/github/stars/PostHog/posthog?style=social&color=white)](https://github.com/PostHog/posthog/stargazers)  
  🦔 Open-source product analytics, event-based multi-touch tracking, session recording, feature flags, and conversion funnel analysis platform built for self-hosting.

- **[Matomo](https://github.com/matomo-org/matomo)** [![GitHub stars](https://img.shields.io/github/stars/matomo-org/matomo?style=social&color=white)](https://github.com/matomo-org/matomo/stargazers)  
  🔒 Leading open-source web and digital marketing analytics platform with full data ownership, campaign tracking, multi-channel conversion attribution, and Google Analytics replacement capabilities.

- **[Snowplow](https://github.com/snowplow/snowplow)** [![GitHub stars](https://img.shields.io/github/stars/snowplow/snowplow?style=social&color=white)](https://github.com/snowplow/snowplow/stargazers)  
  ❄️ Enterprise-grade behavioral data pipeline that generates high-fidelity first-party customer event streams into Snowflake, BigQuery, and Databricks for custom multi-touch journey attribution.

- **[Jitsu](https://github.com/jitsucom/jitsu)** [![GitHub stars](https://img.shields.io/github/stars/jitsucom/jitsu?style=social&color=white)](https://github.com/jitsucom/jitsu/stargazers)  
  🔄 Open-source data ingestion engine and Segment alternative designed for streaming marketing touchpoints and clickstream data directly into analytical data warehouses.

- **[RudderStack Server](https://github.com/rudderlabs/rudder-server)** [![GitHub stars](https://img.shields.io/github/stars/rudderlabs/rudder-server?style=social&color=white)](https://github.com/rudderlabs/rudder-server/stargazers)  
  ⛵ Warehouse-native customer data platform (CDP) and event collection infrastructure for capturing marketing interactions across apps and routing to attribution databases.

- **[Open Web Analytics](https://github.com/Open-Web-Analytics/Open-Web-Analytics)** [![GitHub stars](https://img.shields.io/github/stars/Open-Web-Analytics/Open-Web-Analytics?style=social&color=white)](https://github.com/Open-Web-Analytics/Open-Web-Analytics/stargazers)  
  🌐 Open-source web analytics software framework (PHP/MySQL) providing visitor tracking, campaign referrals, e-commerce transaction tracking, and clickstream logging.

- **[Orbit](https://github.com/uber/orbit)** [![GitHub stars](https://img.shields.io/github/stars/uber/orbit?style=social&color=white)](https://github.com/uber/orbit/stargazers)  
  🪐 Uber's open-source Python package for Bayesian time series forecasting and marketing mix modeling, incorporating Bayesian Structural Time Series (BSTS) with additive priors.

- **[Google Meridian](https://github.com/google/meridian)** [![GitHub stars](https://img.shields.io/github/stars/google/meridian?style=social&color=white)](https://github.com/google/meridian/stargazers)  
  🧭 Google's Bayesian Marketing Mix Modeling (MMM) framework in Python; models media channel incrementality, reach and frequency, adstock, and saturation curves.

- **[Robyn (Meta)](https://github.com/facebookexperimental/Robyn)** [![GitHub stars](https://img.shields.io/github/stars/facebookexperimental/Robyn?style=social&color=white)](https://github.com/facebookexperimental/Robyn/stargazers)  
  🤖 Meta's experimental automated Marketing Mix Modeling (MMM) engine (R and Python); uses ridge regression with multi-objective hyperparameter evolutionary optimization (Nevergrad) for multi-channel calibration.

- **[PyMC-Marketing](https://github.com/pymc-labs/pymc-marketing)** [![GitHub stars](https://img.shields.io/github/stars/pymc-labs/pymc-marketing?style=social&color=white)](https://github.com/pymc-labs/pymc-marketing/stargazers)  
  🐍 Open-source Bayesian marketing measurement library in Python; unifies Bayesian Marketing Mix Modeling (MMM), Customer Lifetime Value (CLV) models, and experiment-informed calibration.

- **[LightweightMMM (Google)](https://github.com/google/lightweight_mmm)** [![GitHub stars](https://img.shields.io/github/stars/google/lightweight_mmm?style=social&color=white)](https://github.com/google/lightweight_mmm/stargazers)  
  📦 Google's lightweight Bayesian Marketing Mix Modeling library built on top of JAX and NumPyro (predecessor framework to Meridian for media spend optimization).

- **[DP6 Marketing Attribution Models](https://github.com/DP6/Marketing-Attribution-Models)** [![GitHub stars](https://img.shields.io/github/stars/DP6/Marketing-Attribution-Models?style=social&color=white)](https://github.com/DP6/Marketing-Attribution-Models/stargazers)  
  📐 Python library for digital marketing attribution; implements first-touch, last-touch, linear, position-based, time-decay, and Markov chain attribution algorithms.

- **[mta](https://github.com/eeghor/mta)** [![GitHub stars](https://img.shields.io/github/stars/eeghor/mta?style=social&color=white)](https://github.com/eeghor/mta/stargazers)  
  🎲 Python package for multi-touch attribution analysis in digital marketing; supports rule-based models, Markov chains (removal effects), Shapley values, and survival analysis models.

- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)** [![GitHub stars](https://img.shields.io/github/stars/trieu/leo-cdp-framework?style=social&color=white)](https://github.com/trieu/leo-cdp-framework/stargazers)  
  🦁 Open-source AI-first Customer Data Platform (CDP) with real-time Customer 360, ML-based segmentation, behavioral tracking, and omnichannel customer journey mapping.

- **[MultiTouch-Attribution-Marketing-Spend-Optimization](https://github.com/AjNavneet/MultiTouch-Attribution-Marketing-Spend-Optimization)** [![GitHub stars](https://img.shields.io/github/stars/AjNavneet/MultiTouch-Attribution-Marketing-Spend-Optimization?style=social&color=white)](https://github.com/AjNavneet/MultiTouch-Attribution-Marketing-Spend-Optimization/stargazers)  
  🎯 Multi-touch attribution and marketing spend optimization pipeline implementing Markov chains and Shapley values with constrained non-linear optimization for budget allocation.

- **[Attributor](https://github.com/Crynge/Attributor)** [![GitHub stars](https://img.shields.io/github/stars/Crynge/Attributor?style=social&color=white)](https://github.com/Crynge/Attributor/stargazers)  
  ⚙️ Go-based multi-touch attribution and media mix modeling engine; implements Shapley value attribution, Markov chain removal effects, Bayesian MMM fitting, and budget simulation CLI/API.

- **[Marketing Data Hub](https://github.com/Bhargava-R-dev/marketing-data-hub)** [![GitHub stars](https://img.shields.io/github/stars/Bhargava-R-dev/marketing-data-hub?style=social&color=white)](https://github.com/Bhargava-R-dev/marketing-data-hub/stargazers)  
  🦆 Unified local marketing data pipeline that pulls GA4, Google Search Console, Google Ads, and Meta Ads into DuckDB, with REST API, CSV exports, and Claude MCP server integration.

- **[pyattrscore](https://github.com/ucmani/pyattrscore)** [![GitHub stars](https://img.shields.io/github/stars/ucmani/pyattrscore?style=social&color=white)](https://github.com/ucmani/pyattrscore/stargazers)  
  ⚽ Python attribution modeling package covering heuristic models (first-touch, last-touch, linear, U-shaped, decay) and a novel role-based "football" attribution archetype model.

- **[Kafka Real-Time Attribution](https://github.com/mizcausevic-dev/kafka-real-time-attribution)** [![GitHub stars](https://img.shields.io/github/stars/mizcausevic-dev/kafka-real-time-attribution?style=social&color=white)](https://github.com/mizcausevic-dev/kafka-real-time-attribution/stargazers)  
  ⚡ Java and Kafka Streams-based real-time multi-touch attribution engine modeling click, session, and conversion events as an immutable ledgered stream for replay-safe credit assignment.

- **[causal-mmm-mta-platform](https://github.com/Crynge/causal-mmm-mta-platform)** [![GitHub stars](https://img.shields.io/github/stars/Crynge/causal-mmm-mta-platform?style=social&color=white)](https://github.com/Crynge/causal-mmm-mta-platform/stargazers)  
  🔬 Research platform and reference implementation combining Bayesian Marketing Mix Modeling (adstock, saturation), Multi-Touch Attribution, and causal graph discovery.

---

## 🤝 How to Contribute 💡

Contributions to make this ecosystem index comprehensive are welcome!

1. 🍴 **Fork the repo**.
2. ✍️ **Add or edit entries** in `README.md` adhering to the table or listed format.
3. 📝 **Include**: product/repo name, official link, star badge (for open-source), 1–2 sentence description, and pricing/scale details.
4. 🚀 **Submit PR** with a concise explanation.

---

## ⭐ Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Marketing-Analytics-Attribution&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Marketing-Analytics-Attribution&type=date&legend=top-left)

---

## 💖 Support & Community ☕

Thank you for visiting and supporting **Awesome Marketing Analytics & Attribution**! If you find this curated resource helpful for your work, research, or measurement stack, please consider supporting the project:

- ⭐ **Star this repository** on GitHub to help others discover it!
- 🍴 **Fork & Share** it with your fellow data scientists, marketing engineers, and growth marketers.
- 💬 Join the conversation on [Discord](https://discord.gg/jc4xtF58Ve) to discuss attribution challenges, MMM, and modern privacy architectures.
- ☕ **Buy me a coffee / Sponsor**: If you'd like to support ongoing curation and open-source contributions, visit the [GitHub Sponsors Dashboard](https://github.com/sponsors/ishandutta2007). Your support is deeply appreciated!

---

## ⚠️ Disclaimer 📜

- This repository is a **community-curated** list — not exhaustive and not a commercial endorsement.
- Marketing attribution platforms handling customer journey and conversion data must comply with applicable privacy regulations (GDPR, CCPA, ePrivacy) and user consent requirements.
- Multi-touch attribution outcomes depend heavily on data hygiene, identity resolution quality, and tracking compliance.
- Always verify licensing terms for commercial deployments (MIT, Apache 2.0, or proprietary).

---

<p align="center">
  <b>Built for marketing analysts, growth teams, and data scientists engineering modern measurement infrastructure. 🎯</b>
</p>
