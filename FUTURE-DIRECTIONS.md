# FUTURE DIRECTIONS — Hardware–Software Co-Evolution of Intelligence

## Research Agenda Beyond the First HSCI Cycle

**Repository:** Hardware–Software Co-Evolution of Intelligence
**Abbreviation:** HSCI
**Status:** Future Research Agenda
**Version:** 1.0
**Date:** 2026

---

# 1. Purpose

The first HSCI research cycle establishes four connected ideas:

```text
HSCI-001
Hardware–Software Co-Evolution of Intelligence
        ↓

HSCI-002
Intelligence Before Representation
        ↓

HSCI-003
Hardware Function Tunnels
and Multi-Substrate Brain-Unit AI
        ↓

HSCI-004
Autonomous Drones as a
Canonical Engineering Testbed
```

The next phase should not simply add more concepts.

It should ask:

> **Which parts of HSCI can be measured, formalized, implemented, falsified, and reused?**

The priority is therefore to move from:

```text
Conceptual Architecture
```

toward:

```text
Operational Definitions
        ↓
Measurement
        ↓
Runtime Design
        ↓
A/B Experiments
        ↓
Structural Learning
        ↓
Engineering Validation
```

---

# 2. Future Direction 1 — Operationalize the Structural Consequence Boundary

One of the most important concepts introduced by HSCI is the:

# Structural Consequence Boundary — SCB

The conceptual definition is:

> **The Structural Consequence Boundary is the transition at which a physical or sensory difference begins to alter downstream computational structure, routing, state, control, or action.**

The next research step is to make SCB measurable.

Possible observable effects include:

```text
Route Switch
State Change
Attention Increase
Sampling Increase
Memory Write
Specialist Activation
Controller Change
Emergency Trigger
Action Change
```

A possible operational question is:

> **Can structural consequence be quantified without requiring semantic interpretation?**

---

# 3. SCB Metrics

Candidate SCB metrics may include:

$$
\Delta R
$$

for routing change,

$$
\Delta S
$$

for runtime-state change,

$$
\Delta C
$$

for computational allocation,

and:

$$
\Delta A
$$

for action change.

A conceptual structural-consequence score might therefore take the form:

$$
SC
=
w_r \Delta R
+
w_s \Delta S
+
w_c \Delta C
+
w_a \Delta A
$$

This is not yet a canonical equation.

Its purpose is to define an experimental direction:

> **When does a signal stop being merely transformed and begin changing the architecture of what happens next?**

---

# 4. Future Direction 2 — Build a Taxonomy of Pre-Representational Intelligence Primitives

HSCI currently introduces:

# PRIP — Pre-Representational Intelligence Primitive

The next step is to classify PRIPs systematically.

Possible families include:

```text
Physical Selectivity
Resonance
Thresholding
Event Detection
Salience Generation
Structural Triggering
Local Routing
Reflex Control
Structural Anchoring
Sparse Memory Activation
```

Each primitive should be described by:

```text
Input Domain
Selective Mechanism
Structural Consequence
Latency
Energy
Adaptability
Failure Regime
Escape Path
```

This would turn PRIP from a conceptual category into an engineering vocabulary.

---

# 5. Future Direction 3 — Formalize Hardware Intelligence Primitives

A narrower subset is:

# Hardware Intelligence Primitive — HIP

A future HIP taxonomy could distinguish:

```text
Sensor HIP
Analog HIP
Mechanical HIP
Optical HIP
Acoustic HIP
Thermal HIP
Neuromorphic HIP
Control HIP
```

The important research question is not:

> Is this device intelligent?

It is:

> **Which intelligence-relevant distinction does this physical mechanism perform?**

This keeps the concept operational rather than rhetorical.

---

# 6. Future Direction 4 — Hardware Function Tunnel Detection

HSCI introduces:

# Hardware Function Tunnel — HFT

A key future problem is automatic detection.

Suppose a runtime repeatedly observes:

```text
Pattern X
   ↓
Salience Y
   ↓
Trigger Z
   ↓
Action A
   ↓
Successful Outcome
```

Can the system recognize that:

```text
X → Y → Z → A
```

is becoming a stable Function Tunnel?

Possible indicators include:

```text
High Usage Frequency
Low Structural Variance
High Outcome Consistency
Low Semantic Ambiguity
High Latency Sensitivity
High Compute Cost
```

This creates a direct bridge between runtime traces and structural optimization.

---

# 7. Future Direction 5 — Automatic Hardware Candidate Detection

Once a stable software Function Tunnel exists, the next question is:

> **Should it remain software?**

A candidate hardware score might consider:

$$
H(F)
=
w_1 U
+
w_2 S
+
w_3 L
+
w_4 E
-
w_5 A
-
w_6 V
$$

where:

* \(U\) = usage frequency,
* \(S\) = structural stability,
* \(L\) = latency benefit,
* \(E\) = energy benefit,
* \(A\) = adaptation requirement,
* \(V\) = environmental variability.

High \(H(F)\) would not automatically imply hardware migration.

It would identify:

# Hardware Consolidation Candidates

for further testing.

---

# 8. Future Direction 6 — Intelligence Placement Compiler

A longer-term engineering goal is an:

# Intelligence Placement Compiler

Instead of compiling only:

```text
Software
   ↓
Machine Instructions
```

the system would analyze an intelligent function and ask:

```text
Should this function live in:

Physical Structure?
Sensor?
Analog?
Boolean?
CCC?
ANN?
World Model?
LLM?
```

The output might be:

```text
Function F1 → Sensor
Function F2 → Boolean
Function F3 → CCC
Function F4 → ANN
Function F5 → World Model
Function F6 → LLM
```

This would make HSCI placement an explicit system-design process.

---

# 9. Future Direction 7 — Dynamic Intelligence Placement

Placement should not necessarily be static.

The same function may move depending on runtime conditions.

For example:

```text
Normal Battery
   ↓
ANN Path

Low Battery
   ↓
Local FT

High Risk
   ↓
World Model + Redundancy

Emergency
   ↓
Fast Hardware / Control Path
```

This suggests:

# Dynamic Per-Function Intelligence Placement

where placement depends on:

```text
Energy State
Risk State
Urgency
Confidence
Compute Load
Sensor Health
Network Availability
Mission State
```

---

# 10. Future Direction 8 — Placement Frontier

A useful engineering tool would be an:

# Intelligence Placement Frontier

For a given function, compare candidate implementations in:

```text
Energy
Latency
Accuracy
Reliability
Adaptability
Physical Cost
Governance Cost
```

A placement frontier could reveal that no single implementation dominates every metric.

For example:

```text
Hardware
→ lowest latency

ANN
→ highest adaptive accuracy

CCC
→ highest auditability

World Model
→ best temporal context
```

The real decision then becomes policy-dependent.

---

# 11. Future Direction 9 — Representation-Cost Accounting

HSCI makes an important claim:

> **Representation itself has cost.**

Future work should measure that cost explicitly.

A representation-cost decomposition might include:

```text
Sampling
ADC
Transfer
Memory
Preprocessing
Feature Construction
Embedding
Inference
State Maintenance
Synchronization
```

A useful system-level quantity could be:

$$
C_{rep}
=
C_{sense}
+
C_{convert}
+
C_{move}
+
C_{store}
+
C_{construct}
+
C_{maintain}
$$

This would allow direct comparison between:

```text
Represent Everything
```

and:

```text
Select First
Represent Selectively
```

---

# 12. Future Direction 10 — Structural Intelligence per Representation Cost

One candidate metric introduced in HSCI is:

# Structural Intelligence per Representation Cost

A future benchmark might define:

$$
SIR
=
\frac{
\text{Useful Structural Decisions}
}{
C_{rep}
}
$$

A more refined version could incorporate:

```text
Correctness
Safety
Latency
Energy
```

The goal is not to produce one universal score.

It is to expose an overlooked architectural dimension:

> **How much useful intelligence is obtained before expensive representation is constructed?**

---

# 13. Future Direction 11 — Salience-Triggered Computation

A highly practical research path is:

# Salience-Triggered AI

Instead of continuously running expensive models:

```text
Sensor
  ↓
ANN
  ↓
ANN
  ↓
ANN
  ↓
...
```

use:

```text
Sensor
  ↓
Salience Gate
  ↓
ANN only when needed
```

This can be tested in:

```text
Vision
Audio
Industrial Monitoring
Robotics
Drones
Wearables
Edge AI
```

The primary metrics are simple:

```text
Model Calls
Energy
Latency
Miss Rate
False Trigger Rate
```

---

# 14. Future Direction 12 — Anchor-Driven Structural Mapping

HSCI proposes that salient events may act as:

```text
Anchor
Trigger
Structural Organizer
```

Future research can test whether Anchor formation improves early structural organization.

For sequences:

```text
Anchor
  ↓
Before / After Structure
  ↓
Sequence Starmap
```

For images:

```text
Anchor
  ↓
Local Spatial Relations
  ↓
Image Starmap
```

This creates a possible bridge between:

```text
Pre-Representational Intelligence
```

and:

```text
Structured Representation
```

---

# 15. Future Direction 13 — Starmap Before World Model

A particularly interesting question is:

> **Can useful local structural maps be formed before a full world model?**

Instead of:

```text
Raw Data
   ↓
Full Scene Model
   ↓
Relations
```

consider:

```text
Salient Anchor
   ↓
Local Relations
   ↓
Starmap
   ↓
Selective World-Model Construction
```

This may reduce representation cost while preserving decision-relevant structure.

---

# 16. Future Direction 14 — Structural Recognition Benchmarks

Most recognition benchmarks emphasize:

```text
What is this?
```

HSCI suggests a complementary benchmark family:

# Structural Recognition Benchmarks

Questions may include:

```text
Is something changing?
Is something approaching?
Is something unstable?
Is something anomalous?
Is something structurally important?
Does this event require escalation?
```

These tasks may not require full semantic identity.

They would directly test:

# Recognition Before Recognition

---

# 17. Future Direction 15 — Multi-Timescale Intelligence Runtime

HSCI proposes that intelligence operates on different clocks.

A future runtime should coordinate:

```text
μs–ms
Physical / Hardware

ms
Trigger

ms–10 ms
Control

10–100 ms
CCC / ANN

100 ms–seconds
World Model

seconds+
LLM / Brain Unit
```

The key problem is not simply execution.

It is:

# Cross-Timescale State Coordination

Fast paths must act without waiting.

Slow paths must later:

```text
Confirm
Correct
Explain
Update
Learn
```

---

# 18. Future Direction 16 — Runtime Reconciliation

Parallel intelligence paths can disagree.

For example:

```text
Hardware FT:
HIGH RISK

ANN:
UNCERTAIN

World Model:
LOW RISK
```

Future research must define:

```text
Authority
Confidence
Urgency
Risk
Reversibility
Sensor Health
```

and determine how they combine.

This creates a new problem:

# Multi-Substrate Runtime Arbitration

---

# 19. Future Direction 17 — Capability–Authority Separation

A central HSCI architectural principle is:

> **Capability hierarchy is not authority hierarchy.**

Future Brain-Unit systems should explicitly represent both.

For example:

```text
LLM
Capability: High
Emergency Authority: Low

Collision FT
Capability: Narrow
Emergency Authority: High
```

This distinction should become machine-readable.

A runtime object may therefore contain:

```text
Capability Scope
Authority Scope
Priority
Allowed Actions
Escalation Rights
Override Rules
```

---

# 20. Future Direction 18 — Governed Function Tunnels

Every Function Tunnel should eventually become a governable runtime object.

A canonical FT definition could include:

```text
FT-ID
Purpose
Input Domain
Entry Condition
Structural Path
Runtime Invariant
Output
Confidence
Authority
Priority
Escape Condition
Fallback
Audit Fields
```

This would connect HSCI directly with runtime invariant architecture and structural governance.

---

# 21. Future Direction 19 — Function-Tunnel Certification

Once Function Tunnels can directly control physical systems, a certification layer becomes important.

Possible certification dimensions include:

```text
Input Validity
Invariant Coverage
Latency Bound
Failure Rate
False Trigger Rate
Miss Rate
Escape Reliability
Policy Compliance
Trace Completeness
```

A certified HFT could become a reusable runtime primitive.

---

# 22. Future Direction 20 — Function-Tunnel Escape Design

Fast narrow intelligence requires explicit escape.

Future work should study:

```text
When should a tunnel stop trusting itself?
```

Signals may include:

```text
Sensor Conflict
Out-of-Range Input
Novel Pattern
Low Confidence
Invariant Violation
Unexpected Outcome
Control Saturation
```

A healthy FT should have:

```text
Fast Path
+
Failure Detection
+
Escape Path
```

not merely a fast path.

---

# 23. Future Direction 21 — Hardware–Software Bidirectional Migration

A mature HSCI architecture should support both:

```text
Software → Hardware
```

and:

```text
Hardware → Software
```

### Downward

```text
Repeated Stable Pattern
      ↓
Structural Consolidation
```

### Upward

```text
Novelty / Failure
      ↓
Flexible Re-Interpretation
```

The resulting architecture is not permanently layered.

It is dynamically evolvable.

---

# 24. Future Direction 22 — Structural Continual Learning

Continual learning is often modeled as:

```text
New Data
   ↓
Parameter Update
```

HSCI suggests a broader form:

```text
Consistency Failure
      ↓
Candidate Difference
      ↓
New Branch
      ↓
New Function Tunnel
      ↓
Placement Optimization
      ↓
Structural Consolidation
```

This creates:

# Structural Continual Learning

where the architecture itself grows.

---

# 25. Future Direction 23 — Dispatch-Tree Growth

Brain-Unit intelligence may use a dispatch tree:

```text
Event
  ↓
Which Intelligence Path?
```

Repeated consistency failures can drive:

```text
Existing Branch
      ↓
Failure
      ↓
Candidate Difference
      ↓
A/B
      ↓
New Branch
```

Over time, the Brain Unit becomes structurally richer.

This creates a strong bridge between:

```text
Continual Learning
```

and:

```text
Hardware–Software Co-Evolution
```

---

# 26. Future Direction 24 — Structural Consolidation Ladder

A newly discovered function may begin at a highly flexible layer:

```text
Human
  ↓
LLM
  ↓
World Model
  ↓
ANN
  ↓
CCC
  ↓
Boolean
  ↓
Hardware
```

Future work should identify the conditions under which each transition is justified.

This creates a:

# Structural Consolidation Ladder

The ladder should be reversible.

---

# 27. Future Direction 25 — Autonomous Drone Validation Program

Autonomous drones remain the most immediate engineering testbed.

A minimal program should prioritize four experiments:

```text
1. Collision Salience

2. Vibration / Propulsion Anomaly

3. Salience-Triggered ANN Activation

4. Emergency Fast Path + Parallel Semantic Path
```

Each experiment should compare:

```text
Representation-First Architecture
```

against:

```text
HSCI Architecture
```

---

# 28. Drone Validation Metrics

The most important measurements are:

```text
Energy
Latency
ANN Calls
Memory Traffic
Data Movement
Flight Time
False Trigger Rate
Miss Rate
Minimum Safe Distance
Recovery Time
Control Stability
```

HSCI should succeed or fail on system-level metrics.

Not on conceptual elegance alone.

---

# 29. Future Direction 26 — Drone Body Intelligence

A deeper drone research direction concerns the physical body itself.

Potential information sources include:

```text
Airframe Vibration
Motor Current
Propeller Acoustics
IMU Residuals
Thermal Distribution
Pressure
Airflow
Mechanical Flex
```

The question is:

> **Can the body reveal structural problems before general digital diagnosis?**

This could produce new Hardware Function Tunnels for:

```text
Damage
Instability
Payload Shift
Motor Failure
Environmental Disturbance
```

---

# 30. Future Direction 27 — Recognition Before Recognition in Robotics

The drone example generalizes.

A robot may first determine:

```text
Something is unstable.
```

before:

```text
The cup is falling.
```

or:

```text
Something is entering my safety zone.
```

before:

```text
The moving object is a human arm.
```

This suggests a broad robotics research program around:

# Structural Significance Before Semantic Identity

---

# 31. Future Direction 28 — Edge AI and Low-Power Intelligence

HSCI may be particularly useful where power is constrained.

Candidate domains include:

```text
Wearables
Industrial Sensors
Remote Monitoring
Agricultural Robotics
Underwater Robotics
Space Systems
IoT
Embedded Medical Devices
```

The recurring question is:

> **Can early structural intelligence suppress unnecessary high-level computation?**

---

# 32. Future Direction 29 — Neuromorphic HSCI

Neuromorphic computing is a natural neighboring field.

HSCI can contribute a placement-oriented question:

> **Which intelligence functions should be mapped into event-driven, local, low-power neural hardware?**

This is different from simply accelerating ANN inference.

The relevant goal is:

```text
Early Selection
+
Sparse Activation
+
Local Structural Consequence
```

---

# 33. Future Direction 30 — Physical Intelligence Beyond Electronics

Hardware intelligence should not be restricted to chips.

Possible substrates include:

```text
Mechanical Structure
Optics
Acoustics
Materials
Fluid Dynamics
Thermal Structure
Morphology
```

A provocative but testable question is:

> **Can material or physical structure perform useful intelligent discrimination before electronics become involved?**

This should be studied carefully without equating all physical behavior with intelligence.

---

# 34. Future Direction 31 — Music, Rhythm, and Sequence Anchoring

The resonance discussion suggests a research direction around temporal structure.

A conservative hypothesis is:

```text
Selective Response
      ↓
Salience
      ↓
Anchor
      ↓
Sequence Organization
```

Future work may ask whether strong temporal or frequency anchors help construct:

```text
Rhythm
Prediction
Segmentation
Expectation
Sequence Starmaps
```

This remains a hypothesis domain and should be clearly separated from established biological claims.

---

# 35. Future Direction 32 — Biological Comparison Without Biological Overclaim

HSCI is inspired partly by evolutionary reasoning.

Future biological comparison should distinguish three levels:

```text
Established Biological Observation

Plausible Structural Analogy

Speculative Evolutionary Hypothesis
```

These should never be merged.

This allows biology to guide engineering questions without using evolutionary narratives as proof.

---

# 36. Future Direction 33 — Evolutionary MET Formalization

The current evolutionary MET is conceptual.

A future research program may study how selection trades off:

```text
Energy
Latency
Material Cost
Developmental Cost
Reliability
Adaptability
Survival Value
```

The main question is not to reduce evolution to one equation.

It is to understand:

> **Why certain distinctions become physically specialized rather than remaining general-purpose computation.**

---

# 37. Future Direction 34 — Hardware Intelligence Economics

HSCI also has an economic dimension.

A function that is frequently executed may justify specialized hardware because:

```text
Development Cost
        ↓
Amortized Across
Millions / Billions of Executions
```

This creates a trade-off between:

```text
Flexibility
```

and:

```text
Marginal Execution Cost
```

Future work could model when specialization becomes economically rational.

---

# 38. Future Direction 35 — Intelligence Capital Across Substrates

A mature system may accumulate reusable intelligence in different forms:

```text
Hardware Capital
Sensor Capital
Function-Tunnel Capital
ANN Capital
World-Model Capital
Policy Capital
LLM / Knowledge Capital
```

This suggests that system capability may depend not only on model size, but on the portfolio of reusable intelligence structures already available.

---

# 39. Future Direction 36 — Brain-Unit AI Runtime

The long-term architectural destination is a Brain Unit that coordinates multiple substrates.

A mature Brain Unit may contain:

```text
Physical Intelligence
Sensor Intelligence
PRIPs
HFTs
Boolean
CCC
ANN Specialists
World Models
Trajectory Intelligence
Emergency Intelligence
LLM
Memory
Policy
Runtime Invariants
Human Escalation
```

Its primary intelligence function may increasingly become:

# Dispatch

rather than:

# Universal Computation

---

# 40. Future Direction 37 — Brain-Unit Intelligence Placement Policy

A Brain Unit should be able to answer:

```text
Which intelligence?
Which substrate?
Which clock?
Which authority?
Which fallback?
```

for each event.

This turns intelligence placement into runtime governance.

A canonical decision may include:

$$
Route
=
f(
Urgency,
Risk,
Novelty,
Confidence,
Energy,
Capability,
Authority
)
$$

---

# 41. Future Direction 38 — Multi-Brain Intelligence

Different Brain Units may specialize.

For example:

```text
Flight Brain
Vision Brain
Mechanical Health Brain
Mission Brain
Communication Brain
Human-Interaction Brain
```

Each can contain its own multi-substrate Function Tunnels.

The larger system then becomes:

# Multi-Brain Multi-Substrate Intelligence

This creates another scale of routing and governance.

---

# 42. Future Direction 39 — Collective Hardware–Software Co-Evolution

Once multiple systems share validated structural knowledge, a pattern discovered by one system may become:

```text
Shared Software Rule
      ↓
Validated Function Tunnel
      ↓
Common Hardware Candidate
```

This suggests a future collective-learning pipeline from field experience to hardware redesign.

The loop becomes:

```text
Fleet Experience
      ↓
Structural Pattern
      ↓
Shared FT
      ↓
Hardware Revision
      ↓
Next Generation Fleet
```

This would be a literal engineered co-evolution cycle.

---

# 43. Future Direction 40 — HSCI Benchmark Suite

A future HSCI benchmark suite should include tasks across multiple placement layers.

Possible categories:

```text
SCB Detection

Salience Triggering

Structural Recognition

Selective Representation

Function-Tunnel Efficiency

Escalation Quality

Hardware Consolidation Benefit

Multi-Timescale Coordination

Runtime Arbitration

Energy / Latency / Safety Trade-Off
```

The benchmark should evaluate systems, not only models.

---

# 44. A Canonical HSCI Experiment Template

Every future HSCI experiment should report:

```text
Function
Baseline Architecture
Candidate Placement
Input
Output
Runtime Invariant
Escape Path
Energy
Latency
Compute
Accuracy
False Positive
False Negative
Safety Impact
Representation Cost
Outcome
```

This would make experiments comparable.

---

# 45. Research Discipline

HSCI is intentionally broad.

That creates a risk of becoming unfalsifiable.

Future work should therefore follow four rules.

## Rule 1 — Separate Theory From Evidence

A conceptual possibility is not an empirical result.

## Rule 2 — Define the Placement

Every claimed intelligence function should identify its substrate.

## Rule 3 — Measure the Trade-Off

Energy or latency gains should not hide safety or reliability losses.

## Rule 4 — Permit Rejection

If a hardware or pre-representational placement does not improve the relevant MET, reject it.

---

# 46. Three Evidence Zones

Future HSCI documents should distinguish:

## Confirmed Zone

Supported by existing engineering or experimental evidence.

## Extension Zone

Reasonable architectural extrapolation from known mechanisms.

## Speculative Zone

Hypotheses requiring significant validation.

This is especially important for:

```text
Evolution
Biological Resonance
Pleasure / Valence
Animal Cognition
Physical Intelligence
```

---

# 47. Near-Term Roadmap

The most valuable near-term work is not to expand HSCI into dozens of documents.

It is to validate the core framework.

Recommended order:

```text
Step 1
SCB Operational Definition

Step 2
PRIP / HIP Taxonomy

Step 3
Drone Architecture A/B Specification

Step 4
Salience-Triggered ANN Experiment

Step 5
Hardware Function Tunnel Trace Format

Step 6
Placement Metrics

Step 7
Dispatch-Tree Growth Experiment

Step 8
Structural Consolidation Experiment
```

---

# 48. Medium-Term Roadmap

Once the basic measurements are stable:

```text
HFT Candidate Detector
        ↓
Dynamic Intelligence Placement
        ↓
Runtime Arbitration
        ↓
FT Certification
        ↓
Multi-Timescale Brain Unit
        ↓
Structural Continual Learning
```

This would move HSCI from a conceptual architecture toward a reusable runtime discipline.

---

# 49. Long-Term Roadmap

The longer-term HSCI vision is:

```text
Physical World
      ↓
Distributed Intelligence Primitives
      ↓
Multi-Substrate Function Tunnels
      ↓
Brain-Unit Runtime
      ↓
Structural Continual Learning
      ↓
Automatic Intelligence Placement
      ↓
Hardware–Software Structural Migration
      ↓
Next-Generation Intelligent System
      ↺
```

The system would not merely learn parameters.

It would learn:

```text
what to notice,
where to compute,
when to escalate,
what to consolidate,
and how to reorganize itself.
```

---

# 50. The Deepest Future Question

The deepest question raised by HSCI may not be:

> How intelligent can a model become?

It may be:

> **How much of intelligence should be a model at all?**

Some distinctions may belong in:

```text
Physics
Sensors
Structure
Triggers
Function Tunnels
ANNs
World Models
LLMs
Humans
```

The future architecture may therefore be defined less by one dominant model and more by:

> **the organization of intelligence across substrates.**

---

# 51. Canonical Future Research Questions

### FRQ-1

Can the Structural Consequence Boundary be operationally measured?

### FRQ-2

Can Pre-Representational Intelligence Primitives be systematically classified?

### FRQ-3

Can stable Function Tunnels be discovered automatically from runtime traces?

### FRQ-4

Can software Function Tunnels be ranked for hardware consolidation?

### FRQ-5

Can intelligence placement be optimized dynamically?

### FRQ-6

Can selective representation reduce system cost without unacceptable information loss?

### FRQ-7

Can salience-driven activation significantly reduce ANN and world-model calls?

### FRQ-8

Can local Starmaps organize useful structure before complete semantic representation?

### FRQ-9

Can multi-timescale intelligence outperform serial model-centered pipelines?

### FRQ-10

Can Brain-Unit dispatch trees grow through structural continual learning?

### FRQ-11

Can capability and authority be cleanly separated in runtime governance?

### FRQ-12

Can autonomous drones demonstrate measurable gains from HSCI placement?

### FRQ-13

Can stable learned intelligence migrate safely from software toward hardware?

### FRQ-14

Can failed hardware specialization migrate upward again without destabilizing the system?

### FRQ-15

Can HSCI produce a general engineering methodology for intelligence placement?

---

# 52. What Should Not Be Done Yet

Several tempting directions should remain secondary until the core architecture is validated.

Do not rush into:

```text
Large HSCI Ontology

Dozens of Intelligence Categories

Universal Biological Theory

Claims About Consciousness

Claims That Resonance Explains Pleasure

Claims That Hardware Is Superior to Software

Large Hardware Build Programs Before A/B Evidence
```

The first responsibility is to establish:

```text
Measurement
Validation
Failure Conditions
Reproducibility
```

---

# 53. First Principle for Future Work

The next generation of HSCI research should repeatedly ask:

> **Can this intelligent distinction be detected earlier, placed better, executed cheaper, governed more clearly, and escalated safely?**

If the answer is no, added structure may not be useful.

If the answer is yes, the result may identify a new Function Tunnel.

---

# 54. Second Principle for Future Work

HSCI should resist the assumption that the most general intelligence should perform the most tasks.

Instead:

> **General intelligence should remain available for the distinctions that genuinely require generality.**

This preserves expensive flexibility for high-value uncertainty.

---

# 55. Third Principle for Future Work

Every successful HSCI path should preserve the possibility of escape.

```text
Specialize
   ↓
Monitor
   ↓
Invariant Fails?
   ↓
Escape
   ↓
Re-Evaluate
```

Specialization without escape becomes brittleness.

Co-evolution requires both consolidation and reopening.

---

# 56. Fourth Principle for Future Work

The physical world should be treated not only as an input source.

It can also be treated as:

# A Computational Partner

The design question becomes:

> **What distinction can physics expose before software computes it?**

This may become one of the most productive engineering questions in HSCI.

---

# 57. Fifth Principle for Future Work

The long-term objective is not maximum hardware intelligence.

It is not maximum software intelligence.

It is:

# Optimal Structural Distribution of Intelligence

across:

```text
Physical
Sensory
Structural
Neural
Representational
Generative
Human
```

layers.

---

# 58. Final Roadmap

The HSCI program can be summarized in five stages:

```text
STAGE 1
FOUNDATION
Intelligence Before Representation

        ↓

STAGE 2
MEASUREMENT
SCB / PRIP / Representation Cost

        ↓

STAGE 3
ARCHITECTURE
Function Tunnels / Intelligence Placement

        ↓

STAGE 4
VALIDATION
Autonomous Drone A/B Experiments

        ↓

STAGE 5
EVOLUTION
Structural Learning /
Bidirectional Intelligence Migration /
Brain-Unit AI
```

---

# 59. Closing Perspective

The first HSCI cycle asks whether intelligence may begin before representation.

The next cycle must ask whether that idea can be turned into a measurable engineering advantage.

The important path is therefore:

```text
Physical Difference
      ↓
Structural Consequence
      ↓
Function Tunnel
      ↓
Intelligence Placement
      ↓
Runtime Validation
      ↓
Structural Learning
      ↓
Hardware–Software Co-Evolution
```

The future of HSCI should remain disciplined around one central objective:

> **Place intelligence where it produces the greatest structural value at the lowest sufficient cost.**

And one broader architectural principle:

> **The future of AI may depend not only on how much intelligence a system contains, but on how intelligently that intelligence itself is distributed.**

---

**Hardware–Software Co-Evolution of Intelligence (HSCI)**
**FUTURE DIRECTIONS — Research Agenda Beyond the First HSCI Cycle**
