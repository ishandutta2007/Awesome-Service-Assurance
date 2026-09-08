# Awesome-Service-Assurance

## Top Service Assurance Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Telecom & Network Service Assurance, Fault Management, Performance Management, QoS/QoE, Root-Cause Analysis & OSS Monitoring*  

**Last updated: September 2026**



This repository tracks notable **SaaS/commercial platforms** and **open-source projects** for **Service Assurance**. These systems help communications service providers and network operators monitor service health, detect faults, measure performance, assure SLAs, and improve customer experience across fixed, mobile, and multi-vendor networks.



**Examples** include Amdocs Service Assurance, Nokia Service Assurance, Ericsson Expert Analytics, Netcracker Assurance, Viavi, Accedian, Infovista, EXFO, Spirent, and Subex (the category leaders).



**Open-source emphasis**: Full commercial-grade service assurance suites are largely proprietary. However, strong open-source OSS and network monitoring platforms exist. **NOC Project**, **OpenNMS**, **Boda Telecom Suite**, and related tools provide fault, performance, inventory, and discovery capabilities that can form the backbone of custom assurance solutions. This section lists every major active project found.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Amdocs Service Assurance](https://www.amdocs.com/)**  

  Comprehensive service assurance portfolio covering fault, performance, quality of experience, and automated assurance for large-scale telecom operators.



- **[Nokia Service Assurance](https://www.nokia.com/)**  

  End-to-end assurance solutions integrated with Nokia’s broader network and OSS portfolio, including AI-assisted analytics and multi-domain monitoring.



- **[Ericsson Expert Analytics / Service Assurance](https://www.ericsson.com/)**  

  Analytics-driven assurance and customer experience solutions leveraging Ericsson’s network expertise and AI capabilities.



- **[Netcracker Assurance](https://www.netcracker.com/)**  

  Digital OSS/BSS-aligned service assurance platform supporting modern, cloud-native, and multi-vendor network environments.



- **[Viavi Solutions](https://www.viavisolutions.com/)**  

  Test, measurement, and assurance portfolio widely used for network performance, 5G, fiber, and service quality monitoring.



- **[Accedian](https://www.accedian.com/)**  

  Performance assurance and visibility platform focused on end-to-end service quality, latency, and experience metrics.



- **[Infovista](https://www.infovista.com/)**  

  Network and service assurance solutions covering planning, optimization, performance management, and customer experience.



- **[EXFO](https://www.exfo.com/)**  

  Test, monitoring, and analytics platform for service providers, with strong capabilities in fiber, 5G, and service quality assurance.



- **[Spirent, Subex](https://www.spirent.com/)**  

  Additional vendors offering service assurance, fraud management, network testing, and analytics solutions used in telecom environments.



- **[Other assurance & OSS platforms](https://www.amdocs.com/)**  

  Solutions from NETSCOUT, Huawei, IBM, Mycom OSI, and related providers that deliver overlapping fault, performance, and experience assurance capabilities.



## Open-Source GitHub Projects



- **[NOC Project](https://github.com/gufolabs/noc)**  

  Full-featured open-source Operation Support System (OSS) for telecom and enterprise NOCs. Includes Fault Management, Performance Management, Inventory, Discovery, topology correlation, and multi-vendor support.



- **[OpenNMS](https://github.com/OpenNMS/opennms)**  

  Enterprise-grade open-source network management platform providing fault, performance, and traffic monitoring, alarm generation, inventory, and extensive protocol support.



- **[Boda Telecom Suite (BTS-CE)](https://github.com/bodastage/bts-ce)**  

  Open-source, vendor- and technology-agnostic telecommunication network management platform focused on configuration management, topology, RAN audit, and reporting.



- **[NMS Prime / CableLabs OS Provisioning](https://github.com/cablelabs/os-provisioning)**  

  Open-source network management and provisioning platform (Community Edition) supporting DOCSIS, FTTH, DSL, WiFi, and related access technologies, with integrated monitoring components.



- **[LibreQoS](https://github.com/LibreQoE/LibreQoS)**  

  Open-source traffic management and network operations platform for ISPs, focused on QoS, bufferbloat reduction, subscriber visibility, and topology-aware insights.



- **[Prometheus + Grafana + Alertmanager stacks](https://github.com/prometheus/prometheus)**  

  De-facto open-source monitoring and alerting foundation widely used for performance metrics, service health, and custom assurance dashboards in telecom environments.



- **[Zabbix, Nagios, Icinga, and related monitoring](https://github.com/zabbix/zabbix)**  

  Mature open-source monitoring systems frequently deployed for infrastructure and service availability assurance.



- **[Anomaly detection & research tools](https://github.com/search?q=service+assurance+OR+network+anomaly+OR+telecom+OSS)**  

  Academic and community projects focused on BGP/MPLS VPN anomaly detection, service disruption detection, and related analytics.



### Additional Strong Open-Source Options



- **Flow & telemetry collectors**: Tools for NetFlow, IPFIX, sFlow, gNMI, and streaming telemetry ingestion.

- **Topology & discovery engines**: Open-source components for network discovery and relationship mapping.

- **Event correlation engines**: Rule-based or AI-assisted open-source correlation frameworks.

- **Ticketing & ITSM integration**: Systems such as Zammad, Glpi, or custom workflows linked to assurance events.

- **Digital experience monitoring**: Synthetic and real-user monitoring open-source projects.

- Kafka, NATS, or other messaging layers used to build scalable assurance data pipelines.



**Frameworks for building custom systems**:  

For the closest open-source foundation to commercial service assurance, start with **NOC Project** or **OpenNMS** for fault + performance + inventory.  

Layer **Prometheus/Grafana** for metrics and visualization, and add domain-specific collectors or probes as needed.  

**Boda Telecom Suite** and **NMS Prime** are particularly relevant for telecom configuration and access-network operations.  

Commercial platforms (Amdocs, Nokia, Ericsson, Viavi, Accedian, etc.) remain dominant for large operators because of multi-vendor mediation, AI/ML analytics, SLA management, probe ecosystems, and carrier-grade support. Open-source stacks excel for cost control, customization, and environments where operators want full ownership of the assurance pipeline.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Service assurance systems are operationally critical for network availability and customer experience. Any deployment must consider scalability, security, multi-vendor compatibility, and integration with existing OSS/BSS.

- Open-source solutions provide transparency and flexibility but require significant integration, mediation, and operational expertise to approach the breadth of commercial assurance platforms used by large service providers.



---



**Made for network operations teams, OSS architects, telecom engineers, and service assurance specialists.**  

Let's advance open, observable, and operator-controlled service assurance through strong open-source OSS and monitoring platforms.
