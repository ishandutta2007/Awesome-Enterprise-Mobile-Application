# Awesome-Enterprise-Mobile-Application

## Top Enterprise Mobile Application Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Mobile App Development, Device Management & Enterprise Mobility*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Enterprise Mobile Applications**. These tools enable organizations to build, deploy, secure, and manage mobile applications and devices across their workforce—covering the full spectrum from low-code app development and backend services to mobile device management (MDM) and unified endpoint management (UEM).



**Examples** include Workday Mobile, Microsoft Intune, VMware Workspace ONE, ServiceNow Mobile Agent, SAP Mobile Services, Salesforce Mobile, Ivanti Neurons for UEM, Jamf Pro, ManageEngine Endpoint Central, and Citrix Workspace (the category leaders).



**Open-source emphasis**: Enterprise Mobility is a domain where open-source tooling is **fragmented across distinct sub-categories**. **Convertigo** provides a mature low-code platform for building cross-platform enterprise mobile apps . **Parse Server** and **Appwrite** provide self-hosted Backend-as-a-Service foundations for mobile apps . For device management, **Cairn-MDM** offers a single-binary Apple MDM server for macOS/iOS , while **MDMesh** provides a modern self-hosted Android MDM with kiosk and app delivery . No single open-source platform matches the full UEM capability of Microsoft Intune or VMware Workspace ONE across all device types.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Workday Mobile](https://www.workday.com/)**  

  Mobile access to Workday's HCM and financial management suite, enabling employees to view payslips, request time off, approve transactions, and access workforce data on iOS and Android.



- **[Microsoft Intune](https://learn.microsoft.com/en-us/mem/intune/)**  

  Comprehensive endpoint management for Windows, Apple, Android, and Linux devices; provides MDM, MAM, configuration profiles, compliance enforcement, conditional access, and Copilot-powered AI agents for device troubleshooting.



- **[VMware Workspace ONE (Omnissa)](https://www.omnissa.com/)**  

  Unified endpoint management platform ranked a Leader in the 2026 Gartner Magic Quadrant; supports Windows, macOS, iOS, Android, ChromeOS, Linux, and rugged devices with zero-touch onboarding and automated app lifecycle.



- **[ServiceNow Mobile Agent](https://www.servicenow.com/)**  

  Mobile-first app for service desk agents to triage and resolve requests on the go, with offline work, native device capabilities, and out-of-the-box workflows for IT, CSM, HR, and Field Services.



- **[SAP Mobile Services](https://www.sap.com/)**  

  Mobile app development and management platform within SAP's ecosystem, enabling enterprise mobile app deployment and secure connectivity to SAP systems.



- **[Salesforce Mobile](https://www.salesforce.com/)**  

  Mobile access to Salesforce CRM with offline capabilities, push notifications, and mobile-optimized workflows for sales and service teams.



- **[Ivanti Neurons for UEM](https://www.ivanti.com/)**  

  Unified endpoint management with mobile threat defense, Apple Declarative Device Management, Android Enterprise workflows, and tiered packaging covering secure email, MAM, and SSO.



- **[Jamf Pro](https://www.jamf.com/)**  

  Apple-focused enterprise mobility management with zero-touch deployment for iPad, iPhone, Mac, and Apple TV; trusted by 76,600+ organizations for native OS management and self-service app catalog.



- **[ManageEngine Endpoint Central](https://www.manageengine.com/)**  

  Unified endpoint management with MDM for Android and Apple devices, kiosk mode, geo-fencing, remote lock/wipe, and OS update management.



- **[Citrix Workspace](https://www.citrix.com/)**  

  Endpoint management with MDM+MAM capabilities, micro-VPN via NetScaler Gateway, and integration with Citrix Virtual Apps and Desktops for secure mobile access to enterprise resources.



## Open-Source GitHub Projects



### Low-Code Mobile App Development



- **[Convertigo](https://github.com/convertigo/convertigo)**  

  Mature open-source AI-driven low-code and no-code platform (AGPL-3.0) for building complex cross-platform enterprise mobile and web apps; includes Convertigo Server (backend with offline data synchronization), Eclipse-based Studio for full-stack development, and No Code Studio for citizen developers; Docker/Helm deployment; used by 150K+ developers worldwide . **The most complete open-source platform for building enterprise mobile apps** with backend integration and offline capabilities.



- **[Joget DX](https://github.com/jogetworkflow/jw-community)**  

  Open-source no-code/low-code application platform (GPL-3.0) combining rapid application development, business process automation, and workflow management; apps built are **mobile ready and cloud ready**, with Progressive Web App (PWA) support including offline support and push notifications via configuration . **Strong for workflow-driven enterprise mobile apps** with visual development and BPM capabilities.



### Backend-as-a-Service for Mobile Apps



- **[Parse Server](https://github.com/parse-community/parse-server)**  

  Open-source Backend-as-a-Service (Apache 2.0) built on Node.js; provides auto-generated REST/GraphQL APIs, user authentication with social login and MFA, file storage, push notifications, Cloud Code for server-side logic, and **LiveQuery for real-time data sync** . Originally created by Facebook, now community-maintained with 21K+ GitHub stars; compatible with MongoDB and PostgreSQL. **The most mature open-source BaaS for mobile apps** requiring self-hosted backend infrastructure .



- **[Appwrite](https://github.com/appwrite/appwrite)**  

  Open-source end-to-end backend server for frontend and mobile apps (BSD-3-Clause, 48K+ GitHub stars); provides authentication, databases, storage, functions, and real-time capabilities; Docker-deployable with SDKs for Android, iOS, Flutter, and React Native . **Modern alternative to Parse Server** with a more contemporary developer experience.



### Mobile Device Management (MDM)



- **[Cairn-MDM](https://github.com/nickpdawson/Cairn-MDM)**  

  Single-binary, open-source Apple MDM server (MIT, v0.1.1 public beta) for macOS and iOS/iPadOS devices; embeds MDM protocol server (NanoMDM), SCEP certificate authority, and admin UI in one Go binary with SQLite database; supports over-the-air enrollment, configuration profile delivery, and Apple HIG-inspired web console; **no Apple Business Manager account required** for the non-ABM path . **The simplest self-hosted Apple MDM option** for homelabs, small businesses, and non-profits; pre-1.0 with DDM and ABM/ADE on the roadmap.



- **[MDMesh](https://github.com/MDMesh-app/MDMesh)**  

  Modern self-hosted **Android MDM** (fork of Headwind MDM, being rebuilt as distinct product); features QR-code Device-Owner enrollment, kiosk/COSU mode with crash-loop guard and exit PIN, app delivery (APK upload, F-Droid catalog, silent install), location tracking, remote actions, and **signed auto-updates with rollback**; console built with React/TypeScript; server uses Java/PostgreSQL . **The most feature-complete open-source Android MDM** with modern console and no paywalled "enterprise edition."



- **[MicroMDM](https://github.com/micromdm/micromdm)**  

  Open-source Apple MDM server (Go, 2,500+ GitHub stars); the upstream project from which Cairn-MDM builds; provides the core MDM protocol implementation for teams wanting to build custom Apple device management workflows .



### Additional Strong Open-Source Options



- **Vibra Code** — Open-source AI mobile app builder (AGPL-3.0) that generates Expo React Native apps from natural language descriptions; self-hostable with Claude/Cursor/Gemini support and E2B sandboxes . **Novel AI-assisted development** rather than traditional enterprise platform.

- **Monkshu** — Open-source JavaScript enterprise application server for mobile apps (iOS/Android), PWAs, and responsive web apps; includes web container, JSON API container, and hybrid app frameworks with minimal dependencies . **Application server infrastructure** rather than a complete mobile platform.



**Frameworks for building custom systems**: Combine **Convertigo** or **Joget DX** for low-code enterprise mobile app development with backend integration, **Parse Server** or **Appwrite** for self-hosted Backend-as-a-Service, and **Cairn-MDM** (Apple) or **MDMesh** (Android) for device management in a sovereign enterprise mobility stack. Note that no single open-source platform spans both app development and cross-platform device management like Microsoft Intune or VMware Workspace ONE.



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- Enterprise mobile platforms handling device and user data must comply with applicable privacy regulations (GDPR, CCPA) and organizational security policies; MDM enrollment grants significant device control requiring careful consent and data governance.

- **Open-source enterprise mobility is fragmented across sub-categories**—Convertigo and Joget provide app development, Parse Server and Appwrite provide backend services, Cairn-MDM and MDMesh provide device management. No single open-source platform matches Microsoft Intune or VMware Workspace ONE for unified cross-platform UEM. Cairn-MDM is Apple-only and pre-1.0 ; MDMesh is Android-only and in active rebuild .

- Verify license terms for commercial use; Convertigo uses AGPL-3.0 , Joget uses GPL-3.0 , Parse Server uses Apache 2.0 , Appwrite uses BSD-3-Clause , Cairn-MDM uses MIT , and MDMesh is open-source .



---



**Made for enterprise mobility architects, mobile developers, IT administrators, and device management engineers.**  

Let's make enterprise mobile applications more open, manageable, and worker-empowering.
