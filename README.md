# Awesome-Care-Navigation-Platform

# Top Care Navigation Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on Provider Matching, Benefits Navigation, Care Steerage, Virtual Care Coordination & Member Guidance*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Care Navigation**. These systems help members find appropriate providers, understand benefits, navigate care pathways, and reduce friction and cost in healthcare journeys—often for employers, health plans, and health systems.

**Examples** include Kyruus Health, League, Rightway Health, Included Health, Transcarent, Accolade, HealthJoy, Quantum Health, Castlight Health, and Carelon (the category leaders).

**Open-source emphasis**: Full care navigation platforms with provider networks, benefits logic, clinical triage, and member engagement are almost entirely commercial. Open options are limited to FHIR-based provider directories, experimental AI triage/navigator prototypes, and general open healthcare frameworks. This section is realistic about the commercial gap.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[Kyruus Health](https://www.kyruushealth.com/)**  
  Provider search, matching, and access platform used by health systems to improve patient-provider matching and scheduling.

- **[League](https://league.com/)**  
  Digital health platform focused on personalized benefits, care navigation, and member engagement for employers and plans.

- **[Rightway Health](https://www.rightwayhealthcare.com/)**  
  Care navigation and benefits guidance platform helping members find care and understand coverage.

- **[Included Health](https://includedhealth.com/)**  
  Integrated virtual care and navigation platform (including legacy Grand Rounds / Doctor On Demand capabilities) for employers and health plans.

- **[Transcarent](https://www.transcarent.com/)**  
  Health and care navigation platform combining guidance, virtual care, and specialized pathways (including Accolade-related capabilities in some configurations).

- **[Accolade](https://www.accolade.com/)**  
  Personalized health advocacy and care navigation services/platform for employers and members.

- **[HealthJoy](https://www.healthjoy.com/)**  
  Benefits and care navigation platform with digital tools and advocacy for employee populations.

- **[Quantum Health](https://www.quantum-health.com/)**  
  Care coordination and navigation platform focused on high engagement and claims/trend impact for self-insured employers.

- **[Castlight Health](https://www.castlighthealth.com/)**  
  Healthcare navigation and transparency platform helping members find care and understand costs.

- **[Carelon](https://www.carelon.com/)**  
  Care delivery and navigation capabilities within broader health services and benefits ecosystems.

## Open-Source GitHub Projects
- **[FHIR-based provider directory experiments](https://github.com/)**  
  Open projects implementing FHIR Plan Net / provider directory patterns for searchable, standards-based provider data.

- **[NPPES and public provider data open tooling](https://github.com/)**  
  Scripts and pipelines that ingest CMS NPPES and related public provider data for directory and matching prototypes.

- **[AI Health Navigator prototypes](https://github.com/)**  
  Experimental open projects using LLMs and medical ontologies for symptom triage, care-level recommendations, and provider matching (not production care navigation).

- **[OpenMRS and open EHR frameworks](https://github.com/openmrs)**  
  Open-source medical record platforms that can serve as foundations for clinic-level navigation and referral workflows in resource-constrained settings.

- **[SMART on FHIR and scheduling open components](https://github.com/)**  
  Open standards and libraries for connecting to EHR scheduling and clinical data in patient-facing apps.

- **[Benefits and coverage explanation open experiments](https://github.com/)**  
  Research or community tools for explaining insurance benefits (highly limited compared with commercial navigation).

- **[Care pathway and referral open templates](https://github.com/)**  
  Shared templates and workflow definitions for referral tracking and care transitions.

- **[Patient engagement open messaging stacks](https://github.com/)**  
  Open communication tools that can support outreach as part of a navigation program.

- **[Healthcare data standards (FHIR, US Core) open resources](https://hl7.org/fhir/)**  
  Foundational open standards used by any modern care navigation or provider directory system.

- **[Documentation and open healthcare navigation playbooks](https://github.com/)**  
  Guides on FHIR directories, privacy considerations, and the limits of open-source for regulated care navigation.

### Additional Strong Open-Source Options
- Building internal provider search on **FHIR Plan Net** and public NPPES data for directory accuracy projects.
- Experimenting with open AI triage prototypes only in non-production, carefully governed research contexts.
- Using **OpenMRS** or similar for clinic-level coordination in settings where commercial navigation platforms are unavailable.
- Accepting that employer/plan-scale care navigation, clinical advocacy, network steerage, virtual care integration, and outcomes tracking still require commercial platforms (Included Health, Transcarent/Accolade, Quantum Health, Kyruus, League, etc.).
- Focusing open-source efforts on standards, transparency of provider data, and reducing directory error rates.

**Frameworks for building custom systems**: Aggregate provider data (NPPES + network files) → expose via FHIR → add simple matching rules → integrate messaging. Suitable for research, public health, or internal tools. Production care navigation for employers and health plans is dominated by commercial platforms.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Care navigation involves clinical and benefits decisions that affect patient outcomes and costs. Open-source tools are not substitutes for regulated or clinically governed navigation programs. This list is not medical or benefits advice.

---
**Made for benefits leaders, care coordinators, and open health-standards advocates.**
Let's keep care access clearer, fairer, and as transparent as practical.
