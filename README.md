# Cisco Certification Resource Hub & Exam Blueprint Study Guides (2026 Edition)

[![Cisco Certified](https://img.shields.io/badge/Cisco_Certified-2026_Edition-049fd9?style=for-the-badge&logo=cisco&logoColor=white)](https://www.cisco.com/)
[![Tracks](https://img.shields.io/badge/Tracks-Associate_|_Professional_|_Specialist_|_CCIE-1BA0D7?style=for-the-badge)](https://www.cisco.com/c/en/us/training-events/training-certifications/certifications.html)
[![Practice Partner](https://img.shields.io/badge/Practice_Partner-CertsClub_(20%25_Off_Code:_club20)-28a745?style=for-the-badge&logo=shield)](https://www.certsclub.com/cisco/)
[![Maintained](https://img.shields.io/badge/Maintained%3F-Yes_(2026)-brightgreen?style=for-the-badge)](https://github.com/CiscoCertifications/cisco-certifications-hub-2026)
[![License](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)

Welcome to the definitive **Cisco Certification Resource Hub (2026 Edition)**. This repository provides architectural study guides, official blueprint domain mappings, technical deep-dives, and scenario-based exam preparation materials across Cisco's entire career certification portfolio—spanning Entry, Associate (CCNA/DevNet/CyberOps), Professional Core (CCNP/DevNet Core), and High-Demand Concentration Specialist examinations.

---

## Executive Summary: Cisco Certification Hierarchy

Cisco's certification framework is designed around modular, career-progressive learning paths that validate both broad architectural understanding and deep domain specialization.

```
       +-----------------------------------------------------------+
       |                  EXPERT LEVEL (CCIE)                      |
       |  8-Hour Hands-On Lab Exam (Requires Professional Core)   |
       +-----------------------------+-----------------------------+
                                     ^
                                     |
       +-----------------------------+-----------------------------+
       |               PROFESSIONAL LEVEL (CCNP / DevNet)          |
       |     1x Technology Core Exam  +  1x Concentration Exam     |
       +-----------------------------+-----------------------------+
                                     ^
                                     |
       +-----------------------------+-----------------------------+
       |                   ASSOCIATE LEVEL (CCNA)                  |
       |   Foundational Networking, Programmability, & Security    |
       +-----------------------------------------------------------+
```

### The Modular Professional & CCIE Model
1. **No Formal Prerequisites:** Cisco does not require candidates to pass Associate-level exams (such as CCNA) before attempting Professional-level exams. Candidates may begin directly at the CCNP or Specialist level depending on their technical experience.
2. **Dual-Purpose Core Exams:** Every CCNP Core exam (e.g., `350-401 ENCOR`, `350-701 SCOR`, `350-601 DCCOR`) acts as both:
   - The primary core requirement for earning the corresponding **CCNP credential** (when paired with any eligible concentration exam within that track).
   - The written qualifying exam required to book and sit for the corresponding **8-hour CCIE hands-on lab exam**.
3. **Specialist Credential per Exam:** Every passed Cisco exam (whether core or concentration) awards an individual **Cisco Certified Specialist** certification, verifying specific domain mastery.
4. **Three-Year Recertification Lifecycle:** All Associate and Professional credentials are valid for 3 years. They can be renewed via retaking exams or accumulating **Continuing Education (CE)** credits through Cisco U. and official training modules.

---

## Master Certification Exam Catalog

| Exam Code | Official Credential Title | Technology Track | Certification Level | Blueprint Version | Exam Guide Link |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **200-301** | Cisco Certified Network Associate (CCNA) | Enterprise / Routing & Switching | Associate | v1.1 | [View 200-301 Guide](exams/200-301.md) |
| **200-201** | Understanding Cisco Cybersecurity Operations Fundamentals (CBROPS) | Security Operations (CyberOps) | Associate | v1.1 | [View 200-201 Guide](exams/200-201.md) |
| **200-901** | Developing Applications and Automating Workflows using Cisco Platforms (DEVASC) | Software & Network Automation | Associate | v1.1 | [View 200-901 Guide](exams/200-901.md) |
| **350-401** | Implementing and Operating Cisco Enterprise Network Core Technologies (ENCOR) | Enterprise Infrastructure & Wireless | CCNP Core / CCIE Qualifier | v1.2 | [View 350-401 Guide](exams/350-401.md) |
| **350-701** | Implementing and Operating Cisco Security Core Technologies (SCOR) | Network & Cloud Security | CCNP Core / CCIE Qualifier | v1.1 | [View 350-701 Guide](exams/350-701.md) |
| **350-601** | Implementing and Operating Cisco Data Center Core Technologies (DCCOR) | Data Center Architecture & Nexus | CCNP Core / CCIE Qualifier | v1.1 | [View 350-601 Guide](exams/350-601.md) |
| **350-801** | Implementing and Operating Cisco Collaboration Core Technologies (CLCOR) | Unified Communications & Webex | CCNP Core / CCIE Qualifier | v1.1 | [View 350-801 Guide](exams/350-801.md) |
| **350-501** | Implementing and Operating Cisco Service Provider Network Core Technologies (SPCOR) | Carrier IP/MPLS & Segment Routing | CCNP Core / CCIE Qualifier | v1.1 | [View 350-501 Guide](exams/350-501.md) |
| **350-901** | Developing Applications using Cisco Core Platforms and APIs (DEVCOR) | Cisco DevNet Programmability Core | DevNet Professional Core | v1.1 | [View 350-901 Guide](exams/350-901.md) |
| **300-410** | Implementing Cisco Enterprise Advanced Routing and Services (ENARSI) | Enterprise Routing & Troubleshooting | CCNP Concentration / Specialist | v1.1 | [View 300-410 Guide](exams/300-410.md) |
| **300-710** | Securing Networks with Cisco Firepower (SNCF) | NGFW, NGIPS, & Threat Defense | CCNP Concentration / Specialist | v1.1 | [View 300-710 Guide](exams/300-710.md) |
| **300-435** | Automating Cisco Enterprise Solutions (ENAUTO) | DNA Center, SD-WAN, & Meraki APIs | CCNP Concentration / Specialist | v1.1 | [View 300-435 Guide](exams/300-435.md) |

---

## Categorized Track Breakdowns & CCIE Qualification

### 1. Cisco Enterprise Track (Routing, Switching, Wireless, SD-WAN)
* **Core Exam:** `350-401 ENCOR`
* **Eligible Concentration Exams:**
  * `300-410 ENARSI` (Advanced Routing: EIGRP, OSPF, BGP, MPLS VPNs, DMVPN)
  * `300-415 ENSDWI` (Cisco SD-WAN Architecture & Edge Deployment)
  * `300-420 ENSLD` (Enterprise Network Design & Campus Topologies)
  * `300-425 ENWLSD` (Enterprise Wireless Design & Site Surveys)
  * `300-430 ENWLSI` (Enterprise Wireless Implementation & FlexConnect)
  * `300-435 ENAUTO` (Automating Enterprise Solutions with Python, REST, & NETCONF)
* **Expert Lab Qualification:** Passing `350-401 ENCOR` qualifies candidates to attempt either:
  * **CCIE Enterprise Infrastructure v1.1 Lab**
  * **CCIE Enterprise Wireless v1.0 Lab**

### 2. Cisco Security Track (Threat Defense, Identity, Cloud, SASE)
* **Core Exam:** `350-701 SCOR`
* **Eligible Concentration Exams:**
  * `300-710 SNCF` (Cisco Firepower Threat Defense & Management Center)
  * `300-715 SISE` (Implementing and Configuring Cisco Identity Services Engine - ISE)
  * `300-720 SESA` (Securing Email with Cisco Email Security Appliance)
  * `300-725 SWSA` (Securing the Web with Cisco Web Security Appliance)
  * `300-730 SVPN` (Implementing Secure Solutions with Virtual Private Networks)
  * `300-735 SAUTO` (Automating and Programming Cisco Security Solutions)
* **Expert Lab Qualification:** Passing `350-701 SCOR` qualifies candidates for the **CCIE Security v6.1 Lab**.

### 3. Cisco Data Center Track (Nexus, ACI, UCS, HyperFlex, SAN)
* **Core Exam:** `350-601 DCCOR`
* **Eligible Concentration Exams:**
  * `300-610 DCID` (Designing Cisco Data Center Infrastructure)
  * `300-615 DCIT` (Troubleshooting Cisco Data Center Infrastructure)
  * `300-620 DCACI` (Implementing Cisco Application Centric Infrastructure - ACI)
  * `300-625 DCSAN` (Implementing Cisco Storage Area Networking)
  * `300-635 DCAUTO` (Automating Cisco Data Center Solutions)
* **Expert Lab Qualification:** Passing `350-601 DCCOR` qualifies candidates for the **CCIE Data Center v3.1 Lab**.

### 4. Cisco Service Provider Track (Carrier Core, BGP, Segment Routing, MPLS)
* **Core Exam:** `350-501 SPCOR`
* **Eligible Concentration Exams:**
  * `300-510 SPRI` (Implementing Cisco Service Provider Advanced Routing Solutions)
  * `300-515 SPVI` (Implementing Cisco Service Provider VPN Services)
  * `300-535 SPAUTO` (Automating Cisco Service Provider Solutions)
* **Expert Lab Qualification:** Passing `350-501 SPCOR` qualifies candidates for the **CCIE Service Provider v5.1 Lab**.

### 5. Cisco Collaboration Track (CUCM, Webex, SIP Gateways, QoS)
* **Core Exam:** `350-801 CLCOR`
* **Eligible Concentration Exams:**
  * `300-810 CLICA` (Implementing Cisco Collaboration Applications)
  * `300-815 CLACCM` (Implementing Cisco Advanced Call Control and Mobility Services)
  * `300-820 CLCEI` (Implementing Cisco Collaboration Cloud and Edge Solutions)
  * `300-835 CLAUTO` (Automating Cisco Collaboration Solutions)
* **Expert Lab Qualification:** Passing `350-801 CLCOR` qualifies candidates for the **CCIE Collaboration v3.1 Lab**.

### 6. Cisco DevNet & Software Automation Track
* **Associate Exam:** `200-901 DEVASC`
* **Professional Core Exam:** `350-901 DEVCOR`
* **Eligible Concentrations:** Any automation concentration (`300-435 ENAUTO`, `300-735 SAUTO`, `300-635 DCAUTO`, `300-535 SPAUTO`, `300-835 CLAUTO`, `300-910 DEVOPS`, `300-915 DEVIOT`).

---

## Official Cisco Exam Policies & Testing Environment

| Specification | Policy Detail |
| :--- | :--- |
| **Exam Duration** | Standard 120 Minutes (Associate, Professional Core, and Concentration exams). Non-native English speakers testing in non-English speaking countries receive a 30-minute ESL extension. |
| **Item Count** | Typically 90–110 items for Associate exams; 90–105 items for Professional Core exams; 55–65 items for Concentration exams. |
| **Passing Score** | Scaled score range of **300 to 1000**. Passing threshold is typically **800 to 850** depending on dynamic item statistical calibration. |
| **Navigation Rule** | **Strict Linear Navigation:** You cannot mark a question and return to it later. Once an answer is submitted, it is permanent. |
| **Question Formats** | Multiple-choice single-select, Multiple-choice multi-select, Drag-and-drop sequencing, Performance-based Simlets (interactive CLI terminal emulation), and Testlets (case scenarios with multiple dependent items). |
| **Retake Waiting Period** | If an exam is failed, candidates must wait **5 calendar days** starting the day after the failed attempt before re-testing. Passed exams cannot be retaken within 180 days. |
| **Testing Modality** | Delivered worldwide via **Pearson VUE** authorized testing centers or remotely via **OnVUE online proctoring**. |

---

## Proven Preparation Methodology & Recommended Resources

1. **Official Cisco Learning Platforms:**
   - **Cisco U. (Digital Learning):** Modular self-paced courses aligned directly with blueprint domains.
   - **Cisco Learning Network (CLN):** Official blueprint checklists, community study groups, and exam webinars.
   - **Cisco Press Certification Guides:** Official Cert Guides (OCG) authored by principal Cisco engineers and CCIEs.

2. **Practical Hands-On Lab Engines:**
   - **Cisco Modeling Labs (CML 2.x):** Enterprise network simulation platform running authentic Cisco IOS XE, IOS XR, and NX-OS virtualized machine images.
   - **Cisco Packet Tracer:** Ideal for CCNA-level topology building, switching protocol verification, and IPv6 routing.
   - **Cisco DevNet Sandbox:** Free, reservation-based hardware sandboxes for testing RESTCONF, NETCONF, DNA Center APIs, and Meraki dashboards.

3. **Verified Practice Test Partner: CertsClub**
   - Practicing with high-fidelity, scenario-driven practice exams is critical to mastering Cisco's time management and complex item formats.
   - Access verified, regularly updated exam practice materials at **[CertsClub Cisco Certification Catalog](https://www.certsclub.com/cisco/)**.
   - **Special Discount:** Use promo code **`club20`** at checkout to receive **20% off** all Cisco practice tests and simulator bundles.

---

## Repository Structure & Navigation

```
cisco-certifications-hub-2026/
├── README.md                 # Master certification repository overview and catalog
└── exams/                    # Detailed individual exam blueprint study guides
    ├── 200-301.md            # CCNA: Cisco Certified Network Associate
    ├── 200-201.md            # CBROPS: Understanding Cisco Cybersecurity Operations Fundamentals
    ├── 200-901.md            # DEVASC: Cisco DevNet Associate
    ├── 350-401.md            # ENCOR: Implementing Cisco Enterprise Network Core Technologies
    ├── 350-701.md            # SCOR: Implementing Cisco Security Core Technologies
    ├── 350-601.md            # DCCOR: Implementing Cisco Data Center Core Technologies
    ├── 350-801.md            # CLCOR: Implementing Cisco Collaboration Core Technologies
    ├── 350-501.md            # SPCOR: Implementing Cisco Service Provider Core Technologies
    ├── 350-901.md            # DEVCOR: Developing Applications Using Cisco Core Platforms & APIs
    ├── 300-410.md            # ENARSI: Cisco Enterprise Advanced Routing & Services
    ├── 300-710.md            # SNCF: Securing Networks with Cisco Firepower
    └── 300-435.md            # ENAUTO: Automating Cisco Enterprise Solutions
```

---
*Maintained by the Cisco Certifications Community. Updated for the 2026 Exam Cycle.*
