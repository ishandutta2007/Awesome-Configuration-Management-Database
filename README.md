# Awesome-Configuration-Management-Database

# Top Configuration Management Database (CMDB) Platforms Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on IT Asset Inventory, Configuration Items, Dependency Mapping, Discovery, Service Mapping & ITIL CMDB*
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Configuration Management Database (CMDB)**. These systems inventory configuration items (CIs), map relationships and dependencies, support discovery, and underpin ITSM, change, and incident processes.

**Examples** include ServiceNow CMDB, Device42, i-doit, Virima, Device42 Core, Xurrent CMDB, ManageEngine CMDB, OpenText Universal CMDB, BMC Helix CMDB, and InvGate Insight (the category leaders).

**Open-source emphasis**: CMDB has a solid open-source landscape. **i-doit**, **iTop**, **CMDBuild**, **GLPI**, **Ralph**, **DataGerry**, and **NetBox** are widely used for documentation, asset management, and infrastructure source-of-truth. This section heavily expands those projects.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[ServiceNow CMDB](https://www.servicenow.com/products/it-operations-management.html)**  
  Market-leading enterprise CMDB with deep governance, discovery integration, service mapping, and tight coupling to the broader ServiceNow ITSM platform.

- **[Device42](https://www.device42.com/)**  
  Infrastructure-centric CMDB and discovery platform strong on data center, hybrid, and detailed asset inventory with dependency mapping.

- **[i-doit](https://www.i-doit.com/)**  
  IT documentation and CMDB platform (with open-source community options) focused on structured asset and relationship documentation.

- **[Virima](https://www.virima.com/)**  
  CMDB and IT asset management platform with discovery, visualization, and service mapping capabilities.

- **[Xurrent CMDB](https://www.xurrent.com/)**  
  Modern ITSM platform CMDB for configuration items, relationships, and service management workflows.

- **[ManageEngine CMDB](https://www.manageengine.com/)**  
  CMDB capabilities within ManageEngine’s ITSM and asset management suites for mid-market and enterprise environments.

- **[OpenText Universal CMDB](https://www.opentext.com/)**  
  Enterprise discovery and CMDB suite (Universal Discovery and CMDB) for complex hybrid environments and service mapping.

- **[BMC Helix CMDB](https://www.bmc.com/it-solutions/bmc-helix.html)**  
  Enterprise CMDB within the BMC Helix platform supporting discovery, service models, and IT operations management.

- **[InvGate Insight](https://invgate.com/)**  
  IT asset and CMDB-oriented platform for inventory, relationships, and operational visibility.

## Open-Source GitHub Projects
- **[i-doit Open](https://github.com/)** / [i-doit.org](https://i-doit.org/)  
  Open-source CMDB and IT documentation platform—servers, networks, software, contracts, locations, relationships, and CMDB Explorer views.

- **[iTop](https://github.com/Combodo/iTop)**  
  Open-source CMDB with integrated ITSM—devices, software, applications, processes, locations, organizations, and service desk workflows.

- **[CMDBuild](https://www.cmdbuild.org/)** / [GitHub](https://github.com/)  
  Highly configurable open-source platform for building custom CMDB applications, data models, workflows, and dashboards.

- **[GLPI](https://github.com/glpi-project/glpi)**  
  Broad open-source IT asset management and service desk platform with strong inventory, relationships, and ITAM/ITSM coverage.

- **[Ralph](https://github.com/allegro/ralph)**  
  Open-source CMDB and asset management focused on data center and back-office hardware lifecycle (Apache 2.0).

- **[DataGerry](https://github.com/DATAGerry/DATAGerry)**  
  Flexible open-source CMDB that lets administrators define custom object types, fields, and relationships with import/export support.

- **[NetBox](https://github.com/netbox-community/netbox)**  
  Open-source network source of truth and DCIM/IPAM platform frequently used as a foundational CMDB component for infrastructure.

- **[OCS Inventory / FusionInventory](https://github.com/)**  
  Open-source discovery and inventory agents commonly paired with GLPI or other CMDBs for automated asset collection.

- **[Snipe-IT](https://github.com/snipe/snipe-it)**  
  Open-source IT asset management focused on lifecycle tracking; lighter than a full relationship CMDB but useful for inventory.

- **[Documentation and open CMDB playbooks](https://www.cmdbuild.org/en/documentation)**  
  Guides for modeling CIs, relationships, and discovery integrations in open-source CMDB stacks.

### Additional Strong Open-Source Options
- Choosing **i-doit** for structured IT documentation and dependency visualization.
- Using **iTop** when CMDB and service desk need to live in one open platform.
- Adopting **CMDBuild** or **DataGerry** for highly customized data models and workflows.
- Relying on **GLPI** for combined ITAM + ITSM, and **Ralph** or **NetBox** for data-center and network-centric environments.
- Accepting that enterprise-scale automated discovery, continuous service mapping, governance workflows, and multi-cloud hybrid correlation still favor commercial platforms (ServiceNow, BMC Helix, Device42, OpenText, etc.).
- Focusing open-source efforts on data ownership, cost control, and transparent relationship models.

**Frameworks for building custom systems**: Model CIs and relationships in i-doit / iTop / CMDBuild / GLPI → feed inventory via agents or NetBox → expose data to ITSM and monitoring. Suitable for mid-size IT teams and organizations prioritizing open standards. Large enterprises often still standardize on commercial CMDBs for discovery depth and platform integration.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- CMDB accuracy depends on discovery quality and process discipline. Open-source deployments require ongoing data ownership and integration work. This list is not ITIL or
