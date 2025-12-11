# EIOC Guard™ Product Specification

## Scenario Generation Engine

---

## 🎯 Vision

Transform EIOC Guard from a static scenario library into a **dynamic, adaptive training platform** that generates fresh, emotionally-layered scenarios on demand. Learners can't memorize answers. Facilitators get infinite variety. Training becomes a living, measurable resilience engine.

---

## 📋 Current State vs. Future State

| Aspect | Current (Content Library) | Future (Generation Engine) |
|--------|---------------------------|---------------------------|
| Scenarios | 88 pre-written variants | Unlimited generated combinations |
| Variety | Facilitator rotates manually | System randomizes automatically |
| Memorization risk | Reduced but possible | Eliminated |
| Customization | Choose from existing | Generate to specification |
| Scalability | Add scenarios manually | Generate programmatically |
| Metrics | Manual tracking | Automated analytics |

---

## 🔧 Scenario Generation Engine

### Input Parameters

**1. Industry Selection**
```
[ ] Healthcare
[ ] Utilities
[ ] Finance
[ ] Retail
[ ] Education
[ ] Manufacturing
[ ] Technology / SaaS
[ ] Insurance
[ ] Government
[ ] Transportation / Logistics
[ ] Hospitality
[ ] Custom: _______________
```

**2. Role Selection**
```
Dynamic list based on industry selection

Healthcare:
  [ ] Nurse / Clinical Staff
  [ ] Billing Clerk
  [ ] IT Administrator
  [ ] Medical Records
  [ ] Executive / Department Head

Finance:
  [ ] Bank Teller
  [ ] Loan Officer
  [ ] CFO / Executive
  [ ] Compliance Analyst
  [ ] Wire Transfer Specialist

[etc. for each industry]
```

**3. Emotional Lever Selection**
```
Select 2-4 levers to emphasize:

[ ] Trust (known relationship)
[ ] Continuity (shared history reference)
[ ] Empathy (sender appears stressed/vulnerable)
[ ] Duty (professional responsibility appeal)
[ ] Urgency (time pressure)
[ ] Guilt (consequence if you don't help)
[ ] Authority (senior/respected source)
```

**4. Difficulty Level**
```
( ) Level 1: Single lever (obvious manipulation)
( ) Level 2: Double lever (moderate complexity)
( ) Level 3: Triple lever (sophisticated attack)
( ) Level 4: Full stack (multi-layered, subtle cues)
( ) Adaptive: Start simple, escalate based on performance
```

**5. Contextual Details**
```
[ ] Recent meeting reference
[ ] Shared project history
[ ] Known vendor/supplier relationship
[ ] Past favor or collaboration
[ ] Specific deadline or event
[ ] Custom context: _______________
```

**6. Scenario Format**
```
( ) Email
( ) SMS / Text message
( ) Phone call script
( ) In-person conversation
( ) Slack / Teams message
( ) Voicemail transcript
```

---

### Template Engine

**Core Template Structure:**
```
[SENDER_RELATIONSHIP] + [CONTINUITY_REFERENCE] + [EMOTIONAL_TONE] + [ACTION_REQUEST] + [CONSEQUENCE]
```

**Variable Placeholders:**

| Placeholder | Options |
|-------------|---------|
| `[SENDER]` | Colleague, Supervisor, Client, Vendor, Family member, Senior executive, Peer, Mentee |
| `[RELATIONSHIP_HISTORY]` | "we worked on together," "you helped me with last week," "we've known each other for years," "remember when you..." |
| `[EMOTIONAL_TONE]` | Stressed, Pleading, Apologetic, Anxious, Urgent, Overwhelmed, Grateful-in-advance |
| `[ACTION_REQUEST]` | Open attachment, Click link, Approve transfer, Update records, Apply patch, Process request, Share information |
| `[CONSEQUENCE]` | "or the team suffers," "or I'll let everyone down," "or we lose the client," "or production halts," "before the deadline" |
| `[TIME_PRESSURE]` | "in the next hour," "before end of day," "before my shift ends," "before the meeting," "immediately" |

**Example Template:**
```
Email from [SENDER] you've [RELATIONSHIP_HISTORY].
Tone: [EMOTIONAL_TONE]

"[GREETING], [CONTINUITY_REFERENCE]. I'm [EMOTIONAL_STATE] and 
[ACTION_REQUEST] [TIME_PRESSURE]. [CONSEQUENCE]. [GUILT_HOOK]."
```

**Generated Output Example:**
```
Email from a colleague you've worked with for three years.
Tone: Stressed, apologetic

"Hey, remember the patient case we discussed last Tuesday? I'm 
completely overwhelmed with the audit prep and I need you to 
review this file before my shift ends in 20 minutes. If it 
doesn't get reviewed, the compliance team will flag our whole 
unit. I'm really counting on you here—I wouldn't ask if it 
wasn't urgent."
```

---

### Output Components

**For each generated scenario, the engine produces:**

**1. Scenario Text**
```
The full scenario narrative (email, SMS, conversation)
formatted for presentation to learners.
```

**2. Facilitator Notes**
```
EMOTIONAL LEVERS EXPLOITED:
- Trust: Known colleague, established relationship
- Continuity: References shared patient case
- Empathy: Sender is overwhelmed
- Urgency: 20-minute deadline
- Guilt: "counting on you," unit consequences

DIFFICULTY LEVEL: 3 (Triple lever)

REALISTIC DETAILS:
- Specific time reference (last Tuesday)
- Concrete deadline (20 minutes)
- Organizational consequence (compliance flag)
```

**3. Role-Play Script**
```
ATTACKER LINES:
- Opening: [stressed tone] "Hey, do you have a second?"
- Pressure: "I really wouldn't ask if it wasn't urgent."
- Escalation: "The whole unit is counting on this."
- Guilt close: "I don't know what I'll do if this doesn't get done."

FACILITATOR COACHING:
- Emphasize the stressed vocal tone
- Use pauses to create pressure
- Make eye contact during guilt statements
```

**4. Assessment Prompt**
```
RECOGNITION QUESTION:
"Which emotional levers are being exploited in this scenario?"

DECISION QUESTION:
"What would you do, and why?"

COUNTER-MOVE QUESTION:
"How would you respond while maintaining the relationship?"
```

---

## 📊 Metrics & Analytics Module

### Individual Tracking

| Metric | Description |
|--------|-------------|
| **Lever Susceptibility** | Which emotional levers cause failures |
| **Difficulty Ceiling** | Highest level consistently passed |
| **Recognition Speed** | Time to identify manipulation |
| **Counter-Move Fluency** | Quality of defensive response |
| **Progression Rate** | Improvement over sessions |

### Team/Organizational Tracking

| Metric | Description |
|--------|-------------|
| **Departmental Heatmap** | Vulnerability by team/department |
| **Role Risk Profile** | Which roles show highest susceptibility |
| **Lever Trends** | Most exploited levers across organization |
| **Training Effectiveness** | Pre/post improvement by lever |
| **Benchmark Comparison** | Performance vs. industry averages |

### Dashboard Visualization

```
┌─────────────────────────────────────────────────────────────┐
│  EIOC Analytics Dashboard                                   │
├─────────────────────────────────────────────────────────────┤
│                                                             │
│  Organizational Vulnerability Profile                       │
│  ═══════════════════════════════════                       │
│                                                             │
│  Urgency    ████████████████████░░░░ 78%                   │
│  Authority  ███████████████░░░░░░░░░ 62%                   │
│  Guilt      ██████████████░░░░░░░░░░ 58%                   │
│  Empathy    ███████████░░░░░░░░░░░░░ 45%                   │
│  Trust      ████████░░░░░░░░░░░░░░░░ 34%                   │
│                                                             │
│  High-Risk Departments        Training Recommendations      │
│  ─────────────────────        ────────────────────────      │
│  1. Finance (Authority)       → Counter-authority scripts   │
│  2. Healthcare (Empathy)      → Empathy boundary training   │
│  3. IT (Urgency)              → Verification protocols      │
│                                                             │
│  Trend: Urgency susceptibility ↓ 15% after Q3 training     │
│                                                             │
└─────────────────────────────────────────────────────────────┘
```

---

## 🌍 Localization Module

### Cultural Adaptation Parameters

| Parameter | Options |
|-----------|---------|
| **Region** | North America, Western Europe, East Asia, Latin America, Middle East, South Asia |
| **Language** | English, Spanish, Mandarin, Japanese, German, French, Arabic, Hindi, Portuguese |
| **Formality Level** | Casual, Professional, Formal, Hierarchical |
| **Authority Weight** | High (authority-respecting cultures) / Medium / Low |
| **Collectivism** | Individual focus ("I need you") / Group focus ("The team needs you") |

### Localized Output Example

**Same scenario, different cultural adaptation:**

**North America (Direct, Individual):**
> "I really need your help with this. If you don't approve it, I'm in trouble."

**Japan (Indirect, Hierarchical):**
> "Tanaka-bucho has indicated this matter requires attention. Your cooperation in maintaining departmental harmony would be appreciated."

**Brazil (Warm, Relationship-focused):**
> "My friend, you know I wouldn't ask if it wasn't important. We've worked together so long—please help me today."

---

## 📤 Export & Integration

### Export Formats

| Format | Use Case |
|--------|----------|
| **PDF** | Workshop handouts, printed materials |
| **PowerPoint** | Presentation integration |
| **CSV** | Data import to LMS |
| **JSON** | API integration |
| **SCORM** | LMS compatibility |

### Integration Options

| Platform | Integration Method |
|----------|-------------------|
| **LMS (Cornerstone, Workday)** | SCORM packages, API |
| **Security Platforms (KnowBe4, Proofpoint)** | Module integration, white-label |
| **HR Systems** | Employee data sync for role-based scenarios |
| **SSO** | SAML, OAuth for enterprise authentication |
| **Reporting** | Webhook to BI tools (Tableau, Power BI) |

---

## 🛠️ Technical Architecture (Conceptual)

```
┌─────────────────────────────────────────────────────────────┐
│                      USER INTERFACE                         │
│  (Web App / Mobile / LMS Integration)                       │
└─────────────────────────┬───────────────────────────────────┘
                          │
                          ▼
┌─────────────────────────────────────────────────────────────┐
│                    API GATEWAY                              │
│  (Authentication, Rate Limiting, Routing)                   │
└─────────────────────────┬───────────────────────────────────┘
                          │
          ┌───────────────┼───────────────┐
          ▼               ▼               ▼
┌─────────────────┐ ┌───────────────┐ ┌─────────────────┐
│ SCENARIO ENGINE │ │ METRICS ENGINE│ │ LOCALIZATION    │
│                 │ │               │ │ ENGINE          │
│ - Templates     │ │ - Tracking    │ │ - Cultural      │
│ - Randomization │ │ - Analytics   │ │   adaptation    │
│ - Difficulty    │ │ - Reporting   │ │ - Translation   │
│   scaling       │ │ - Dashboards  │ │ - Tone adjust   │
└────────┬────────┘ └───────┬───────┘ └────────┬────────┘
         │                  │                  │
         └──────────────────┼──────────────────┘
                            │
                            ▼
┌─────────────────────────────────────────────────────────────┐
│                      DATA LAYER                             │
│  (Scenario Templates, User Progress, Org Metrics, Exports)  │
└─────────────────────────────────────────────────────────────┘
```

---

## 📈 Business Model Options

| Model | Description | Target |
|-------|-------------|--------|
| **SaaS Subscription** | Per-user/month pricing | Enterprise customers |
| **Platform License** | One-time + maintenance | Large organizations |
| **White-Label** | Branded for resellers | MSSPs, consultancies |
| **API Access** | Per-call or tier pricing | Integration partners |
| **Freemium** | Basic free, advanced paid | SMB market entry |

---

## 🚀 Implementation Phases

| Phase | Deliverable | Timeline (with resources) |
|-------|-------------|---------------------------|
| **Phase 1** | Core scenario generator (single industry) | 8-12 weeks |
| **Phase 2** | Multi-industry support + difficulty scaling | 6-8 weeks |
| **Phase 3** | Metrics dashboard + tracking | 6-8 weeks |
| **Phase 4** | Localization engine | 8-10 weeks |
| **Phase 5** | LMS/platform integrations | 4-6 weeks |
| **Phase 6** | Mobile app + API | 8-12 weeks |

**Total estimated development:** 40-56 weeks with dedicated engineering team

---

## 💡 Strategic Value

### For Acquirers

This specification transforms EIOC Guard from:
- ❌ A static content library requiring manual updates
- ✅ A dynamic platform with unlimited scenario generation

**What you're acquiring:**
1. Complete methodology and framework (done)
2. 88 seed scenarios across 22 roles (done)
3. Full documentation and training materials (done)
4. Product specification for technology build (this document)
5. Clear roadmap for platform development

### For Partners

This specification enables:
- White-label deployment with customization
- Integration into existing security awareness platforms
- API-based scenario generation for proprietary tools

### For Investors

This specification demonstrates:
- Clear product vision beyond initial content
- Scalable technology architecture
- Multiple monetization paths
- Defensible market differentiation

---

## 📋 What's Built vs. What's Specified

| Component | Status |
|-----------|--------|
| EIOC Framework & Methodology | ✅ Built |
| Scenario Bank (88 variants) | ✅ Built |
| Facilitator Guides & Scripts | ✅ Built |
| Training Methodology | ✅ Built |
| **Scenario Generation Engine** | 📋 Specified |
| **Metrics & Analytics** | 📋 Specified |
| **Localization Engine** | 📋 Specified |
| **Platform & Integrations** | 📋 Specified |

---

*This specification is provided as part of the EIOC Guard™ intellectual property package. Development requires engineering resources beyond the scope of the original creator.*

---

*© 2024-2025 Soft Armor Labs. All Rights Reserved.*

*EIOC Guard™ and Emotional Indicators of Compromise™ are trademarks of Soft Armor Labs.*
