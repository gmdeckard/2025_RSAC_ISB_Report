# RSA Innovation Sandbox 2025 Finalist Report

Finalist Company Name: Metalware

## 1. Executive Summary
Metalware offers an automated firmware fuzzing platform that helps enterprises and governments secure critical infrastructure at scale. The company's solution automates the traditionally complex process of firmware testing, enabling organizations to detect and remediate vulnerabilities in embedded systems before deployment. By focusing on the often-overlooked firmware layer, Metalware aims to bridge a critical gap in hardware security across multiple industries [1][3].

## 2. Company Overview

Launch Date: Founded in June 2023 [6]
Headquarters: San Francisco, California, USA [6][7]
Website: https://metalware.com
Contact Information: contact@metalware.com [7]

## 3. Product/Services

Primary Product(s)/Service(s): Metalware Havoc - an automated, end-to-end firmware fuzzing solution.

Key Features:
- Automated firmware unpacking and emulation
- Intelligent fuzzing engine
- Plug-and-play deployment requiring no test harnesses
- Full-system emulation replicating operational environments
- Parallelized fuzzing for faster results
- Automated root cause analysis and reproducibility
- Instant vulnerability categorization according to CWE
- CI/CD integration with Jenkins, GitLab CI, and GitHub Actions
- Flexible deployment options (on-premise and cloud-based) [1][2]

Technology Stack: 
- Binary fuzzing technology
- Full-system emulation platform
- Coverage-guided fuzzing
- Concolic execution
- Sanitization techniques
- Automated crash deduplication and taint analysis
- Proprietary boot solver technology
- AWS GovCloud integration [1][2]

## 4. Addressing the Cybersecurity Challenge

Identified Problem: Organizations deploy code scanners and network analyzers, but firmware—the code that powers embedded devices—often remains a critical security blind spot. As systems become increasingly connected and software-driven, the security of embedded firmware has emerged as a major vulnerability point, with potential impacts ranging from privacy breaches to critical infrastructure compromise [1].

Market Size & Opportunity: The embedded systems market spans multiple critical sectors, including:
- Aerospace and defense
- Automotive
- Consumer IoT
- Industrial controls
- Medical devices
- Telecommunications

As these industries increasingly rely on connected, software-driven devices, the need for automated firmware security testing has grown substantially. The company aims to address this expanding market by providing scalable solutions for firmware security testing that were previously only possible through resource-intensive manual methods [1][2].

## 5. Solution Approach

Core Technology & Innovation: Metalware's approach centers on automated binary fuzzing combined with full-system emulation, enabling organizations to test firmware security at scale. The company's technology can automatically extract, re-host, and analyze firmware images without requiring test harnesses or custom instrumentation, significantly reducing the complexity and resource requirements of firmware security testing [1][2].

Key Features and Functionality Explained:
- **Metalware Emulation Platform**: The platform provides full-system emulation that replicates the operational environment of devices, enabling realistic testing of low-level firmware behavior. It automatically extracts, re-hosts, and analyzes firmware images without requiring test harnesses or custom instrumentation. The platform is specifically designed for the unique challenges of embedded systems, including hooking peripheral memory accesses, interrupt routines, and DMA operations [1][2].

- **Metalware Fuzzing Engine**: The fuzzing engine uses parallelized techniques to deliver results much faster than traditional methods. It simulates sophisticated, real-world attacks on critical code paths using hybrid techniques including coverage-guided fuzzing, concolic execution, and sanitization. The engine is hardware-aware, allowing it to recreate the exact conditions under which RTOS and bare-metal bugs occur over any communication protocol. A proprietary boot solver gets firmware into a booted state before fuzzing, eliminating false positives induced by uninitialized peripherals [1][2].

- **Automated Root Cause Analysis**: The platform provides immediate insights and reproducible test cases to accelerate remediation. It analyzes stack traces, categorizes vulnerabilities according to CWE, and documents the precise conditions that triggered failures. By generating deterministic artifacts, it allows developers to reliably reproduce and verify issues, ensuring efficient debugging and patching [1][2].

- **Ecosystem Integrations**: Metalware integrates with modern development and security ecosystems through flexible APIs and connectors. It offers native integrations with CI/CD systems like Jenkins, GitLab CI, and GitHub Actions for automated testing with every firmware compilation. The platform also connects with bug tracking systems, enterprise SIEM solutions, dashboards, and compliance reporting systems [1][2].

Scalability & Future Roadmap: Metalware is designed to scale from single-device testing to an entire portfolio, meeting rigorous security testing demands far beyond the capabilities of manual methods. Early adopters have reportedly seen a 50–70% reduction in manual testing effort and a 2–3x boost in finding critical vulnerabilities. The platform architecture supports both on-premise and cloud-based deployment options to accommodate various organizational needs [1][2].

## 6. Customer & Traction

Current Customers (as of May 2025): While specific customer names aren't publicly disclosed, Metalware targets customers across multiple industries, including:
- Aerospace and defense
- Automotive manufacturers
- Consumer IoT producers
- Industrial control systems operators
- Medical device manufacturers
- Telecommunications equipment providers [1]

Implementation Status: Metalware's platform is currently deployed in production environments, with implementation options including both on-premise and cloud-based deployments. The company is ITAR registered, approved for AWS GovCloud for highly sensitive government data, working toward AICPA SOC Type 2 compliance, and registered with SAM.gov as a federal vendor [1].

Customer Testimonials: No specific customer testimonials are publicly available.

Key Metrics (if available): 
- Early adopters have seen a 50–70% reduction in manual testing effort
- 2–3x boost in finding critical vulnerabilities compared to traditional methods
- Results in hours rather than days for firmware vulnerability detection [1][2]

Additional Insights from RSA 2025 Pitch:
- Metalware's founders are firmware development veterans from SpaceX, L3Harris, and Northrop Grumman, bringing deep domain expertise as "outsiders" to traditional cybersecurity.
- The platform requires no hardware, configuration, or instrumentation—users simply upload firmware and press go, with everything else automated.
- Metalware's solution is already making an impact with open source vendors (Analog Devices, Arduino) and large commercial customers, reporting and disclosing vulnerabilities.
- The platform can complete large-scale projects in weeks that would otherwise take months manually.
- Metalware automates the complexity of firmware emulation and fuzzing, running thousands of tests per second and providing real-time vulnerability data and traceability [8].

## 7. Go-To-Market (GTM) Strategy

Target Market Segments: 
- Aerospace and defense organizations
- Automotive manufacturers and suppliers
- Consumer IoT device manufacturers
- Industrial control system operators
- Medical device manufacturers
- Telecommunications equipment providers [1]

Sales Channels: 
- Direct sales through personalized demos (prominent "Book a Demo" CTA on website)
- Industry-specific solutions briefs for target verticals
- Federal government sales channel (SAM registered vendor) [1]

Pricing Model: Not publicly disclosed on the company website.

Marketing Strategy: 
- Industry-specific solutions targeting key verticals with unique needs
- Educational content highlighting the risks of unsecured firmware
- Emphasis on automated, end-to-end firmware security testing
- Focus on meeting regulatory and compliance requirements in regulated industries [1][2]

## 8. Management & Leadership

Management Structure: Metalware has a lean management structure led by two co-founders with deep expertise in embedded systems and security.

Leadership Team:
- **Ryan Chow** - Co-founder & CEO: Prior to founding Metalware, Ryan worked at SpaceX for 6 years, developing embedded firmware programs for Starlink-related devices. He has approximately 10 years of total work experience in embedded systems and firmware development [1][8].

- **Andrew Nedea** - Co-founder & CTO: Andrew also worked at SpaceX, where he and Ryan met. He brings technical expertise in embedded firmware development and security. According to the company website, the founding team includes engineers with experience from L3Harris, Amazon Robotics, and SpaceX [1][8].

Advisory Board (if applicable): No specific advisory board members are publicly listed.

## 9. Financial Information (2023 & 2024)

Revenue (2023): Information not publicly available

Revenue (2024 - Projected or Actual): Information not publicly available

Funding History:
- Seed funding: $3 million (September 6, 2023) [9][10]
- Investors: Y Combinator, Liquid 2 Ventures, Pioneer Fund, and other investors (total of 8 investors reported) [9][10]
- As of May 2025, the company will receive an additional $5 million uncapped SAFE investment as part of being an RSA Innovation Sandbox finalist

Burn Rate (if available): Information not publicly available

## 10. Appendix

According to the Forrester report, Metalware pitched a binary fuzzer to find security flaws in firmware. The judges pointed out that fuzzing is a common approach in the IoT and OT security world, and that the vendor will have to navigate a crowded supply chain security market [4].

Metalware is addressing the critical but often overlooked area of firmware security in embedded systems. As more devices become connected and integrated into critical infrastructure, the security implications of vulnerable firmware have grown significantly. The company's founding team brings direct experience from SpaceX, giving them firsthand understanding of the challenges in developing and securing complex embedded systems.

Several factors distinguish Metalware's approach in the firmware security market:

1. **End-to-End Automation**: By automating the entire process from firmware extraction to vulnerability detection and reporting, Metalware aims to eliminate the significant manual effort traditionally required for firmware security testing.

2. **Full-System Emulation**: Rather than testing individual functions in isolation, the platform emulates the full application environment, providing more realistic and comprehensive security testing.

3. **Hardware Awareness**: The platform's ability to handle the unique challenges of embedded systems, including peripheral memory accesses, interrupt routines, and DMA operations, addresses specific firmware testing challenges that generic security tools miss.

4. **Integration into Development Workflows**: By offering direct integration with CI/CD systems, Metalware enables "shift left" security testing, allowing vulnerabilities to be detected earlier in the development lifecycle.

While the judges at the RSA Innovation Sandbox noted that fuzzing is a common approach in IoT and OT security, Metalware's specific focus on automating the complex process of firmware fuzzing at scale could potentially address major efficiency and coverage gaps in current approaches. As the company navigates the competitive supply chain security market, its success will likely depend on demonstrating quantifiable improvements in efficiency, accuracy, and coverage compared to existing solutions.

## Citations

[1] Metalware. "Company and Product Information." https://metalware.com. Accessed May 2025.

[2] Metalware. "Product Overview." https://www.metalware.com/product. Accessed May 2025.

[3] RSA Conference. "Finalists Announced for 20th Annual RSAC™ Innovation Sandbox Contest 2025." April 8, 2025. https://www.rsaconference.com/library/press-release/finalists-announced-for-20th-annual-rsac-innovation-sandbox-contest-2025

[4] Forrester. "RSAC Conference 2025: Innovation Sandbox Turns 20." May 7, 2025.

[5] Futurum Group. "RSA Conference Innovation Sandbox Announces 2025 Finalists." April 2025.

[6] Y Combinator. "Metalware: Cybersecurity for firmware." https://www.ycombinator.com/companies/metalware. Accessed May 2025.

[7] Crunchbase. "Metalware Company Profile & Funding." https://www.crunchbase.com/organization/metalware. Accessed May 2025.

[8] Metalware RSA Innovation Sandbox 2025 Pitch Transcript, video-pitches/metalware-pitch-transcript, May 2025.

[9] Crunchbase. "Metalware Funding, Financials, Valuation & Investors." https://www.crunchbase.com/organization/metalware/company_financials. Accessed May 2025.

[10] Crunchbase. "Seed Round - Metalware - 2023-09-06." https://www.crunchbase.com/funding_round/metalware-seed--570f0fab. Accessed May 2025.
