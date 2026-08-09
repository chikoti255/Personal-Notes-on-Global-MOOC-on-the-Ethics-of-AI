# Module 7 — AI Ethics: Environmental Sustainability

## 1. Introduction

AI is not only software.

Every AI system depends on **physical resources**: electricity, water, computer chips, servers, data centres, networks, and eventually discarded hardware.

Therefore, AI ethics must ask:

> **“Is this AI system worth the environmental and social resources it consumes?”**

Environmental sustainability in AI means looking at the **whole lifecycle** of an AI system—not only its carbon emissions.

A useful way to remember this module is:

**AI → Compute → Energy + Water + Materials → Waste → People + Environment**

---

# 2. The Big Idea: AI Has an Invisible Lifecycle

When a user types a question into an AI system, they may only see the answer.

Behind that answer, however, many things may be happening:

1. The request travels through a network.
2. Servers receive the request.
3. GPUs perform computations.
4. Data-centre equipment consumes electricity.
5. Cooling systems may consume water.
6. Hardware was previously manufactured using raw materials.
7. Hardware eventually becomes electronic waste.

This hidden infrastructure is called the **invisible lifecycle**.

### Easy way to remember

> **What you see:** the AI answer.  
> **What you don't see:** the machines, electricity, water, materials, and waste behind the answer.

---

# 3. Environmental Sustainability in AI

## Definition

**Environmental sustainability in AI** means comparing the environmental and social value of an AI system against its impacts throughout its full lifecycle.

It considers:

- Energy
- Water
- Materials
- Carbon emissions
- Hardware
- E-waste
- Social and community impacts

### Important point

> **Sustainability is more than carbon.**

An AI system may reduce carbon emissions but still consume large amounts of water or create significant e-waste.

---

# 4. Compute

## What is Compute?

**Compute** is the processing power required to train and run an AI model.

AI models require computers to perform enormous numbers of mathematical calculations.

More computation generally means:

**More compute → More electricity → More cooling → Greater environmental impact**

Compute is especially important when AI systems operate at very large scale.

---

# 5. GPUs

## What is a GPU?

A **GPU (Graphics Processing Unit)** is a specialised processor designed to perform many calculations in parallel.

GPUs are widely used for:

- Training AI models
- Running AI models
- Processing large amounts of data

### Simple analogy

Think of a CPU as a small team of highly flexible workers.

Think of a GPU as a **large team of workers doing many similar calculations at the same time**.

This makes GPUs very useful for AI—but they also consume significant electricity when used at scale.

---

# 6. Data Centres

## What is a Data Centre?

A **data centre** is a facility containing:

- Servers
- Storage
- Networking equipment
- Power systems
- Cooling systems

AI workloads can run continuously inside these facilities.

### Hyperscale Data Centres

A **hyperscale data centre** is a very large data centre designed to operate huge amounts of computing infrastructure.

### Remember

> **AI needs computers. Computers need data centres. Data centres need energy and cooling.**

---

# 7. Training vs Inference

One of the most important distinctions in AI sustainability is between **training** and **inference**.

## Training

Training is the process of building an AI model by processing large amounts of data and adjusting the model's parameters.

It can require:

- Large amounts of compute
- Many GPUs
- Significant electricity
- Significant cooling

Training is often intensive and may happen only occasionally.

## Inference

Inference happens when the trained model is used to produce an answer or prediction.

For example:

> User asks a question → Model processes it → Model generates an answer

One request may seem small, but millions or billions of requests can create a large environmental footprint.

### Key lesson

> **Training can be very intensive, but inference can become the bigger issue at massive scale.**

### Easy memory trick

**Training = Build the model**

**Inference = Use the model**

---

# 8. Embodied vs Operational Impact

AI's environmental impact comes from two major areas.

## 8.1 Embodied Impact

**Embodied impact** comes from making, transporting, and disposing of hardware.

Examples:

- Mining raw materials
- Manufacturing chips
- Manufacturing servers
- Producing GPUs
- Transporting equipment
- Disposing of old equipment

Think:

> **Embodied = making the machine**

## 8.2 Operational Impact

**Operational impact** comes from actually running the system.

Examples:

- Electricity consumption
- Cooling
- Water consumption
- Data-centre operations

Think:

> **Operational = running the machine**

### Easy comparison

| Impact | Main question |
|---|---|
| Embodied | What did it take to make the hardware? |
| Operational | What does it take to run the hardware? |

---

# 9. E-Waste

## What is E-Waste?

**E-waste** is discarded electronic equipment.

For AI, this can include:

- GPUs
- Servers
- Storage devices
- Networking equipment
- Other electronic components

AI hardware can become outdated quickly because newer and more powerful hardware is continuously introduced.

### Ethical question

> What happens to the hardware after we no longer need it?

Sustainability therefore includes the **end of life** of AI infrastructure.

---

# 10. Externalities

## What is an Externality?

An **externality** occurs when the environmental or social cost of an activity is experienced by people or communities other than the main beneficiaries.

For example:

An AI company benefits from operating a large data centre.

But nearby communities may experience:

- Increased water demand
- Pressure on local electricity supplies
- Environmental pollution
- Noise
- Waste

The company receives the benefit, while some costs may be carried by others.

### Easy definition

> **Externality = Someone else pays part of the cost.**

This is an important ethical issue because environmental costs should not simply be pushed onto:

- Local communities
- Ecosystems
- Future generations

---

# 11. Materiality

## What is Materiality?

**Materiality** means identifying which environmental impacts matter most for a particular AI system.

Not every environmental impact is equally important in every situation.

For example:

- In one location, electricity use may be the biggest concern.
- In another location, water consumption may be more serious.
- For another system, hardware manufacturing and e-waste may dominate.

### Key principle

> **Measure first. Focus effort where the biggest impacts are.**

---

# 12. Impact Hotspots

## What are Impact Hotspots?

**Impact hotspots** are the parts of an AI lifecycle where the largest environmental impacts occur.

Possible hotspots include:

- Model training
- Large-scale inference
- Data storage
- Cooling
- Hardware manufacturing
- Hardware replacement
- Deployment at massive scale

### Example

Suppose a model requires little energy during training but is used by millions of people every day.

The hotspot may be:

> **Inference at scale**

Therefore, we should not automatically assume that training is always the biggest environmental problem.

---

# 13. Right-Sizing

## What is Right-Sizing?

**Right-sizing** means choosing the smallest and most efficient AI model or infrastructure capacity that can successfully perform the required task.

The ethical question is:

> **Do we really need the biggest model?**

Sometimes a smaller model can provide nearly the same result while using much less:

- Memory
- Compute
- Electricity
- Cooling

### Example

If a small model can classify library documents accurately, using a massive general-purpose model for every document may be unnecessary.

### Remember

> **Use enough AI—not maximum AI.**

---

# 14. Bounded Use vs Always-On

AI systems do not always need to run continuously.

## Always-On

An always-on system performs inference continuously, even when demand is low.

This can waste resources.

## Bounded Use

A bounded system runs only when it is needed.

Possible techniques include:

- Batching requests
- Caching results
- Scheduling jobs
- Running workloads at appropriate times
- Escalating difficult requests to larger models only when necessary

### Example

Instead of using a large AI model for every simple request:

**Simple request → Small model**

**Difficult request → Larger model**

This can reduce unnecessary compute.

### Key principle

> **Do not spend resources when they are not needed.**

---

# 15. Lifecycle Accountability

## What is Lifecycle Accountability?

**Lifecycle accountability** means treating sustainability as a responsibility throughout the entire life of an AI system.

It includes:

1. Design
2. Development
3. Deployment
4. Scaling
5. Updates
6. Operation
7. Decommissioning

Sustainability should not be considered only after the system has already been built.

### Remember

> **Responsible from beginning to end.**

---

# 16. Lock-In

## What is Lock-In?

**Lock-in** occurs when early decisions become difficult or expensive to change later.

For example, an organisation may choose:

- A particular data-centre location
- A particular power source
- A particular cooling technology
- A particular infrastructure scale

Once the infrastructure becomes large, changing these choices may be extremely difficult.

### Ethical lesson

> **Early decisions can determine future environmental impacts.**

Therefore, sustainability should be considered **before** major investments are made.

---

# 17. PUE — Power Usage Effectiveness

## What is PUE?

**PUE (Power Usage Effectiveness)** is a data-centre efficiency metric.

It compares:

**Total facility energy ÷ Energy used by IT equipment**

### Formula

**PUE = Total Data Centre Energy / IT Equipment Energy**

A lower PUE generally indicates better energy efficiency.

### Example

If a data centre uses:

- 1,500 kWh total energy
- 1,000 kWh for IT equipment

Then:

**PUE = 1,500 ÷ 1,000 = 1.5**

The remaining energy is used for things such as cooling and other facility operations.

### Remember

> **PUE asks: “How much extra facility energy is needed to support the computers?”**

---

# 18. WUE — Water Usage Effectiveness

## What is WUE?

**WUE (Water Usage Effectiveness)** measures water consumption in relation to IT energy use.

It helps organisations understand the water intensity of data-centre operations.

### Why does it matter?

AI systems may require significant cooling.

In areas where water is scarce, water consumption can become a major ethical concern.

### Remember

> **PUE = Energy efficiency**

> **WUE = Water efficiency**

---

# 19. Carbon Offsets

## What are Carbon Offsets?

Carbon offsets attempt to compensate for emissions by supporting activities that reduce or remove emissions elsewhere.

For example, an organisation may fund an external environmental project.

However:

> **Offsets should not replace actual emission reductions.**

A company should first try to reduce its own environmental impact.

### Good principle

**First reduce → Then compensate where appropriate**

Not:

**Pollute → Buy offsets → Continue polluting**

---

# 20. Carbon-Aware Scheduling

## What is Carbon-Aware Scheduling?

Carbon-aware scheduling means moving flexible computing workloads to:

- Times when electricity is cleaner
- Regions where electricity has lower carbon intensity

For example, if a computing job does not need to run immediately, it may be scheduled for a period when renewable electricity is more available.

### Important condition

This works best for **flexible workloads**.

Critical real-time workloads may not be able to wait.

### Remember

> **If the job can wait, run it when electricity is cleaner.**

---

# 21. Small Language Models (SLMs)

## What is an SLM?

A **Small Language Model (SLM)** is a smaller AI model that generally requires less:

- Memory
- Compute
- Electricity
- Infrastructure

For some specific tasks, an SLM can provide accuracy comparable to a much larger model.

### Example

A library may need an AI system to:

- Classify documents
- Detect document language
- Extract metadata
- Answer simple questions about a known collection

A small specialised model may be sufficient.

### Ethical principle

> **Choose the model that matches the task.**

---

# 22. Model Compression and Distillation

## Model Compression

Model compression reduces the size or computational requirements of a model while trying to preserve its useful performance.

## Knowledge Distillation

**Distillation** trains a smaller model to reproduce useful behaviour learned by a larger model.

Think of it as:

**Large teacher model → Smaller student model**

The goal is to keep much of the useful capability while reducing resource requirements.

### Remember

> **Distillation = Teach a smaller model what the bigger model knows.**

---

# 23. Quantization

## What is Quantization?

**Quantization** reduces the numerical precision used to represent model parameters.

Instead of storing values with high numerical precision, the model can use lower-precision representations.

This can reduce:

- Model size
- Memory requirements
- Compute requirements
- Energy consumption

### Simple idea

> **Less numerical precision → Smaller model representation → Potentially less resource use**

The trade-off is that too much compression may reduce model accuracy.

---

# 24. Software Carbon Intensity (SCI)

## What is SCI?

**Software Carbon Intensity (SCI)** is a standardised methodology for calculating the carbon emissions associated with running software.

It provides a way to measure and compare the carbon intensity of software systems.

The methodology is standardised under **ISO/IEC 21031:2024**.

### Why is SCI useful?

It encourages developers to ask:

- How much carbon does this software generate?
- Can we reduce the amount?
- Does a new version improve or worsen efficiency?
- Which design is more environmentally efficient?

### Remember

> **SCI helps make software carbon impact measurable.**

---

# 25. Scale Creep

## What is Scale Creep?

**Scale creep** happens when an AI system gradually expands in:

- Number of users
- Number of requests
- Features
- Data
- Model size
- Infrastructure

The expansion may happen quietly.

As usage grows:

**More users → More inference → More compute → More energy → Larger footprint**

The problem is that governance may not grow at the same speed.

### Key lesson

> **A small environmental impact can become a large impact at scale.**

---

# 26. Decision Gates

## What are Decision Gates?

**Decision gates** are checkpoints where sustainability is deliberately considered before moving forward.

They can occur during:

### Gate 1 — Site Selection
Ask:

- Is water available?
- What is the electricity source?
- What are the local environmental risks?

### Gate 2 — System Design
Ask:

- Can we use a smaller model?
- Can we reduce compute?
- Can we design bounded use?

### Gate 3 — Deployment
Ask:

- Is the system actually needed at this scale?
- Are we measuring energy and water use?

### Gate 4 — Operations
Ask:

- Is usage growing?
- Are environmental impacts increasing?
- Can workloads be scheduled more efficiently?

### Gate 5 — Decommissioning
Ask:

- What happens to old hardware?
- Can equipment be reused or recycled?
- How will the system be safely retired?

### Remember

> **Decision gates prevent sustainability problems before they become expensive to fix.**

---

# 27. Putting Everything Together: The AI Sustainability Lifecycle

A simple way to understand the entire module is to follow the lifecycle:

```text
                 AI SYSTEM LIFECYCLE

       ┌─────────────────────────────┐
       │  1. DESIGN                  │
       │  Choose model + architecture│
       └──────────────┬──────────────┘
                      ↓
       ┌─────────────────────────────┐
       │  2. BUILD / TRAIN           │
       │  Compute + GPUs + Energy    │
       └──────────────┬──────────────┘
                      ↓
       ┌─────────────────────────────┐
       │  3. DEPLOY                  │
       │  Servers + Data Centre      │
       └──────────────┬──────────────┘
                      ↓
       ┌─────────────────────────────┐
       │  4. INFERENCE AT SCALE      │
       │  Queries + Compute + Cooling│
       └──────────────┬──────────────┘
                      ↓
       ┌─────────────────────────────┐
       │  5. UPDATE / EXPAND         │
       │  Scale Creep + Lock-In      │
       └──────────────┬──────────────┘
                      ↓
       ┌─────────────────────────────┐
       │  6. DECOMMISSION             │
       │  Reuse + Recycling + E-waste│
       └─────────────────────────────┘
```

At every stage, ask:

> **What resources are we consuming, who benefits, and who bears the costs?**

---

# 28. The Four Main Environmental Questions

When evaluating an AI system, remember these four questions:

## 1. Energy
**How much electricity does it require?**

Think:

- Compute
- GPUs
- Data centres
- PUE
- Carbon-aware scheduling

## 2. Water
**How much water does it require?**

Think:

- Cooling
- Data centres
- WUE
- Local water availability

## 3. Materials
**What physical resources are required?**

Think:

- Chips
- Servers
- GPUs
- Raw materials
- Manufacturing

## 4. Waste
**What happens when the hardware becomes obsolete?**

Think:

- Hardware replacement
- E-waste
- Reuse
- Recycling
- Disposal

### Easy memory trick

**E-W-M-W**

> **Energy → Water → Materials → Waste**

---

# 29. Ethical Questions to Ask About AI Sustainability

Before approving an AI system, ask:

### About necessity
- Do we actually need AI?
- What problem is it solving?
- Is the environmental cost justified by the benefit?

### About efficiency
- Are we using the smallest suitable model?
- Can we use an SLM?
- Can we compress or quantize the model?
- Can we reduce unnecessary inference?

### About operations
- Does the system need to be always-on?
- Can we use caching?
- Can we batch workloads?
- Can flexible workloads be scheduled during cleaner-energy periods?

### About resources
- How much electricity is being used?
- How much water is being consumed?
- What hardware is required?

### About fairness
- Who receives the benefits?
- Who experiences the environmental costs?
- Are local communities affected?

### About the future
- What happens when usage scales?
- Are we creating lock-in?
- What happens to old hardware?
- Can the system be retired responsibly?

---

# 30. A Practical Example

Imagine a university wants to deploy an AI chatbot for its library.

There are two possible designs.

## Option A — Large Model for Everything

Every question is sent to a very large model.

```text
Every question
      ↓
Large model
      ↓
High compute
      ↓
More electricity
      ↓
More cooling
```

This may provide excellent general capability, but it may use more resources than necessary.

## Option B — Right-Sized AI

```text
Simple question
      ↓
Small model / cached answer
      ↓
Low compute

Difficult question
      ↓
Large model
      ↓
Higher compute
```

This approach uses the larger model only when necessary.

### Ethical advantage

Option B may provide a better balance between:

- Service quality
- Cost
- Energy use
- Environmental impact

The correct choice, however, should be based on actual measurement and requirements—not simply on the assumption that smaller is always better.

---

# 31. Key Relationships to Remember

## Relationship 1

**More compute → More energy demand**

## Relationship 2

**More energy + cooling → Greater operational impact**

## Relationship 3

**More hardware → Greater embodied impact**

## Relationship 4

**More hardware replacement → More e-waste**

## Relationship 5

**More users → More inference**

## Relationship 6

**More inference at scale → Potentially larger environmental footprint**

## Relationship 7

**Better right-sizing → Less unnecessary resource use**

## Relationship 8

**Early decisions → Future lock-in**

---

# 32. Quick Glossary for Revision

| Term | Easy Meaning |
|---|---|
| **Environmental sustainability** | Managing AI's environmental and social impacts across its full lifecycle |
| **Invisible lifecycle** | Hidden physical infrastructure behind AI use |
| **Compute** | Processing power needed by AI |
| **GPU** | Processor specialised for parallel calculations |
| **Data centre** | Facility containing servers, storage, networking and cooling |
| **Training** | Building the AI model |
| **Inference** | Using the trained model |
| **Embodied impact** | Impact from making and disposing of hardware |
| **Operational impact** | Impact from running the system |
| **E-waste** | Discarded electronic equipment |
| **Externality** | Cost shifted to others |
| **Materiality** | Identifying the most important impacts |
| **Impact hotspot** | Lifecycle area with the largest impact |
| **Right-sizing** | Using enough capacity, not excessive capacity |
| **Bounded use** | Running AI only when needed |
| **Lifecycle accountability** | Managing sustainability from design to retirement |
| **Lock-in** | Early decisions becoming difficult to change |
| **PUE** | Data-centre energy efficiency metric |
| **WUE** | Data-centre water efficiency metric |
| **Carbon offsets** | Compensating for emissions elsewhere |
| **Carbon-aware scheduling** | Running flexible workloads when/where electricity is cleaner |
| **SLM** | Smaller language model |
| **Distillation** | Training a smaller model from a larger model |
| **Quantization** | Reducing numerical precision to reduce resource use |
| **SCI** | Method for measuring software carbon intensity |
| **Scale creep** | Growth in usage/features that increases impact |
| **Decision gates** | Checkpoints for sustainability decisions |

---

# 33. Exam-Friendly Memory Framework

Remember:

## **“AI USES RESOURCES”**

**A — Assess the need**  
Do we really need AI?

**I — Identify hotspots**  
Where are the biggest environmental impacts?

**U — Use the right size**  
Choose the smallest suitable model.

**S — Schedule intelligently**  
Use batching, caching and carbon-aware scheduling.

**E — Evaluate the lifecycle**  
Consider design, operation, hardware and disposal.

**R — Reduce waste**  
Reuse, recycle and avoid unnecessary hardware replacement.

**E — Examine externalities**  
Who benefits and who bears the costs?

**S — Scale responsibly**  
Do not allow usage to grow faster than governance.

**O — Observe metrics**  
Measure energy, water, carbon and efficiency.

**U — Use decision gates**  
Check sustainability before major commitments.

**R — Review continuously**  
Sustainability is an ongoing responsibility.

**C — Consider communities**  
Include local and social impacts.

**E — End responsibly**  
Plan for decommissioning and e-waste.

**S — Sustain the system**  
Keep environmental responsibility throughout the lifecycle.

---

# 34. The Most Important Lessons

If you remember only **10 things** from this module, remember these:

1. **AI is physical, not just digital.**
2. **Every AI query has an invisible infrastructure behind it.**
3. **Compute consumes electricity and requires cooling.**
4. **AI affects energy, water, materials and waste—not carbon alone.**
5. **Training builds the model; inference uses the model.**
6. **At large scale, inference can become a major environmental hotspot.**
7. **Use the smallest model and infrastructure that can meet the need.**
8. **Do not shift environmental costs onto communities or future generations.**
9. **Make sustainability decisions early because infrastructure can create lock-in.**
10. **Environmental responsibility must continue from design to decommissioning.**

---

# 35. Final Takeaway

The central ethical question is not:

> **“Can we build this AI system?”**

It is:

> **“Should we build it this way, at this scale, using these resources, and who will bear the consequences?”**

Responsible AI therefore requires us to balance:

**AI benefits**

against

**Energy + Water + Materials + Waste + Social impacts**

The goal is not necessarily to stop using AI.

The goal is to build and operate AI that is:

**Useful + Efficient + Measurable + Fair + Sustainable**

---

## One-Sentence Summary

> **AI sustainability means making sure the benefits of AI justify its environmental and social costs across the entire lifecycle, while continuously reducing unnecessary resource use.**
