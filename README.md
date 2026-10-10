# Awesome-Application-Performance-Diagnostics

# Awesome-Application-Performance-Diagnostics 🔍 📊

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Application Performance Diagnostics Banner" width="100%">
</p>

<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Diagnostics"><img src="https://img.shields.io/github/stars/ishandutta2007/Awesome-Application-Performance-Diagnostics?style=social" alt="GitHub_Stars"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Diagnostics/fork"><img src="https://img.shields.io/github/forks/ishandutta2007/Awesome-Application-Performance-Diagnostics?style=social" alt="GitHub Forks"/></a>
  <a href="https://github.com/ishandutta2007/Awesome-Application-Performance-Diagnostics/blob/main/LICENSE"><img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Application-Performance-Diagnostics?color=blue" alt="License"/></a>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

---

## 🌟 Top Application Performance Diagnostics Ecosystem

**Curated List of Commercial APM Platforms & Open-Source Performance Diagnostics Tools**  
*Focused on Distributed Tracing, Profiling, Root Cause Analysis, Real User Monitoring, Error Tracking & Self-Hosted Observability*

**Last updated: October 2026** 📅

---

### 📌 Overview & SEO Summary
Welcome to the ultimate curated directory of **application performance diagnostics platforms**, **open-source APM tools**, and **distributed tracing frameworks**. Whether you are looking for enterprise-grade commercial solutions (such as *Datadog APM*, *Dynatrace*, and *New Relic*), or self-hostable open-source alternatives (like *SigNoz*, *Pixie*, and *Guider*), this list covers category leaders, profiling, and privacy-respecting performance diagnostics.

**Key Market Context:**
- **Salesforce Scale Center is now generally available for all major editions** including Enterprise and Professional, providing self-serve near real-time performance visibility with on-demand insights, Search Insights, and Lightning Experience Insights using Experienced Page Time (EPT) as the key metric [citation:3][citation:13].
- **SAP Cloud ALM Real User Monitoring** uses AI-driven change point detection to automatically determine which applications to monitor, detect significant and consistent performance shifts while ignoring single outliers, and translate complex technical metrics into user-friendly insights [citation:1].
- **Honeycomb** launched **Metrics and MCP integrations** in March 2026, positioning itself as the first observability platform purpose-built for AI agents, with Agent Skills for Claude Code and Cursor, Automated Investigations, and Slackbot with Chain of Thought logic [citation:5].
- **IBM Instana** provides automated discovery and monitoring at 1-second granularity across 300+ technologies, with AI capabilities including generative AI observability, AI gateway, AI evaluation, AI agent framework monitoring, and intelligent incident investigation [citation:6].
- **Coralogix** was named a **Leader in the 2026 Gartner Magic Quadrant for Observability Platforms**, processing petabytes of production data daily with its streaming-first architecture, Olly AI investigator, and MCP/CLI interfaces [citation:8][citation:18].
- **Sentry** connects errors, traces, logs, replays, and high-cardinality application metrics into workflows, with anomaly detection that surfaces latency spikes without manual threshold configuration [citation:7].

---

## 📑 Table of Contents
- [🏢 SaaS & Commercial Platforms](#-saas--commercial-platforms)
- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)
- [🛠️ How to Contribute](#%EF%B8%8F-how-to-contribute)
- [📊 Star History](#-star-history)
- [🤝 Support & Sponsorship](#-support--sponsorship)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🏢 SaaS / Commercial Platforms

The application performance diagnostics market spans **full-stack observability platforms** (Datadog, Dynatrace, New Relic) that bundle APM, tracing, logs, and metrics, **specialized diagnostics platforms** (Salesforce Scale Center, SAP Cloud ALM) that focus on platform-specific performance, and **AI-native observability platforms** (Honeycomb, Coralogix, Instana) that provide autonomous investigation and root cause analysis. **Salesforce Scale Center** is **free for all major editions** including Enterprise and Professional [citation:13]. **Datadog APM** charges **$31/host/month** for APM, with indexed spans at **$1.70/million after 5M included**. **Honeycomb** charges **$3.00 per million events** on Pro. **Sentry** offers a **generous free tier** with transparent, predictable pricing [citation:7].

| SaaS / Commercial Platform | Company / Owner | Valuation / Market Cap | Standard Edition Starting Price | Free Tier / Free Trial Limits | Description |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **[Salesforce Scale Center](https://help.salesforce.com/s/articleView?id=xcloud.scale_center_overview.htm&type=5)** ☁️ | Salesforce | ~$250 Billion | **Free for all major editions** [citation:13] | **Free: included with Salesforce subscription** | **Salesforce-native performance diagnostics** — **Near real-time org performance metrics, on-demand insights (3 per week per org), Search Insights, and Lightning Experience Insights with EPT** [citation:3][citation:13]. **Org Overview for monitoring org health and peak usage**. **Access via Setup > Scale Center** [citation:13]. |
| **[Datadog APM](https://www.datadoghq.com/product/apm/)** 🐶 | Datadog Inc. | ~$40 Billion | **$31/host/month** (APM) | **14-day free trial** | **Full-stack observability with APM** — **Distributed tracing, code profiling, and continuous profiler**. **Indexed spans: $1.70/million after 5M included** [citation:14]. **The most widely deployed commercial APM**. |
| **[Dynatrace](https://www.dynatrace.com/)** 🔮 | Dynatrace | ~$15 Billion | **$0.04/hour per host** | **15-day free trial** | **Causal AI for root cause** — **Davis AI combines topology graph with causal analysis**. **PurePath technology for code-level tracing without sampling**. **The most advanced causal AI diagnostics platform** [citation:14]. |
| **[New Relic](https://newrelic.com/)** 🚀 | New Relic Inc. | ~$5 Billion | **$99/user/month** (Standard) | **Free tier: 100 GB/month ingest** | **Consumption-based full-stack** — **Distributed tracing with Infinite Tracing** for tail-based sampling. **25+ language agents, 700+ integrations** [citation:14]. |
| **[Honeycomb](https://www.honeycomb.io/)** 🍯 | Honeycomb.io | Private | **$3.00/million events** (Pro) | **Free: up to 20M events/month** | **Event-based observability for AI agents** — **Honeycomb Metrics, Agent Skills for Claude Code/Cursor, Automated Investigations, Slackbot with Chain of Thought logic** [citation:5]. **BubbleUp analysis and high-cardinality debugging**. |
| **[Instana](https://www.ibm.com/products/instana)** ⚡ | IBM | ~$200 Billion | **Custom pricing** | **Free trial available** | **Automated APM** — **1-second monitoring granularity, automatic discovery, 300+ technologies** [citation:6]. **AI capabilities: generative AI observability, AI gateway, AI evaluation, AI agent framework monitoring, intelligent incident investigation** [citation:6]. |
| **[Sentry](https://sentry.io/)** 🎯 | Sentry | Private | **$26/month** (Team) | **Free Developer: 5K errors/month** | **Developer-first error tracking + APM** — **Errors, traces, logs, replays, and high-cardinality metrics connected in one workflow** [citation:7]. **Anomaly detection without manual threshold configuration** [citation:7]. |
| **[Coralogix](https://coralogix.com/)** 🔵 | Coralogix | Private | **Usage-based** from **$0.20/GB** | **Free tier: 1 GB/day** | **Leader in 2026 Gartner Magic Quadrant for Observability Platforms** [citation:8]. **Streaming-first architecture, Olly AI investigator, MCP/CLI interfaces** [citation:18]. **Processes petabytes of production data daily** [citation:8]. |
| **[Raygun](https://raygun.com/)** 🟠 | Raygun | Private | **Team plan required for Dashboards** [citation:9] | **Free trial available** | **Digital experience monitoring** — **Real-time insights into software performance and quality** [citation:19]. **Screen boards and time boards for visualizing error and performance data** [citation:9]. |
| **[SAP Cloud ALM](https://help.sap.com/docs/cloud-alm/applicationhelp/requests)** 🟢 | SAP | ~$200 Billion | **Custom enterprise pricing** | **Demo available** | **SAP-native ALM with Real User Monitoring** — **AI-driven change point detection, request analysis, exception analysis** [citation:1]. **Net time, database time, and correlation view for root cause analysis** [citation:11]. |

---

## 🔓 Open-Source GitHub Projects

*Sorted by GitHub_Stars_Count (Descending)* 🌟

- **[SigNoz](https://github.com/SigNoz/signoz)** [![Stars](https://img.shields.io/github/stars/SigNoz/signoz?style=social&color=white)](https://github.com/SigNoz/signoz/stargazers)  
  **Open-source Datadog alternative with OpenTelemetry-native APM**, Apache-2.0 licensed. **22K+ GitHub stars** — **unified logs, traces, and metrics** in a single pane. **ClickHouse-powered for high-cardinality data**. **Built-in dashboards, alerts, and exception tracking**. **Thoughtworks Technology Radar: Trial**. 📊

- **[Pixie](https://github.com/pixie-io/pixie)** [![Stars](https://img.shields.io/github/stars/pixie-io/pixie?style=social&color=white)](https://github.com/pixie-io/pixie/stargazers)  
  **Open-source observability tool for Kubernetes applications**, Apache-2.0 licensed. **CNCF Sandbox project** — **contributed by New Relic** [citation:20]. **Uses eBPF to automatically capture telemetry data without manual instrumentation**. **Deploy bpftrace programs to all nodes in your cluster** [citation:20]. **Dynamic Go logging without recompiling and redeploying** [citation:20]. **The most innovative open-source Kubernetes-native diagnostics platform**. 🔮

- **[Apache SkyWalking](https://github.com/apache/skywalking)** [![Stars](https://img.shields.io/github/stars/apache/skywalking?style=social&color=white)](https://github.com/apache/skywalking/stargazers)  
  **Observability platform for distributed systems**, Apache-2.0 licensed. **24K+ GitHub stars** — **APM, service mesh telemetry, eBPF profiling, and metrics aggregation**. **Designed for cloud-native, microservices, and containerized architectures**. **CNCF Graduated project**. 🌌

- **[Jaeger](https://github.com/jaegertracing/jaeger)** [![Stars](https://img.shields.io/github/stars/jaegertracing/jaeger?style=social&color=white)](https://github.com/jaegertracing/jaeger/stargazers)  
  **Distributed tracing platform by Uber**, Apache-2.0 licensed. **21K+ GitHub stars** — **end-to-end distributed tracing, root cause analysis, service dependency analysis**. **OpenTelemetry-native**. **CNCF Graduated project**. 🕵️

- **[OpenTelemetry](https://github.com/open-telemetry/opentelemetry-collector)** [![Stars](https://img.shields.io/github/stars/open-telemetry/opentelemetry-collector?style=social&color=white)](https://github.com/open-telemetry/opentelemetry-collector/stargazers)  
  **Vendor-neutral observability framework**, Apache-2.0 licensed. **The emerging standard for telemetry collection** — **100+ instrumentation libraries across languages**. **Supported natively by Datadog, New Relic, Dynatrace, Elastic, Splunk, Honeycomb, and Instana**. 🔭

- **[Grafana Tempo](https://github.com/grafana/tempo)** [![Stars](https://img.shields.io/github/stars/grafana/tempo?style=social&color=white)](https://github.com/grafana/tempo/stargazers)  
  **High-scale distributed tracing backend**, AGPL-3.0 licensed. **Cost-efficient trace storage that only requires object storage**. **TraceQL query language**. **Deep integration with Grafana, Loki, and Prometheus**. 📈

- **[Pinpoint](https://github.com/pinpoint-apm/pinpoint)** [![Stars](https://img.shields.io/github/stars/pinpoint-apm/pinpoint?style=social&color=white)](https://github.com/pinpoint-apm/pinpoint/stargazers)  
  **APM for large-scale distributed systems**, Apache-2.0 licensed. **13K+ GitHub stars** — **Java/PHP/Python agent-based monitoring**. **Call stack visualization, server map, and real-time active thread monitoring**. 📍

- **[Uptrace](https://github.com/uptrace/uptrace)** [![Stars](https://img.shields.io/github/stars/uptrace/uptrace?style=social&color=white)](https://github.com/uptrace/uptrace/stargazers)  
  **Open-source APM with OpenTelemetry**, BSD-2-Clause licensed. **Distributed tracing, metrics, and logs in a unified platform**. **ClickHouse-based** — **processes billions of spans on a single server at 10x lower cost**. 📉

- **[Guider](https://github.com/iipeace/guider)** [![Stars](https://img.shields.io/github/stars/iipeace/guider?style=social&color=white)](https://github.com/iipeace/guider/stargazers)  
  **Unified performance analyzer for Linux and Android**, open-source. **10 years of development (2015–2025)** [citation:10]. **Provides precise measurements in counts, execution time (μs), and data size (bytes)** [citation:10]. **Monitoring, profiling, tracing, control, logging, visualization (line graph, flame graph, histogram), testing, and utilities** [citation:10]. **Continuous monitoring with configurable thresholds and automated event management** [citation:10]. **The most comprehensive open-source Linux/Android performance diagnostics tool**. 🐧

- **[Coroot](https://github.com/coroot/coroot)** [![Stars](https://img.shields.io/github/stars/coroot/coroot?style=social&color=white)](https://github.com/coroot/coroot/stargazers)  
  **Open-source observability with zero instrumentation**, Apache-2.0 licensed. **eBPF-based metrics, logs, traces, profiles, and continuous profiling**. **Automatically detects anomalies and root causes**. 🎯

- **[Hypertrace](https://github.com/hypertrace/hypertrace)** [![Stars](https://img.shields.io/github/stars/hypertrace/hypertrace?style=social&color=white)](https://github.com/hypertrace/hypertrace/stargazers)  
  **Observability platform for cloud-native apps**, Apache-2.0 licensed. **Distributed tracing, service graph, and trace-to-log correlation**. **Built on OpenTelemetry and Jaeger**. 🔗

- **[OpenObserve](https://github.com/openobserve/openobserve)** [![Stars](https://img.shields.io/github/stars/openobserve/openobserve?style=social&color=white)](https://github.com/openobserve/openobserve/stargazers)  
  **Cloud-native observability platform**, Apache-2.0 licensed. **Logs, metrics, traces, and RUM in one platform**. **140x lower storage costs than Elasticsearch**. **Rust-based, single binary**. 🌊

---

## 🛠️ How to Contribute

Contributions are welcome! Follow these steps to submit new performance diagnostics platforms or open-source APM software:

1. 🍴 **Fork** the repository.
2. 📝 **Add/edit** entries in `README.md` maintaining table/list structure and formatting.
3. 🔗 Include project title, official website/GitHub link, exact Stars_Count, license, and brief description.
4. 🚀 Submit a **Pull Request** with a descriptive summary of your changes.

---

## 📊 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Application-Performance-Diagnostics&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Application-Performance-Diagnostics&type=date&legend=top-left)

---

## 🤝 Support & Sponsorship

If you find this application performance diagnostics repository useful, please consider supporting the project:

- ⭐ **Star** this repository to increase visibility!
- 🔀 **Fork** and share with fellow SREs, platform engineers, and open-source advocates.
- ☕ **Sponsor & Buy Me a Coffee**: Support ongoing open-source curation via the [GitHub Sponsor Dashboard](https://github.com/sponsors/ishandutta2007).

---

## ⚠️ Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement. ℹ️
- **Salesforce Scale Center is now GA for all major editions** — **on-demand insights are limited to 3 per week per org** [citation:3]. **SAP Cloud ALM change point detection uses unsupervised online ML models** that qualify only "consistent" and "durable" changes as alerts [citation:1].
- **AI-native observability is the defining trend** — **Honeycomb is purpose-built for AI agents with MCP integrations** [citation:5]. **Coralogix was named a Leader in the 2026 Gartner Magic Quadrant for Observability Platforms** [citation:8]. **Instana provides 1-second granularity across 300+ technologies** [citation:6].
- **Open-source APM tools are not turnkey** — **SigNoz requires ClickHouse and Docker** . **Pixie requires Kubernetes and eBPF support** . **Guider requires Linux kernel access** [citation:10]. **Always validate trace collection, profiling accuracy, and anomaly detection with a proof-of-concept** before production deployment. 🔍

---

<p align="center">
  <b>Made with ❤️ for SREs, platform engineers, and open-source performance diagnostics advocates.</b>
</p>
