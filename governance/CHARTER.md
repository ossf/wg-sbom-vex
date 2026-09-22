# CHARTER: SBOM & VEX Working Group (SBOM-VEX-WG)

## 1. Mission

The mission of the SBOM & VEX Working Group is to drive the practical adoption, harmonization, and maturity of Software Bills of Materials (SBOM) and Vulnerability Exploitability eXchange (VEX) artifacts across the open-source ecosystem.

Operating as a format-agnostic, neutral forum under the Open Source Security Foundation (OpenSSF), this Working Group unites tool builders, software producers, end-users, and standard bodies. Our objective is to bridge the gap between specification and application—transforming community energy into actionable guidance, interoperable tooling, and automated supply chain security outcomes.

## 2. Scope

The Working Group structures its initiatives, hosted projects, and community engagement around three core pillars:

### 2.1 Formats and Standards

We serve as a neutral ground to map implementation gaps, capture emerging requirements, and drive the effective application of existing industry specifications.

> * **Format-Neutral Advocacy:** Foster an environment of interoperability ("Pax Interoperabilitatis") across competing and complementary formats.  
> * **Implementation Guidance:** Provide technical assessment and deployment support for **SPDX** and **CycloneDX** for SBOM, and for **CSAF**, **CycloneDX**, **OpenVEX** and **SPDX** for VEX vulnerability suppression.  
> * **VEX Evolution:** Enhance, refine, and support the deployment of the **VEX "metaspec"** across its foundational flavors.  
> * **Cross-Ecosystem Bridge:** Maintain active feedback loops with external standards bodies, including SPDX, CycloneDX, and CSAF, and the multiple standards that reference SBOM data and requirements.

### 2.2 Technical Initiatives

We incubate, host, maintain, and support developer-focused utilities and projects that automate the generation, consumption, validation, and enrichment of SBOM and VEX artifacts across all stages of project maturity.

> * **Core Hosted Projects:** Active governance, maintenance, and roadmap execution for foundational tools including *Protobom*, *bomctl*, *SBOMit*, BOMHort and *OpenVEX*.  
> * **Emerging & Domain-Specific Tools:** Evaluate, collaborate with, and support specialized software transparency tools extending SBOM and VEX paradigms into emerging technical domains like Data and Artificial Intelligence (AI).

### 2.3 Education and Adoption

We harness end-user feedback to resolve practical deployment hurdles and lower the barrier to entry for software supply chain security and transparency.

* **Resources:** Author definitive guides, playbooks, and educational materials tailored to both software producers and downstream consumers.

* **Benchmarking:** Establish criteria to evaluate the feature sets, output quality, and specific use-case applicability of existing tools.

* **Community Support:** Cultivate open forums for knowledge transfer, troubleshooting, and peer-to-peer enablement.

## 3. Ecosystem & Foundation Alignment

The Working Group recognizes that fragmented efforts harm the ecosystem. To ensure cohesive progress, the WG actively positions itself at the intersection of industry standards, regulatory compliance, and foundational open-source engineering through a dual approach to alignment. This dual approach ensures our work remains grounded in practical engineering reality while proactively addressing the emerging security, safety, and compliance requirements posed by next-generation, AI-driven software systems.

### 3.1 OpenSSF Cross-Pollination

Recognizing that software transparency underpins multiple facets of security and compliance, active cross-pollination across the foundation is essential. The WG will foster mutual participation and maintain strategic touchpoints with the following OpenSSF Working Groups to coordinate efforts:

> * **Supply Chain Integrity:** Coordinating on overall attestation frameworks, amplify and promote successful projects for greater adoption, and defining how SBOM and VEX artifacts integrate with broader secure software provenance pipelines.  
> * **Vulnerability Disclosures:** Collaborating on downstream consumer ingestion workflows and aligning VEX data structures with coordinated vulnerability disclosure and advisory practices.  
> * **Global Cyber Policy:** Serving as a technical advisory resource to help translate emerging international software transparency regulations and compliance mandates into actionable developer tools.  
> * **AI/ML Security:** Partnering on the design, validation, and practical expansion of SBOM paradigms into data and machine learning domains (e.g., AIBOM).

As part of its initial formation, the WG will propose a new collaboration model with each of the existing working groups. Subject to the other WG's agreement, the SBOM VEX WG will either host or attend recurring joint calls with those groups. These calls will follow a cadence to be determined and may take place as part of each WG's regular community calls.

The purpose of these cross-WG discussions is to identify opportunities for collaboration and to plan joint efforts that are time-bounded and objective-driven with a mix of experts from the SBOM world and sister WGs.

### 3.2 External Industry Alignment

> * **Standards Ecosystem:** Directly engaging and inviting non-OpenSSF technical communities (such as **CycloneDX**, OASIS **CSAF**, and **SPDX**) into core forums to preserve format-neutral interoperability.  
> * **Regulatory Frameworks:** Acting as an agile technical responder to evolving international regulatory frameworks requiring robust software tracking.

## 4. Meeting Cadence

To maintain momentum across a diverse set of deliverables while remaining accessible, the Working Group utilizes a multi-tiered meeting structure:

> * **Bi-weekly SBOM Call:** A structured engineering and planning forum to track deliverables, tool development, and broader ecosystem alignment.  
> * **Bi-weekly VEX Call:** A format-neutral sync to review real-world implementation experiences, address automation gaps, and optimize VEX interoperability.  
> * **Monthly OpenVEX Project Call:** A dedicated technical sync focused exclusively on OpenVEX specification updates, tooling, and roadmap execution.  
> * **Weekly SBOM and VEX Coffee Hour:** An informal community gathering for guest presentations, emerging research reviews, and unstructured Q\&A for new adopters.

## 5. Governance

The Working Group operates under standard OpenSSF governance principles, striving for lazy consensus among active contributors.

* **Chairs:** The Working Group shall be led by three (3) Steering Chairs to facilitate meetings, manage the technical roadmap, and serve as primary liaisons to the OpenSSF Technical Advisory Council (TAC).

  * Chairs will serve staggered, renewable one-year terms and are elected by the active contributors of the Working Group.

  * To ensure immediate operational momentum upon TAC approval, the following individuals will serve as **Interim Steering Chairs** until formal elections are held:

    * **Interim Chair 1:** Allan Friedman
    * **Interim Chair 2:** Adolfo García Veytia
    * **Interim Chair 3:** Kate Stewart

  * Interim chairs will bootstrap the new WG's activities, aiming to hold its first election process within the first 3 months after formation.

  * **Chair Responsibilities:** Beyond standard moderation, Chairs are explicitly accountable for maintaining the group's issue/PR backlog, delivering quarterly technical status updates to the TAC, and ensuring the WG's output is "legible" across the foundation (e.g., posting brief bi-weekly summaries to primary OpenSSF community Slack channels).

* **Project Lifecycle:** The progression of hosted tools (from Sandbox to Incubating to Graduated) adheres strictly to OpenSSF TAC guidelines.  

* **Reporting:** Chairs will regularly compile status reports and track technical milestones for submission to the TAC.  

* **Licensing:** All code contributions follow the standard OpenSSF default (*Apache-2.0* license), and documentation follows *CC-BY-4.0*.

* **Compliance:** All members of the Working Group shall abide by the OpenSSF Code of Conduct and the Linux Foundation Antitrust Policy.
