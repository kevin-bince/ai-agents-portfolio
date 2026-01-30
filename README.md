# ai-agents-portfolio

## Overview
This repository serves as a comprehensive portfolio of my AI Agent development skills, demonstrating the end-to-end design, orchestration, and evaluation of agentic workflows. I am building and deploying two high-utility agents that bridge the gap between Large Language Models and deterministic business logic.

Key Objectives:
* Tool Orchestration: Integrating LLMs with external APIs and productivity suites (Notion, Zapier, Google Sheets, Todoist, and Google Calendar) to move beyond simple chat interfaces into actionable systems.
* Deterministic Reliability: Implementing a "Calculation Engine" approach where the AI interacts with structured data (Google Sheets) to ensure financial accuracy and eliminate hallucinations.
* Evaluation Discipline: Utilizing a robust logging system in Notion to track "Runs" and "Actions," allowing for groundedness scoring and iterative improvement.
* Security & Governance: Demonstrating a "public-but-gated" deployment model that protects personal data while remaining accessible for professional demonstration.

## Privacy boundary
Personal-only data. No work tools or work data. Live demos are public but gated by passphrase.

## Agent A: Finance Scenario Planner
[Details will be added here on Day 14.]

## Agent B: Life Systems OS
[Details will be added here on Day 26.]

## Links
- Finance Agent: (Pending)
- Life OS Agent: (Pending)

## Changelog
### [January 29, 2026] - Day 1
Concept, Architecture & Environment Setup
- Problem Statement: Defined the vision for a "Deterministic Financial Advisor"—bridging the gap between the flexibility of LLMs and the rigid accuracy required for corporate financial strategy.
- Enterprise Tech Stack: Selected a robust "Modular AI" architecture: Botpress (Conversational UX), Google Sheets (Logic Engine), Zapier (Integration Layer), and Notion (Audit/Governance Log).
- Infrastructure: Initialized version control and project documentation standards.

Persona Engineering & Ethical Guardrails
- System Prompting: Developed a sophisticated persona for the agent—analytical, objective, and risk-aware—modeled after a Senior Strategic Finance Partner.
- Regulatory Compliance: Engineered "hard-coded" ethical guardrails within the system prompt to prevent the unauthorized provision of legal or tax advice, ensuring brand safety.
- Variable Mapping: Architected the 9 core financial data points required to power the backend engine.

Knowledge Base & Contextual Intelligence
- Vertical Knowledge Integration: Ingested curated financial datasets (relocation costs, tax benchmarks) to provide the agent with high-fidelity context for user queries.
- RAG Implementation: Configured Retrieval-Augmented Generation (RAG) to allow the agent to reference specific internal business rules without hallucinating figures.

Deterministic Logic Engine (The "Math Brain")
- Engine Decoupling: Architected a multi-tab Google Sheets engine to separate user inputs from complex financial formulas, mimicking enterprise ERP logic.
- Automated Regression Testing: Built a "Math Sanity" suite within the engine to run real-time PASS/FAIL tests on every calculation, ensuring 100% mathematical integrity.
- Financial Stress Testing: Programmed the "Stress" and "Move" scenarios to simulate variance in runway and cash flow under different economic pressures.

Conversational UX & Secure Logic Gates
- Gatekeeper Security: Designed a secure entry-point node with passphrase validation to simulate enterprise access controls.
- Deterministic Flow Design: Built a branched logic tree in Botpress to handle "Standard" vs "Custom" user paths, ensuring data is collected only when necessary.
- Lead Conversion Funnel: Integrated an automated fallback flow for unauthorized users to capture lead data (Name, Intent, Email), demonstrating a strategic approach to user acquisition.
