# Proportionality & AI Risk Governance - Study Notes

## Core Principles

### Proportionality
Simple definition: Any action taken must be just enough to achieve the goal - not more, not less.

Think of it like: You would not use a sledgehammer to crack a nut.

Key idea: Interventions (technical, legal, or organizational) must not exceed what is necessary.


### Do No Harm
Simple definition: An obligation to not cause or worsen harm, and to actively prevent foreseeable harm before it happens.

Think of it like: A doctor's oath - "first, do no harm."

Key idea: You must assess risks before deploying an AI system, not after problems appear.


### The Four Proportionality Tests

| Test | Question It Asks | Example |
|------|------------------|---------|
| Legitimacy | Is the purpose valid, lawful, and defensible? | "Is using AI to screen job applicants legal and justified?" |
| Suitability | Will it actually achieve its stated goal? | "Does the screening tool actually predict good hires?" |
| Necessity | Could a less intrusive option work? | "Could a simpler questionnaire achieve the same results?" |
| Balancing | Do benefits outweigh harms and risks? | "Are the hiring improvements worth the privacy risks?" |


### "Zero Questions" Check

What it is: A go/no-go checkpoint applying all four tests.

Outcomes:
- Proceed - Passes all tests
- Redesign - Needs changes
- Narrow scope - Reduce use case
- Stop - Fails one or more tests


## Risk Assessment Concepts

### Ex-Ante Risk Assessment
Simple definition: Evaluating and preventing harms before deployment.

Think of it like: Getting a building inspected before people move in, not after it collapses.

Opposite: Ex-post = reacting after harm occurs.


### Anticipatory Governance
Simple definition: Preventing foreseeable harms before they happen, especially irreversible ones.

Think of it like: Building flood defenses before the storm hits.


### Risk-Based Regulation
Simple definition: Stronger rules for higher-risk systems, lighter rules for lower-risk.

| Risk Tier | Regulatory Response |
|-----------|---------------------|
| High | Strict oversight, mandatory audits, human oversight |
| Medium | Regular monitoring, documented assessments |
| Low | Basic compliance, lighter touch |


## Hard Lines & Boundaries

### Inherently Disproportionate Use
Simple definition: Uses that are categorically unacceptable - no matter how you try to make them "safe."

Think of it like: Some things are just wrong - like using facial recognition to track political opponents.

Key idea: No amount of technical refinement makes it okay.


### Precautionary Principle
Simple definition: Be extra cautious when there is potential for serious or irreversible harm, especially to vulnerable groups.

Think of it like: "Better safe than sorry" - you do not need 100% proof of harm to take action.

Key idea: Lack of full scientific certainty is NOT a reason to delay protective measures.

Source: UN Global Compact, Principle 7


## Facial Recognition & Biometrics

### Facial Recognition Technology (FRT)
Simple definition: A biometric system that creates templates from faces and matches them.

Key fact: Considered sensitive personal data under data protection law.


### Biometric Template
Simple definition: A mathematical representation of a person's face created and stored for matching.

Think of it like: A digital "fingerprint" of your face.


### Function Creep
Simple definition: When infrastructure built for one purpose creates capability and precedent for more intrusive uses.

Example: Face scanning for lunch payments -> Used for tracking student attendance -> Eventually used for access control


## Legal & Documentation

### Data Protection Impact Assessment (DPIA)
Simple definition: A systematic, legally required analysis identifying and minimizing data-protection risks before high-risk processing.

Think of it like: A safety checklist for handling people's personal data.

When required: Before any high-risk data processing.


## The Three Pillars of Proportionality

Proportionality operates at three levels:

| Level | Applies To |
|-------|------------|
| 1. Project Design | The AI application itself |
| 2. Regulation/Standards | Rules and requirements |
| 3. Risk Governance | Management and oversight |


## Risk Analysis Framework

### COBRA (Context-Based Risk Analysis)
Simple definition: A structured pre-deployment evaluation across three contexts.

The same AI = Different risk in different contexts:

AI System: Employee Absence Prediction
- Context A: Schedules for retail workers
  - Risk: LOW
- Context B: Airport security screening
  - Risk: HIGH
- Context C: Healthcare staff deployment
  - Risk: VERY HIGH


### Types of Risk Factors

| Type | Definition | Can We Change It? |
|------|------------|-------------------|
| Modifiable Risk Factors | Risk drivers the organization controls | YES - design, data, safeguards, oversight, rollout |
| Circumstantial Risk Factors | Risk drivers from the environment | NO - domain sensitivity, population vulnerability, legal context |


## Risk & Governance Calibration

### Risk Calibration
Simple definition: Classifying a system's overall risk level to match governance intensity to actual stakes.


### Governance Calibration
Simple definition: Matching the intensity of safeguards to the actual risk profile.

Safeguard intensity example:
- Low risk: Basic monitoring
- Medium risk: Regular reviews, human-in-the-loop
- High risk: Independent audits, strict oversight, human decision authority


## Stakeholder Engagement

### Stakeholder Engagement Spectrum
Scaling involvement based on risk:

| Level | Approach |
|-------|----------|
| Inform | Tell them what is happening |
| Consult | Ask for their input |
| Partner | Work together on solutions |
| Empower | Give them decision-making authority |


## Mitigation Hierarchy

Simple definition: Prioritizing harm responses in order of effectiveness.

1. AVOID    - Do not do it at all (BEST)
2. REDUCE   - Minimize the harm
3. RESTORE  - Fix what was damaged
4. COMPENSATE - Make up for it (LAST RESORT)

Why this order? Many AI harms cannot be undone - so prevention is critical.


## Quick Reference Summary

| Concept | One-Sentence Summary |
|---------|---------------------|
| Proportionality | Do not use a sledgehammer to crack a nut |
| Do No Harm | Prevent harm before it happens |
| Four Tests | Legitimacy, Suitability, Necessity, Balancing |
| Zero Questions | Go/no-go checkpoint |
| Precautionary Principle | Better safe than sorry |
| Function Creep | Purpose expansion over time |
| COBRA | Context determines risk |
| Mitigation Hierarchy | Avoid > Reduce > Restore > Compensate |


These notes are designed for easy understanding of key AI governance and proportionality concepts. Use them as a reference guide when evaluating AI systems and their risks.
