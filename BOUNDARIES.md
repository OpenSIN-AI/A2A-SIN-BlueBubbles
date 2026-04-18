# A2A-SIN-BlueBubbles Boundaries

## Role
`A2A-SIN-BlueBubbles` owns BlueBubbles messaging integration, iMessage bridge workflows, and BlueBubbles-specific contracts.

## This repo should own
- BlueBubbles integration, routing, and coordination flows
- message evidence, recovery, sync, and delivery handling
- BlueBubbles contracts used by downstream automation agents
- runbooks tied to BlueBubbles integration on OpenSIN platforms

## This repo must not own
- unrelated messaging surfaces or generic app automation
- browser/runtime infrastructure
- organization SSOT docs or architecture canon
- downstream business logic unrelated to BlueBubbles ownership

## Hard rules
- Keep changes scoped to BlueBubbles messaging integration and routing.
- Move non-BlueBubbles behavior back to the repos that own it.
- Keep reusable contracts focused on message coordination and delivery.
