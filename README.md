# SafeMind 🧠
### AI-Powered Psychological Triage System for Adolescents

[![Figma](https://img.shields.io/badge/Figma-Prototype-purple?style=flat&logo=figma)](https://figma.com)
[![Status](https://img.shields.io/badge/Status-Completed-brightgreen?style=flat)]()
[![Area](https://img.shields.io/badge/Area-AI%20·%20Mental%20Health-pink?style=flat)]()

---

## 🧩 The Problem

Adolescent mental health is a growing global crisis — marked by underreporting and delayed diagnoses. The barriers are well known: fear, shame, and the scarcity of mental health professionals.

Even when a young person decides to seek help, the system often fails them: long waiting lists, no way to assess urgency, and no clear path to the right level of care.

**The result:** patients in need of immediate attention are lost in queues, while the system wastes resources on misrouted cases.

---

## 💡 The Solution

SafeMind is a **digital psychological triage platform** designed for government health institutions and health insurance providers. It uses AI and Natural Language Processing to analyze self-reported symptoms and classify risk levels — then automates routing to the appropriate care path.

```
Adolescent completes guided self-assessment
            ↓
NLP engine analyzes symptom language and patterns
            ↓
Risk classification: Low · Moderate · High · Critical
            ↓
Automated routing:
  Critical  → On-call psychiatrist (immediate)
  High      → Psychologist appointment (priority)
  Moderate  → Video call follow-up (scheduled)
  Low       → Self-care resources + monitoring
```

---

## 🎨 Design Principles

The interface was built around three non-negotiable constraints:

- **Safety** — no data that could identify or expose the user
- **Accessibility** — readable typography, high contrast, simple language
- **Trust** — warm visual design that reduces anxiety, not a clinical form

---

## 🛠️ Stack & Methods

| Layer | Approach |
|---|---|
| Requirements | Object-Oriented Analysis (OOA) · Use case modeling |
| System Design | UML diagrams · Component architecture |
| Prototype | Figma — high-fidelity, navigable |
| AI Layer | Natural Language Processing (conceptual architecture) |
| Focus | Usability · Privacy · Accessibility |

---

## 📐 System Architecture (Conceptual)

```
SafeMind/
├── frontend/          # Mobile app (React Native — conceptual)
│   ├── onboarding/    # Anonymous profile setup
│   ├── assessment/    # Guided symptom questionnaire
│   └── results/       # Risk level + routing output
├── backend/           # API layer (conceptual)
│   ├── nlp_engine/    # Symptom analysis + classification
│   └── routing/       # Care path automation
├── design/
│   └── figma/         # High-fidelity prototype files
└── docs/
    ├── use_cases.md   # OOA documentation
    └── architecture.md
```

---

## 🖼️ Prototype

The navigable Figma prototype covers the full user journey — from anonymous onboarding through symptom assessment to triage result and routing output.

> 🔗 **[View Prototype on Figma](https://www.figma.com/proto/gyIjZpPRpowfaW4I1sGgFJ/SafeMind?node-id=1-3225&t=iZ3zAoo3Xe3DNNcM-1)** ← *(link to be added)*

**Screens included:**
- Onboarding & privacy consent
- Guided symptom questionnaire (adaptive flow)
- Risk level result screen
- Routing output (care path + next steps)
- Professional dashboard (institution-side view)

---

## 🌍 Social Impact

SafeMind was designed with the Brazilian public health system (SUS) and private health insurers in mind — but the architecture is adaptable to any national context.

**Target users:**
- Adolescents aged 12–18 seeking confidential mental health support
- Government health secretariats looking to optimize triage workflows
- Health insurance providers managing mental health coverage

---

## 👩‍💻 About the Author

**Mikaelly Cardoso** — Software Engineering & AI for Social Impact  
FAESA Centro Universitário Espírito-Santense · Vitória, ES, Brazil

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mikaelly--cardoso-0A66C2?style=flat&logo=linkedin)](https://linkedin.com/in/mikaelly-cardoso)
[![Portfolio](https://img.shields.io/badge/Portfolio-mikaellycardoso.github.io-4CAF50?style=flat)](https://mikaellycardoso.github.io/mikaelly-cardoso.github.io/)
[![Email](https://img.shields.io/badge/Email-mikaellycardosodev@gmail.com-red?style=flat&logo=gmail)](mailto:mikaellycardosodev@gmail.com)
