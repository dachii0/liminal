# liminal

**Authorization analysis through behavioral observation.**

## The Problem
Conventional authorization testing tools work by checking known patterns — they look for IDOR signatures, test against OWASP rules, flag known misconfigurations. 
They're good at finding what they're designed to find.

But authorization logic in real applications is rarely that clean. Permission systems are built incrementally, inherited from legacy code, inconsistent across endpoints. The interesting vulnerabilities live in the gaps between rules — in behavioral combinations no scanner was designed to catch.


## The Idea
Liminal treats authorization as an **unknown system**.

Instead of validating against a known model, it reverse-engineers the permission landscape purely from observed behavior:
- No predefined schema
- No API spec required
- No assumptions about how permissions should work

It builds probabilistic representations of what the application actually does — then systematically probes the boundaries for inconsistencies.


## How It Works
- **Behavioral identity fingerprinting** — identity defined by observable behavior, not user records or account IDs
- **Probabilistic access modeling** — authorization maps built from scratch through observation
- **Multi-identity capability mapping** — tracks authority mechanisms, capability surfaces, and object access patterns across identities
- **Boundary probing** — systematically tests the edges of the permission landscape for inconsistencies


## Status

Core engine in active development. Approach validated against real production applications through authorized bug bounty programs — 32 findings and counting.
Manual methodology available now. Automated engine coming.


## Why "liminal"
Liminal means *threshold* — the space between states.
That's where authorization breaks.


## What Liminal Is Not
No AI. No machine learning. No black box.
liminal is pure logic - deterministic behavioral analysis and probabilistic modeling built from first principles. Every decision it makes can be traced and understood.

*Built by a 19-year-old security researcher in Tbilisi, Georgia.*
*Because the existing tools weren't enough.*

