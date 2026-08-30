# HSCI-004 — Intelligence Before Representation in Autonomous Drones

## A Canonical Testbed for Hardware–Software Structural Intelligence

**Series:** Hardware–Software Co-Evolution of Intelligence (HSCI)
**Document:** HSCI-004
**Status:** Engineering / Validation Framework
**Version:** 1.0
**Date:** 2026
**Language:** English

---

## Abstract

Autonomous drones provide an unusually demanding environment for artificial intelligence.

They must operate under simultaneous constraints on:

* energy,
* weight,
* latency,
* computational capacity,
* communication bandwidth,
* thermal budget,
* reliability,
* flight time,
* and safety.

These constraints make drones a particularly useful engineering testbed for **Hardware–Software Co-Evolution of Intelligence (HSCI)**.

HSCI proposes that intelligence does not necessarily begin after a complete digital or semantic representation has been constructed.

A physical or sensory difference may already participate in intelligence when it creates a meaningful downstream structural consequence such as salience, triggering, routing, state change, control activation, or behavioral response.

This paper applies that principle to autonomous flight.

Instead of requiring every event to traverse:

```text id="3jzhp1"
Sensor
  ↓
Digitization
  ↓
Representation
  ↓
ANN
  ↓
World Model
  ↓
Decision
```

an HSCI drone may support parallel paths:

```text id="jgvjpd"
Physical / Sensor Difference
          ↓
        Salience
          ↓
        Trigger
       ↙       ↘
Emergency FT   Selective Representation
     ↓                   ↓
Fast Control          ANN / World Model
```

The first path may respond to collision risk, instability, vibration anomalies, thermal events, or other urgent structural differences before complete semantic recognition is available.

The second path can continue toward richer recognition, prediction, planning, and explanation.

The architecture therefore separates:

> **knowing that something matters**

from:

> **knowing exactly what it is.**

This paper proposes autonomous drones as a **canonical model organism for structural intelligence engineering** because the benefits and costs of intelligence placement can be measured directly through energy consumption, latency, model activations, data movement, response time, flight duration, false-trigger rate, missed-event rate, and safety outcomes.

The objective is not to prove that hardware intelligence should replace ANN or world-model intelligence.

It is to test a narrower and more practical hypothesis:

> **Can intelligent distinctions placed earlier in the physical and structural pipeline reduce unnecessary computation and improve autonomous response without unacceptable loss of reliability or flexibility?**

---

![Fig-005-Autonomous-Drone-Multi-Substrate-Intelligence.png](./figures/Fig-005-Autonomous-Drone-Multi-Substrate-Intelligence.png)

---

# 1. Why Autonomous Drones?

HSCI is a general intelligence architecture.

But a general architecture requires a concrete experimental environment.

Autonomous drones are especially suitable because they expose the cost of intelligence immediately.

In a large data center, additional computation may primarily increase:

```text id="7cz89s"
Compute Cost
Energy Cost
Latency
```

In a drone, additional computation can also affect:

```text id="5h2a5w"
Battery Life
Flight Time
Payload Capacity
Thermal Load
Control Latency
Communication Dependency
Safety Margin
```

A drone therefore forces a fundamental architectural question:

> **How much intelligence should be performed, where, and when?**

---

# 2. Representation Is Not Free

AI architecture diagrams often treat representation as an abstract intermediate state:

```text id="hsyl3a"
Sensor
  ↓
Representation
  ↓
Model
```

But representation has physical cost.

Constructing a representation may require:

```text id="x9e9id"
Sampling
   ↓
Analog-to-Digital Conversion
   ↓
Data Transfer
   ↓
Memory Write
   ↓
Preprocessing
   ↓
Feature Extraction
   ↓
Model Inference
   ↓
State Maintenance
```

Each stage consumes resources.

For a continuously operating autonomous drone, these costs accumulate.

Therefore:

> **Representation itself should be treated as an engineering resource.**

---

# 3. The Representation-First Drone

A simplified representation-first autonomous architecture may use:

```text id="m3v3pa"
Physical World
      ↓
Sensors
      ↓
Digitization
      ↓
Full Data Stream
      ↓
ANN
      ↓
Object / Event Representation
      ↓
World Model
      ↓
Prediction
      ↓
Planning
      ↓
Control
```

This architecture has an important advantage:

> it creates a rich common computational substrate.

But it also risks forcing many events through expensive stages even when the required response is simple.

For example:

```text id="m67c94"
Rapid Optical Expansion
```

may already strongly indicate:

```text id="y1mkr5"
Immediate Collision Risk
```

before the object has been semantically classified.

---

# 4. The HSCI Drone

An HSCI architecture introduces earlier intelligence paths.

```text id="08k3cy"
                    PHYSICAL WORLD
                          │
                          ▼
                     SENSORS
                          │
                          ▼
             PHYSICAL / SENSOR SELECTIVITY
                          │
                          ▼
                      SALIENCE
                          │
                          ▼
                       TRIGGER
                    ↙           ↘
             Emergency FT      Normal Path
                  │                 │
                  ▼                 ▼
             Fast Control      Representation
                                    │
                                    ▼
                                   ANN
                                    │
                                    ▼
                               World Model
                                    │
                                    ▼
                                 Planning
                                    │
                    ┌───────────────┘
                    ▼
              Runtime Reconciliation
```

The two paths are complementary.

The fast path answers:

> **Must something happen now?**

The slower path answers:

> **What is happening, why, and what should happen next?**

---

# 5. Recognition Before Recognition

Consider a drone approaching an unexpected object.

The conventional semantic sequence may be:

```text id="nbcnd4"
Pixels
  ↓
Object Detection
  ↓
Object Classification
  ↓
Trajectory Estimation
  ↓
Collision Prediction
  ↓
Avoidance
```

But another sequence is possible:

```text id="xxu0op"
Optical Expansion
      +
Motion Discontinuity
      +
Depth Change
      ↓
Structural Salience
      ↓
Collision Trigger
      ↓
Avoid
```

At this stage the system may know:

> **Something is entering a dangerous structural relation with me.**

It may not yet know:

> **This is a bird.**

This is:

# Recognition Before Recognition

The first recognition is structural.

The second is semantic.

---

# 6. Structural Recognition in Flight

For autonomous flight, structural recognition may include distinctions such as:

```text id="xys76d"
Approaching / Receding

Stable / Unstable

Expected / Anomalous

Clear / Obstructed

Balanced / Imbalanced

Safe / Collision-Likely

Normal Vibration / Abnormal Vibration

Normal Temperature / Thermal Anomaly
```

Many of these distinctions do not initially require object-level semantics.

They require reliable structural consequence.

This makes them strong candidates for pre-representational intelligence.

---

# 7. Structural Consequence Boundary in a Drone

The HSCI Structural Consequence Boundary can be applied directly.

Consider:

```text id="8x8lyr"
Photon
  ↓
Photodetector Response
  ↓
Electrical Signal
  ↓
Optical-Flow Feature
  ↓
Rapid Expansion Detected
  ↓
----------------------------- SCB
  ↓
Collision Path Activated
  ↓
Flight-Control State Changed
```

The precise SCB location depends on implementation.

The important point is that after the boundary, the signal changes what the system does computationally or physically.

Possible consequences include:

```text id="pzdwmn"
Increase Sampling
Activate Specialist
Switch Controller
Raise Priority
Write Memory
Interrupt Planner
Reduce Speed
Change Trajectory
Emergency Avoid
```

---

# 8. Drone Hardware Intelligence Primitives

Potential Hardware Intelligence Primitives in autonomous flight may include:

```text id="s3q2ea"
Optical Selectivity
Thermal Selectivity
Acoustic Selectivity
Vibration Resonance
IMU Threshold Events
Pressure Events
Motor-Current Anomalies
Event-Camera Activity
Range Thresholds
Mechanical Compliance
```

Again:

> A sensor is not intelligent merely because it senses.

The primitive becomes intelligence-relevant when its selective response participates in downstream structural consequence.

---

# 9. Sensor Intelligence as Early Selection

A conventional camera may provide a large general data stream.

A specialized sensor can sometimes expose a useful distinction directly.

For example:

```text id="y6f60w"
Thermal Sensor
      ↓
Strong Thermal Difference
      ↓
Salience
      ↓
Activate Specialist
```

instead of requiring:

```text id="s7s36z"
Visible Image
      ↓
Large ANN
      ↓
Infer Thermal-Relevant Condition
```

The correct architecture depends on the task.

HSCI does not claim that specialized sensing is always superior.

It claims:

> **Sensor design is part of intelligence placement.**

---

# 10. The Drone as a Multi-Sensor Structural System

An autonomous drone may contain:

```text id="m12sfw"
Drone Sensor Field
│
├── RGB Camera
├── Event Camera
├── Depth / Range
├── Thermal
├── IMU
├── GPS / GNSS
├── Barometer
├── Microphone
├── Vibration Sensor
├── Motor Current
└── Internal Temperature
```

The conventional approach asks:

> How do we fuse all of these into a representation?

HSCI adds a prior question:

> **Which sensor can expose which intelligent distinction earliest and most cheaply?**

---

# 11. Hardware Function Tunnels in Flight

A Hardware Function Tunnel can map a recurring physical pattern directly toward a useful response.

For example:

```text id="52h4pd"
Optical Expansion
      ↓
Collision Salience
      ↓
Collision HFT
      ↓
Avoidance Control
```

or:

```text id="avb2yh"
Abnormal Vibration
      ↓
Mechanical Salience
      ↓
Stability HFT
      ↓
Control-Profile Switch
```

or:

```text id="gnhd47"
Motor Current Spike
      ↓
Powertrain Salience
      ↓
Motor-Fault HFT
      ↓
Load Redistribution
```

These paths can operate before detailed diagnosis.

---

# 12. Case A — Collision Avoidance

Consider a rapidly approaching obstacle.

## Architecture A — Representation First

```text id="1w4ivn"
Camera
  ↓
Frame
  ↓
Preprocessing
  ↓
ANN
  ↓
Object Detection
  ↓
Object Classification
  ↓
Depth / Motion Estimation
  ↓
World Model
  ↓
Collision Prediction
  ↓
Avoidance
```

## Architecture B — HSCI

```text id="gnivkp"
Optical / Depth Signal
        ↓
Expansion / Motion Salience
        ↓
Collision Trigger
        ↓
Emergency FT
        ↓
Immediate Avoidance
```

in parallel with:

```text id="09h8t8"
Camera
  ↓
ANN
  ↓
Object Recognition
  ↓
World Model
  ↓
Detailed Prediction
```

Architecture B does not eliminate Architecture A.

It adds an earlier path.

---

# 13. Collision Experiment

A controlled experiment can measure:

| Metric                | Architecture A | Architecture B |
| --------------------- | -------------: | -------------: |
| Detection latency     |       measured |       measured |
| Action latency        |       measured |       measured |
| ANN calls             |       measured |       measured |
| Energy/event          |       measured |       measured |
| False avoidance       |       measured |       measured |
| Missed collision risk |       measured |       measured |
| Minimum safe distance |       measured |       measured |
| Semantic accuracy     |       measured |       measured |

The key question is:

> **Can Architecture B begin safe action earlier without producing an unacceptable increase in false triggers?**

---

# 14. Case B — Propeller and Mechanical Anomaly

Mechanical failure provides another strong HSCI case.

A drone's body itself generates information.

Possible signals include:

```text id="b6ygol"
Vibration
Motor Current
Acoustic Pattern
Angular Acceleration
Temperature
Control Error
```

A representation-first architecture may use:

```text id="gz1uqn"
Raw Vibration
      ↓
Digitization
      ↓
Feature Extraction
      ↓
ANN
      ↓
Damage Classification
      ↓
Control Change
```

An HSCI path may use:

```text id="3cr9j6"
Abnormal Resonance Pattern
        ↓
Mechanical Salience
        ↓
Structural Trigger
        ↓
Safe Flight Profile
```

Detailed diagnosis can follow later.

---

# 15. Something Is Wrong Before What Is Wrong

This produces another form of Recognition Before Recognition.

Stage 1:

```text id="v07rpe"
Something is structurally wrong.
```

Stage 2:

```text id="p70gmq"
The anomaly is associated with propulsion.
```

Stage 3:

```text id="mkt6tz"
Motor / propeller subsystem #3 is abnormal.
```

Stage 4:

```text id="9x3z8x"
Probable propeller damage.
```

Stage 5:

```text id="c8c8ox"
Specific failure diagnosis.
```

Emergency control may begin at Stage 1 or Stage 2.

Full diagnosis does not always need to precede safe action.

---

# 16. The Drone Body as an Intelligence Surface

This leads to a broader idea:

# Embodied Intelligence Surface

The drone's intelligence does not need to begin only at the processor.

Its:

```text id="ry9wzl"
Airframe
Propellers
Motors
Sensors
Mechanical Coupling
Vibration Modes
Power System
Thermal System
```

all interact physically with the environment.

These interactions may expose useful distinctions before general computation.

Thus the drone body itself can become part of the intelligence architecture.

---

# 17. Morphology and Physical Computation

Some physical design choices can reduce computational burden.

Examples may include:

* passive stabilization,
* compliant structures,
* aerodynamic geometry,
* vibration isolation,
* sensor orientation,
* optical arrangement,
* mechanical filtering.

Such mechanisms should not automatically be labeled intelligence.

But when they systematically simplify or select downstream decision-relevant distinctions, they can participate in the intelligence pipeline.

This motivates an engineering question:

> **Can physical design make the correct computational distinction easier?**

---

# 18. Case C — Thermal Event

Suppose a drone operates near equipment or in search-and-rescue environments.

A thermal anomaly may be important before its semantic cause is known.

```text id="wdjvcj"
Thermal Difference
      ↓
High Salience
      ↓
Anchor
      ↓
Increase Sampling
      ↓
Activate Thermal / Vision Specialist
      ↓
Local Structural Map
```

The system first knows:

> **Something thermally significant is here.**

Only later:

```text id="vwc28f"
Person
Fire
Engine
Reflection
Background Artifact
```

may be determined.

---

# 19. Anchor and Image Starmap

A salient location can become an Anchor.

```text id="l1ej1j"
              Feature B
                  |
Feature C ------ Anchor ------ Feature D
                  |
              Feature E
```

The drone can organize:

```text id="0xd69h"
Depth
Motion
Thermal Difference
Optical Contrast
Relative Direction
Distance
Trajectory
```

around the anchor.

This forms a local:

# Image Starmap

before full scene semantics are available.

---

# 20. Sequence Starmap in Flight

Flight intelligence is inherently temporal.

Consider:

```text id="s7e0hn"
t-4  stable
t-3  stable
t-2  vibration rise
t-1  angular deviation
t0   high-salience anomaly
t+1  controller switch
t+2  stabilization
```

The high-salience event at \(t_0\) can serve as an Anchor.

Events before and after it can be organized into a:

# Sequence Starmap

This may support:

* anomaly learning,
* fault prediction,
* trajectory analysis,
* emergency diagnosis,
* and future Function-Tunnel construction.

---

# 21. Normal Intelligence

Normal autonomous flight may use:

```text id="hfbjvo"
Sensors
  ↓
Representation
  ↓
Sensor Fusion
  ↓
World Model
  ↓
Trajectory Prediction
  ↓
Planning
  ↓
Control
```

This pathway is appropriate when the system has enough time to build and use richer representations.

Examples include:

```text id="up1f34"
Route Planning
Landing-Site Selection
Object Tracking
Mission Optimization
Navigation
Long-Horizon Energy Planning
```

---

# 22. Emergency Intelligence

Emergency intelligence follows a different MET.

Its priority may be:

```text id="3w9n8o"
Safety
Latency
Stability
Reliability
```

rather than:

```text id="jqad28"
Semantic Completeness
Rich Explanation
Global Optimization
```

Therefore:

```text id="q4j5qa"
Physical Difference
      ↓
Salience
      ↓
Emergency Trigger
      ↓
Emergency FT
      ↓
Immediate Action
```

may be preferable.

The governing principle is:

> **Act intelligently before fully understanding when latency dominates semantic completeness.**

---

# 23. Normal and Emergency Intelligence Are Complementary

The architecture should not choose one permanently.

Instead:

```text id="q1n7jf"
                    EVENT
                      │
             ┌────────┴────────┐
             │                 │
             ▼                 ▼
       Emergency Path      Normal Path
             │                 │
       Fast Response        Rich Model
             │                 │
             └────────┬────────┘
                      ▼
              Runtime Reconciliation
```

The emergency path protects the system.

The normal path improves understanding.

Later information can:

* confirm,
* refine,
* cancel,
* explain,
* or learn from

the initial response.

---

# 24. Multi-Timescale Flight Intelligence

Autonomous flight provides a natural example of multi-timescale intelligence.

```text id="vnibwq"
μs–ms
Physical / Sensor Intelligence
        ↓

ms
Salience / Event Trigger
        ↓

ms–10 ms
Stability / Emergency Control
        ↓

10–100 ms
Boolean / CCC / ANN
        ↓

100 ms–seconds
World Model / Trajectory Intelligence
        ↓

seconds+
Mission Planning / Brain-Unit Reasoning
        ↓

minutes+
Human / Organizational Coordination
```

This leads to an important principle:

> **A drone should not require every intelligent function to run at the same cognitive clock.**

---

# 25. The Wrong Intelligence at the Wrong Time

A powerful intelligence substrate can still be architecturally wrong.

For example:

```text id="2wgrtn"
Collision in 20 ms
       ↓
LLM reasoning in hundreds of ms+
```

is a placement mismatch.

Likewise:

```text id="m9rm07"
Complex mission ambiguity
       ↓
Single hardware threshold
```

is also a placement mismatch.

Therefore intelligence quality depends not only on capability.

It depends on:

```text id="n98grz"
Capability
    +
Placement
    +
Timing
```

---

# 26. Per-Function Intelligence Placement for Drones

A drone may distribute functions approximately as follows:

| Function                      | Candidate Substrate |
| ----------------------------- | ------------------- |
| Mechanical resonance anomaly  | Physical / Sensor   |
| Extreme temperature threshold | Sensor / Boolean    |
| Immediate collision salience  | Sensor / HFT        |
| Stability protection          | Control FT          |
| Policy trigger                | CCC                 |
| Object recognition            | ANN                 |
| Local scene dynamics          | World Model         |
| Trajectory planning           | Structural / Model  |
| Mission replanning            | Brain Unit          |
| Open semantic interpretation  | LLM                 |
| High-risk unresolved judgment | Human               |

This is not a universal mapping.

It illustrates the HSCI placement question.

---

# 27. Smallest Sufficient Intelligence in Flight

Suppose a distinction can be resolved with:

```text id="7puc8q"
3 μJ
```

using a dedicated local mechanism.

Using:

```text id="0e88h7"
30 mJ
```

of generalized inference for the same reliable distinction may be architecturally inefficient.

But if the local mechanism produces unacceptable false negatives, the larger model may still be necessary.

Thus the principle is not:

> always use the smallest mechanism.

It is:

> **use the smallest sufficient mechanism.**

The word **sufficient** carries the safety requirement.

---

# 28. Selective Upward Escalation in Flight

A flight runtime can escalate only when necessary.

```text id="tkg6lm"
Sensor / HFT
    ↓
Confident?
├── YES → Act
└── NO
     ↓
    CCC
     ↓
Resolved?
├── YES → Act
└── NO
     ↓
    ANN
     ↓
Resolved?
├── YES → Act
└── NO
     ↓
World Model
     ↓
Brain Unit / LLM
     ↓
Human
```

This allows expensive intelligence to concentrate on difficult cases.

---

# 29. Emergency Escalation Is Different

Emergency escalation may use:

```text id="5bz6kc"
Urgent Event
     ↓
Safe Local Action First
     ↓
Escalate in Parallel
```

rather than:

```text id="q2u7vw"
Urgent Event
     ↓
Escalate
     ↓
Wait
     ↓
Act
```

This distinction is critical.

In safety-sensitive systems:

> **Escalation must not automatically imply delayed action.**

---

# 30. Downward Structural Consolidation

Suppose an ANN repeatedly detects the same highly stable collision precursor.

The system may discover:

```text id="0u8af1"
Pattern X
   ↓
ANN Detection
   ↓
Collision Response
```

across millions of cases.

If Pattern X is sufficiently stable, it may become a candidate for:

```text id="h6hkwb"
ANN
 ↓
CCC
 ↓
Boolean
 ↓
Hardware Trigger
```

This is:

# Downward Structural Consolidation

It converts learned regularity into cheaper structural intelligence.

---

# 31. Hardware Candidate in a Drone

A useful hardware candidate may have:

```text id="b2p5tz"
High Frequency of Use
        +
Stable Structural Pattern
        +
Strong Latency Requirement
        +
High Energy Saving Potential
        +
Low Semantic Ambiguity
```

Examples might include:

* collision precursor detection,
* motor anomaly detection,
* stability threshold detection,
* battery emergency conditions,
* extreme thermal events.

The exact candidates must be experimentally validated.

---

# 32. Hardware–Software Co-Evolution Loop in Flight

The drone runtime may evolve through:

```text id="6ryyiv"
Hardware Bias
      ↓
Software Learning
      ↓
Repeated Structural Pattern
      ↓
Function Tunnel
      ↓
Validation
      ↓
Hardware Candidate
      ↓
Structural Consolidation
      ↓
New Hardware Bias
      ↺
```

This is the HSCI co-evolution loop in an engineered system.

---

# 33. Architecture A — Representation-First Baseline

A canonical experimental baseline is:

```text id="tm9ax1"
                    PHYSICAL WORLD
                          │
                          ▼
                       SENSOR
                          │
                          ▼
                    DIGITIZATION
                          │
                          ▼
                 FULL REPRESENTATION
                          │
                          ▼
                         ANN
                          │
                          ▼
                    WORLD MODEL
                          │
                          ▼
                       DECISION
                          │
                          ▼
                        ACTION
```

This is:

# Architecture A

It represents the conventional representation-first baseline.

---

# 34. Architecture B — HSCI Multi-Substrate Runtime

The experimental alternative is:

```text id="xtgvx3"
                    PHYSICAL WORLD
                          │
                          ▼
                       SENSOR
                          │
                          ▼
             PHYSICAL / SENSOR SELECTIVITY
                          │
                          ▼
                       SALIENCE
                          │
                          ▼
                       TRIGGER
              ┌───────────┼───────────┐
              │           │           │
              ▼           ▼           ▼
           Ignore     Emergency FT   Selective
                          │         Representation
                          │              │
                          ▼              ▼
                    Fast Control        ANN
                                         │
                                         ▼
                                    World Model
                                         │
                                         ▼
                                      Decision
              │                          │
              └────────────┬─────────────┘
                           ▼
                  Runtime Reconciliation
```

This is:

# Architecture B

The experiment asks whether Architecture B creates a better system-level MET under specific workloads.

---

# 35. Canonical A/B Metrics

The experiment should measure at least:

## Resource Metrics

```text id="ej8brd"
Energy per event
Average power
Peak power
Compute utilization
Memory traffic
Data movement
ANN activations
World-model updates
```

## Timing Metrics

```text id="g17xtb"
Detection latency
Trigger latency
Control latency
Semantic recognition latency
Recovery time
```

## Flight Metrics

```text id="8cggcc"
Flight duration
Battery consumption
Payload impact
Thermal load
Mission completion
```

## Intelligence Metrics

```text id="ejr8x4"
True Positive
False Positive
False Negative
Confidence
Semantic Accuracy
Structural Detection Accuracy
```

## Safety Metrics

```text id="l1m1r5"
Collision rate
Minimum obstacle distance
Stability loss
Emergency recovery
Unsafe false suppression
```

---

# 36. A/B Validation Matrix

A first validation matrix can include:

| Experiment        | Representation-First | HSCI                         |
| ----------------- | -------------------- | ---------------------------- |
| Collision event   | Full ANN path        | Salience + Emergency FT      |
| Propeller anomaly | ANN diagnosis first  | Anomaly trigger first        |
| Thermal anomaly   | Full fusion          | Thermal salience             |
| Stable cruising   | Continuous inference | Selective activation         |
| Novel object      | ANN / WM             | Escalation to ANN / WM       |
| Emergency event   | Semantic pipeline    | Fast FT + parallel semantics |

The objective is not to force HSCI to win every row.

The objective is to discover:

> **Where does early intelligence placement produce measurable value?**

---

# 37. Important Negative Result

A serious HSCI experiment must allow failure.

Suppose Architecture B produces:

```text id="6x7fxv"
Lower latency
Lower energy
```

but also:

```text id="cud9dt"
Unacceptable false negatives
```

Then the Hardware Function Tunnel is not sufficient.

It should not be deployed as the sole decision mechanism.

Likewise, if:

```text id="tyi5ap"
Energy Saving ≈ 0
Latency Saving ≈ 0
Complexity ↑
```

then the additional HSCI structure may not be justified.

This is important:

> **HSCI should be experimentally falsifiable at the function-placement level.**

---

# 38. HSCI Does Not Require Hardware to Win

The purpose of the framework is not:

```text id="8v88hr"
Hardware > Software
```

The purpose is:

```text id="mmobd6"
Find Best Placement
```

For some functions:

```text id="5qv3xf"
Hardware FT
```

may dominate.

For others:

```text id="g4y40f"
ANN
```

may dominate.

For others:

```text id="ikrq6p"
World Model
```

may be necessary.

And for some rare cases:

```text id="ym0i82"
LLM / Human
```

may be appropriate.

The success of HSCI lies in correct allocation, not hardware maximalism.

---

# 39. Flight Intelligence Dispatch Tree

A simplified dispatch tree is:

```text id="e10q8f"
                       EVENT
                         │
                    Urgent?
                   /       \
                 YES        NO
                 /           \
          Local Safe FT     Known?
              │            /     \
              │          YES      NO
              │          /         \
              │       CCC/ANN    World Model
              │                     │
              │                  Resolved?
              │                  /      \
              │                YES       NO
              │                /          \
              │              Act       Brain Unit
              │                            │
              └───────────────→ Reconcile
```

This tree can itself evolve through experience.

---

# 40. Dispatch-Tree Growth

Suppose a recurring event repeatedly causes:

```text id="x3m5gf"
General Path
     ↓
High Latency
     ↓
Same Structural Solution
```

The runtime may create:

```text id="t2g4d1"
Candidate Difference
       ↓
A/B Validation
       ↓
New Branch
       ↓
Specialist FT
```

This creates:

# Structural Continual Learning

at the architecture level.

The system does not merely update parameters.

It grows new intelligence paths.

---

# 41. Drone Brain Unit

The resulting autonomous-flight Brain Unit may be:

```text id="w4bfb4"
AUTONOMOUS FLIGHT BRAIN UNIT
│
├── Physical / Sensor Intelligence
│   ├── Optical
│   ├── Event
│   ├── Thermal
│   ├── IMU
│   ├── Acoustic
│   ├── Vibration
│   └── Motor / Power
│
├── Pre-Representational Intelligence
│   ├── Salience
│   ├── Anchor
│   ├── Trigger
│   └── Structural Organizer
│
├── Hardware Function Tunnels
│   ├── Collision
│   ├── Stability
│   ├── Propulsion
│   ├── Thermal
│   └── Power Emergency
│
├── Structural Runtime
│   ├── Boolean
│   ├── CCC
│   ├── Policy
│   └── Dispatch Tree
│
├── ANN Specialists
│   ├── Vision
│   ├── Terrain
│   ├── Object
│   └── Anomaly
│
├── World Model
│   ├── Local Scene
│   ├── Dynamics
│   ├── Trajectory
│   └── Prediction
│
├── High-Level Intelligence
│   ├── Mission Planning
│   ├── Reasoning
│   └── LLM
│
└── Governance
    ├── Runtime Invariants
    ├── Authority
    ├── Escape Paths
    ├── Audit
    └── Human Escalation
```

---

# 42. Capability vs Authority in Flight

The most computationally capable component should not automatically control the fastest safety response.

For example:

```text id="91y1ht"
LLM
```

may have greater semantic capability than:

```text id="ox7ek7"
Collision HFT
```

but during an immediate collision event:

```text id="9ox5sn"
Collision HFT
```

may have greater action authority.

Therefore:

> **Capability hierarchy is not authority hierarchy.**

This is essential for autonomous safety architecture.

---

# 43. Runtime Invariants

Every direct-action Function Tunnel should have explicit invariants.

For example:

```text id="lg8ksd"
Collision HFT

Entry:
rapid expansion detected

Invariant:
sensor health valid
range estimate consistent
flight mode supports lateral avoidance

Authority:
temporary emergency maneuver

Escape:
sensor conflict
control saturation
unexpected dynamics

Fallback:
stabilize + escalate
```

This makes fast intelligence governable.

---

# 44. Function-Tunnel Escape

No Hardware Function Tunnel should be assumed universally valid.

```text id="km9n5n"
HFT
 ↓
Invariant Holds?
├── YES → Continue
└── NO
     ↓
   Escape
     ↓
CCC / ANN / World Model / Safe State
```

The purpose of an HFT is to create a fast path.

The purpose of escape is to prevent the fast path from becoming a trap.

---

# 45. Runtime Reconciliation

Fast and slow paths may disagree.

Example:

```text id="tsoucc"
Collision HFT:
HIGH RISK

ANN:
OBJECT UNCERTAIN

World Model:
LOW-MEDIUM RISK
```

The runtime must reconcile these outputs according to:

```text id="rfq0y3"
Urgency
Confidence
Sensor Health
Safety Policy
Current Dynamics
Action Reversibility
```

Thus:

$$
Action
=
Governance
(
FastPath,
SlowPath,
Risk,
State
)
$$

not simply:

$$
Action
=
LargestModelOutput
$$

---

# 46. Structural Audit Trace

A useful flight trace might look like:

```text id="z7t0gz"
EVENT
Optical expansion detected

TIME
T+0 ms

SALIENCE
0.94

HFT
Collision-Avoidance-03

POLICY
Emergency

ACTION
Lateral avoidance

ACTION START
T+4 ms

ANN RESULT
Flying object detected

ANN COMPLETE
T+61 ms

WORLD MODEL
Crossing trajectory confirmed

RESULT
Safe separation maintained

POST-RUN
HFT confirmed
```

This trace reveals the temporal structure of intelligence.

It shows:

> who noticed first,

> who acted first,

> who understood later,

and:

> whether the early action was justified.

---

# 47. Learning From Flight Traces

Flight traces can support structural evolution.

Suppose:

```text id="8p4r43"
HFT-A
10,000 activations
9,995 useful
5 false triggers
0 dangerous misses
```

This may support retention.

Another tunnel:

```text id="3nrr8w"
HFT-B
10,000 activations
7,300 useful
2,700 unnecessary
```

may require:

* threshold adjustment,
* context addition,
* branch splitting,
* ANN confirmation,
* or retirement.

Thus the architecture itself learns.

---

# 48. From Flight Learning to Hardware Consolidation

Suppose an ANN repeatedly discovers a stable pattern:

```text id="dl5cm8"
Pattern P
     ↓
High Collision Risk
```

After sufficient validation:

```text id="fvvgpq"
ANN Pattern
    ↓
CCC Rule
    ↓
Boolean Approximation
    ↓
Hardware Candidate
    ↓
A/B Test
    ↓
HFT
```

The intelligence has moved downward.

If environmental conditions later change:

```text id="6v4mdw"
HFT Failure
    ↓
Escape
    ↓
ANN / World Model
```

moves it upward again.

This is hardware–software co-evolution in operation.

---

# 49. Intelligence per Watt

Traditional AI benchmarks often emphasize:

```text id="g2ohp7"
Accuracy
Throughput
Model Size
```

Autonomous drones motivate another family of metrics:

# Intelligence per Watt

and more broadly:

# Effective Intelligence per Resource

A useful architecture should ask:

```text id="bvx7vq"
How much useful discrimination?
How much safe action?
How much prediction?
How much autonomy?
```

per:

```text id="g8mqum"
Joule
Millisecond
Gram
Byte
Model Call
```

This shifts evaluation from model capability alone toward system capability.

---

# 50. Structural Intelligence per Representation

Another useful metric is:

# Structural Intelligence per Representation Cost

For example:

$$
SIR
=
\frac{
\text{Useful Structural Decisions}
}{
\text{Representation Cost}
}
$$

The exact metric requires future formalization.

But the conceptual question is valuable:

> **How much useful intelligence can the system obtain before constructing expensive representations?**

---

# 51. Compute Scaling vs Placement Scaling in Drones

Compute scaling says:

```text id="9jsszv"
Better Model
      ↓
Better Recognition
```

Placement scaling asks:

```text id="c01qnf"
Better Sensor
      +
Better Salience
      +
Better Trigger
      +
Better Routing
      ↓
Less Unnecessary Recognition
```

The strongest architecture may combine both:

```text id="0nwf6r"
Physical Intelligence
      +
Structural Intelligence
      +
Powerful Models
      ↓
Resource-Efficient Autonomous Intelligence
```

---

# 52. Model Organism for Structural Intelligence Engineering

Autonomous drones have several properties that make them unusually useful for HSCI research:

1. they interact directly with the physical world;
2. energy is measurable;
3. latency is measurable;
4. weight matters;
5. failures have structural consequences;
6. multiple sensors are available;
7. fast and slow intelligence must coexist;
8. emergency intelligence is necessary;
9. world models are useful but costly;
10. structural learning can be evaluated through repeated flight.

For these reasons:

> **Autonomous drones can serve as a model organism for structural intelligence engineering.**

The phrase does not imply biological equivalence.

It means drones provide a compact experimental system containing many of the architectural problems HSCI seeks to study.

---

# 53. Minimal Experimental Program

A first HSCI drone program does not require a complete autonomous-aircraft platform.

It can begin with four experiments.

## Experiment 1 — Collision Salience

Compare:

```text id="s77is1"
Full Vision ANN
```

against:

```text id="i3pquj"
Early Motion / Expansion Trigger
```

Measure latency, energy, false triggers, and misses.

---

## Experiment 2 — Vibration Anomaly

Compare:

```text id="nkwckb"
ANN-First Diagnosis
```

against:

```text id="e35k2y"
Resonance / Threshold Trigger
```

Measure detection time and safe-control response.

---

## Experiment 3 — Selective ANN Activation

Compare:

```text id="7b1k28"
Continuous ANN
```

against:

```text id="ap6w6c"
Salience-Triggered ANN
```

Measure:

```text id="l92ysn"
ANN Calls
Energy
Latency
Accuracy
Flight Time
```

---

## Experiment 4 — Emergency Dual Path

Compare:

```text id="q73xbw"
Semantic Decision Before Action
```

against:

```text id="zzffat"
Safe Action First
+
Semantic Confirmation in Parallel
```

Measure safety and false-action cost.

---

# 54. Minimal Validation Ladder

The research can proceed gradually.

```text id="4n4bt7"
Level 0
Offline sensor traces

      ↓

Level 1
Software simulation

      ↓

Level 2
Hardware-in-the-loop

      ↓

Level 3
Static physical rig

      ↓

Level 4
Controlled indoor flight

      ↓

Level 5
Controlled outdoor flight

      ↓

Level 6
Multi-condition autonomous campaign
```

This avoids requiring full autonomous deployment before testing the theory.

---

# 55. Validation Criteria

An HSCI placement should be considered promising when it produces a favorable combination of:

```text id="ynzogb"
Lower Energy
Lower Latency
Lower Compute
Lower Data Movement
Equal or Better Safety
Acceptable Accuracy
Acceptable False Trigger Rate
Robust Escape Behavior
```

No single metric is sufficient.

A faster but unsafe system is not better.

A lower-energy system with catastrophic misses is not better.

The relevant object is a multi-dimensional MET.

---

# 56. Failure Criteria

A proposed Hardware Function Tunnel should be rejected, revised, or restricted when:

```text id="f84y62"
False negatives exceed safety tolerance

False positives create excessive instability

Energy savings are negligible

Latency improvement is negligible

Sensor dependence is fragile

Environmental shift breaks invariants

Escape path is unreliable

Governance complexity exceeds benefit
```

This keeps HSCI experimentally disciplined.

---

# 57. What HSCI-004 Does Not Claim

This paper does not claim that:

1. all drone intelligence should move into hardware;
2. semantic recognition is unnecessary;
3. world models are unnecessary;
4. ANN inference should be avoided;
5. all emergency actions should bypass representation;
6. every sensor is an intelligence primitive;
7. physical resonance is required for autonomous flight;
8. specialized hardware always saves energy;
9. HSCI has already been experimentally validated;
10. autonomous drones are the only or necessarily the largest future beneficiary of HSCI.

The narrower claim is:

> **Autonomous drones provide a strong experimental environment for testing whether earlier intelligence placement can improve system-level efficiency and response while preserving required safety and reliability.**

---

# 58. Research Questions

## RQ-1 — Representation Cost

How much energy and latency in autonomous flight are consumed before useful semantic inference begins?

## RQ-2 — Early Structural Recognition

Which flight-critical events can be detected reliably before object-level recognition?

## RQ-3 — Hardware Function Tunnels

Which collision, stability, propulsion, thermal, and power events are suitable for HFT implementation?

## RQ-4 — Salience-Triggered Computation

How much ANN computation can be eliminated through selective activation?

## RQ-5 — Emergency Intelligence

When is immediate structurally informed action safer than waiting for semantic completion?

## RQ-6 — Multi-Timescale Coordination

How should millisecond emergency intelligence interact with slower world models and planners?

## RQ-7 — Structural Consolidation

Which repeatedly learned patterns should migrate downward toward CCC, Boolean, or hardware?

## RQ-8 — Escape and Recovery

How should a Hardware Function Tunnel detect that its operating assumptions no longer hold?

## RQ-9 — Authority

Which intelligence substrate should have control authority under different flight regimes?

## RQ-10 — Structural Continual Learning

Can repeated flight traces automatically grow and reorganize the dispatch tree?

---

# 59. Canonical Drone HSCI Architecture

```text id="67ajqv"
                         PHYSICAL WORLD
                               │
                               ▼
                  ┌────────────────────────┐
                  │ SENSOR / BODY SURFACE  │
                  │ optical / IMU /        │
                  │ thermal / vibration /  │
                  │ acoustic / power       │
                  └────────────┬───────────┘
                               │
                               ▼
                  ┌────────────────────────┐
                  │ PHYSICAL SELECTIVITY   │
                  │ / EARLY FEATURES       │
                  └────────────┬───────────┘
                               │
                               ▼
                  ┌────────────────────────┐
                  │ SALIENCE / TRIGGER     │
                  └────────────┬───────────┘
                               │
                ┌──────────────┼──────────────┐
                │              │              │
                ▼              ▼              ▼
             IGNORE       EMERGENCY FT      NORMAL
                               │              PATH
                               │               │
                               ▼               ▼
                         FAST CONTROL      BOOLEAN / CCC
                                               │
                                               ▼
                                          ANN SPECIALIST
                                               │
                                               ▼
                                           WORLD MODEL
                                               │
                                               ▼
                                      TRAJECTORY / PLANNING
                                               │
                                               ▼
                                      BRAIN UNIT / LLM
                │                              │
                └──────────────┬───────────────┘
                               ▼
                     RUNTIME RECONCILIATION
                               │
                               ▼
                            ACTION
                               │
                               ▼
                        FLIGHT TRACE
                               │
                               ▼
                    STRUCTURAL LEARNING
                               │
                 ┌─────────────┴─────────────┐
                 ▼                           ▼
          DISPATCH-TREE GROWTH       FT CONSOLIDATION
                 │                           │
                 └─────────────┬─────────────┘
                               ▼
                      UPDATED BRAIN UNIT
```

---

# 60. Core Engineering Principles

## Principle 1 — Representation Has Cost

> Representation should be treated as a resource-consuming operation.

## Principle 2 — Recognition Before Recognition

> A drone may detect structural significance before semantic identity.

## Principle 3 — Safe Action Before Complete Understanding

> Under strict latency constraints, safe action may begin before semantic processing is complete.

## Principle 4 — Sensor Design Is Intelligence Placement

> The choice of sensor determines which distinctions become physically cheap.

## Principle 5 — Smallest Sufficient Intelligence

> Use the smallest substrate that can safely and reliably resolve the required distinction.

## Principle 6 — Parallel Fast and Slow Paths

> Emergency intelligence and semantic intelligence should cooperate rather than wait serially for one another.

## Principle 7 — Capability Is Not Authority

> The most general intelligence substrate does not automatically deserve the highest real-time control authority.

## Principle 8 — Every Fast Path Needs Escape

> Hardware Function Tunnels require explicit invariants, failure detection, and fallback.

## Principle 9 — Learn Upward, Consolidate Downward

> Novelty should access flexible intelligence; repeated stable regularities can become candidates for structural consolidation.

## Principle 10 — Measure the Whole System

> Intelligence should be evaluated in energy, latency, safety, reliability, flight time, and computational cost—not model accuracy alone.

---

# 61. Canonical Statement

> **Autonomous drones provide a canonical engineering testbed for Intelligence Before Representation because their strict energy, weight, latency, and safety constraints make the placement of intelligence directly measurable. Physical and sensory mechanisms can detect structurally important differences, generate salience, and activate fast Function Tunnels before complete semantic representation, while ANN, world-model, and Brain-Unit intelligence continue in parallel for richer recognition, prediction, and planning.**

---

# 62. The HSCI Drone Hypothesis

The primary engineering hypothesis can be stated compactly:

$$
\text{Early Structural Intelligence}
+
\text{Selective Representation}
+
\text{Selective Escalation}
$$

may produce:

$$
\text{Lower Energy}
+
\text{Lower Latency}
+
\text{Lower Compute}
$$

while maintaining:

$$
\text{Required Safety}
+
\text{Required Reliability}.
$$

If those conditions are not met for a particular function, the proposed placement should be rejected or revised.

Thus HSCI is not a doctrine that hardware must win.

It is a framework for discovering:

> **where intelligence should live.**

---

# 63. Conclusion

Autonomous drones expose a fundamental weakness in representation-first thinking:

> representation, computation, and model invocation are physical costs.

A drone has limited energy.

It has limited weight.

It has limited time.

And sometimes it must act before it can fully understand.

This makes autonomous flight a natural environment for testing Intelligence Before Representation.

The conventional sequence:

```text id="i5bq0a"
Sense
  ↓
Represent
  ↓
Recognize
  ↓
Understand
  ↓
Act
```

can be complemented by:

```text id="s0q6fr"
Sense
  ↓
Detect Structural Significance
  ↓
Trigger
  ↓
Act Safely
  ↓
Recognize
  ↓
Understand
  ↓
Refine
```

The first path prioritizes semantic completeness.

The second prioritizes structural consequence.

A mature autonomous system needs both.

Hardware Function Tunnels can provide fast, low-cost paths for stable and time-critical distinctions.

CCC and Boolean intelligence can provide deterministic structural routing.

ANN specialists can provide learned recognition.

World models can provide temporal and relational understanding.

Brain-Unit intelligence can provide high-level planning, reasoning, and coordination.

Humans can remain available where uncertainty, accountability, or novelty requires escalation.

The resulting drone is not controlled by one intelligence.

It becomes a:

> **multi-substrate, multi-timescale, policy-routed intelligence system.**

This leads to three compact engineering rules:

> **Do not compute what physics can already select.**

> **Do not represent everything before deciding what matters.**

> **Put the smallest sufficient intelligence at the earliest effective layer, and escalate only when necessary.**

Autonomous drones therefore offer more than an application of HSCI.

They offer a practical environment in which the theory can be measured, challenged, falsified, refined, and eventually engineered.

---

## HSCI First-Round Research Chain

```text id="xbxjnd"
HSCI-001
Hardware–Software Co-Evolution of Intelligence
        ↓
Why intelligence need not begin with representation

HSCI-002
Resonance, Salience, and Triggering
        ↓
How physical difference acquires structural consequence

HSCI-003
From Hardware Function Tunnels to Brain-Unit AI
        ↓
How intelligence is placed and routed across substrates

HSCI-004
Intelligence Before Representation in Autonomous Drones
        ↓
How the framework can be experimentally tested
```

---

## First-Round Validation Target

```text id="6uz9ve"
THEORY
Intelligence Before Representation
        ↓
ARCHITECTURE
Multi-Substrate Intelligence
        ↓
RUNTIME
Function Tunnels + Selective Escalation
        ↓
TESTBED
Autonomous Drone
        ↓
A/B EXPERIMENT
Representation-First vs HSCI
        ↓
MEASUREMENT
Energy / Latency / Compute / Safety
        ↓
RESULT
Validate / Reject / Refine Placement
```

---

**Hardware–Software Co-Evolution of Intelligence (HSCI)**
**HSCI-004 — Engineering and Validation Framework**
