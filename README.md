# AnimMD

> **Status:** Draft (v0.1) — not yet stable. Part of the [LearnSpec](https://github.com/learnspec) suite.

**AnimMD** is an open, Markdown-based format for **step-reveal animations** over existing vector scenes — diagrams from a [DiagramMD](https://github.com/learnspec/diagrammd) catalogue or SVG assets from a [MediaMD](https://github.com/learnspec/mediamd) catalogue.

An AnimMD script is valid Markdown: one heading per step, directive lines, prose captions. It contains no timeline, no keyframes, and no coordinates — it only chooses the *order of revelation* of elements the scene already contains, through a generator-agnostic binding layer. Every failure mode degrades to the static scene the host already displays.

## Specification

See [SPEC.md](./SPEC.md) for the full format specification. Worked examples live in [examples/](./examples/). The shared design principles, universal frontmatter fields, and cross-format directives are defined in the [LearnSpec Architecture Charter](https://learnspec.org/charter/).

## Related formats

| Format | Repo |
|---|---|
| LearnMD — instructional content | [learnspec/learnmd](https://github.com/learnspec/learnmd) |
| QuizMD — assessments | [learnspec/quizmd](https://github.com/learnspec/quizmd) |
| MediaMD — media catalogue | [learnspec/mediamd](https://github.com/learnspec/mediamd) |
| DiagramMD — diagram syntax | [learnspec/diagrammd](https://github.com/learnspec/diagrammd) |
| AnimMD — step-reveal animations | [learnspec/animmd](https://github.com/learnspec/animmd) |
| FlashMD — flashcards | [learnspec/flashmd](https://github.com/learnspec/flashmd) |
| GlossaryMD — glossaries | [learnspec/glossarymd](https://github.com/learnspec/glossarymd) |
| TrackMD — learning paths | [learnspec/trackmd](https://github.com/learnspec/trackmd) |
| BadgeMD — micro-credentials | [learnspec/badgemd](https://github.com/learnspec/badgemd) |
| CertMD — macro-credentials | [learnspec/certmd](https://github.com/learnspec/certmd) |

## License

[MIT](./LICENSE)
