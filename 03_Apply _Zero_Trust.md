## Zero Trust Implementation Roadmap

Waypoints define progressive phases toward creating technical foundation

Base waypoints are Discovery, Architecture Design, Architecture Optimization, Policy Design, and Implementation/Monitoring/Maintenance

Each phase contributes to building technical foundation that defines and establishes zero trust 

Technical Business Discovery: Data is gathered to estalish basline of existing security posture, business-related information collected, critical assets identified to know what needs to be protected, (active/iterative), up-to-date

Zero Trust Architecture Design: Defining procedures necessary to migrate organization to new security posture, detailed inputs, key stakeholders to design and understand scope

Architecture Optimization: Detailed scheme for maturity journal, identify resources to be protected and security architecture implemented
    
Policy Design: Map and catalog asset operational interdependencies, what conditions they may need access, least privilege

Zero Trust Implementation: policies deployed to establish and enforce, cyclical process

Monitoring & Maintenance:  ensures implementation remain effective, diagnosis, troubleshooting, updates

Policy design & Implementation & Maintenance  work together in periodic process, changes and fixes applied to existing or new policies

## Zero Trust Design Consideration

ZT architecture cannot be invincible as monitoring all users is more important and most protective

Effective controls rely on specific capabilities in pillar model

User: human and nonhuman identities

Device: all endpoints with local/remote access

Application & Workload: Resources bridge gap between users and organization's data

Data: Sensitive data that can create harm if misused or compromised

Network: Provides poath and maintains connection between endpoints and applications

Environment: IT environment provide data processing resources for applications and workloads

## Zero Trust Policy & Design Consideration

Design and policy driven approach and support them by establishing trust with devices and applications in environment, enforce least privilege, continuously verify, respond to change rapidly for potential incidents

## Zero Trust User Pillar Design Consideration

User Inventory: Authorized user list and audited user identities list

Conditional User Access: capture user status changes

Multi-Factor Authentication: User behaving normally, gather intel on centralized identity, 

Priviledged Access Management: Access automation engine 

Identity Federation User Credentialing: Seven laws of Identity: User control and consent, minimal disclosure, justification, directed identity, competition, human integration, consistency, SAML-based (Security Assertion Markup Language)

Behavioral, Contextual ID, and Biometrics: Sending detailed alerts, isolating threats, right policies based on unique environment needs

Least Privileged Access: Access policies for end-to-end enterprise identity

Continuous Authentication: tracking data points and typing pattern enrolled to verify identity 

Integrated ICAM Platform: Defining requirements for identification and authentication

## Zero Trust Device Pillar Design Considerations

Device Inventory: complete endpoint inventory, where it is located

Device Detection and Compliance: track and identify each device and how they communicate 

Device Authorization with Real-time Inspection: application control and file integrity monitoring

Remote Access: specify limits of allowed device activity, limit BYOD

Automated Asset, Vulnerability, and Patch Management: Automatically apply patches and recommend remediation

Unified Endpoint Management and Mobile Device Management:  UEM solution showing insights on device usage

Endpoint and Extended Detection and Response (EDR/XDR): identify suspicious activity and automated responses on predetermined triggers

## Zero Trust Application and Workload Pillar Design Consideration

Application Inventory: (APM) how applications integrate with each other

Secure Software Development and Integration: Application security become part of their workflow

Software Risk Management: (BOM), approved vulnerability databases 

Resource Authorization and Integration: User request gateway to route appropriate authentication, API manage sessions

Continuous Monitoring and Authorizations: (FISMA) (ATO) authorization to operate, 

## Zero Trust Network Pillar Design Considerations

Data Flow Mapping: Understanding data traffic across entire network

Software-Defined Networking: API is control point for each component of network

Macro Segmentation: Easily identifiable and measurable 

Micro Segmentation: Fewer but more effective policies, ML-based policy and cyptographic fingerprints

## Zero Trust Design Considerations

Common barrier to optimized zero trust is not taking a thorough approach toward establishing it across the enterprise

Simplistic Approach: Assumption of optimized point product purchase (need to be applied correctly), quick-fix mindset (continuously applied), viewed as authenticating user and devices (applicable behaviors at application/workload), rebuilding or replacing legacy infrastructure (digital transformation)

## Zero Trust Implementation Factors

what asset types must be protected, how protection defines, suit each unique asset (DAAS)

Data: must be protected

Applications: working with sensitive information

Assets: assets most sensitive

Services: which services can be exploited to disrupt normal IT operations

## Shift Implementation Focus to Securing the Protect Surface

Focus on protect the attack surface but inefficient as attack surface macro perimeter evolving and expaning

Attack Surface: New Tech = New vulnerabilities, wireless access points, thousands of different endpoints, intricate software and hardware vulnerabilities

Protect Surface: Exactly what is to be protected, defining surface provides more effective security controls as close as possible to assets, define microperimeter

## Traditional Perimeter Security vs. Microperimeter Security

Traditional Perimeters: only works at network level, only protect inside network from outside network, firewalls, VPNs, other border controls, traffic outside is untrusted and restricted while traffic inside is trusted by default

Microperimeters: created around each protect surface, point of control, not derived from software solutions or hardware but through policy

Microsegmentation logically divides data centers into security segments but not same as microperimeters

## Categorize Protect Surface Resources

Each protect surface resource is defined as a element under DAAS

(Voice over IP & Messaging = Services)

## Identify Protect Surface Resource Business Functions Workflow

Workstations = Assets

Email = Services

## Understand the Current Protect Surface Operational Baseline

Protect Surface mapping: transaction flows

Mapped data catalog: helps organize into operational baseline

## Zero Trust Policy Development Using the Kipling Method

Policy statements must be limited and concise, Kipling Method helps with who, what, when, where, why, and how protect surface should be accessed

## Microsegmentation Overview

Method of creating zones and isolating workloads to secure them individually

Helps admins create policies to limit network flow between workloada and apply appropriate security controls with segmented networks

Used to reduce network attack surface, improve breach containment, strengthen regulatory compliances

Principles: visbility, granular security, dynamic adaptation

## Benefits of Microsegmentation

Reduce Impact of Attack: provide visibility of entire network

Improve Breach Containment: shorten time to respond and remediate breach

Strengthen Compliance: Granular control of systems

Streamline Policy Management: unified policy for subnet access

## Software Defined Perimeter Overview

SDP microsegments network access based on identity, need-to-know model of identity verified before granting access

## Benefits of Software Defined Perimeter

simplify access controls, reduce attack surface, remove policy management complexity, automation

## Software Defined Perimeter Solution

1) SDP client request, SDP controller verifies applying access policies

2) After confirmation SDP controller send cryptographically signed token to client

3) SDP client then uploads live entitlements to SDP gateway to find correct resources based on request

4) Mutual session between gateway and client is formed to access resources (access logs recorded for auditing)

5) SDP controller monitors changes and ensure session segmentation between SDP client and resources

## Differences between Microsegmentation and SDP

Microsegmentation: dividing network into small segments with each having it's own policies, limit lateral movement and contain threat in segment, applied within data centers, internal segmentation, predefined rules at network level, visibility of network, MFA, less complex to manage/implement, broader adopting in traditional networks (mature)

SDP (Software Defined Perimeter): giving access to only designated resources and personalized perimeter for each user, cloak resources and ensures zero-trust access, extend across all environments, individual users and devices, user authentication and application level access (identity), degree of invisbility and protection of hidden resources, SSO or contemporary, more complex to implement especially at large environment, need for secure remote access and cloud security increases

## Identity Governance Overview

verify identity of end-user, Role-Based Access Control (RBAC), Policy-based Access Control (PBAC), Attribute-based Access Control (ABAC), certification, lifecycle management, SoD (Segregation of Duties), audit/compliances

## Benefits of Identity Governance

Visibility: high-level overview, prompt action

Streamlined identity life cycle management: leverages resources to uphold

Enhanced compliance and security: updated automatically for user accounts

Risk management: least privilege (SoD) violations

## Zero Trust Adoption Overview

Takes time and major investment, organizational security requirements, existing technology, process, budget

Framework for organization to improve unauthorized access

Identity, Devices, networks, Applications & Workloads, Data

Visbility and Analytics, Automation & Orchestration, Governance

Maturity levels 

Traditional: Manual configurations, static, limited risk assessment, limited visbility

Initial: cross pillar solutions, policy decision enforcement, automation of configurations, MFA

Advanced: Policies enforced across pillars, implement basic analytics of behavior, aumotated wherever applicable, centralzlied authentication

Optimal: FUlly automated and better alignment to relevan security standards, high visibility, enhance incident response and mitigation, automatic threat detection

## Scope of Traditional Zero Trust Maturity Levels

Many organizations start at traditional if zero trust hasn't started

Identity: traditional MFA, periodic view, on-premise identity, limited risk assessments

Devices: manually tracking device inventory, limited compliance visibility

Networks: macrosegmentation, manually, minimal traffic encryption

Application and Workloads: manual, private network, minimal workflow integration

Data: Manual inventory, on-premise, static, minimal encryption

## Scope of Initial Zero Trust Maturity Level

Initial level has automation of attribute

Identity: MFA, access expires automated view, manual identity risk assessments

Devices: physical assets tracked, some protection delivered through automation

Network: Initial isolation of workloads, dynamic configuration on some parts, more traffic and formalized key management policies

Application and Workloads: static and dynamic testing prior to deployment, accessible over public networks to authorized users

Data: limited automation to inventory data, beginning implementation of data categorization, encrypting data in transit, initial centralized key management

## Scope of Advanced Zero Trust Maturity Levels

Automated configurations of policies with cross-pillar coordination

Identity: phishing-resistant MFA, consolidation of identity stores, automated risk assessment, session-based access

Devices: all physical and most virtual assets tracked, enforced compliance integrated with threat protection, resource access depends on device posture

Network: expanded isolation, configurations adapt on automated risk-aware, encrypts netowork traffic and manages rotation of keys

Application & Workloads: Most critical applications available over public network with authorized users, context-based access controls, coordinate teams for operations and deployment

Data: automated data inventory, consistent labeling, hihgly available data stores, encryption of data-at-rest

## Scope of Optimized Zero Trust Maturity Level

significant improvements to security implementation

Identity: enterprise-wide identity integration, continuous validation and risk analysis, tailored automated access

Devices: continuous asset analysis, real-time resource access

Network: microperimeters with just-in-time access controls, best practices for cryptographic agility

Application and Workloads: automated data inventory, redundant available data stores, encryption at rest

Data: continuous data inventory, automated data categorization, dynamic access controls, encrypts data in use

## Challenges of Adopting Zero Trust

Legacy systems may not adapt to Zero Trust: costly to switch as model is bsaed on traditional maturity level

No single Zero Trust product: requires combination of products and tools to be customized to each organization

Zero Trust requires continuous maintenance: The need for time strain to keep up with system and make sure updated in real-time

Zero Trust can impact productivity: Adapting to new environment and getting used to new tools












