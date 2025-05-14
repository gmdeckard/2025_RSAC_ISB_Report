# RSA Innovation Sandbox 2025 Finalist Report

Finalist Company Name: Smallstep

## 1. Executive Summary
Smallstep is a San Francisco-based cybersecurity company founded in 2016 by Mike Malone that specializes in automated certificate management for Zero Trust security implementations. The company provides device attestation using the ACME protocol to help fight phishing and exfiltration, representing a new approach to solving perennial security problems. Through its certificate management platform and SSH authentication solutions, Smallstep is improving how devices are identified in Zero Trust environments through innovative use of established protocols [1][2]. 

With $26.1 million in funding from investors including StepStone Group, boldstart ventures, Accel Partners, and Bain Capital Ventures, the company has established itself as an innovator in certificate management automation. Smallstep combines open-source tools with enterprise offerings to make complex security best practices accessible to developers and operators across organizations of all sizes [1][4].

## 2. Company Overview

Launch Date: Founded in August 2016
Headquarters: San Francisco, California, USA
Website: https://smallstep.com
Contact Information: Available through contact form at https://smallstep.com/webforms/contact-us/
Organization Type: Smallstep Labs, Inc. (For-profit corporation)

## 3. Product/Services

Primary Product(s)/Service(s): 
- Device Identity Platform™ - The world's first platform specifically designed for device identity
- ACME Device Attestation (ACME DA) - A modern standard co-developed with Google at the IETF
- Hardware-bound device credentials that prevent credential theft and phishing

Key Products and Services:
1. Device Identity Platform™ - Provides hardware-bound credentials for devices to access sensitive resources
2. ACME Device Attestation - A modern replacement for SCEP that leverages hardware co-processors for attestation
3. Enterprise Device Identity Solutions - Secures Wi-Fi, VPNs, SaaS apps, and cloud APIs with hardware-bound credentials

Key Features:
- Hardware-bound credentials that cannot be exfiltrated or phished
- Multi-OS support across MacOS, Windows, Linux, iOS, and Android
- Seamless integration with existing security infrastructure
- Certificate-based authentication for device access
- Easy device credential revocation
- Support for enterprise IT and DevOps use cases
- Protection for Wi-Fi networks, VPNs, financial dashboards, and other sensitive resources

Technology Stack: 
- ACME Device Attestation protocol (co-developed with Google)
- Hardware co-processors for attestation and keybinding
- PKI (Public Key Infrastructure) technology
- Strong cryptographic foundations built on trusted open-source software
- Integration with MDM, IdP, and device posture platforms [1]

## 4. Addressing the Cybersecurity Challenge

Identified Problem: 
1. Organizations focus too much on user identity while neglecting device identity in Zero Trust implementations
2. SCEP, the standard for device certificate enrollment for over 20 years, has serious security limitations:
   - No standardized way to generate dynamic challenges for each device
   - Many integrations use static challenges that can be exploited to issue any certificate
   - Lack of hardware attestation capabilities
3. Credential theft, phishing, and impersonation attacks continue to threaten organizations
4. Current security approaches don't leverage hardware security capabilities in modern devices
5. Most organizations have no way to verify that a device requesting access is actually company-owned
6. Different operating systems have inconsistent security implementations

Company Mission: According to their website, Smallstep believes that "when security is easy, everyone wins." Their mission envisions "a future where trusted people, tools, and resources can seamlessly and securely connect anytime, anywhere, so good can thrive." [1]

Market Size & Opportunity: 
The Zero Trust security market continues to grow as organizations recognize the critical need for both user and device authentication:
- Most organizations start their Zero Trust journey with Single Sign-On (SSO) and Multi-Factor Authentication (MFA) but neglect device identity
- Every endpoint (laptops, servers, containers, IoT devices) represents an identity that can be compromised
- The rise of remote work has accelerated the need for hardware-bound device identity
- Organizations in regulated industries need stronger guarantees that only company-owned devices access sensitive data
- Across all industries, companies are seeking protection for Wi-Fi networks, VPNs, financial systems, intellectual property, and GDPR-sensitive databases [1]

## 5. Solution Approach

Core Technology & Innovation: 
Smallstep has developed ACME Device Attestation (ACME DA) in collaboration with Google at the IETF as a modern replacement for SCEP, which has been the standard for device authentication for over 20 years. Their approach addresses critical security issues:
- Leveraging hardware co-processors for attestation and keybinding (like a fingerprint for devices)
- Creating a proper standard for high-assurance device identity to prevent credential exfiltration
- Addressing the "other half" of Zero Trust (device identity) beyond just user authentication
- Providing cross-platform support for all major operating systems
- Binding access to device hardware to prevent credential theft

Key Features and Functionality Explained: 
- Hardware-Bound Device Identity: Creates a device "fingerprint" leveraging hardware co-processors that prevents credential theft, phishing, and impersonation attacks
- Multi-OS Support: Provides consistent security across MacOS, Windows, Linux, iOS, and Android platforms
- Enterprise Integration: Seamlessly extends existing security investments by integrating with MDM, IdP, and device posture platforms
- Certificate-Based Authentication: Uses modern cryptographic methods for secure device access to resources
- Easy Management: Enables simple enrollment and revocation of device credentials across the organization
- True Zero Trust: Addresses both user and device authentication for comprehensive security

Differentiation:
- Purpose-built platform specifically for device identity rather than adapting other technologies
- Co-development of the ACME DA standard with Google at the IETF
- Native support for all operating systems (including Linux)
- Replacement for the outdated and insecure SCEP standard
- Device attestation using hardware co-processors for the strongest security guarantees
- Integration capabilities with over 100 enterprise security tools [1]

Additional Insights from RSA 2025 Pitch:
- Smallstep's device identity platform is built on a new standard, ACME Device Attestation, co-developed with Google and already adopted by Apple, Samsung, and Google.
- The platform enables drop-shipping of laptops to remote employees with automatic identification and enrollment, and can upgrade existing device fleets to high-assurance identity.
- Smallstep automates configuration and enforcement, integrates with major enforcement points (Zscaler, Cisco ISE), and supports tricky use cases like Git, SSH, and cloud APIs.
- The company is extending its approach to non-human identities, including cloud workloads and agentic AI.
- Smallstep's team has deep expertise in open-source, standards, and partnerships, and is focused on accessible, trusted compute.

Scalability & Future Roadmap: 
- Smallstep has developed support from major device manufacturers, which lessens technology adoption friction
- The company plans to expand its compliance and audit capabilities
- Future development includes enhanced access control features and broader protocol support
- Partnerships with Google and Apple to develop new standards for high-assurance device identity

## 6. Customer & Traction

Current Customers & User Base (as of May 2025):
- Enterprise customers include IBM, Meta, Capital One, Etsy, Cisco Kenna Security, HashiCorp, Samsara, Crusoe, Kameleoon, and KCF Technologies
- Trusted by 78 of the Fortune 100 companies
- Open-source tools widely adopted in the security community

Implementation Status:
- Successfully deployed across a diverse range of enterprise environments
- Used to secure Wi-Fi networks, VPNs, financial dashboards, intellectual property repositories, and GDPR-sensitive databases
- Integrated with over 100 enterprise security tools

Customer Testimonials:
- "We knew we had device identity gaps, and Smallstep is the only one doing this." - Client Platform Engineer at an Enterprise SaaS Company
- "We thought we had a solution for device identity until we talked with Smallstep and learned about the gaps we hadn't seen." - Senior Security Engineer at a Visual Media Platform
- "We started trying to build this ourselves, and it was a total tire fire. Far more expensive than we first estimated." - Security Architect at a Social Technology Company
- "Don't waste your time with other vendors that treat Device Identity as a slapped-on feature." - Sr. IT Systems Engineer at a Financial Services company

Strategic Partnerships:
- Partnership with Google to co-develop the ACME Device Attestation standard at the IETF
- Integration partnerships with major operating system vendors
- Integration with leading MDM, IdP, and device posture platforms [1]

## 7. Go-To-Market (GTM) Strategy

Target Market Segments:
- Enterprise IT teams securing corporate-owned devices, networking infrastructure, and source code
- DevOps teams needing to secure VMs, Kubernetes, cloud workloads, SSH, and mTLS
- Security teams implementing Zero Trust architecture
- Organizations with sensitive resources requiring hardware-level protection
- Companies concerned about phishing and credential theft

Key Use Cases:
- Securing corporate Wi-Fi
- Protecting VPN access
- Securing SaaS applications
- Protecting financial dashboards
- Safeguarding intellectual property
- Securing GDPR-sensitive databases and systems
- Securing cloud APIs

Sales Channels:
- Direct enterprise sales with "Book a Demo" approach
- Strategic partnerships with device manufacturers
- Technology integrations with over 100 enterprise security tools
- Open-source community engagement

Pricing Model:
- Enterprise licensing with customized pricing based on deployment size
- Consultation-based approach for specific organizational needs
- Free open-source components for certain use cases

Marketing Strategy:
- Case studies featuring successful implementations at major companies
- Educational content focused on device identity as "the other half of Zero Trust"
- Technical blog posts on security topics
- Partner ecosystem development
- Conference presentations highlighting ACME Device Attestation
- Customer testimonials emphasizing real-world implementation challenges [1]

## 8. Management & Leadership

Management Structure: The company is led by its founder and CEO with a distributed team of security and engineering experts located around the world.

Leadership Team:
- Mike Malone - Founder & CEO
  - Prior to founding Smallstep in 2016, Mike served as CTO at Betable
  - Expertise in distributed systems, infrastructure security, and authentication
  - Published researcher in cybersecurity policy
  
- Ted Malone - VP Strategy & GTM
- Geoff Leonard - Chief Revenue Officer
- Cass Fultz - Head of Operations
- Alan Thomas - Software Engineering Manager
- Max Furman - Engineer & Manager
- Josh Drake - Principal Architect

Team Structure:
Smallstep describes itself as a remote-first company with team members distributed globally. Key roles include:
- Software Engineers
- Security Solutions Architects
- Developer Advocates
- Account Executives
- Operations Staff

The company emphasizes building security that's easy to use, fostering a vision where "trusted people, tools, and resources can seamlessly and securely connect anytime, anywhere, so good can thrive." [1] As of 2025, the company has approximately 24 employees.

## 9. Financial Information (2023 & 2024)

Revenue (2023): [Information not publicly available]

Revenue (2024 - Projected or Actual): [Information not publicly available]

Funding History:
- Seed Round: $7 million - Led by boldstart ventures with participation from Accel Partners, Bain Capital Ventures, and Upside Partnership
- Series A Round: $19 million (April 2022) - Led by StepStone Group with participation from existing investors
- Additional Funding: $100,000 venture funding in SAFE Notes (December 2024)
- RSA Innovation Sandbox Prize: Finalist for $5 million uncapped SAFE investment (May 2025)

Total Funding: $26.1 million (excluding potential RSA prize)

Key Investors:
- StepStone Group (Series A lead)
- boldstart ventures (Seed round lead)
- Accel Partners
- Bain Capital Ventures
- Upside Partnership

## 10. Company Outlook & Future Direction

### Industry Perspective
According to the Forrester report, Smallstep is considered "game-changing" in introducing new technologies to solve perennial problems. Many analysts liked Smallstep's pitch around device attestation during the 2025 RSA Innovation Sandbox competition, though they didn't think the judges would select it as the winner [3].

Smallstep is applying ACME in innovative ways to address challenges in device attestation through the new ACME Device Attestation standard co-developed with Google. The company has developed a groundswell of support from major device manufacturers, which helps reduce technology adoption friction for their solutions [1][3]. As Zero Trust security models continue to gain importance, Smallstep's approach to device identity and attestation aligns with industry needs for stronger verification methods [1][2].

### Company Vision
Smallstep states on their website: "We believe when security is easy, everyone wins. We envision a future where trusted people, tools, and resources can seamlessly and securely connect anytime, anywhere, so good can thrive." [1]

Their vision focuses on:
- Completing the Zero Trust journey by addressing device identity alongside user identity
- Replacing outdated standards like SCEP with modern solutions like ACME Device Attestation
- Making security stronger through hardware attestation while keeping it simple and usable
- Supporting all operating systems with a consistent approach to device identity
- Integrating with existing security infrastructure to enhance rather than replace current investments

### Market Positioning
Smallstep positions itself as the creator of the world's first Device Identity Platform™, providing the strongest possible guarantee of authentic device identity by binding access to a device's silicon. They differentiate by addressing what they call "the other half of Zero Trust" - device identity - which complements existing user authentication solutions.

### Recent Developments
1. Co-development of ACME Device Attestation standard with Google at the IETF
2. Launch of hardware-bound credential solutions for all major operating systems
3. Introduction of device identity solutions for Wi-Fi, VPNs, SaaS apps, and cloud APIs
4. Integration with device posture and identity systems from leading vendors

### Future Growth Areas
1. Expanding ecosystem integrations beyond the current 100+ enterprise tools
2. Enhancing hardware attestation capabilities as new device technologies emerge
3. Developing additional standards for secure device authentication
4. Continuing to build enterprise adoption in regulated industries [1]

## Citations

[1] Smallstep. "Company and Product Information." https://smallstep.com. Accessed May 2025.

[2] Futurum Group. "RSA Conference Innovation Sandbox Announces 2025 Finalists." April 2025.

[3] Forrester. "RSAC Conference 2025: Innovation Sandbox Turns 20." May 7, 2025.

[4] Business Wire. "Smallstep Secures $26M in Funding to Further Practical Zero Trust by Automating Certificate Management." April 28, 2022.

[5] Smallstep Blog. "How We Got Here: Smallstep Raises Series A Funding." May 20, 2024.

[6] Crunchbase. "Smallstep Company Profile & Funding." Retrieved May 2025.

[8] Smallstep RSA Innovation Sandbox 2025 Pitch Transcript, video-pitches/smallstep-pitch-transcript, May 2025.
