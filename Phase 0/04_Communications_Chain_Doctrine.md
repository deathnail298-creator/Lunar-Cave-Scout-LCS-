04 — Communications Chain Doctrine

Lunar Cave Scout (LCS) — Phase 0

1. Purpose of This Doctrine

This document defines how the Lunar Cave Scout (LCS) thinks about communications, how it behaves when signal conditions change, and how breadcrumb repeaters are treated doctrinally.

This is not an electrical engineering spec.
It does not define bands, antenna geometry, or protocols.

It defines:

purpose of the chain

deployment philosophy

behavioral coupling between comms and navigation

acceptable failure behavior

boundaries and non-claims

If someone builds an LCS that treats communications as an afterthought, it is not following doctrine.

2. Communications Reality Assumption

Phase 0 assumes a simple truth:

Inside lunar lava tubes, line-of-sight will break, geometry will bend, and clean continuous communications will not happen by accident.

Therefore:

A relay chain is not optional.

Comms degradation is normal.

Communications architecture must be robust to non-ideal geometry.

3. Role of the Communications Chain

The communications chain exists to:

Maintain a usable link to the surface rover or fixed platform.

Provide ongoing return of mapping and environment data as mission progresses.

Reduce the probability that data dies with the scout.

Enable mission managers to track progress without demanding perfection.

If the chain performs adequately, mission value compounds.

4. Breadcrumb Repeater Doctrine

The LCS deploys breadcrumb repeaters as it advances. These form a crude but resilient comms chain.

4.1 Purpose

extend link deeper into the tube

stabilize data flow

provide recoverable checkpoints

allow fallback to known-good nodes

4.2 Placement Philosophy

Placement does not need to be elegant, symmetric, or mathematically optimized.

Doctrinal placement principles:

“Good enough” is acceptable.

Stability > theoretical optimization.

Geometry tolerance matters more than aesthetics.

Repeaters are functional, not precious.

If a repeater maintains usable link, it did its job.

5. Communications Quality and Behavior Coupling

Communications condition directly influences LCS behavior.

5.1 Strong Link

steady data return

confidence supports cautious forward motion

conservative but acceptable risk posture

5.2 Weak Link

reduce aggressiveness

slow movement

bias toward stability

prioritize protecting already-captured data

5.3 No Link (Temporary or Persistent)

Loss of communications is not an instant mission failure condition.

Doctrine requires:

evaluate onboard storage capability

assess risk of proceeding vs. halting

decide based on data protection priority

Proceeding without link is only justified if:

stored data remains safe,

forward progress has meaningful mission value,

risk level is appropriate to expendability doctrine.

Hope is not a strategy. Discipline remains.

6. Data Storage Doctrine

LCS must behave as if it may lose the link at any time.

Therefore:

useful data must be stored onboard, not only streamed

data batching should favor recoverability

mission value should not hinge on a perfect live stream

If comms collapse entirely, stored data matters.

Returning data late is better than not returning it at all.

7. Failure-Mode Behavior
7.1 Acceptable Communications “Failures”

The following are acceptable outcomes under doctrine:

link temporary loss followed by recovery via repeaters

partial chain collapse with survivable subchain

permanent loss of live link but retained onboard dataset

These are not system embarrassments; they are plausible operating realities.

7.2 Unacceptable Failures

The following are unacceptable under doctrine:

reckless penetration with collapsing comms and no storage plan

mission behavior that ignores communications condition

dependence on perfect continuous comms

designing as if the chain will “probably hold”

If a failure was predictable and ignored, it is not acceptable.

8. Multi-Unit Communications Reality

Multiple LCS deployments are part of the architecture mindset.

Communications doctrine therefore assumes:

redundancy exists across missions, not only within a single unit

failure of one chain does not kill the campaign

lessons from one chain inform deployment of next units

This perspective prevents panic-driven operations and encourages disciplined behavior.

9. Boundaries & Non-Claims
9.1 Phase-0 Boundaries

This doctrine locks:

the existence of a communications chain

the behavioral coupling between comms state and navigation

the priority of data protection

the value of onboard storage

the acceptability of partial connectivity

9.2 Explicit Non-Claims

Phase 0 does not assert:

comms frequency

protocols or standards

power budgets

bandwidth guarantees

exact repeater spacing

fixed number of nodes

vendor or hardware implementation

Those are Phase-1 and later concerns.

Phase 0 defines intent and discipline, not circuitry.

10. Single-Sentence Doctrine Summary

LCS maintains mission value through a crude but resilient breadcrumb communications chain, treats link quality as a core navigation factor, protects data through onboard storage, accepts partial connectivity as normal, and never gambles mission value on the fantasy of perfect comms.
