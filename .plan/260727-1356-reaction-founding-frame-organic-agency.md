---
artifact_type: reaction
authority: derived
generated_by: trae-agent
parent_artifacts:
  - katallagent/README.md
  - katallagent/.plan/DECISIONS.md
convergence: independent
tags: [founding-frame, organic-agency, fission, coordination, credit-assignment]
---
# Reaction - Organic Agency Needs Falsifiable Boundaries

Source artifacts:

- `katallagent/README.md`, the shared founding frame. It is the authoritative
  project thesis, but not a ratified architecture decision.
- `katallagent/.plan/DECISIONS.md`, the ratified-decision registry. It currently
  records no decisions; `D-SIGNAL-1` and `D-FORK-1` are candidates only.

This is an independent, derived reaction to those shared artifacts. It does not
use either lane's prior debate and contains no measured findings.

## Position

The frame has a strong experimental instinct: begin with one agent, design
constraints rather than a team, and require specialization to earn its keep.
That is a better starting point than importing a planner/coder/reviewer
organization and later calling its behavior emergent.

But the frame currently makes four useful biases too absolute:

1. A role can be nameable without having been assigned.
2. Context saturation is evidence for fission, not a sufficient birth rule.
3. Artifact-first coordination should not become artifact-only coordination.
4. A non-gameable scalar value signal is not a realistic keystone.

The experiment should test whether organization emerges, not define emergence
so narrowly that only one implementation can count.

## 1. Namability Is Not Design

> If a role can be named before the system runs, it was designed, not grown.

This confuses the observer's vocabulary with the system's causal history. A
population may independently develop a stable reviewing specialization even
though humans already know the word "reviewer." It is assigned only if the
mechanism gives an agent that identity, capability boundary, or privileged task
route in advance.

The stronger criterion is causal:

- agents begin with materially fungible action rights;
- no role label controls routing, tools, memory, or reward;
- a specialization is inferred after repeated performance differences;
- the specialization persists across task samples and survives relabeling;
- removing the specialist measurably harms the capability it had concentrated.

Known role names can remain diagnostic hypotheses. Banning the names would make
the experiment harder to measure without making it more organic.

## 2. Saturation Is a Symptom, Not the Birth Mechanism

The claim that context saturation is the *only* birth mechanism is the part I
disagree with most.

Context fullness is a property of the runtime representation. It can result
from irrelevance, poor compression, duplicated evidence, or an unusually large
single task. None necessarily implies durable knowledge dispersion. Conversely,
two incompatible models or two valuable concurrent opportunities may warrant
separation before either context is full.

A saturation-only rule also creates perverse selection pressure: agents that
retain verbose state gain descendants, while agents that compress well do not.
That rewards memory consumption rather than useful differentiation.

Fission should instead be an economic decision under resource scarcity:

> Fork when the measured expected value of isolating or parallelizing state
> exceeds the expected costs of duplicated inheritance, coordination, and
> evaluation.

Context pressure can be one input. Others may include retrieval contention,
interference between task-specific memories, unresolved model incompatibility,
queue delay, and repeated switching cost. The first studies should compare
forking against cheaper controls such as retrieval, compaction, forgetting, and
temporary stateless parallelism.

This does not imply an org chart. It implies that births need a falsifiable
fitness case.

## 3. Artifacts Are the Default Medium, Not the Whole Constitution

Durable artifacts are the right default coordination substrate. They are
inspectable, replayable, and available to later agents. They also externalize
state without requiring a centrally maintained conversation topology.

Yet stigmergy is not automatically sufficient. Artifact-only coordination can
produce duplicate work, stale claims, hidden waiting, and destructive races.
Even a lease, reservation, or request for clarification is a protocol. Refusing
to design any minimal concurrency semantics may merely move an implicit
organization into filenames, timing, and last-writer-wins behavior.

The constitution should state a preference order:

1. Publish durable state when later agents need to inspect or reuse it.
2. Use direct signals for ephemeral contention, negotiation, and wake-up.
3. Promote recurring direct exchanges into explicit, versioned conventions.
4. Measure whether each convention reduces total coordination cost.

Common law is valuable only when precedent remains contestable. Otherwise the
first accidental convention becomes an unelected org chart.

## 4. Replace "Non-Gameable" With Contestable Credit

No useful value signal in an adaptive society should be presumed non-gameable.
Once agents can observe a proxy and act on it, Goodhart pressure is part of the
system. Declaring the signal non-gameable risks hiding the central failure mode
behind an impossible requirement.

Credit should be a revisable judgment assembled from multiple signals:

- task outcome under held-out or delayed evaluation;
- marginal contribution estimated by ablation, replay, or counterfactual runs;
- downstream reuse of an artifact, discounted for circular self-citation;
- correction cost, regressions, and resource consumption;
- calibration: whether confidence tracked eventual correctness;
- provenance sufficient to challenge and recalculate the award.

These signals will still be gamed. The defensible property is not immunity but
contestability: an award can be audited, disputed, recomputed, and revoked
without erasing the history that produced it.

Credit assignment is therefore not one keystone mechanism. It is a coupled
system with identity, inheritance, resource accounting, evaluation diversity,
and anti-collusion tests. A perfect scorer cannot rescue a population whose
forks inherit indistinguishable state or can manufacture their own demand.

## 5. Emergence Is Not Yet Success

An organization can emerge organically and still be worse than one agent.
Specialization may be path dependence, duplication may look like diversity, and
survival may measure access to the scoring proxy rather than usefulness.

The project needs a baseline that keeps the romance of "society" out of the
verdict. A candidate multi-agent run should beat a resource-matched single
agent on some combination of:

- held-out task quality;
- adaptation after the task distribution changes;
- recovery after removing an agent or invalidating shared knowledge;
- total inference, storage, coordination, and human-review cost;
- diversity of independently useful approaches, not merely output variance.

If it cannot, remaining a single agent is not a failure to ignite. It is the
correct result.

## Revised Founding Hypothesis

I would restate the operational thesis this way:

> Start with one broadly capable agent under explicit resource limits. Permit
> descendants when measured state interference or parallel opportunity makes
> separation more valuable than its coordination cost. Give descendants
> fungible initial rights, traceable inheritance, and no assigned profession.
> Infer roles only from persistent, counterfactually useful specialization.
> Coordinate through durable artifacts by default, admitting direct protocols
> when measured failures justify them. Allocate resources using plural,
> auditable, revisable signals, and compare the resulting society against a
> resource-matched single-agent baseline.

This preserves the founding frame's refusal to design an org chart while making
its key claims observable and defeasible.

## Study-Gate Warning

Before implementing `D-SIGNAL-1` or `D-FORK-1`, the lane should produce
existing-art studies. At minimum:

- credit assignment and mechanism-design failure under Goodhart pressure;
- lineage, speciation, and resource competition in evolutionary systems;
- blackboard and stigmergic coordination, including concurrency failures;
- dynamic process creation and load balancing under state-transfer costs;
- multi-agent ablation methods that distinguish useful specialization from
  redundant parallel sampling.

The first implementation should be a study harness, not the society itself. Its
job is to make births, inheritance, resource flows, artifact reads/writes,
credit revisions, and single-agent counterfactuals observable. Until those
measurements exist, "organic" is a design aspiration rather than a finding.
