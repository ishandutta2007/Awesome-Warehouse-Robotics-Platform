# Awesome-Warehouse-Robotics-Platform

## Top Warehouse Robotics Platform Tools Ecosystem
**Curated List of SaaS Products & Open-Source GitHub Projects**
*Focused on AMR/AGV Fleet Management, Warehouse Automation, Orchestration, AS/RS Integration & Multi-Robot Coordination*
**Last updated: August 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Warehouse Robotics**. These systems coordinate autonomous mobile robots (AMRs), automated guided vehicles (AGVs), goods-to-person systems, and related automation — handling task allocation, traffic management, integration with WMS/WES, and multi-fleet interoperability inside warehouses and fulfillment centers.

**Examples** include SVT Robotics, Formic, Locus Robotics, 6 River Systems, GreyOrange, Geek+, Fetch Robotics, Exotec, Vecna Robotics, InOrbit, AutoStore, Symbotic, Quicktron, Attabotics, and Swisslog SynQ (the category leaders and widely deployed platforms).

**Open-source emphasis**: Full commercial warehouse robotics suites remain largely proprietary, but a strong open-source layer exists for fleet coordination, navigation, and interoperability. This section prioritizes the most capable open frameworks that teams can use to build or extend multi-robot warehouse systems.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites / GitHub repos.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms
- **[SVT Robotics](https://www.svtrobotics.com/)**  
  Softbot platform focused on rapid integration and orchestration of heterogeneous warehouse robots and automation equipment without heavy custom engineering.
- **[Formic](https://www.formic.co/)**  
  Robotics-as-a-Service model that deploys and operates warehouse automation (including AMRs) with outcome-based pricing.
- **[Locus Robotics](https://locusrobotics.com/)**  
  Leading AMR platform for person-to-goods fulfillment, known for collaborative robots and warehouse execution software.
- **[6 River Systems](https://6river.com/)** (Shopify)  
  Collaborative mobile robot (Chuck) platform and warehouse orchestration software for fulfillment centers.
- **[GreyOrange](https://www.greyorange.com/)**  
  AI-driven fulfillment and warehouse robotics platform combining Ranger robots with GreyMatter orchestration software.
- **[Geek+](https://www.geekplus.com/)**  
  Broad portfolio of warehouse robots (picking, sorting, moving) and intelligent warehouse management software.
- **[Fetch Robotics](https://fetchrobotics.com/)** (Zebra Technologies)  
  AMR platform for material transport and warehouse workflows, integrated into broader Zebra automation offerings.
- **[Exotec](https://www.exotec.com/)**  
  Skypod goods-to-person system and warehouse robotics platform focused on high-density storage and rapid picking.
- **[Vecna Robotics](https://www.vecnarobotics.com/)**  
  Autonomous mobile robots and orchestration software for warehouse and manufacturing material movement.
- **[InOrbit](https://www.inorbit.ai/)**  
  Robot operations platform (cloud robotics) for monitoring, managing, and integrating robot fleets across vendors.
- **[AutoStore](https://www.autostoresystem.com/)**  
  Cube-based automated storage and retrieval system (AS/RS) with robots that work on top of the grid.
- **[Symbotic](https://www.symbotic.com/)**  
  AI-powered warehouse automation and robotics systems for high-volume distribution centers.
- **[Quicktron](https://www.quicktron.com/)**, **[Attabotics](https://www.attabotics.com/)**, **[Swisslog SynQ](https://www.swisslog.com/)**  
  Additional major players in AMR, 3D storage, and warehouse execution/robotics software.

## Open-Source GitHub Projects
- **[Open-RMF](https://github.com/open-rmf)** (Robotics Middleware Framework)  
  The leading open-source framework for multi-fleet robot coordination. Handles task allocation, traffic deconfliction, shared infrastructure (doors, lifts), and interoperability between heterogeneous robot fleets. Built on ROS 2 and widely used as the open standard for facility-scale robot orchestration.
- **[openTCS](https://www.opentcs.org/)** (Fraunhofer IML)  
  Vendor-independent open-source platform for controlling and coordinating AGV and AMR fleets. Provides routing, dispatching, scheduling, deadlock prevention, and pluggable adapters for mixed-manufacturer fleets.
- **[Nav2](https://github.com/ros-navigation/navigation2)**  
  The standard open-source navigation stack for ROS 2. Forms the foundation for individual AMR localization, path planning, and obstacle avoidance in warehouse environments.
- **VDA 5050 Fleet Managers** (e.g., TARS and related projects)  
  Open-source fleet management implementations following the VDA 5050 interface standard for interoperable AGV/AMR communication.
- **Free Fleet & Open-RMF Adapters**  
  Community and official adapters that connect commercial and research robots (MiR, Clearpath, TurtleBot, and others) into Open-RMF-managed fleets.
- **ROS-Industrial & Mobile Robot Stacks**  
  Open components for industrial mobile robots, mapping, localization, and integration with warehouse systems.
- **Simulation & Demo Environments**  
  Gazebo / Ignition-based Open-RMF demos and multi-robot warehouse simulation packages used for development and testing.
- **DIY / Low-Cost AMR Projects**  
  Open hardware and software efforts (e.g., OpenAMR-style platforms) demonstrating affordable LiDAR-SLAM mobile robots for smaller warehouses.

### Additional Strong Open-Source Options
- Traffic editor and building map tools within the Open-RMF ecosystem.
- Task allocation and auction-based planners.
- Elevator, door, and infrastructure adapters for full-facility integration.
- Monitoring dashboards and observability tools for robot fleets.
- Integration patterns between open fleet managers and open-source or commercial WMS/WES systems.

**Frameworks for building custom systems**: Most open warehouse robotics efforts combine **Nav2** (or equivalent navigation) on individual robots with **Open-RMF** or **openTCS** as the fleet coordination layer. VDA 5050 provides a standardized interface for mixing vendors. Full commercial platforms still dominate large-scale, high-reliability deployments, but the open stack is increasingly capable for research, mid-size facilities, and custom integrations.

## How to Contribute
1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer
- This is a **community-curated** list — not exhaustive and not an endorsement.
- Warehouse robotics platforms should be evaluated for robot performance, fleet scale, WMS/WES integration depth, traffic management robustness, safety certifications, vendor lock-in risk, and total cost of ownership (including RaaS models).
- Open-source fleet and navigation frameworks provide excellent interoperability and control but require significant robotics and systems engineering expertise to achieve production-grade reliability, safety, and throughput in live warehouse environments.
---
**Made for warehouse automation engineers, robotics integrators, logistics technologists, and teams building interoperable multi-robot systems.**
Let's make warehouse robotics more open, vendor-agnostic, and free from proprietary fleet lock-in.
