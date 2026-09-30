# Awesome-Digital-Workspace-Management

# Top Digital Workspace Management Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Digital Employee Experience (DEX), EUC Monitoring, Endpoint Performance, VDI Analytics & Workspace Observability*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Digital Workspace Management**. These systems measure and improve how applications, devices, and virtual desktops perform for end users—proactively detecting issues across physical and virtual workspaces.

**Examples** include Nexthink, ControlUp, Lakeside SysTrack, Aternity, VMware/Omnissa Workspace ONE, Nerdio, Liquidware, Flexxible, and UberAgent (the category leaders).

**Open-source emphasis**: Full commercial DEX platforms dominate enterprises. Open options include **EUC monitoring scripts**, **osquery**, **Prometheus/Grafana** endpoint stacks, and general observability tools adapted for workspace health. This section lists every significant relevant project found.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[Nexthink](https://www.nexthink.com/)**  
  Leading digital employee experience platform—real-time endpoint analytics, sentiment, and automated remediation across the workspace.

- **[ControlUp, Lakeside SysTrack, Aternity, UberAgent](https://www.controlup.com/)**  
  EUC and DEX monitoring specialists for VDI, DaaS, and physical endpoints—performance, logon times, and application health.

- **[VMware / Omnissa Workspace ONE, Nerdio, Liquidware, Flexxible](https://www.omnissa.com/)**  
  Workspace management and EUC platforms combining UEM, VDI optimization, profile management, and analytics.

- **[Other commercial digital workspace platforms](https://www.nexthink.com/)**  
  Additional tools for digital experience scores, proactive support, and hybrid workforce visibility.

## Open-Source GitHub Projects

- **[EUCMonitoring](https://github.com/dbretty/EUCMonitoring)**  
  Community PowerShell-based End User Compute monitoring platform—high-level health dashboards for Citrix and expanding EUC stacks.

- **[osquery](https://github.com/osquery/osquery)**  
  Open SQL-powered endpoint instrumentation—query processes, network, and configuration across fleets for workspace visibility.

- **[Prometheus + node_exporter / Windows exporters](https://github.com/prometheus/node_exporter)**  
  Open metrics collection for CPU, memory, disk, and service health—foundation for DIY workspace observability with Grafana.

- **[Grafana](https://github.com/grafana/grafana)**  
  Open dashboarding widely used to visualize endpoint and VDI metrics from Prometheus, Loki, and custom EUC collectors.

- **[Zabbix / Checkmk open monitoring](https://github.com/zabbix/zabbix)**  
  Open infrastructure monitoring adaptable to user-session and endpoint performance tracking.

- **[LibreNMS & network/workspace adjacency tools](https://github.com/librenms/librenms)**  
  Open monitoring for connectivity issues that impact digital workspace experience.

- **[Custom logon / VDI timing scripts](https://github.com/search?q=Citrix+logon+time+OR+VDI+monitoring+PowerShell)**  
  Community scripts measuring logon duration, profile load, and session quality for Citrix, AVD, and Horizon.

- **[Fleet / osquery management](https://github.com/fleetdm/fleet)**  
  Open device management and osquery orchestration for continuous endpoint inventory and compliance signals.

### Additional Strong Open-Source Options

- **EUC overview**: EUCMonitoring for Citrix-centric health views.
- **Endpoint telemetry**: osquery + Fleet for fleet-wide queries.
- **Metrics stack**: Prometheus exporters → Grafana for performance dashboards.
- **Composable stacks**: osquery/Prometheus on endpoints → central Grafana + alertmanager → ticket integration.
- Commercial DEX platforms still lead in user sentiment, AI remediation, and cross-layer correlation (app + device + network).

**Frameworks for building custom systems**:  
**osquery** + **Prometheus/Grafana** for metrics; **EUCMonitoring** for EUC-specific views.  
Commercial platforms (Nexthink, ControlUp, SysTrack, Aternity, Workspace ONE, etc.) provide end-to-end DEX scores and automation.  
Homelab and cost-sensitive teams can assemble open observability; large enterprises typically need commercial DEX for scale and support. Fully open workspace experience management is partial—strong on metrics, weaker on unified UX analytics.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Endpoint monitoring collects device and sometimes user-activity data. Comply with privacy law, employee notice, and works-council requirements. Avoid invasive surveillance; focus on performance and reliability.
- Open-source stacks offer control but require integration and tuning. Commercial DEX platforms shift product depth and support to the vendor. Neither replaces good IT service management and application ownership.

---

**Made for EUC architects, desktop support leaders, and digital workplace teams.**  
Let's expand open workspace observability while recognizing the DEX depth and remediation that leading commercial platforms deliver.
