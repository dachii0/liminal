# liminal

**Authorization analysis through behavioral observation.**

## The Problem
Conventional authorization testing tools work by checking known patterns — they look for IDOR signatures, test against OWASP rules, flag known misconfigurations. 
They're good at finding what they're designed to find.
But authorization logic in real applications is rarely that clean. Permission systems are built incrementally, inherited from legacy code, inconsistent across endpoints. The interesting vulnerabilities live in the gaps between rules — in behavioral combinations no scanner was designed to catch.

