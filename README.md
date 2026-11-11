# Awesome-Cloud-Security-Posture-Threat-Detection

# Top Cloud Security Posture & Threat Detection Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cloud-Native Application Protection (CNAPP), CSPM & Runtime Threat Detection*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Security Posture & Threat Detection**. These tools help security teams identify misconfigurations, detect runtime threats, and prioritize risk across multi-cloud and Kubernetes environments—covering agentless scanning, behavioral analytics, and compliance posture management.

**Examples** include Wiz, Orca Security, Palo Alto Prisma Cloud, Lacework (FortiCNAPP), CrowdStrike Falcon Cloud Security, Datadog Cloud Security, Sysdig Secure, SentinelOne, Aqua Security, and Zoho Directory (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted cloud security posture management, open-source CNAPP tooling, and community-driven threat detection—ideal for security engineers, platform teams, and organizations seeking transparent, vendor-neutral visibility without per-workload enterprise pricing.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Wiz](https://www.wiz.io/)** | Agentless CNAPP with graph-based risk prioritization, CSPM, CIEM, and DSPM. Pricing is workload-based or cloud-spend percentage; buyers with 500–2,000 workloads typically see mid-five to low-six-figure annual contracts . | Workload-based; negotiated rate ~$5–$8/workload/month at upper enterprise volume . Estimated ~$24K/yr for 100 workloads (list) . | No public free tier; trial via sales . Multi-year commitments commonly yield 20–35% discounts . |
| **[Orca Security](https://orca.security/)** | Agentless cloud security platform using SideScanning technology. Single all-inclusive SKU covering CNAPP, AppSec, and runtime (Orca Sensor); no feature tiers or add-ons . | Workload-based; estimated ~$20K/yr for 100 workloads (list) . AWS Marketplace private offer: $124,440/yr (Small-Medium tier) . | No public free tier; trial via sales . |
| **[Palo Alto Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)** | Comprehensive CNAPP with credit-based licensing. Credits consumed by resource type: hosts without containers (0.5), container hosts (5), hosts running applications (7), serverless (1 per 6 functions), and WAAS (2 per Defender) . | Credit-based; contracts often start higher than Wiz for similar workloads, though aggressive discounting (20–40%) is common for large enterprises . | No public free tier; trial via sales . |
| **[Lacework (FortiCNAPP)](https://www.lacework.com/)** | Behavioral ML-based CNAPP (Polygraph engine) now fully integrated into Fortinet Security Fabric. Strong for organizations already invested in FortiGate/FortiAnalyzer; pricing available standalone or bundled . | Estimated ~$15K/yr for 100 workloads (standalone); mid-market ARR typically $80K–$200K . | No public free tier; trial via Fortinet sales . |
| **[CrowdStrike Falcon Cloud Security](https://www.crowdstrike.com/)** | Cloud security modules within the Falcon platform. CSPM priced per resource (~$0.25/resource/month list, best achieved ~$0.15); Cloud Workload Protection ~$180/workload/year (best ~$108) . | CSPM: ~$0.25/resource/month; CWP: ~$180/workload/year  | No public free tier; trial via sales . |
| **[Datadog Cloud Security](https://www.datadoghq.com/)** | Cloud Security Management (CSM Pro) and Cloud Workload Security (CWS) integrated into Datadog's observability platform. CSM Pro ~$120/host/year; CWS ~$180/host/year . | CSM Pro: $120/host/year; CWS: $180/host/year; CSM Enterprise: $300/host/year . | No public free tier; trial available via Datadog . |
| **[Sysdig Secure](https://sysdig.com/)** | Cloud-native security with runtime threat detection, CSPM, and compliance. Strong Kubernetes depth; requires agent deployment. AWS Marketplace: $72/host/month with 20-host minimum . | $72/host/month (AWS Marketplace, 20-host minimum) . | No public free tier; trial via sales . |
| **[SentinelOne Cloud Workload Security](https://www.sentinelone.com/)** | Autonomous cloud workload protection extending endpoint detection to cloud compute, containers, and Kubernetes via Singularity platform . | ~$431.99/year per POD/task (100–500 license volume, CDW listing) . | No public free tier; trial via sales . |
| **[Aqua Security](https://www.aquasec.com/)** | CNAPP platform with workload-based pricing. Trivy OSS is free; enterprise CNAPP custom-priced . | Enterprise custom pricing; Trivy OSS free . | **Trivy OSS**: free open-source scanner; enterprise trial via sales . |
| **[Zoho Directory](https://www.zoho.com/directory/)** | Workforce IAM with conditional access, BYOK encryption, Cloud RADIUS for WiFi/VPN auth, and device authentication (Windows/Mac/Linux). Part of Zoho's integrated security stack (alongside Vault, OneAuth, Ulaa) . | Included with Zoho ecosystem; standalone pricing via Zoho sales . | No public free tier for Directory specifically; trial available via Zoho . |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Trivy](https://github.com/aquasecurity/trivy)** | [![Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers) | Comprehensive open-source security scanner for containers, Kubernetes, code repositories, and cloud environments. Detects vulnerabilities, misconfigurations, secrets, and licenses. The most widely adopted open-source CNAPP component; free forever (Apache 2.0) . |
| **[Prowler](https://github.com/prowler-cloud/prowler)** | [![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social&color=white)](https://github.com/prowler-cloud/prowler/stargazers) | Open-source cloud security posture management (CSPM) tool for AWS, Azure, GCP, and Kubernetes. 500+ checks mapped to CIS, PCI-DSS, HIPAA, and other frameworks. CLI and dashboard. |
| **[OpenRaven Magpie](https://github.com/openraven/magpie)** | [![Stars](https://img.shields.io/github/stars/openraven/magpie?style=social&color=white)](https://github.com/openraven/magpie/stargazers) | Cloud Security Posture Manager (CSPM) focused on modern cloud stack security, including cloud ransomware and supply chain attack detection. Java-based, Apache 2.0 licensed, ~188 stars . |
| **[Kube-bench](https://github.com/aquasecurity/kube-bench)** | [![Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=social&color=white)](https://github.com/aquasecurity/kube-bench/stargazers) | Checks Kubernetes clusters against CIS Kubernetes Benchmark. Lightweight Go binary; runs as Job or CLI. Foundational for Kubernetes security posture validation. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Kube-hunter](https://github.com/aquasecurity/kube-hunter)** | [![Stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=social&color=white)](https://github.com/aquasecurity/kube-hunter/stargazers) | Penetration testing tool for Kubernetes clusters. Discovers weaknesses and attack vectors from an attacker's perspective. |
| **[CloudSploit](https://github.com/aquasecurity/cloudsploit)** | [![Stars](https://img.shields.io/github/stars/aquasecurity/cloudsploit?style=social&color=white)](https://github.com/aquasecurity/cloudsploit/stargazers) | Open-source cloud security scanning for AWS, Azure, GCP, Oracle, and GitHub. Detects misconfigurations and compliance risks. |
| **[Falco](https://github.com/falcosecurity/falco)** | [![Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=social&color=white)](https://github.com/falcosecurity/falco/stargazers) | CNCF runtime security tool for Kubernetes and containers. Detects anomalous activity using eBPF and syscall monitoring. Complements posture tools with runtime threat detection. |

**Frameworks for building custom systems**: Combine **Trivy** for vulnerability and misconfiguration scanning, **Prowler** for multi-cloud CSPM checks, **Falco** for runtime threat detection, and **Kube-bench** for Kubernetes CIS compliance—creating a fully open-source CNAPP stack without per-workload licensing.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud security platforms require broad read access to cloud APIs and workload metadata; enforce least-privilege IAM roles and audit data access.
- Pricing models (per-workload, per-credit, per-host) vary dramatically and are highly negotiable at enterprise scale; model total cost against actual workload counts and negotiate multi-year discounts before committing. Open-source tools require ongoing tuning and integration effort to match commercial CNAPP coverage.

---

**Made for security engineers, cloud architects, SOC analysts, and organizations building cloud-native defense.**  
Let's make cloud security posture and threat detection more open, transparent, and cost-effective.
