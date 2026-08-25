# Changelog

All notable changes to the AnimMD specification are documented here.
Format based on [Keep a Changelog](https://keepachangelog.com/).

## [0.1] — 2026-08-25

### Added
- Initial draft: five verbs (`show`, `hide`, `draw`, `focus`, `pulse`) with cumulative vs momentary semantics and replay-from-zero state.
- The binding layer: three intents (`{node}`, `{edge}`, `{label}`), adapter constraints (patterns over exact rendered ids; an edge is one name, all its elements).
- Host embeddings: DiagramMD companion block (`anim for:`), MediaMD asset fields (`bindings`, `animation`), LearnMD reference block (`anim ref:`).
- `captions` anchor (`overlay` | `below`) and opt-in `badges` narrative overlay.
- Normative graceful-degradation table, accessibility notes, lenient/strict validation rules.
