# AI-first design thinking — system architecture

An interactive system diagram for running design thinking workshops at AI-first organizations.

**Live demo:** _enable GitHub Pages on this repo; see Setup below_

## What this is

A POC concept exploring what design thinking workshops look like when re-architected around the capabilities AI now brings: delegate agents that represent participants, live sense-making over conversation, real-time tangibility, and a meta-layer that learns from each session and improves the next.

Scrub the lifecycle to see which subsystems activate at each stage.

## The premise

Design thinking's principles are durable — human centricity, divergence and convergence in distinct problem and solution spaces, diversity in participation, tangibility through prototyping. What's becoming re-architectable is the workshop's *meta*: who participates, how context arrives, how convergence is enacted, and how the practice itself learns over time.

## What the diagram shows

- **Meta layer (Workshop architect)** — sits outside the workshop. Takes intent from the facilitator, consults a pattern library, composes a tuned instance, and learns from each session via sentiment + outcomes feedback.
- **Workshop lifecycle** — eight phases from Spawn through Post-event, with the classic double-diamond mapped to phases 3–6.
- **System architecture** — four layers (Input, Context, Intelligence, Output) with twelve components that activate per phase.

## Setup (one-time)

This is a single self-contained HTML file. To publish:

1. In this repo's **Settings → Pages**, set source to `main` branch, `/` (root).
2. Wait ~30 seconds; the live URL appears at the top of the same page.
3. Update the **Live demo** link above with that URL.

## Author

Jason Armstrong — senior Design Operations / Design Strategy leader. 25+ years across Walmart, Netflix, Airbnb, Nike, R/GA.

## Status

POC concept · v0.3 · scrubable system view. Built with Claude.
