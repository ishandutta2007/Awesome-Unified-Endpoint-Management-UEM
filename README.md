# Awesome-Unified-Endpoint-Management-UEM

## Top Unified Endpoint Management (UEM) Ecosystem



**Curated List of SaaS Products & Open-Source GitHub Projects**  

*Focused on Device Fleet Management, Security Compliance & IT Automation*  

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Unified Endpoint Management (UEM)**. These tools help IT teams enroll, configure, secure, and monitor every device in their organization — from laptops and desktops to mobile phones, tablets, and even servers — across all operating systems.



**Examples** include Microsoft Intune, VMware Workspace ONE, Ivanti (MobileIron), Jamf Pro, ManageEngine Endpoint Central, IBM Security MaaS360, Citrix Endpoint Management, SOTI MobiControl, Hexnode UEM, and Cisco Meraki Systems Manager (the category leaders).



**Open-source emphasis**: UEM is a domain where open-source has made significant strides. **Fleet** leads as the most adopted open-source device management platform, used by Stripe, Netflix, and Uber . **OpenUEM** provides a clean, Apache-2.0 licensed alternative . **Tactical RMM** and **Headwind MDM** offer focused alternatives for Windows/Linux and Android respectively. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms



- **[Microsoft Intune](https://www.microsoft.com/microsoft-intune)**  

  Microsoft's cloud-based UEM platform integrated with Entra ID (Azure AD). Manages Windows, macOS, iOS, Android, and Linux devices with configuration profiles, compliance policies, app deployment, and conditional access. Bundled with Microsoft 365 E3/E5 or available standalone.



- **[VMware Workspace ONE](https://www.vmware.com/products/workspace-one.html)**  

  Enterprise UEM platform (now part of Omnissa) with unified endpoint management, virtual desktop integration, and Zero Trust access. Supports all major OS platforms with strong automation and analytics capabilities.



- **[Ivanti (MobileIron)](https://www.ivanti.com/)**  

  UEM and security platform with mobile threat defense, zero-trust access, and unified endpoint management. Popular in regulated industries.



- **[Jamf Pro](https://www.jamf.com/products/jamf-pro/)**  

  The standard for Apple device management in enterprise. Manages macOS, iOS, iPadOS, tvOS, and watchOS with zero-touch enrollment, configuration profiles, and app deployment. Cloud-only (on-premises deprecated) .



- **[ManageEngine Endpoint Central](https://www.manageengine.com/products/desktop-central/)**  

  Unified endpoint management and security platform with patch management, software deployment, asset tracking, and remote control. Supports Windows, macOS, Linux, iOS, and Android.



- **[IBM Security MaaS360](https://www.ibm.com/products/maas360)**  

  Cloud-based UEM with AI-powered threat management, mobile threat defense, and integrated security analytics.



- **[Citrix Endpoint Management](https://www.citrix.com/)**  

  UEM integrated with Citrix Workspace for unified app and device management with microapp support.



- **[SOTI MobiControl](https://soti.net/products/soti-mobicontrol/)**  

  Enterprise mobility management with strong IoT and ruggedized device support for logistics, retail, and field service.



- **[Hexnode UEM](https://www.hexnode.com/)**  

  Unified endpoint management platform with broad OS support, kiosk mode, and remote troubleshooting at accessible pricing.



- **[Cisco Meraki Systems Manager](https://meraki.cisco.com/)**  

  Cloud-managed UEM integrated with Meraki networking. Strong for organizations already using Meraki infrastructure.



## Open-Source GitHub Projects



- **[Fleet](https://github.com/fleetdm/fleet)**  

  **The leading open-source UEM platform**, used in production by Stripe, Netflix, Fastly, Uber, and Reddit . MIT licensed (majority of code) with a commercial license for paid features . **Manages macOS, Windows, Linux, ChromeOS, iOS, and Android from one console** . Features **GitOps-native management** — configuration lives in YAML, changes go through pull requests, and CI/CD validates deployments . Includes built-in **vulnerability detection** with CVE data and CISA KEV/EPSS scoring, **file integrity monitoring**, and **near real-time device state reporting** (vs. Jamf's 5-60 minute intervals) . Software management with a maintained app catalog (Chrome, Office, Firefox, Slack, Zoom) and self-service portal . **Scope transparency** — end users can see exactly what data is collected via Fleet Desktop . Self-hosted on-premises, cloud, or air-gapped environments . **The de facto open-source Intune/Jamf alternative** — used by organizations managing 400,000+ devices .



- **[OpenUEM](https://github.com/open-uem/openuem-console)**  

  **Clean, modern open-source UEM from Spain**, Apache-2.0 licensed, recognized with a SourceForge Rising Star award in January 2026 . Go-based with a web console and agents for **Windows, Linux, and macOS** . **Designed from the ground up to be easily installed** with a focus on a clean and concise interface . Active development with 22 repositories including console, agents, workers, and certificate manager . **The best choice for organizations wanting a lightweight, European-sovereign UEM alternative**.



- **[Tactical RMM](https://github.com/amidaware/tacticalrmm)**  

  **Open-source remote monitoring and management platform** with 4,100+ GitHub stars, built with Django, Vue, and Go . Uses a Go agent and integrates with **MeshCentral** for remote desktop . Features TeamViewer-like remote control, real-time remote shell, file browser, Windows Registry Editor, remote script execution (bash, PowerShell, Python, batch), event log viewer, services management, **Windows patch management**, automated checks with alerting, task runner for scheduled scripts, **Chocolatey-based software installation**, and hardware/software inventory . Supports Windows 7 through Server 2025, any systemd Linux distro, and 64-bit Intel/Apple Silicon macOS . **Best for IT teams wanting RMM capabilities with UEM** — not a pure MDM.



- **[Headwind MDM](https://github.com/h-mdm/hmdm-server)**  

  **The leading open-source Android MDM**, Apache-2.0 licensed with an open-core model . **Android-only** — manages corporate Android devices with a web panel and Android launcher . Features kiosk mode, app management, configuration policies, and API integration . Supports integration with **custom Android ROMs (AOSP)** — critical for startups developing custom Android devices . **The best choice for Android-only fleets** or organizations needing deep Android customization. **Note**: paid commercial support and enterprise features available .



- **[MicroMDM / NanoMDM](https://github.com/micromdm/nanomdm)**  

  **Open-source Apple MDM servers** for macOS and iOS device management. MicroMDM (2,539 GitHub stars) is the original, now in **maintenance mode** . **NanoMDM** is the actively developed minimalist successor (484 stars), heavily inspired by MicroMDM but designed for simplicity and composability . **NanoHUB** unifies NanoMDM, NanoCMD, and KMFDDM into a single MDM server . **Best for Apple-focused environments** wanting full control over MDM infrastructure without vendor dependencies.



- **[GLPI](https://github.com/glpi-project/glpi)**  

  **Open-source IT Asset Management (ITAM) and service desk platform** with UEM capabilities through plugins . Tracks hardware, software, and licenses across the organization. Plugin ecosystem extends to device management and remote control. **Best for organizations wanting integrated asset management with service desk** rather than pure UEM.



### Additional Strong Open-Source Options



- **TheOpenEM** — Open-source endpoint management platform for OS deployment, software deployment, and remote control. Often recommended as a free alternative to commercial cloning and deployment tools .

- **RustDesk** — Open-source remote desktop alternative to TeamViewer with self-hosted server option, P2P connections, and end-to-end encryption . **Not a UEM** but essential for remote support workflows.

- **Wazuh** — Open-source security platform for endpoint detection and response (EDR), file integrity monitoring, vulnerability detection, and log analysis . Complements UEM with security visibility.

- **MeshCentral** — Open-source web-based remote management platform for remote desktop, terminal, and file management across all OS platforms. Integrated with Tactical RMM .



**Frameworks for building custom UEM solutions**: Combine **Fleet** for comprehensive multi-platform device management with GitOps workflows and built-in vulnerability detection . Use **OpenUEM** for a clean, lightweight European alternative with easy installation . Deploy **Tactical RMM** for Windows/Linux/Mac fleets needing RMM with remote control and patch management . Choose **Headwind MDM** for Android-only fleets or custom AOSP integration . For Apple-only environments, **NanoMDM/NanoHUB** provides the minimalist MDM server foundation . Integrate **Wazuh** for security monitoring and **RustDesk** or **MeshCentral** for remote support . **Critical consideration**: Open-source UEM requires self-hosting, certificate management (especially annual Apple push certificate renewal), and security patch responsibility . For small IT teams without operational capacity, commercial solutions with support SLAs may have lower total cost .



## How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- UEM platforms have broad access to sensitive device data including location, installed software, and potentially personal information on BYOD devices. Self-hosted solutions require proper security hardening, access controls, and compliance with data privacy regulations (GDPR, CCPA).

- **Open-source UEM requires significant operational responsibility** — server management, certificate renewal (especially Apple's annual push certificate), security patches, and updates . The license is free; the operations are not.

- **BYOD enrollment** requires careful consideration of privacy boundaries. Fleet and other platforms support work profile/work account separation for Android and account-based user enrollment for Apple devices .

- The open-source ecosystem provides strong device management, vulnerability detection, and GitOps foundations, but enterprise support, managed SLAs, and advanced threat detection (MTD) remain primarily commercial offerings.



---



**Made for IT administrators, security engineers, and endpoint management professionals.**

Let's make unified endpoint management more open, transparent, and manageable.
