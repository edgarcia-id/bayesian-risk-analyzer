# 🎲 Enterprise Bayesian IT Risk & Alert Analyzer

**A client-side Bayesian Network inference engine and Decision Support System (DSS). Calculate the *actual* probability of security breaches and evaluate strategic IT decisions under uncertainty to defeat the Base Rate Fallacy.**

[![Live Application](https://img.shields.io/badge/Live_Bayesian_Engine-Launch_Analyzer-ef4444?style=for-the-badge&logo=githubpages)](https://edgarcia-id.github.io/bayesian-risk-analyzer/)
[![Algorithm](https://img.shields.io/badge/Algorithm-Bayesian_Exact_Inference-10b981?style=for-the-badge)](#)
[![Architecture](https://img.shields.io/badge/Architecture-100%25_Client--Side-f59e0b?style=for-the-badge)](#)
[![Maintained By](https://img.shields.io/badge/Maintained_By-NusaIT-0f172a?style=for-the-badge)](https://nusait.com)

---

## 🌐 Interactive Mathematical Modeling Lab
Do not let "Alert Fatigue" or flawed intuition drive your cybersecurity incident response or IT procurement. 

We have deployed an interactive client-side Bayesian Network calculator where IT Leaders, Security Analysts, and Enterprise Architects can build causal networks, update probabilities based on new evidence, and compare strategic decisions using Expected Value metrics:  
👉 **[Launch the Enterprise Bayesian Risk Analyzer](https://edgarcia-id.github.io/bayesian-risk-analyzer/)**

---

## 🧐 Executive Overview: The Base Rate Fallacy in IT Operations
In cybersecurity and IT operations, systems generate thousands of alerts daily. Even with a 99% accurate Intrusion Detection System (IDS), if actual attacks are rare (the "base rate"), the vast majority of alerts will be false positives. This leads to **Alert Fatigue**, where security teams begin ignoring critical warnings.

By utilizing **Bayes' Theorem** and **Bayesian Networks**, this tool forces a mathematically rigorous approach. It calculates the *posterior probability*—the actual likelihood that a threat is real given the observed evidence and the underlying base rates. Furthermore, it integrates **Expected Utility Theory** to evaluate which strategic action (e.g., isolate a server vs. monitor) minimizes financial or operational risk.

---

## 🏛️ The 3-Stage Inference & Decision Architecture

This tool automates exact probabilistic inference and expected value calculations:

```text
[ Defining the Causal Network ]
                 │
                 ▼
┌────────────────────────────────────────────────────────┐
│ STAGE 1: Network Structure & Conditional Probabilities │
│ • Define binary variables (e.g., Attack, Alert).       │
│ • Build the causal chain (Parent -> Child nodes).      │
│ • Input Conditional Probability Tables (CPT).          │
└────────────────────────────────────────────────────────┘
                 │
                 ▼
┌────────────────────────────────────────────────────────┐
│ STAGE 2: Exact Inference & Posterior Calculation       │
│ • Input observed evidence (e.g., Alert = True).        │
│ • Calculate the exact posterior probability of any     │
│   hidden variable given the evidence.                  │
└────────────────────────────────────────────────────────┘
                 │
                 ▼
┌────────────────────────────────────────────────────────┐
│ STAGE 3: Strategic Decision Analysis                   │
│ • Define decision options (e.g., Block IP vs Ignore).  │
│ • Input the utility/cost for each scenario.            │
│ • Calculate Expected Value & EVPI to recommend action. │
└────────────────────────────────────────────────────────┘
```

---

## 🛠️ Core Features for Security Analysts & IT Directors

### 1. Dynamic Bayesian Network Construction
Users can define up to 18 interconnected binary variables (Yes/No states). The engine automatically generates the required Conditional Probability Tables (CPTs) based on the defined parent-child relationships, ensuring mathematical completeness.

### 2. Exact Probabilistic Inference
Input any observed evidence (e.g., "CPU Spike = Yes", "Failed Logins = Yes"), and the calculator performs exact inference by enumerating all state combinations. It calculates the updated (posterior) probability for any target variable, providing a mathematically sound basis for incident triage.

### 3. Decision Analysis & EVPI (Expected Value of Perfect Information)
Move beyond simple probability to financial and operational impact. Define strategic actions (e.g., "Switch to Backup Supplier A" vs. "Wait for Supplier B") and assign utility values (costs/benefits) to different scenarios. The engine calculates the **Expected Value** for each action based on the posterior probabilities and recommends the optimal choice. It also calculates the **EVPI**, showing the maximum justifiable cost to acquire more data before deciding.

### 4. Audit-Ready PDF Reporting
Generates a structured, printable report detailing the network structure, the entered evidence, the resulting posterior distributions, and the decision analysis matrix. This provides defensible, quantitative documentation for major IT choices or incident responses.

---

## 💻 Technical Architecture
This application is built with the "Reachable Code" philosophy and strict privacy standards:
* **100% Client-Side Inference:** Written in Vanilla JavaScript. The exact inference algorithm runs entirely within the browser. No sensitive operational data, network topologies, or cost figures are sent to external servers.
* **No Backend Dependencies:** PDF generation utilizes optimized browser-native print capabilities (`window.print()`) with tailored `@media print` CSS, avoiding bloated external libraries.
* **Responsive UI:** Clean, enterprise-focused design using modern CSS.

---

## 👨‍💻 About the Author & Enterprise Architecture Partner

Calculating probability is only **part of Risk Management**; the rest is **secure architecture, automated guardrails, and rapid incident response**.

If your organization requires a seasoned technology partner to conduct an **ISO 27001 Risk Assessment**, harden **IT Infrastructure**, or develop custom **ERP platforms engineered with resilience**:

**Alfredo (Ed) Garcia** is a Senior ERP Architect, IT Infrastructure Lead, and Principal Consultant at **[Nusa Industri Teknologi (NusaIT)](https://nusait.com)**. He brings deep practical expertise in bridging complex governance mandates with reachable, maintainable software architecture.

* 👔 **LinkedIn:** [Alfredo (Ed) Garcia](https://www.linkedin.com/in/alfredo-garcia-elbarta-tarigan/)
* 🏢 **Consulting Firm:** [PT Nusa Industri Teknologi (NusaIT)](https://nusait.com)
* 📧 **Consultation Inquiries:** [NusaIT Contact & Advisory](https://nusait.com/contact)

---
*© 2026 Alfredo Garcia / NusaIT. Released under the MIT License.*
