# AI-first design thinking — system architecture

An interactive scrollytelling system diagram for running design thinking workshops at AI-first organizations.

**Live demo:** [designisagoodidea-2026.github.io/claude-dt-system](https://designisagoodidea-2026.github.io/claude-dt-system/)

## What this is

A POC concept exploring what design thinking workshops look like when re-architected around the capabilities AI now brings: delegate agents that represent participants, a main orchestrator that dials each agent's volume up and down by phase, a shared multiplayer canvas + workshop HUD, a real-time skill exchange that grows the group's collective toolkit during the session, and a meta-layer architect that spawns the workshop, governs access, updates the configuration mid-flight, and learns from each session to improve the next.

Scroll through the three acts: **Before** (architect spawns the workshop), **During** (humans gather; scrub the lifecycle), **After** (synthesis + architect learns). The system architecture is the sticky constant — it stays in view as the surrounding scenes move past it.

## The premise

Design thinking's principles are durable — human centricity, divergence and convergence in distinct problem and solution spaces, diversity in participation, tangibility through prototyping. What's becoming re-architectable is the workshop's *meta*: who participates, how context arrives, how convergence is enacted, how the group's collective toolkit grows during the session, and how the practice itself learns over time.

The event itself is fundamentally **humans coming together to discuss something that matters**. The system supports, surrounds, and accelerates — it doesn't replace the humans in the room.

## What the diagram shows

- **Meta layer (Workshop architect)** — sits outside the workshop. Six components: Intent intake, Pattern library, Composer, Updater (live updates mid-flight), Permissions (governance), Outcomes store (post-event learning).
- **System architecture** — 14 subsystems across four layers:
  - *Input* — voice ingest, transcription, speaker diarization
  - *Context* — indexed org IP, pre-event research, skill exchange
  - *Orchestration* — main orchestrator, delegate agents, research agents, facilitator agent, sense-making layer
  - *Output* — shared canvas, decision capture, post-event synthesis
- **Workshop lifecycle** — six scrubable phases from Opening through Decision, with the classic double-diamond mapped to phases 2–5.

## Author

Jason Armstrong — senior Design Operations / Design Strategy leader. 25+ years across Walmart, Netflix, Airbnb, Nike, R/GA.

## Status

POC concept · v0.9 · scrollytelling presentation. Built iteratively with Claude. Source is a single self-contained `index.html` file with no build step.
