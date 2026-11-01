# Awesome-Marketing-Analytics-Attribution

## Top Marketing Analytics & Attribution Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Multi-Touch Attribution, Marketing Mix Modeling & Self-Hosted Measurement Infrastructure*  

**Last updated: November 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Marketing Analytics & Attribution**. These tools enable marketing teams to measure channel performance, understand customer journeys, and allocate budget based on evidence—turning the "which half of my advertising is wasted" question into a data-backed answer.



**Examples** include HubSpot Analytics and Attribution, Google Analytics, Adobe Analytics, Dreamdata, Bizible, Triple Whale, Rockerbox, Mixpanel, Amplitude, and Attribution App (the category leaders).



**Open-source emphasis**: Marketing Analytics & Attribution is a domain where open-source tooling is **genuinely emerging but remains fragmented across distinct measurement philosophies**. The strongest active projects are **Attributor** (a Go-based multi-touch attribution engine implementing Shapley values, Markov chains, and Bayesian MMM with budget simulation) , **pyattrscore** (a Python package covering first-touch, last-touch, linear, U-shaped, exponential decay, and a novel "football" attribution model) , and **mta-audit** (a reproducibility-focused audit package that scores attribution reliability across model disagreement and data quality dimensions) . For marketing mix modeling specifically, **Google's Meridian** is now open-source, using Bayesian causal inference to measure incremental impact across channels . The critical caveat: **no open-source project matches the turnkey, warehouse-native attribution** of Dreamdata or Bizible—those platforms handle identity resolution, CRM stitching, and multi-touch journey assembly out of the box, while open-source requires assembling an event pipeline, identity graph, and attribution model separately.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[HubSpot Analytics and Attribution](https://www.hubspot.com/)**  

  Native analytics and attribution within HubSpot's CRM; connects marketing touchpoints to contact records and deals for multi-touch revenue attribution.



- **[Google Analytics](https://analytics.google.com/)**  

  Web and app analytics with data-driven attribution models, funnel exploration, and integration with Google Ads for cross-channel measurement.



- **[Adobe Analytics](https://business.adobe.com/)**  

  Enterprise analytics with advanced attribution modeling, Marketing Channels, and integration across Adobe Experience Cloud.



- **[Dreamdata](https://dreamdata.io/)**  

  B2B revenue attribution platform; connects marketing, sales, and CRM data to build multi-touch attribution models across the full go-to-market motion.



- **[Bizible (Adobe)](https://business.adobe.com/)**  

  B2B marketing attribution platform (acquired by Marketo/Adobe); tracks multi-touch attribution from first touch through closed-won revenue.



- **[Triple Whale](https://www.triplewhale.com/)**  

  E-commerce analytics platform with first-party attribution, blended ROAS, and AI-powered insights for DTC brands.



- **[Rockerbox](https://www.rockerbox.com/)**  

  Marketing attribution platform for omnichannel brands; provides multi-touch attribution, marketing mix modeling, and incrementality testing.



- **[Mixpanel](https://mixpanel.com/)**  

  Product analytics with attribution capabilities; tracks user journeys and channel impact on conversion events.



- **[Amplitude](https://amplitude.com/)**  

  Product analytics with attribution and journey analysis; connects marketing touchpoints to product behavior and retention.



- **[Attribution App](https://attributionapp.com/)**  

  Marketing attribution platform for ecommerce and SaaS; provides multi-touch attribution, funnel analysis, and channel reporting.



## Open-Source GitHub Projects



### Multi-Touch Attribution Engines



- **[Attributor](https://github.com/Crynge/Attributor)**  

  The **most complete open-source multi-touch attribution engine** available (Go) . Implements **Shapley value attribution** (marginal contribution across all channel combinations, satisfying symmetry, linearity, and efficiency), **Markov chain attribution** (removal effect—measure the drop in conversion probability when a channel is removed), and **Bayesian media mix modeling** with adstock transformations, saturation curves (Hill functions), and 90% credible intervals. Features a **budget simulation** CLI for reallocating spend to maximize ROAS, plus a REST API for Shapley/Markov attribution and MMM fitting. **Best for data teams wanting rigorous, reproducible attribution** with budget optimization—but it is a modeling engine requiring journey data input, not a turnkey platform with event collection.



- **[pyattrscore](https://pypi.org/project/pyattrscore/)**  

  A **comprehensive Python attribution modeling package** covering the standard models (first-touch, last-touch, linear, U-shaped, exponential decay, time-decay) plus a novel **"football" attribution model** that classifies channels into archetypes (Generator, Assister, Closer, Participant) and computes a Channel Impact Score combining baseline credit with weighted role contributions . Supports YAML configuration, attribution windows, and model comparison. **Best for Python data scientists** wanting a flexible, well-documented attribution library—but it is a library, not an end-to-end platform.



- **[mta-audit](https://pypi.org/project/mta-audit/)**  

  A **reproducibility and reliability audit package** for multi-touch attribution . Runs checks across data quality, conversion window sensitivity, model disagreement (first-touch vs. last-touch vs. linear vs. Markov), path sparsity, and temporal stability—emitting a **0–100 audit robustness score** with qualitative bands (Robust to Highly Fragile). Includes bootstrap resampling and identity-loss simulations to test how sensitive attribution conclusions are to real-world data corruption. **Best for teams wanting to validate attribution before trusting it**—the most honest open-source tool for attribution quality assessment.



### Marketing Mix Modeling (MMM)



- **[Google Meridian](https://github.com/google/meridian)**  

  Google's **open-source Marketing Mix Model** (Python) using **Bayesian causal inference** to blend prior knowledge with real-world data for measuring incremental impact across channels . Includes access to Google's MMM Data Platform for core metrics (impressions, clicks), customizable model parameters, and video effectiveness measurement via reach and frequency. **Best for organizations wanting Google-grade MMM** without building from scratch—but it is a modeling framework, not a data pipeline or dashboard.



- **[causal-mmm-mta-platform](https://github.com/Crynge/causal-mmm-mta-platform)**  

  A **unified marketing measurement research platform** combining Bayesian MMM (adstock, saturation, seasonality), MTA (Markov, Shapley), and causal graph discovery . **Honest scope disclosure**: the repo ships **core modeling modules and reference implementations**, not the fully operational ingestion/dashboard/API surfaces described in older READMEs. **Best for researchers and data scientists** wanting a starting point for custom measurement pipelines—not a production platform.



### Real-Time & Streaming Attribution



- **[Kafka Real-Time Attribution](https://github.com/mizcausevic-dev/kafka-real-time-attribution)**  

  A **Java/Kafka Streams-based real-time multi-touch attribution engine** for SaaS growth teams . Models click, session, and conversion events as a ledgered stream for replay-safe credit assignment; includes a local no-Kafka demo mode and a Redpanda docker-compose stack. **Best for engineering teams** wanting real-time attribution with event ordering guarantees—but it is a technical implementation, not a marketing user-facing tool.



### Data Pipelines for Marketing Analytics



- **[Marketing Data Hub](https://pypi.org/project/marketing-data-hub/)**  

  An open-source **Windsor.ai alternative** that pulls Google Analytics 4, Search Console, Google Ads, Meta Ads, and YouTube into a **local database**—queryable via REST API, scheduled CSV exports, and AI assistants like Claude via MCP . **All data stays on your machine**; tokens never leave your computer. **Best for marketers and analysts** wanting to own their marketing data pipeline without a subscription—but it is a data hub, not an attribution engine.



- **[LEO CDP](https://github.com/trieu/leo-cdp-framework)**  

  An open-source **AI-first Customer Data Platform** with omnichannel data collection, real-time Customer 360, ML-based segmentation (RFM, CLV, churn prediction), behavioral tracking, and **journey mapping** . **Best for organizations wanting a self-hosted CDP foundation** to feed attribution models—but it is a CDP, not an attribution tool itself.



### Additional Strong Open-Source Options



- **DP6 Marketing Attribution Models** — A Python class library for digital marketing attribution (323 GitHub stars); provides standard attribution model implementations for practitioners . **Best for quick Python attribution scripting**—lighter than pyattrscore but less feature-complete.

- **Open Web Analytics** — Open-source web analytics platform (PHP) with visitor tracking, e-commerce transactions, heatmaps, and session recordings; a self-hosted GA alternative for first-party data collection . **Best for owning the data collection layer** that feeds attribution—but it is web analytics, not multi-touch attribution.



**Frameworks for building custom systems**: For **rigorous multi-touch attribution with Shapley and Markov models**, Attributor provides the most complete engine . For **Python flexibility across standard models**, pyattrscore . For **auditing attribution reliability before trusting it**, mta-audit . For **marketing mix modeling**, Google Meridian . For **real-time streaming attribution**, Kafka Real-Time Attribution . **No open-source project matches the turnkey, CRM-stitched attribution** of Dreamdata or Bizible—those handle identity resolution and journey assembly out of the box, while open-source requires assembling the pipeline yourself.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Marketing attribution platforms handling customer journey and conversion data must comply with applicable privacy regulations (GDPR, CCPA) and consent requirements; **attribution results depend heavily on data quality and identity resolution**—mta-audit explicitly scores reliability and warns that results are not causal confidence intervals .

- **Open-source marketing attribution is emerging but fundamentally fragmented**—Attributor and pyattrscore provide modeling engines , and Google Meridian provides MMM , but **no open-source project matches the turnkey, warehouse-native attribution** of Dreamdata or Bizible. Open-source requires assembling event collection, identity resolution, and journey stitching separately. Choose based on whether you need a modeling engine (Attributor), a library (pyattrscore), an audit tool (mta-audit), or MMM (Meridian).

- Verify license terms for commercial use; Attributor is open-source (check repository) , pyattrscore is a PyPI package , and Google Meridian is open-source .



---



**Made for marketing analysts, growth teams, and data scientists building measurement infrastructure.**  

Let's make marketing attribution more open, but with clear eyes about the identity resolution and journey-stitching gaps that turnkey platforms still fill.
