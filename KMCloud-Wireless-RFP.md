# REQUEST FOR PROPOSAL (RFP)
## Wireless Infrastructure Deployment

**Document Number:** RFP-KMC-2025-001  
**Issue Date:** November 20, 2025  
**Submission Deadline:** December 15, 2025, 5:00 PM CST  
**Issued By:** KMCloud Solutions Inc.

---

## TABLE OF CONTENTS
1. [About KMCloud](#1-about-kmcloud)
2. [Project Overview](#2-project-overview)
3. [Project Scope](#3-project-scope)
4. [Technical Requirements](#4-technical-requirements)
5. [Vendor Qualifications](#5-vendor-qualifications)
6. [Evaluation Criteria](#6-evaluation-criteria)
7. [Proposal Submission Guidelines](#7-proposal-submission-guidelines)
8. [Terms and Conditions](#8-terms-and-conditions)
9. [Contact Information](#9-contact-information)
10. [Appendices](#appendices)

---

## 1. ABOUT KMCLOUD

### 1.1 Company Background
KMCloud Solutions Inc. is a leading cloud infrastructure and IT solutions provider specializing in AWS-based enterprise solutions. Founded in 2020, we deliver scalable, secure, and innovative cloud services to businesses across North America. Our core services include:

- Cloud migration and architecture design
- DevOps automation and CI/CD pipeline implementation
- Cloud security and compliance solutions
- Managed AWS services and 24/7 support
- Infrastructure as Code (IaC) development

With a team of 125 cloud engineers, DevOps specialists, and solutions architects, KMCloud has successfully deployed over 200 cloud infrastructure projects for clients in healthcare, finance, retail, and technology sectors.

### 1.2 Current IT Infrastructure
KMCloud's internal operations are powered by AWS cloud platform:

**Cloud Infrastructure:**
- AWS VPC with multi-region deployment
- EC2, ECS, and Lambda for compute workloads
- RDS and DynamoDB for database services
- S3 for object storage and backups
- CloudFront CDN for content delivery
- AWS Direct Connect for dedicated connectivity

**On-Premises Infrastructure:**
- Dual Cisco Catalyst switches (Core Layer)
- Managed Gigabit Ethernet wired network
- Fortinet FortiGate firewall appliances
- Dell PowerEdge servers for local development/testing
- Existing wireless network (802.11n/ac) - outdated and insufficient

**Office Locations:**
- **Building A (Main Office):** 3 floors, 15,000 sq ft, 75 employees
- **Building B (Development Center):** 2 floors, 10,000 sq ft, 50 employees

### 1.3 Need for Wireless Infrastructure Upgrade

KMCloud's current wireless infrastructure is outdated and no longer meets the demands of our growing operations. The existing 802.11ac network deployed in 2021 faces critical limitations:

**Current Challenges:**
- **Insufficient Coverage:** Dead zones in conference rooms, break areas, and building corners result in frequent connectivity drops
- **Capacity Constraints:** Existing access points struggle to support 125+ concurrent devices (laptops, tablets, smartphones, IoT sensors)
- **Performance Bottlenecks:** Bandwidth congestion during peak hours impacts video conferencing, cloud application performance, and large file transfers to AWS S3
- **Security Vulnerabilities:** Lack of WPA3 support and outdated security protocols expose our network to potential breaches
- **Management Complexity:** Standalone access points with no centralized management system increase administrative overhead
- **Business Growth:** Planned hiring of 40 additional employees in Q1 2026 will further strain the existing infrastructure

**Business Impact:**
- Reduced employee productivity due to unreliable connectivity
- Poor client experience during on-site meetings and demonstrations
- Inability to support modern collaboration tools (Zoom, Microsoft Teams, AWS WorkSpaces)
- Compliance risks with inadequate network security controls
- Increased IT support tickets (average 15-20 Wi-Fi issues per week)

**Strategic Objectives:**
KMCloud requires an enterprise-grade wireless infrastructure that:
- Aligns with our commitment to cutting-edge technology
- Supports our AWS-centric operations and remote collaboration
- Scales seamlessly with our rapid business growth
- Provides robust security to protect client data and intellectual property
- Delivers exceptional performance for cloud-based workflows

---

## 2. PROJECT OVERVIEW

### 2.1 Project Purpose
KMCloud Solutions Inc. is seeking qualified vendors to design, deploy, and maintain a state-of-the-art wireless network infrastructure across our two office buildings. The goal is to provide seamless, secure, and high-performance Wi-Fi connectivity that supports our cloud-first operations and enhances employee productivity.

### 2.2 Project Goals
- Deploy enterprise-grade wireless network with 100% coverage across 25,000 sq ft
- Support minimum 200 concurrent users with room for 50% growth
- Achieve 99.9% uptime SLA for wireless services
- Implement robust security controls aligned with SOC 2 and ISO 27001 standards
- Enable centralized network management and monitoring
- Provide seamless roaming between access points and buildings

### 2.3 Project Timeline

| Phase | Activity | Duration | Target Completion |
|-------|----------|----------|-------------------|
| RFP Process | Proposal submission & evaluation | 4 weeks | December 20, 2025 |
| Planning | Kickoff meeting & site survey | 2-3 weeks | January 17, 2026 |
| Procurement | Equipment ordering & delivery | 2-3 weeks | February 7, 2026 |
| Deployment | Installation & configuration | 4-6 weeks | March 21, 2026 |
| Testing | Performance validation & optimization | 2 weeks | April 4, 2026 |
| Training | Staff training & documentation handover | 1 week | April 11, 2026 |
| Go-Live | Full production deployment | - | April 30, 2026 |

---

## 3. PROJECT SCOPE

### 3.1 Objectives
The primary objectives of this wireless infrastructure deployment are:

1. **Complete Coverage:** Provide seamless Wi-Fi coverage throughout both buildings, including offices, conference rooms, common areas, parking lots, and outdoor spaces
2. **High Performance:** Deliver consistent high-speed connectivity (minimum 500 Mbps per AP) to support cloud-based applications, video conferencing, and large data transfers
3. **Scalability:** Design infrastructure to accommodate 50% user growth over the next 3 years
4. **Security:** Implement enterprise-grade security controls including WPA3, network segmentation, and guest network isolation
5. **Reliability:** Achieve 99.9% wireless network uptime with redundancy and failover capabilities
6. **Centralized Management:** Deploy cloud-based or on-premises wireless controller for unified management and monitoring

### 3.2 Scope of Work

#### 3.2.1 Site Survey and Planning
The vendor must conduct a comprehensive site survey to determine optimal wireless design:

- **RF Site Survey:** Perform predictive and on-site validation survey using professional tools (e.g., Ekahau, AirMagnet)
- **Coverage Analysis:** Identify optimal access point locations for maximum coverage and minimal interference
- **Capacity Planning:** Calculate required AP density based on user count, device types, and application bandwidth requirements
- **Interference Assessment:** Analyze existing 2.4 GHz and 5 GHz spectrum for neighboring Wi-Fi networks and non-Wi-Fi interference sources
- **Heat Maps:** Provide detailed heat maps showing signal strength, channel utilization, and coverage overlap
- **Network Design Document:** Deliver comprehensive design documentation including:
  - AP placement diagrams (floor plans with exact mounting locations)
  - Channel and power allocation plan
  - IP addressing scheme and VLAN design
  - Network topology diagram
  - Cable routing paths and infrastructure requirements

#### 3.2.2 Installation and Configuration
The vendor must install, configure, and optimize the wireless infrastructure:

**Hardware Installation:**
- Mount and install all wireless access points per design specifications
- Install wireless LAN controller (physical or virtual appliance)
- Deploy network switches if required for AP connectivity
- Install PoE injectors or PoE+ switches as needed
- Run and terminate CAT6A Ethernet cabling (if not existing)
- Install outdoor-rated APs for parking lot and outdoor coverage
- Perform cable testing and certification (Fluke or equivalent)

**Configuration and Integration:**
- Configure wireless controller with SSIDs, security policies, and VLANs
- Integrate with existing Cisco switch infrastructure and Fortinet firewall
- Configure WPA3-Enterprise with RADIUS authentication (integrate with existing Active Directory or propose solution)
- Set up guest network with captive portal and bandwidth throttling
- Implement network segmentation: Corporate, Guest, IoT, Management VLANs
- Configure QoS policies to prioritize business-critical applications (VoIP, video conferencing)
- Enable wireless intrusion prevention system (WIPS) and rogue AP detection
- Configure load balancing and band steering (5 GHz preference)
- Implement automatic channel and power optimization (RRM - Radio Resource Management)

**Testing and Optimization:**
- Conduct post-installation site survey to validate coverage and performance
- Perform throughput testing from multiple locations (iPerf or similar tools)
- Test roaming performance between APs (seamless handoff)
- Verify security controls (WPA3, MAC filtering, guest isolation)
- Optimize AP power levels and channel assignments
- Document final configuration and "as-built" network diagrams

#### 3.2.3 Integration with Existing Network
The wireless infrastructure must seamlessly integrate with KMCloud's existing network:

- **Switch Integration:** Connect access points to existing Cisco Catalyst core switches via trunk ports supporting multiple VLANs
- **Firewall Integration:** Configure firewall rules on Fortinet FortiGate to control wireless traffic and enable guest internet-only access
- **Active Directory Integration:** Enable 802.1X authentication using existing AD infrastructure for corporate SSID
- **DHCP Services:** Configure DHCP scopes on existing infrastructure or wireless controller
- **DNS Integration:** Ensure wireless clients receive proper DNS configuration
- **Monitoring Integration:** Integrate wireless infrastructure with existing monitoring tools (SNMP, Syslog)
- **Backup Integration:** Configure automated backups of wireless controller configuration
- **AWS Connectivity:** Ensure wireless network provides optimized connectivity to AWS Direct Connect link

#### 3.2.4 Ongoing Maintenance and Support
The vendor must provide comprehensive post-deployment support:

**Maintenance Services (12-month initial contract):**
- 24/7 technical support with guaranteed response times:
  - Critical issues (complete outage): 1-hour response, 4-hour resolution
  - High priority (degraded performance): 4-hour response, 8-hour resolution
  - Medium/Low priority: 8-hour response, 24-hour resolution
- Quarterly on-site health checks and optimization
- Firmware updates and patch management (during maintenance windows)
- Wireless controller backup verification (weekly)
- Performance monitoring and reporting (monthly reports)
- Proactive capacity planning and recommendations
- Annual site survey validation

**Support Deliverables:**
- Dedicated support ticket system and escalation procedures
- Monthly performance reports including:
  - Uptime statistics
  - Top bandwidth consumers
  - Client connection statistics
  - Rogue AP detections
  - Security incident summary
- Knowledge base and troubleshooting documentation
- Remote access for troubleshooting (secure VPN or controller access)

### 3.3 Deliverables

The vendor must provide the following deliverables upon project completion:

| Deliverable | Description | Due Date |
|-------------|-------------|----------|
| Site Survey Report | Comprehensive RF survey with heat maps, AP placement, and design rationale | End of Planning Phase |
| Network Design Document | Detailed technical design including diagrams, configurations, and IP schemes | End of Planning Phase |
| Equipment List | Bill of materials with part numbers, quantities, and pricing | End of Planning Phase |
| Installation Plan | Detailed installation schedule with milestones and resource allocation | Start of Deployment Phase |
| As-Built Documentation | Final network diagrams, configurations, and cable documentation | End of Deployment Phase |
| Test Reports | Coverage validation, throughput tests, and security audit results | End of Testing Phase |
| Configuration Backups | Complete backup of all device configurations (controller, APs, switches) | End of Testing Phase |
| Admin Training | On-site training for KMCloud IT staff (minimum 8 hours) | Training Phase |
| User Guide | End-user documentation for connecting to corporate and guest Wi-Fi | Training Phase |
| Support Runbook | Troubleshooting guide and escalation procedures for IT staff | Training Phase |
| Warranty Documentation | All equipment warranties and support entitlements | Handover |
| Monthly Reports | Performance and health monitoring reports | Ongoing (Monthly) |

---

## 4. TECHNICAL REQUIREMENTS

### 4.1 Coverage Requirements

**Building A (Main Office) - 3 Floors:**
- **Floor 1 (5,000 sq ft):** Reception area, 2 conference rooms, open workspace (25 employees), break room, server room
  - Required Coverage: 100% indoor coverage including all rooms and corridors
  - Outdoor: Front entrance and parking lot (50 ft radius)
  
- **Floor 2 (5,000 sq ft):** Executive offices, 3 meeting rooms, collaboration spaces (25 employees)
  - Required Coverage: 100% indoor coverage with enhanced signal in meeting rooms
  
- **Floor 3 (5,000 sq ft):** Open workspace (25 employees), training room, storage
  - Required Coverage: 100% indoor coverage

**Building B (Development Center) - 2 Floors:**
- **Floor 1 (5,000 sq ft):** Development labs, testing area, collaboration spaces (25 employees)
  - Required Coverage: 100% indoor coverage with high-density support for labs
  
- **Floor 2 (5,000 sq ft):** Open workspace (25 employees), training room, break area
  - Required Coverage: 100% indoor coverage

**Additional Coverage Areas:**
- Outdoor areas: Parking lots, building entrances, courtyard
- Estimated coverage area: Additional 5,000 sq ft outdoor

**Coverage Standards:**
- Minimum signal strength: -67 dBm for data, -65 dBm for VoIP
- Signal-to-Noise Ratio (SNR): Minimum 25 dB
- Channel overlap: Maximum 10% co-channel interference
- Seamless roaming with <50ms handoff time

### 4.2 Wireless Standards and Technology

**Required Standards:**
- **Wi-Fi 6 (802.11ax):** Mandatory for all access points
  - Support for both 2.4 GHz and 5 GHz bands
  - OFDMA and MU-MIMO support
  - Target Wake Time (TWT) for IoT device efficiency
  - 1024-QAM modulation
  - Minimum 2x2:2 MIMO, prefer 4x4:4 MIMO for high-density areas

**Performance Requirements:**
- Per-AP throughput: Minimum 1.2 Gbps aggregate (5 GHz)
- Client throughput: Minimum 500 Mbps per client (ideal conditions)
- Concurrent client capacity: Minimum 50 clients per AP
- Uplink connectivity: Gigabit Ethernet minimum (10 Gbps preferred for controller)

**Advanced Features (Preferred):**
- Wi-Fi 6E support (6 GHz band) - optional but preferred
- Bluetooth Low Energy (BLE) for location services - optional
- IoT sensor integration (temperature, occupancy) - optional

### 4.3 Security Requirements

KMCloud requires enterprise-grade security controls to protect sensitive data and comply with SOC 2 and ISO 27001 standards.

#### 4.3.1 Authentication and Encryption
**Corporate SSID (Employees):**
- **WPA3-Enterprise** mandatory with 802.1X authentication
- RADIUS integration with existing Active Directory or propose RADIUS solution
- AES-256 encryption
- Per-user unique encryption keys (MPSK or certificate-based)
- Support for Windows, macOS, iOS, Android devices

**Guest SSID (Visitors):**
- **WPA3-Personal** or WPA2-Personal with strong passphrase (rotated monthly)
- Captive portal with terms of service acceptance
- Self-registration or sponsor approval workflow
- Guest isolation (clients cannot see each other)
- Bandwidth throttling: Maximum 10 Mbps per guest

**IoT SSID (Optional):**
- WPA2-Enterprise with pre-shared keys or MAC authentication
- Isolated VLAN with restricted internet-only access
- Device whitelisting (MAC address filtering)

#### 4.3.2 Network Segmentation
**VLAN Design:**
- **Corporate VLAN:** Full network access with firewall rules
- **Guest VLAN:** Internet-only access, isolated from corporate network
- **IoT VLAN:** Restricted access for sensors and devices
- **Management VLAN:** Isolated VLAN for AP and controller management

**Firewall Integration:**
- Configure Fortinet FortiGate rules to control inter-VLAN traffic
- Block guest-to-corporate network access
- Allow corporate-to-AWS Direct Connect traffic

#### 4.3.3 Threat Protection
**Required Security Features:**
- **Wireless Intrusion Prevention System (WIPS):**
  - Rogue AP detection and alerting
  - Honeypot AP detection
  - Evil twin attack prevention
  - De-authentication attack mitigation
  
- **MAC Address Filtering:**
  - Corporate SSID: Whitelist approved devices (optional, combined with 802.1X)
  - IoT SSID: Whitelist only (mandatory)
  
- **Rate Limiting and DDoS Protection:**
  - Per-client bandwidth limits
  - Broadcast/multicast storm control
  - Protection against Wi-Fi deauthentication floods
  
- **Encryption and Privacy:**
  - Management frame protection (802.11w)
  - Opportunistic Wireless Encryption (OWE) for open networks
  - IPv6 support with security controls

#### 4.3.4 Compliance Requirements
- **Logging and Auditing:** Syslog integration for all authentication attempts, security events, and configuration changes
- **Data Retention:** Minimum 90 days log retention for compliance audits
- **PCI DSS Considerations:** Network segmentation to isolate payment systems (if applicable)

### 4.4 Capacity and Performance Requirements

**User Capacity:**
- **Current Users:** 125 employees + 20 guests (peak)
- **Projected Growth:** 50% increase over 3 years (185 employees + 30 guests)
- **Device Density:** Average 2.5 devices per user (laptop, phone, tablet)
- **Total Concurrent Devices:** 200+ devices (current), 300+ devices (future)

**High-Density Areas:**
- Training room (Building A, Floor 3): Support 40 users simultaneously
- Conference rooms: Support 20 users per room
- Development labs (Building B, Floor 1): Support 50+ devices

**Bandwidth Requirements:**
- **Per-User Bandwidth:** Minimum 50 Mbps average, 100 Mbps peak
- **Application Requirements:**
  - Video conferencing (Zoom, Teams): 5-10 Mbps per user
  - Cloud applications (AWS WorkSpaces, Salesforce): 10-20 Mbps per user
  - Large file transfers to AWS S3: 100+ Mbps
  - VoIP calls: 100 Kbps per call (G.711 codec)

**Quality of Service (QoS):**
- Prioritize voice and video traffic (DSCP marking)
- Guarantee minimum bandwidth for business-critical applications
- Traffic shaping for guest network (limit to 20% of total bandwidth)

**Performance Benchmarks:**
- Network latency: <20ms to gateway
- Packet loss: <0.5%
- Jitter: <30ms for VoIP
- Throughput: Minimum 500 Mbps per client (ideal conditions)

### 4.5 Network Management and Monitoring

**Controller Requirements:**
- **Centralized Management:** Single pane of glass for all access points
- **Deployment Options:** Cloud-based controller preferred, on-premises acceptable
- **Scalability:** Support minimum 100 APs for future expansion
- **High Availability:** Redundant controllers or failover capability (preferred)

**Management Features:**
- Web-based GUI and CLI access
- Role-based access control (RBAC) for administrators
- Configuration templates and bulk provisioning
- Automated firmware updates with scheduling
- Zero-touch provisioning for new APs
- Backup and restore functionality (automated daily backups)

**Monitoring and Alerting:**
- **Real-Time Monitoring:**
  - Live client connection status and signal strength
  - Per-AP bandwidth utilization and throughput
  - Channel utilization and interference detection
  - Rogue AP detection and security alerts
  
- **Historical Reporting:**
  - Client connection trends (daily, weekly, monthly)
  - Top bandwidth consumers
  - Application usage statistics
  - Uptime and availability reports
  
- **Alerting:**
  - Email/SMS alerts for critical issues (AP down, high interference, security events)
  - SNMP traps for integration with existing monitoring tools
  - Syslog forwarding to centralized log server

**Network Analytics (Preferred):**
- Client location tracking (BLE or RF-based)
- Occupancy analytics for space utilization
- Predictive analytics for capacity planning
- Application performance monitoring (APM)

### 4.6 Hardware and Equipment Specifications

**Access Point Specifications:**
- **Wi-Fi Standard:** 802.11ax (Wi-Fi 6) certified
- **Radio Configuration:** Dual-band (2.4 GHz + 5 GHz) simultaneous operation
- **MIMO:** Minimum 2x2:2, prefer 4x4:4 for high-density areas
- **Power:** 802.3at (PoE+) or 802.3bt (PoE++) support
- **Mounting:** Ceiling-mount (indoor), wall-mount (optional), outdoor-rated (IP67) for external areas
- **Security:** TPM chip for secure boot and configuration encryption

**Controller Specifications:**
- **Form Factor:** Virtual appliance (VMware/Hyper-V), cloud-hosted, or physical appliance
- **Capacity:** Support minimum 100 APs
- **Redundancy:** Active-standby or active-active clustering (preferred)
- **Licensing:** Perpetual or subscription-based acceptable

**Network Switches (if required):**
- Gigabit Ethernet with PoE+ support (802.3at minimum)
- Stacking capability for redundancy
- Layer 3 routing (if required for VLAN routing)

**Additional Equipment:**
- PoE injectors (if existing switches lack PoE)
- UPS backup for controller and core switches
- Cabling: CAT6A or better (if new runs required)

**Preferred Vendors (not mandatory):**
- Cisco (Catalyst, Meraki)
- Aruba (Instant On, Central)
- Juniper Mist
- Ruckus (CommScope)
- Ubiquiti UniFi (for budget-conscious option)

*Vendors may propose alternative solutions with justification.*

### 4.7 Environmental and Physical Requirements

**Indoor APs:**
- Operating temperature: 0°C to 40°C
- Humidity: 10% to 90% non-condensing
- Mounting: Standard drop-ceiling T-bar or hard-ceiling mount

**Outdoor APs:**
- IP67 or IP68 rated (weather-resistant)
- Operating temperature: -40°C to 55°C
- Surge protection: Built-in lightning arrestor

**Power Requirements:**
- PoE+ (802.3at) minimum, 30W per AP
- Total power budget calculation required
- UPS backup for core infrastructure (4-hour runtime minimum)

**Cabling Requirements:**
- CAT6A cabling for all new runs (support 10 Gbps)
- Maximum cable length: 100 meters per 802.3 standards
- Cable testing and certification required (Fluke DTX or equivalent)

---

## 5. VENDOR QUALIFICATIONS

### 5.1 Experience Requirements

**Minimum Qualifications:**
- **Experience:** Minimum 3 years of enterprise wireless network deployments
- **Project Portfolio:** Provide detailed case studies of at least 3 similar projects including:
  - Client name (or anonymized reference)
  - Project scope and scale (number of APs, coverage area, user count)
  - Technologies deployed (vendor, controller platform, wireless standards)
  - Timeline and budget
  - Challenges faced and solutions implemented
  - Client testimonial or reference contact

**Preferred Experience:**
- Multi-building or campus-wide wireless deployments
- Integration with Cisco switching and Fortinet firewall infrastructure
- Wi-Fi 6 and WPA3 deployment experience
- Cloud-based wireless controller implementations
- Healthcare, finance, or technology industry experience (SOC 2, ISO 27001 familiarity)

### 5.2 Certifications and Technical Expertise

**Required Certifications (at least one team member must hold):**
- Cisco Certified Network Associate Wireless (CCNA Wireless) or higher
- Aruba Certified Mobility Professional (ACMP) or higher
- Certified Wireless Network Administrator (CWNA) by CWNP
- Juniper Mist Wireless Professional (if proposing Juniper)
- Ruckus Wireless Certification (if proposing Ruckus)

**Preferred Certifications:**
- Cisco Certified Network Professional Enterprise (CCNP) or Wireless (CCNP Wireless)
- Aruba Certified Mobility Expert (ACMX)
- Certified Wireless Design Professional (CWDP) by CWNP
- Certified Wireless Security Professional (CWSP) by CWNP
- Fortinet NSE4 or higher (for firewall integration)
- Ekahau Certified Survey Engineer (ECSE)

**Technical Expertise:**
Vendors must demonstrate expertise in:
- RF site survey tools (Ekahau, AirMagnet, or equivalent)
- Wireless controller configuration and optimization
- 802.1X and RADIUS authentication
- VLAN design and network segmentation
- Firewall rule configuration (Fortinet preferred)
- Active Directory integration
- Cable installation and termination (CAT6A certification)
- Structured cabling standards (ANSI/TIA-568)

### 5.3 Licensing and Insurance

**Required Licenses:**
- Valid business license in the City of Winnipeg
- Low voltage contractor license (if applicable)
- Structured cabling installer certification

**Insurance Requirements:**
- General Liability Insurance: Minimum $2,000,000 coverage
- Professional Liability/Errors & Omissions: Minimum $1,000,000 coverage
- Workers' Compensation: As required by law
- Proof of insurance must be provided with proposal

### 5.4 References

**Vendor must provide at least 3 references from previous clients:**
- Client name and contact information (name, title, phone, email)
- Project description and scope
- Project completion date
- Reference relationship to vendor (client, partner, etc.)

**Reference Requirements:**
- Projects completed within the last 3 years
- Similar scope and scale (enterprise wireless deployment, 50+ APs)
- Technology relevance (Wi-Fi 6, enterprise controller platforms)

KMCloud reserves the right to contact references and conduct additional due diligence.

### 5.5 Financial Stability

Vendors must demonstrate financial stability:
- Provide Dun & Bradstreet (D&B) number or business credit report
- Bank reference letter (optional)
- Proof of financial capability to complete the project

---

## 6. EVALUATION CRITERIA

KMCloud will evaluate proposals based on the following weighted criteria:

### 6.1 Cost (30%)

**Cost Components to be Evaluated:**
- **Initial Deployment Costs:**
  - Hardware costs (APs, controller, switches, cabling)
  - Software licenses (controller, management platform)
  - Professional services (site survey, installation, configuration)
  - Project management and coordination
  - Testing and optimization
  - Training and documentation
  
- **Ongoing Maintenance Costs (Year 1):**
  - Annual support and maintenance contract
  - Software subscriptions (if applicable)
  - Warranty and hardware replacement
  - On-site support visits (quarterly health checks)
  - 24/7 helpdesk support
  
- **Total Cost of Ownership (3 Years):**
  - Provide 3-year TCO breakdown including maintenance renewals
  - Potential upgrade costs or scalability investments

**Cost Submission Requirements:**
- Itemized bill of materials with part numbers and unit costs
- Labor costs broken down by phase (survey, installation, configuration, testing)
- Travel and expenses (if applicable)
- Payment terms and schedule (e.g., 30% deposit, 40% at installation, 30% at completion)
- Warranty terms and coverage (hardware, labor)
- Clearly identify any assumptions or exclusions

**Evaluation Criteria:**
- Competitiveness of pricing
- Value for money (balance of cost vs. features)
- Transparency and completeness of cost breakdown
- Favorable payment terms

**Note:** KMCloud is open to competitive proposals. Cost is important but not the sole deciding factor. The vendor providing the best overall value will be selected.

### 6.2 Technical Approach (30%)

**Technical Solution Evaluation:**
- **Design Quality:**
  - Thoroughness of proposed network design
  - Justification for AP placement and density
  - RF engineering methodology (site survey tools, channel planning)
  - Scalability and future-proofing (support for growth)
  
- **Technology Selection:**
  - Appropriateness of proposed hardware (AP models, controller platform)
  - Wi-Fi 6 features and capabilities
  - Security features and compliance alignment (WPA3, WIPS, segmentation)
  - Management platform capabilities (monitoring, reporting, analytics)
  
- **Integration Approach:**
  - Plan for integrating with existing Cisco switches and Fortinet firewall
  - Active Directory and RADIUS integration strategy
  - VLAN design and firewall rule recommendations
  - Backup and disaster recovery approach
  
- **Innovation and Value-Add:**
  - Advanced features (location analytics, AI-driven optimization, etc.)
  - Automation and zero-touch provisioning
  - Client experience enhancements (seamless roaming, fast onboarding)
  - Unique differentiators and competitive advantages

**Implementation Methodology:**
- Detailed project plan with clear phases and milestones
- Risk mitigation strategies
- Change management and communication plan
- Quality assurance and testing procedures
- Rollback plan in case of deployment issues

**Support and Maintenance Plan:**
- 24/7 support structure and escalation procedures
- Response and resolution SLAs
- Proactive monitoring and alerting
- Firmware update and patch management process
- Quarterly health check and optimization activities

### 6.3 Timeline (20%)

**Project Schedule Evaluation:**
- **Realistic Timeline:**
  - Achievable milestones aligned with KMCloud's target completion (April 30, 2026)
  - Adequate time allocation for each phase (survey, installation, testing)
  - Buffer for contingencies and unexpected delays
  
- **Speed to Deployment:**
  - Faster deployment is advantageous (within reason)
  - Early completion bonuses may be considered
  
- **Minimize Business Disruption:**
  - Installation schedule that minimizes impact on daily operations
  - Off-hours or weekend work plan (if necessary)
  - Phased rollout approach (e.g., Building A first, then Building B)
  
- **Key Milestones:**
  - Site survey completion
  - Equipment delivery
  - Installation and configuration milestones
  - Testing and optimization completion
  - Training and go-live date

**Timeline Submission Requirements:**
- Detailed Gantt chart or project schedule
- Dependencies and critical path analysis
- Resource allocation and team availability
- Contingency plans for delays (equipment shortages, weather, etc.)

### 6.4 Vendor Reputation and Qualifications (20%)

**Vendor Assessment:**
- **Company Reputation:**
  - Years in business and financial stability
  - Industry recognition and awards
  - Manufacturer partnerships and certifications (Cisco Gold Partner, Aruba Elite, etc.)
  - BBB rating or similar business reviews
  
- **Team Qualifications:**
  - Relevant certifications (CCNA Wireless, CWNA, ACMP, etc.)
  - Experience and expertise of proposed project team
  - Site survey engineer qualifications (ECSE preferred)
  - Availability of team throughout project lifecycle
  
- **Reference Quality:**
  - Positive feedback from reference checks
  - Similar project success stories
  - Long-term client relationships (repeat business indicator)
  
- **Local Presence:**
  - Proximity to KMCloud's office (for on-site support)
  - Local technicians available for urgent issues
  - Regional support infrastructure

**Compliance and Professionalism:**
- Insurance coverage adequacy
- Licensing and legal compliance
- Proposal quality (thoroughness, clarity, professionalism)
- Responsiveness during RFP process

---

## 7. PROPOSAL SUBMISSION GUIDELINES

### 7.1 Proposal Format and Structure

**Proposals must be submitted in the following format:**

**Executive Summary (2 pages maximum)**
- Overview of proposed solution
- Key differentiators and value proposition
- Total project cost summary
- High-level timeline

**Company Profile**
- Company background, history, and ownership
- Relevant experience and project portfolio
- Team qualifications and certifications
- Financial stability and references

**Technical Proposal**
- Proposed network design and architecture
- Equipment specifications and bill of materials
- Site survey methodology and tools
- Installation and configuration approach
- Integration plan with existing infrastructure
- Security implementation details
- Network management and monitoring solution
- Testing and optimization procedures

**Project Management Plan**
- Detailed project timeline (Gantt chart)
- Resource allocation and team roles
- Communication plan
- Risk management and mitigation strategies
- Quality assurance procedures
- Change management process

**Support and Maintenance Plan**
- 24/7 support structure and SLAs
- Escalation procedures
- Proactive maintenance activities
- Reporting and documentation
- Training plan for KMCloud IT staff

**Cost Proposal (separate sealed envelope or PDF)**
- Itemized bill of materials with part numbers and unit costs
- Labor costs by phase and activity
- Travel and expenses
- Year 1 maintenance and support costs
- 3-year total cost of ownership
- Payment terms and schedule
- Warranty and support entitlements

**Appendices**
- Company certifications and licenses
- Insurance certificates
- Reference letters or contact information
- Sample reports (site survey, monthly monitoring)
- Equipment datasheets and specifications
- Compliance documentation (if applicable)

### 7.2 Submission Requirements

**Format:**
- **Primary Format:** PDF (single or multiple files clearly labeled)
- **Optional:** Editable formats for diagrams (Visio, PowerPoint) as supplementary files
- **File Naming Convention:** `KMCloud_RFP_[VendorName]_[Section].pdf`
  - Example: `KMCloud_RFP_AcmeNetworks_TechnicalProposal.pdf`

**Submission Method:**
- **Email Submission (Preferred):** Send to kristine.bagsican@kmcloud.com
  - Subject Line: "RFP Submission - Wireless Infrastructure - [Vendor Name]"
  - Maximum email attachment size: 25 MB (use file sharing link if larger)
  
- **Physical Submission (Optional):**
  - Mail to: KMCloud Solutions Inc., Attn: Kristine Bagsican, IT Infrastructure Manager
  - Address: 360 Portage Avenue, Winnipeg, Manitoba R3C 0G8
  - Include USB drive with digital copy

**Deadline:**
- **Submission Deadline:** December 15, 2025, 5:00 PM Central Standard Time (CST)
- Late submissions will not be accepted unless prior arrangement is made

**Proposal Validity:**
- Proposals must remain valid for 90 days from submission deadline
- Pricing must be firm and not subject to change during evaluation period

### 7.3 Submission Checklist

Vendors must ensure the following are included in their proposal:

- [ ] Executive summary
- [ ] Company profile and background
- [ ] Technical proposal with network design
- [ ] Project management plan with timeline
- [ ] Support and maintenance plan
- [ ] Itemized cost proposal
- [ ] Proof of insurance (general liability, professional liability)
- [ ] Business license and contractor certifications
- [ ] Team certifications (CCNA Wireless, CWNA, etc.)
- [ ] At least 3 client references with contact information
- [ ] Equipment datasheets and specifications
- [ ] Sample deliverables (site survey report, monthly monitoring report)
- [ ] Signed RFP acknowledgment (confirming acceptance of terms)

### 7.4 Evaluation Process

**RFP Timeline:**

| Activity | Date |
|----------|------|
| RFP Issued | November 20, 2025 |
| Pre-Proposal Questions Due | November 29, 2025 |
| Answers to Questions Posted | December 2, 2025 |
| Proposal Submission Deadline | December 15, 2025, 5:00 PM CST |
| Proposal Evaluation | December 16-18, 2025 |
| Vendor Interviews/Demos (if required) | December 19-20, 2025 |
| Vendor Selection and Notification | December 20, 2025 |
| Contract Negotiation | December 23, 2025 - January 3, 2026 |
| Project Kickoff | January 6, 2026 |

**Evaluation Committee:**
- Kristine Bagsican, IT Infrastructure Manager (Lead)
- CTO (To Be Assigned)
- IT Security Manager (To Be Assigned)
- Network Administrator (To Be Assigned)
- Finance Manager (To Be Assigned, cost evaluation)

**Evaluation Process:**
1. **Initial Screening:** Verify completeness and compliance with RFP requirements
2. **Technical Evaluation:** Assess technical approach, design quality, and solution fit (30%)
3. **Cost Evaluation:** Analyze cost competitiveness and value for money (30%)
4. **Timeline Evaluation:** Review project schedule and feasibility (20%)
5. **Vendor Evaluation:** Check references, qualifications, and reputation (20%)
6. **Scoring and Ranking:** Calculate weighted scores and rank vendors
7. **Shortlisting:** Select top 2-3 vendors for interviews or demos (if needed)
8. **Final Selection:** Select winning vendor and begin contract negotiation

**Vendor Interviews/Demonstrations (if required):**
- Shortlisted vendors may be invited for on-site presentation or product demo
- 60-90 minute sessions to clarify technical approach and address questions
- Live demonstration of proposed wireless management platform (preferred)

**Notification:**
- All vendors will be notified of the selection outcome by December 20, 2025
- Winning vendor will receive award notification and contract draft
- Unsuccessful vendors may request debrief to understand decision rationale

### 7.5 Questions and Clarifications

**Pre-Proposal Questions:**
- Vendors may submit questions regarding the RFP by **November 29, 2025**
- Submit questions via email to kristine.bagsican@kmcloud.com
- Subject Line: "RFP Question - Wireless Infrastructure - [Vendor Name]"
- KMCloud will compile and respond to all questions by **December 2, 2025**
- Questions and answers will be shared with all registered vendors to ensure fairness

**Site Visit (Optional):**
- Vendors are encouraged to schedule a site visit to assess the office buildings
- Contact Kristine Bagsican at kristine.bagsican@kmcloud.com to arrange a visit
- Site visits must be completed by **December 10, 2025**
- NDA may be required for site visit access

**RFP Amendments:**
- KMCloud reserves the right to amend the RFP if necessary
- Any amendments will be communicated to all registered vendors
- Vendors must acknowledge receipt of amendments in their proposal

---

## 8. TERMS AND CONDITIONS

### 8.1 Contract Terms

**Contract Duration:**
- **Initial Term:** 12 months for maintenance and support (starting from project go-live date)
- **Renewal Option:** KMCloud reserves the right to renew the contract annually based on vendor performance
- **Automatic Renewal:** Contract will NOT auto-renew; explicit written renewal required
- **Early Termination:** KMCloud may terminate with 60 days written notice (with penalties as negotiated)

**Payment Terms:**
- **Deposit:** 30% upon contract signing
- **Milestone Payments:**
  - 20% upon completion of site survey and equipment delivery
  - 30% upon completion of installation and configuration
  - 20% upon successful testing and go-live
- **Final Payment:** Remaining balance due within 30 days of project completion and acceptance
- **Maintenance Payments:** Annual support contract paid quarterly in advance

**Acceptance Criteria:**
- Project will be considered complete upon successful validation of all deliverables
- Acceptance testing will include coverage validation, throughput testing, and security audit
- KMCloud reserves the right to withhold final payment until all acceptance criteria are met
- Any deficiencies must be remediated within 14 days at vendor's expense

**Warranty:**
- **Equipment Warranty:** Minimum 3 years manufacturer warranty on all hardware (APs, controller, switches)
- **Labor Warranty:** 1-year warranty on installation workmanship
- **Configuration Warranty:** 90 days warranty on configuration errors (vendor must fix at no cost)
- **Performance Guarantee:** 99.9% uptime SLA must be met during warranty period

### 8.2 Confidentiality and Non-Disclosure

**Confidential Information:**
- All information disclosed by KMCloud during the RFP process and project is confidential
- Vendors must sign a Non-Disclosure Agreement (NDA) before site visit or access to sensitive data
- Confidential information includes:
  - Network diagrams and infrastructure details
  - Security policies and configurations
  - Business operations and financial data
  - Client information and intellectual property

**Restrictions:**
- Vendors must not disclose KMCloud's confidential information to third parties
- Vendors must limit access to confidential information to personnel directly involved in the project
- Vendors must not use confidential information for any purpose other than fulfilling the contract
- Confidentiality obligations survive contract termination indefinitely

**Data Protection:**
- Vendors must comply with applicable data privacy laws (e.g., GDPR, PIPEDA)
- Personal data (employee names, devices) must be handled with strict confidentiality
- Vendors must not retain copies of KMCloud's data after project completion (except as required for support)

### 8.3 Legal Compliance and Liability

**Compliance Requirements:**
- Vendors must comply with all federal, state/provincial, and local laws and regulations
- Vendors must obtain all necessary permits and licenses for installation work
- Vendors must follow electrical codes and structured cabling standards (ANSI/TIA-568)
- Vendors must comply with OSHA safety standards during installation

**Liability and Indemnification:**
- Vendors must indemnify KMCloud against any claims arising from vendor's negligence or breach of contract
- Vendors are responsible for any damage to KMCloud's property or infrastructure during installation
- Vendors must carry adequate insurance (general liability, professional liability, workers' compensation)
- Limitation of liability terms will be negotiated in final contract

**Intellectual Property:**
- All deliverables (documentation, configurations, scripts) become property of KMCloud upon final payment
- Vendors retain ownership of proprietary tools and methodologies
- Open-source software licenses must be disclosed and compliant

**Dispute Resolution:**
- Good-faith negotiation is the first step for resolving disputes
- Mediation or arbitration may be required before litigation
- Governing law: Winnipeg, Manitoba, Canada

### 8.4 Performance Standards and SLAs

**Service Level Agreements (SLAs):**
- **Uptime SLA:** 99.9% wireless network availability (measured monthly)
  - Downtime excludes scheduled maintenance windows
  - Penalties for SLA breaches: 5% monthly fee credit per 0.1% below target
  
- **Support Response Times:**
  - Critical (complete outage): 1-hour response, 4-hour resolution
  - High priority (degraded performance): 4-hour response, 8-hour resolution
  - Medium/Low priority: 8-hour response, 24-hour resolution
  
- **Maintenance Windows:**
  - Scheduled maintenance: Sundays 2:00 AM - 6:00 AM CST
  - Emergency maintenance: With 24-hour notice (if possible)

**Performance Monitoring:**
- Vendor must provide monthly performance reports documenting SLA compliance
- KMCloud reserves the right to audit performance metrics
- Continuous SLA breaches (3 consecutive months) may result in contract termination

### 8.5 Right to Reject and Other Provisions

**KMCloud reserves the right to:**
- Reject any or all proposals without explanation
- Request clarifications or additional information from vendors
- Negotiate with one or more vendors simultaneously
- Award the contract to a vendor other than the lowest bidder
- Cancel or reissue the RFP at any time
- Modify the scope of work during contract negotiation

**No Obligation:**
- Issuance of this RFP does not commit KMCloud to award a contract
- KMCloud is not liable for any costs incurred by vendors in preparing proposals

**Proposal Ownership:**
- Submitted proposals become property of KMCloud (except proprietary vendor information)
- KMCloud may use proposal information for evaluation purposes only

**Conflict of Interest:**
- Vendors must disclose any potential conflicts of interest
- Vendors with prior business relationships with KMCloud must disclose details

**Ethics and Conduct:**
- Vendors must not offer gifts, bribes, or incentives to KMCloud employees
- Violations of ethical standards will result in immediate disqualification

---

## 9. CONTACT INFORMATION

### 9.1 Primary Contact

**Kristine Bagsican**  
IT Infrastructure Manager  
KMCloud Solutions Inc.

**Email:** kristine.bagsican@kmcloud.com  
**Phone:** (204) 607-0614  
**Office Address:**  
Building A, 1st Floor  
360 Portage Avenue  
Winnipeg, Manitoba, Canada  
R3C 0G8

**Office Hours:**  
Monday - Friday: 9:00 AM - 5:00 PM CST

### 9.2 Communication Guidelines

**For RFP Questions:**
- Email subject: "RFP Question - Wireless Infrastructure - [Vendor Name]"
- Submit questions by November 29, 2025
- Responses will be provided by December 2, 2025

**For Proposal Submission:**
- Email subject: "RFP Submission - Wireless Infrastructure - [Vendor Name]"
- Submit by December 15, 2025, 5:00 PM CST

**For Site Visit Scheduling:**
- Email subject: "Site Visit Request - [Vendor Name]"
- Provide 3 preferred dates/times
- Site visits must be completed by December 10, 2025

**Response Time:**
- KMCloud will respond to vendor inquiries within 2 business days
- Urgent questions may be addressed via phone

---

## APPENDICES

### APPENDIX A: ACRONYMS AND ABBREVIATIONS

| Acronym | Definition |
|---------|------------|
| AP | Access Point |
| AWS | Amazon Web Services |
| BLE | Bluetooth Low Energy |
| CAPEX | Capital Expenditure |
| CWNA | Certified Wireless Network Administrator |
| DHCP | Dynamic Host Configuration Protocol |
| DNS | Domain Name System |
| DSCP | Differentiated Services Code Point |
| ECSE | Ekahau Certified Survey Engineer |
| GDPR | General Data Protection Regulation |
| IoT | Internet of Things |
| IP | Internet Protocol |
| ISO | International Organization for Standardization |
| MAC | Media Access Control |
| MIMO | Multiple Input Multiple Output |
| MPSK | Multi Pre-Shared Key |
| NDA | Non-Disclosure Agreement |
| OFDMA | Orthogonal Frequency Division Multiple Access |
| OPEX | Operating Expenditure |
| OWE | Opportunistic Wireless Encryption |
| PCI DSS | Payment Card Industry Data Security Standard |
| PoE | Power over Ethernet |
| QoS | Quality of Service |
| RADIUS | Remote Authentication Dial-In User Service |
| RBAC | Role-Based Access Control |
| RF | Radio Frequency |
| RFP | Request for Proposal |
| RRM | Radio Resource Management |
| SLA | Service Level Agreement |
| SNMP | Simple Network Management Protocol |
| SNR | Signal-to-Noise Ratio |
| SOC 2 | Service Organization Control 2 |
| SSID | Service Set Identifier |
| TCO | Total Cost of Ownership |
| TPM | Trusted Platform Module |
| TWT | Target Wake Time |
| UPS | Uninterruptible Power Supply |
| VLAN | Virtual Local Area Network |
| VoIP | Voice over Internet Protocol |
| VPN | Virtual Private Network |
| Wi-Fi 6 | 802.11ax wireless standard |
| Wi-Fi 6E | 802.11ax with 6 GHz band support |
| WIPS | Wireless Intrusion Prevention System |
| WPA3 | Wi-Fi Protected Access 3 |

---

### APPENDIX B: BUILDING FLOOR PLANS

The detailed floor plans for Building A and Building B are maintained internally
and can be provided to shortlisted vendors upon request. These diagrams include
workspace layouts, MDF/IDF locations, and recommended AP mounting areas.

**Floor plans are available upon request for vendors conducting site surveys.**

To request floor plans:
- Email kristine.bagsican@kmcloud.com with subject "Floor Plan Request - [Vendor Name]"
- NDA signature required before release
- Plans provided in PDF and AutoCAD DWG format

**Available Documents:**
- Building A - Floor 1, 2, 3 plans
- Building B - Floor 1, 2 plans
- Site map showing building locations and outdoor areas
- Existing network infrastructure diagrams

---

### APPENDIX C: EXISTING NETWORK INFRASTRUCTURE DIAGRAM

A high-level network diagram will be provided to vendors upon shortlisting and 
execution of a Non-Disclosure Agreement (NDA). The diagram includes the existing 
Cisco switching environment, Fortinet security perimeter, and AWS cloud 
integration points.

**Network diagram available upon request after NDA signing.**

**Current Infrastructure Summary:**
- **Core Switching:** 2x Cisco Catalyst 9300 (stacked)
- **Firewall:** 2x Fortinet FortiGate 200F (HA cluster)
- **Internet:** Dual 1 Gbps fiber connections (redundant ISPs)
- **AWS Connectivity:** AWS Direct Connect (1 Gbps dedicated connection)
- **Existing Wireless:** Legacy 802.11ac APs (to be replaced)

---

## DOCUMENT REVISION HISTORY

| Version | Date | Author | Changes |
|---------|------|--------|---------|
| 1.0 | November 20, 2025 | Kristine Bagsican | Initial RFP release |

---

**END OF DOCUMENT**

---

**KMCloud Solutions Inc.**  
*Cloud Infrastructure Excellence*
