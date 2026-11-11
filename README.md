# Awesome-Cloud-Security-Posture-Threat-Detection

## Top Cloud Security Posture & Threat Detection Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Cloud-Native Application Protection (CNAPP), CSPM & Runtime Threat Detection*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Security Posture & Threat Detection**. These tools help security teams identify misconfigurations, detect runtime threats, and prioritize risk across multi-cloud and Kubernetes environments—covering agentless scanning, behavioral analytics, and compliance posture management.

**Examples** include Wiz, Orca Security, Palo Alto Prisma Cloud, Lacework (FortiCNAPP), CrowdStrike Falcon Cloud Security, Datadog Cloud Security, Sysdig Secure, SentinelOne, Aqua Security, and Zoho Directory.

**Open-source emphasis**: This section highlights active projects for self-hosted cloud security posture management, open-source CNAPP tooling, and community-driven threat detection—ideal for security engineers, platform teams, and organizations seeking transparent, vendor-neutral visibility without per-workload enterprise pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [Sector Overview & Market Dynamics](#sector-overview--market-dynamics)
- [SaaS/Hosted Platforms](#saashosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

---

## Sector Overview & Market Dynamics

The global Cloud-Native Application Protection Platform (CNAPP) and cloud security posture market is estimated at **$10.5B–$13.8B in 2025** and projected to reach **$12.6B–$17.8B in 2026** (~20–22% CAGR), scaling past $50B by the early 2030s.

While the wider security ecosystem remains moderately fragmented with specialized point tools (CSPM, CWPP, CIEM, IaC scanning), enterprise procurement is undergoing rapid consolidation into an oligopolistic, "winner-take-most" platform dynamic dominated by end-to-end code-to-cloud security suites (such as Wiz, Palo Alto Networks, Datadog, and CrowdStrike).

---

## SaaS/Hosted Platforms

| Product | Company Size (Valuation / Market Cap / Revenue) | Pricing (Starting Tier) | Free Tier Limits / Free Trial | Description |
|---------|-------------------------------------------------|-------------------------|--------------------------------|-------------|
| **[Palo Alto Prisma Cloud](https://www.paloaltonetworks.com/prisma/cloud)** | ~$280B–$320B Market Cap (FY26 revenue ~$11.5B) | Starts at ~$18,000/yr (baseline 100 Prisma Cloud Credits at ~$180/credit/yr for CSPM) | 30-day free trial (full evaluation access across multi-cloud environments via sales/marketplace) | Comprehensive CNAPP platform with credit-based licensing across CSPM, CWPP, CIEM, DSPM, and WAAS. |
| **[CrowdStrike Falcon Cloud Security](https://www.crowdstrike.com/)** | ~$220B–$260B Market Cap (FY26 revenue ~$4.8B) | Starts at $0.25/resource/month ($3/resource/yr) for CSPM; $180/workload/yr for Cloud Workload Protection | 15-day free trial (plus a 30-day interactive virtual Falcon Test Drive environment) | Unified cloud workload and container protection extending Falcon EDR to cloud compute and posture. |
| **[Fortinet (FortiCNAPP / Lacework)](https://www.lacework.com/)** | ~$90B–$105B Market Cap (Acquired Lacework for $152.3M) | Starts at ~$15,000/yr (entry standalone tier for up to 100 workloads) | 14-day free trial (full feature access for cloud accounts and container workload analysis) | Behavioral ML-driven CNAPP (Polygraph anomaly detection engine) integrated into Fortinet Security Fabric. |
| **[Datadog Cloud Security](https://www.datadoghq.com/)** | ~$65B–$75B Market Cap (FY26 revenue ~$4.2B TTM) | Starts at $120/host/year ($10/host/month) for Cloud Security Management (CSM Pro); $180/host/year for Cloud Workload Security (CWS) | 14-day free trial (includes full access to host security, posture management, and compliance checks) | Cloud Security Management and runtime detection fully unified within Datadog's observability platform. |
| **[Wiz](https://www.wiz.io/)** | $32B Valuation / Acquisition (Google Cloud; >$1B ARR) | Starts at ~$24,000/yr (entry tier for up to 100 workloads; ~$5–$8/workload/month at enterprise volume) | 14-day free trial (full evaluation access; standard POCs up to 21 days with cloud environment scan) | Agentless CNAPP with graph-based risk correlation, CSPM, CIEM, DSPM, and vulnerability prioritization. |
| **[Zoho Directory](https://www.zoho.com/directory/)** | ~$12.5B Valuation (Bootstrapped, revenue >$1.5B) | Starts at $2.00/user/month (Standard plan, $1.70/user/month billed annually) | Forever Free plan: up to 10 users, 3 third-party cloud apps, 2 directory stores, and 10 devices (45-day free trial for paid tiers) | Workforce IAM and security posture management featuring conditional access, BYOK encryption, and Cloud RADIUS. |
| **[SentinelOne Cloud Workload Security](https://www.sentinelone.com/)** | ~$7.5B–$8.5B Market Cap (FY26 revenue ~$1.0B) | Starts at $431.99/year per POD/task (100–500 volume licensing on CDW/AWS Marketplace) | 14-day to 30-day free trial / Proof of Concept (POC) via enterprise sales and authorized partners | Autonomous runtime cloud protection and behavioral threat detection for compute, containers, and K8s. |
| **[Sysdig Secure](https://sysdig.com/)** | ~$2.5B Valuation (Permira-backed unicorn) | Starts at $72/host/month on AWS Marketplace (with 20-host minimum commitment = $1,440/month) | 30-day free trial (unrestricted access to cloud monitoring, posture compliance, and container runtime security) | Cloud-native security built on eBPF and Falco, providing deep runtime threat detection, CSPM, and K8s compliance. |
| **[Orca Security](https://orca.security/)** | ~$1.8B Valuation (Alphabet/CapitalG backed) | Starts at ~$20,000/yr (entry tier for up to 100 workloads; AWS Marketplace private offers ~$124K/yr) | 30-day free trial / assessment (full SideScanning of AWS, Azure, or GCP accounts with 100% asset discovery) | Agentless cloud security platform using SideScanning technology across CNAPP, AppSec, DSPM, and runtime. |
| **[Aqua Security](https://www.aquasec.com/)** | ~$1.0B Valuation (Series E unicorn) | Starts at ~$10,188/year (Team annual tier; Advanced tier starts at ~$25,188/year) | Trivy OSS is 100% free forever; enterprise CNAPP offers customized 14-to-30 day POC trial via sales | Full lifecycle code-to-cloud CNAPP securing supply chains, cloud infrastructure posture, and container runtimes. |

---

## Open-Source GitHub Projects

Curated open-source cloud security, posture management, runtime detection, and infrastructure compliance projects, sorted by GitHub stargazers count:

| Project | Stars | Description |
|---------|-------|-------------|
| **[Trivy](https://github.com/aquasecurity/trivy)** | [![Trivy Stars](https://img.shields.io/github/stars/aquasecurity/trivy?style=social&color=white)](https://github.com/aquasecurity/trivy/stargazers) | Comprehensive open-source vulnerability, secret, misconfiguration, and SBOM scanner for containers, Kubernetes, code, and cloud environments (Apache 2.0). |
| **[Prowler](https://github.com/prowler-cloud/prowler)** | [![Prowler Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social&color=white)](https://github.com/prowler-cloud/prowler/stargazers) | Open-source cloud security posture management (CSPM) and compliance tool for AWS, Azure, GCP, and Kubernetes. Features 500+ security checks mapped to CIS, PCI-DSS, and HIPAA (Apache 2.0). |
| **[Falco](https://github.com/falcosecurity/falco)** | [![Falco Stars](https://img.shields.io/github/stars/falcosecurity/falco?style=social&color=white)](https://github.com/falcosecurity/falco/stargazers) | CNCF graduated runtime security and threat detection engine for Kubernetes and Linux containers using kernel-level eBPF syscall telemetry (Apache 2.0). |
| **[Checkov](https://github.com/bridgecrewio/checkov)** | [![Checkov Stars](https://img.shields.io/github/stars/bridgecrewio/checkov?style=social&color=white)](https://github.com/bridgecrewio/checkov/stargazers) | Static code analysis tool for Infrastructure as Code (IaC) supporting Terraform, CloudFormation, Kubernetes, ARM, and Dockerfile misconfiguration scanning (Apache 2.0). |
| **[Kube-bench](https://github.com/aquasecurity/kube-bench)** | [![Kube-bench Stars](https://img.shields.io/github/stars/aquasecurity/kube-bench?style=social&color=white)](https://github.com/aquasecurity/kube-bench/stargazers) | Validates Kubernetes cluster security posture against the official CIS Kubernetes Benchmark. Runs as a lightweight Go binary, container, or K8s job (Apache 2.0). |
| **[tfsec](https://github.com/aquasecurity/tfsec)** | [![tfsec Stars](https://img.shields.io/github/stars/aquasecurity/tfsec?style=social&color=white)](https://github.com/aquasecurity/tfsec/stargazers) | Security scanner for Terraform code that spots cloud misconfigurations and compliance violations prior to infrastructure provisioning (MIT). |
| **[Cloud Custodian](https://github.com/cloud-custodian/cloud-custodian)** | [![Cloud Custodian Stars](https://img.shields.io/github/stars/cloud-custodian/cloud-custodian?style=social&color=white)](https://github.com/cloud-custodian/cloud-custodian/stargazers) | CNCF rules engine for multi-cloud governance, security compliance posture, real-time remediation, and cost optimization using YAML DSL (Apache 2.0). |
| **[ThreatMapper](https://github.com/deepfence/ThreatMapper)** | [![ThreatMapper Stars](https://img.shields.io/github/stars/deepfence/ThreatMapper?style=social&color=white)](https://github.com/deepfence/ThreatMapper/stargazers) | Open-source CNAPP and cloud security observability platform that hunts for vulnerabilities, malware, secrets, and cloud misconfigurations across multi-cloud (Apache 2.0). |
| **[Terrascan](https://github.com/tenable/terrascan)** | [![Terrascan Stars](https://img.shields.io/github/stars/tenable/terrascan?style=social&color=white)](https://github.com/tenable/terrascan/stargazers) | Static code analyzer for Infrastructure as Code with 500+ out-of-the-box policies checking for security weaknesses and compliance standards (Apache 2.0). |
| **[Tetragon](https://github.com/cilium/tetragon)** | [![Tetragon Stars](https://img.shields.io/github/stars/cilium/tetragon?style=social&color=white)](https://github.com/cilium/tetragon/stargazers) | eBPF-based real-time security observability and runtime enforcement platform from Cilium capable of process filtering and network-level blocking (Apache 2.0). |
| **[Kube-hunter](https://github.com/aquasecurity/kube-hunter)** | [![Kube-hunter Stars](https://img.shields.io/github/stars/aquasecurity/kube-hunter?style=social&color=white)](https://github.com/aquasecurity/kube-hunter/stargazers) | Penetration testing and automated reconnaissance tool that hunts for security weaknesses in active Kubernetes clusters from an attacker's vantage point (Apache 2.0). |
| **[Tracee](https://github.com/aquasecurity/tracee)** | [![Tracee Stars](https://img.shields.io/github/stars/aquasecurity/tracee?style=social&color=white)](https://github.com/aquasecurity/tracee/stargazers) | Lightweight runtime security and threat detection engine utilizing Linux eBPF technology to trace system calls and detect anomalous behavior (Apache 2.0). |
| **[CloudSploit](https://github.com/aquasecurity/cloudsploit)** | [![CloudSploit Stars](https://img.shields.io/github/stars/aquasecurity/cloudsploit?style=social&color=white)](https://github.com/aquasecurity/cloudsploit/stargazers) | Open-source automated cloud security posture scanner detecting misconfigurations and security risks across AWS, Azure, GCP, and Oracle Cloud (BSD-3-Clause). |
| **[BotKube](https://github.com/kubeshop/botkube)** | [![BotKube Stars](https://img.shields.io/github/stars/kubeshop/botkube?style=social&color=white)](https://github.com/kubeshop/botkube/stargazers) | ChatOps and messaging integration tool monitoring Kubernetes cluster events and security anomalies via Slack, Teams, and Discord (MIT). |
| **[PacketStreamer](https://github.com/deepfence/PacketStreamer)** | [![PacketStreamer Stars](https://img.shields.io/github/stars/deepfence/PacketStreamer?style=social&color=white)](https://github.com/deepfence/PacketStreamer/stargazers) | High-performance distributed network packet capture and streaming sensor for runtime cloud threat detection and forensic investigation (Apache 2.0). |
| **[OpenRaven Magpie](https://github.com/openraven/magpie)** | [![Magpie Stars](https://img.shields.io/github/stars/openraven/magpie?style=social&color=white)](https://github.com/openraven/magpie/stargazers) | Cloud Security Posture Manager (CSPM) framework focused on multi-cloud asset discovery and discovery of cloud ransomware/supply-chain attack vectors (Apache 2.0). |

**Building a custom open-source CNAPP stack**: Combine **Trivy** or **Checkov** for IaC/vulnerability scanning, **Prowler** or **Cloud Custodian** for multi-cloud CSPM governance, **Falco** or **Tetragon** for eBPF runtime threat detection, and **Kube-bench** for Kubernetes CIS compliance.

---

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Cloud security platforms require broad read access to cloud APIs and workload metadata; enforce least-privilege IAM roles and audit data access.
- Pricing models (per-workload, per-credit, per-host) vary dramatically and are negotiable at enterprise scale; model total cost against actual workload counts before committing.

---

**Made for security engineers, cloud architects, SOC analysts, and organizations building cloud-native defense.**  
Let's make cloud security posture and threat detection more open, transparent, and cost-effective.
