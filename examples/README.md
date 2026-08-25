# AnimMD examples

Complete, worked examples of AnimMD scripts, ready to copy.

## `water-cycle.diagram.md` — the DiagramMD companion embedding

A four-node **cycle** (oceans → vapour → clouds → precipitation → oceans),
the archetypal case where the order of revelation carries an argument: shown
all at once, a cycle reads as four boxes and four arrows; revealed in the
direction the water actually travels, the same figure carries the mechanism.

The file demonstrates:

- a DiagramMD catalogue entry and its ` ```anim for:<id> ` companion block;
- `bind` names for every node **and** every edge, written against the ids
  the Mermaid *source* declares (`O`, `V`, `C`, `P`) — never against
  rendered output;
- the `draw` + `show` + `focus` step pattern: each step draws the arriving
  edge, shows the node it introduces, and focuses both — the previous steps
  stay visible (cumulative) but dim (momentary focus);
- a final loop-closing step carrying the script's single `pulse`.

A lesson opts into playback with:

`````markdown
```anim ref:water-cycle
```
`````

## What makes a good AnimMD subject

Animate only when the reveal order argues something: a **cycle** walked in
its true direction, **superposed** layers or hypotheses, a **contrast**
staged before its resolution, a **construction** where each step motivates
the next. A simple linear chain (A → B → C) gains nothing from step-reveal —
the reader already reads it in order.
