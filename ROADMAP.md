# EIOC Guard™ Product Roadmap

## Vision

Transform EIOC Guard from a universal emotional vulnerability assessment into a **role-aware, industry-specific defense system** that scales across organizations while maintaining relevance to daily operational realities.

---

## Architecture: Layered Assessment Model

```
┌─────────────────────────────────────────────────────────┐
│  Layer 5: Platform & Analytics                          │
│  (Metrics, Dashboards, Cultural Variants, API)          │
├─────────────────────────────────────────────────────────┤
│  Layer 4: Training Methodology                          │
│  (Adaptive Difficulty, Escalation Playbooks,            │
│   Role-Play Variants, Anti-Memorization Rotation)       │
├─────────────────────────────────────────────────────────┤
│  Layer 3: Training Delivery                             │
│  (Facilitator Guide, Training Scripts, Workshops)       │
├─────────────────────────────────────────────────────────┤
│  Layer 2: Role-Specific Scenarios                       │
│  (88 emotionally-layered variants across 22 roles,      │
│   12 industries, 4 variants per role)                   │
├─────────────────────────────────────────────────────────┤
│  Layer 1: Baseline EIOC Framework                       │
│  (Universal emotional indicators & vulnerability types) │
└─────────────────────────────────────────────────────────┘
```

Each layer multiplies value without replacing what's beneath it.

**Layers 1-4:** ✅ Complete (content and methodology)
**Layers 5-6:** 📋 Specified in PRODUCT-SPEC.md (requires engineering resources)

---

## Role-Specific Vulnerability Profiling Matrix

> **Note:** The scenarios below are baseline examples. For **emotionally-layered versions** that demonstrate sophisticated social engineering (exploiting trust, continuity, empathy, guilt, and urgency), see [SCENARIO-PLAYBOOK.md](SCENARIO-PLAYBOOK.md) and [COMPARISON.md](COMPARISON.md).

### 🏥 Healthcare Industry

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Nurse / Clinical Staff | Urgent email attachments, patient data phishing | Email titled "Critical Patient Update" with malicious PDF | "Would you open, forward, or verify this file first?" |
| Billing Clerk | Invoice fraud, credential phishing | Fake vendor email requesting updated bank details | "How do you verify vendor payment requests before updating records?" |
| IT Administrator | Credential harvesting, fake patch installs | Email with link to "system patch" requiring login | "What steps do you take before applying a patch from an external email?" |
| Medical Records Staff | Data exfiltration, pretexting calls | Phone call from "insurance company" requesting patient records | "What verification do you require before releasing patient information?" |
| Executive / Department Head | Whaling attacks, BEC fraud | Email from "CEO" requesting urgent wire transfer | "How do you verify executive requests that bypass normal approval chains?" |

### ⚡ Utilities Industry

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Plant Operator | USB drops, rogue devices | USB labeled "Shift Schedule" found in break room | "Would you plug this into the control system PC?" |
| Supply Chain Manager | Fake shipment delay notices | Email claiming critical part shipment is delayed with reschedule link | "How do you confirm shipment delays before clicking on links?" |
| Field Technician | Mobile phishing, SMS spoofing | Text message with link to "update work orders" | "What's your process for validating mobile work order updates?" |
| Control Room Staff | Insider threat, social engineering calls | Call from "vendor support" requesting remote access credentials | "What authorization is required before granting remote system access?" |
| Safety Officer | Compliance-based manipulation | Email threatening regulatory penalties with "urgent compliance form" | "How do you verify regulatory communications before acting?" |

### 🏦 Financial Services Industry

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Bank Teller | Social engineering, fake account updates | Customer requests urgent account change via suspicious email | "How do you verify urgent account update requests?" |
| Loan Officer | Document fraud, spear phishing | Email with "updated loan application" attachment containing malware | "Would you open this file or confirm through the loan system first?" |
| CFO / Finance Executive | Business Email Compromise (BEC), wire transfer fraud | Fake CEO email requesting urgent wire transfer | "What's your process for validating executive transfer requests?" |
| Compliance Analyst | Regulatory phishing, fake audit notices | Email from "regulator" requesting sensitive compliance data | "What channels do you use to verify regulatory requests?" |
| Wire Transfer Specialist | BEC fraud, payment redirection | Email from "vendor" requesting change to wire instructions | "What verification steps are required before changing payment details?" |

### 🎓 Education Industry

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Teacher | Phishing via student emails, oversharing | Student email with "project file" attachment that's malicious | "Would you open the file or verify first?" |
| Registrar | Data theft, fake transcript requests | Email requesting transcript with suspicious attachment | "How do you validate transcript requests before sending records?" |
| IT Support | Credential harvesting, rogue devices | USB labeled "Exam Results" found in office | "Would you plug this into the system or escalate?" |
| Financial Aid Officer | Tax document fraud, social engineering | Student provides falsified financial documents | "What cross-checks do you perform on submitted financial documents?" |
| Administrative Assistant | Executive impersonation, data requests | Email from "principal" requesting student contact lists | "How do you verify administrative requests for sensitive data?" |

### 🏛️ Government & Public Sector

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Civil Servant / Clerk | Fake policy updates, spear phishing from "citizens" | Email from "constituent" with urgent request and malicious attachment | "How do you verify citizen requests before opening attachments?" |
| Procurement Officer | Fraudulent bids, invoice scams | Email from "approved vendor" with updated banking information | "What process validates vendor payment detail changes?" |
| IT Security Staff | Credential harvesting, insider threats | Request from "new employee" for elevated system access | "What authorization chain is required for access privilege changes?" |

### 🛒 Retail Industry

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Cashier | Point-of-sale skimming, phishing | Text claiming "POS system update" with link | "Would you click the link or escalate to IT?" |
| Store Manager | Fake supplier invoices, credential theft | Email from "supplier" with invoice PDF | "How do you confirm supplier invoices before processing?" |
| E-Commerce Admin | Account takeover, credential phishing | Alert email about "customer account breach" with login link | "What steps do you take before logging in via such alerts?" |
| Warehouse Staff | Shipping fraud, misdirection attacks | Email requesting shipment reroute to "updated address" | "What verification is required before changing shipment destinations?" |
| HR / Hiring Manager | Resume fraud, credential fabrication | Applicant provides impressive but unverifiable credentials | "What background verification do you perform on stated qualifications?" |

### 🚚 Transportation & Logistics

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Airline Gate Agent | Fake boarding pass scans, social engineering | Passenger presents digital boarding pass that triggers system alert | "What's your process when a boarding pass scan returns an error?" |
| Truck Driver | SMS phishing, fake dispatch messages | Text message claiming route change with link to "updated delivery instructions" | "How do you verify route changes received via text?" |
| Logistics Coordinator | Shipment rerouting fraud, credential theft | Email requesting shipment reroute to "updated warehouse address" | "What verification is required before changing shipment destinations?" |

### 🏭 Manufacturing & Industrial

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Engineer | Fake CAD file attachments, malware in design updates | Email from "vendor" with "updated specifications" CAD file | "How do you verify design file sources before opening?" |
| Production Supervisor | Phishing disguised as safety alerts, fake compliance notices | Urgent email claiming "safety violation documented" with link to view details | "What's your process for verifying safety compliance communications?" |
| Maintenance Technician | Rogue USB devices, fake IoT/firmware updates | USB labeled "Firmware Update - Critical" found near equipment | "Would you plug this into the system or escalate to IT?" |

### 💻 Technology & SaaS

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Software Developer | Malicious code repos, credential phishing via GitHub | Pull request from unknown contributor with "critical security fix" | "What's your review process for external code contributions?" |
| Customer Success Manager | Fake client escalation emails, impersonation | Email from "enterprise client" demanding immediate account access for new team member | "How do you verify client identity before making account changes?" |
| Cloud Administrator | Privilege escalation, fake patch requests | Email claiming "critical AWS vulnerability" with link to apply patch | "What verification steps are required before applying cloud infrastructure updates?" |

### 🛡️ Insurance

| Role | Top Vulnerabilities | Scenario Example | Questionnaire Prompt |
|------|---------------------|------------------|----------------------|
| Claims Adjuster | Fraudulent claim documents, social engineering | Claimant submits documents with subtle inconsistencies and pressures for fast approval | "What red flags do you look for in submitted claim documentation?" |
| Underwriter | Spear phishing as client risk reports, malicious attachments | Email from "broker" with "updated risk assessment" spreadsheet | "How do you verify broker communications before opening attachments?" |
| Actuary | Malicious spreadsheets, macro-based malware | Email with Excel file claiming "revised mortality tables" from industry source | "What's your process for validating external data files before enabling macros?" |

---

## Emotional Vector Mapping

Each scenario maps to underlying EIOC emotional indicators:

| Emotional Vector | Attack Exploitation | Example Trigger |
|------------------|---------------------|-----------------|
| **Urgency** | Bypasses verification steps | "Critical," "Immediate action required" |
| **Authority** | Overrides personal judgment | "CEO request," "Regulatory mandate" |
| **Fear** | Triggers compliance without thought | "Account suspended," "Legal action pending" |
| **Trust** | Exploits established relationships | "Your vendor," "IT department" |
| **Duty** | Leverages professional responsibility | "Patient needs," "Student safety" |
| **Curiosity** | Baits engagement | "Shift schedule," "Salary info" |
| **Helpfulness** | Exploits desire to assist | "Can you help me access..." |
| **Fatigue** | Targets end-of-shift vulnerability | Late-night requests, weekend emergencies |

---

## How to Use This Matrix

1. **Add new industries** → Identify sectors with distinct operational environments
2. **List critical roles** → Map out who is most exposed in daily operations
3. **Identify top vulnerabilities** → 3–5 attack vectors per role
4. **Design scenarios** → Realistic, role-specific situations tied to emotional vectors
5. **Write questionnaire prompts** → Short, decision-forcing questions that test awareness
6. **Implement feedback loop** → Use results to refine and prioritize scenarios

---

## Why This Works

| Benefit | Description |
|---------|-------------|
| **Scalable** | Each new industry × role combination expands the library organically |
| **Customizable** | Assessments can be tailored per department, role, or client |
| **Actionable** | Results highlight which roles need targeted training |
| **Realistic** | Role-specific scenarios increase engagement and reduce checkbox fatigue |
| **Measurable** | Track vulnerabilities by role and industry, not just generic categories |

---

## Strategic Outcome

- **Multiply scenario library organically**: Each role × industry combination yields new questionnaires
- **Create a living assessment framework**: Grows with industry shifts (e.g., telehealth, AI-driven fraud, remote work)
- **Position EIOC Guard as role-aware defense**: Not just a compliance tool, but an adaptive system that maps to organizational reality

---

## Integration Positioning

EIOC Guard™ can be offered as:

- **Standalone product** → Direct deployment for organizations
- **Integrated module** → Bolt-on to existing security awareness platforms (KnowBe4, Proofpoint, Mimecast)
- **API service** → Emotional vulnerability scoring for third-party applications
- **White-label solution** → Branded implementations for MSSPs and consultancies

---

## Documentation Suite

| Document | Purpose |
|----------|---------|
| [README.md](README.md) | Project overview and quick start |
| [LICENSE.md](LICENSE.md) | Humanitarian use provisions + commercial terms |
| [IP-DOCUMENTATION.md](IP-DOCUMENTATION.md) | Prior art and ownership record |
| [ACQUISITION-SUMMARY.md](ACQUISITION-SUMMARY.md) | Executive overview for potential acquirers |
| [COMPARISON.md](COMPARISON.md) | Generic vs. EIOC scenarios at a glance |
| [SCENARIO-PLAYBOOK.md](SCENARIO-PLAYBOOK.md) | Full emotionally-layered scenario library |
| [SCENARIO-BANK.md](SCENARIO-BANK.md) | 88 rotating variants across 22 roles (anti-memorization) |
| [FACILITATOR-GUIDE.md](FACILITATOR-GUIDE.md) | Training delivery principles and methods |
| [TRAINING-SCRIPTS.md](TRAINING-SCRIPTS.md) | Modular workshop scripts by industry |
| [TRAINING-METHODOLOGY.md](TRAINING-METHODOLOGY.md) | Advanced features: metrics, adaptive difficulty, cultural variants |
| [PRODUCT-SPEC.md](PRODUCT-SPEC.md) | Scenario generation engine specification (for technology build) |

---

## Development Status

| Component | Status |
|-----------|--------|
| **Core Framework** | |
| Baseline EIOC Framework | ✅ Complete |
| Emotionally-Layered Scenarios | ✅ Complete |
| Scenario Bank (88 variants, 22 roles) | ✅ Complete |
| Facilitator Guide | ✅ Complete |
| Training Scripts (12 industries) | ✅ Complete |
| **Industry Modules** | |
| Healthcare Module | ✅ Complete |
| Utilities Module | ✅ Complete |
| Financial Services Module | ✅ Complete |
| Education Module | ✅ Complete |
| Retail Module | ✅ Complete |
| Government Module | ✅ Complete |
| Transportation Module | ✅ Complete |
| Manufacturing Module | ✅ Complete |
| Technology/SaaS Module | ✅ Complete |
| Insurance Module | ✅ Complete |
| Logistics Module | ✅ Complete |
| Hospitality Module | ✅ Complete |
| **Advanced Methodology** | |
| Cross-Role Emotional Analysis | ✅ Complete |
| Escalation Playbooks (STOP Protocol) | ✅ Complete |
| Adaptive Difficulty Framework | ✅ Complete |
| Role-Play Variants | ✅ Complete |
| Anti-Memorization Rotation Strategy | ✅ Complete |
| Reflection Journal Templates | ✅ Complete |
| **Platform Features** | |
| Scenario Generation Engine | 📋 Specified (see PRODUCT-SPEC.md) |
| Metrics & Analytics Dashboard | 📋 Specified (see PRODUCT-SPEC.md) |
| Localization Engine | 📋 Specified (see PRODUCT-SPEC.md) |
| LMS/Platform Integrations | 📋 Specified (see PRODUCT-SPEC.md) |
| Cultural/Regional Variants | ⬜ Planned |
| Interactive Assessment Tool | 🟡 In Development |
| API Architecture | ⬜ Planned |

---

## Workshop Delivery Formats

| Format | Duration | Content |
|--------|----------|---------|
| **Single-Industry Deep Dive** | 90 min | All roles in one industry |
| **Cross-Industry Overview** | 60 min | One role from each of 4-5 industries |
| **Executive Briefing** | 30 min | Finance + one other high-risk industry |
| **Full Curriculum** | Half-day | All industries, with breaks |

See [TRAINING-SCRIPTS.md](TRAINING-SCRIPTS.md) for ready-to-run workshop modules.

---

## Contact

**Soft Armor Labs**

- **Licensing:** narnaiezzsshaa@gmail.com
- **Partnerships:** narnaiezzsshaa@gmail.com
- **Acquisitions:** narnaiezzsshaa@gmail.com

---

*© 2024-2025 Soft Armor Labs. All Rights Reserved.*

*EIOC Guard™ and Emotional Indicators of Compromise™ are trademarks of Soft Armor Labs.*
