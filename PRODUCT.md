# Product

<!-- impeccable:product-schema 1 -->

> Inferred from the user's exhaustive brief (no interview probe: the request fully specifies the artifact). Assumptions are labeled.

## Platform

web

## Stack

Inferred: single self-contained `index.html` (Canvas 2D, vanilla JS), no build step. The brief dictates Canvas 2D and a full-bleed ambient scene; a zero-dependency static file is the simplest thing that runs anywhere.

## Users

Inferred: the user and anyone who visits — people who want a calm, ambient place to rest their eyes, plus a personal dedication to the user's daughter Sofia at the bottom of the pond.

## Product Purpose

An ambient, interactive koi-pond scene. Success is a tender, alive-feeling piece that invites lingering, gentle interaction (ripples, feeding, curiosity) and that quietly carries the dedication to Sofia.

## Capabilities and Constraints

- Procedural koi: spine-segment travelling sine wave, body width profile, paddling pectoral fins, fanning tail, per-fish seeded pattern; varieties kohaku, showa, ogon, tancho.
- Steering: wander, mild separation, edge + lily avoidance, tail-burst/glide; startle on ripple; converge/jostle on feeding; slow-pointer curiosity.
- Scene: caustics on a low-res offscreen canvas, pebbles, drifting/bobbing lily pads + lotus, water striders, rotating maple leaves, corner stone edging with moss, occasional dragonfly with shadow.
- Interaction: tap → ripples; hold / double-tap → food pellets; keyboard Enter → ripple, Space → feed; drawn cursor ring; sound toggle off by default.
- Type: near-zero copy — vertical "Koi pond, noon." caption, fading gesture hint, nearest-fish name readout, all Georgia italic.
- Performance: ≤14 fish (fewer on small screens), low-res caustics, DPR capped at 2.
- Reduced motion: fish at ~1/3 speed, no caustic animation, gentle ripples.
- **Pinned personal requirement:** the bottom of the pool is dedicated to Sofia; her name appears beautifully, as if handwritten / brush-painted.

## Brand Commitments

Exact palette from the brief: teal #2C7A7B → deep #14323A → shallow jade #BFE3D0; koi orange #F26B21, white #FFFFFF, black #1B1B1B, yolk yellow #F2B33D; lily greens #3E8E5A / #6DB37C; lotus #F7C6D0.

## Product Principles

- Earned calm: nothing to achieve, motion is gentle and organic.
- Life through variation: seeded per-fish patterns and variety-specific motion.
- Depth on a flat surface: offset shadows, caustics, layered surface elements.
- The dedication must read as a natural, beautiful part of the pond floor — never a UI label.
