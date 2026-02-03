# PRD — Study Hub Cross-Navigation (Company Deep Dives ↔ AI Value Chain)

## Summary
Add contextual cross-navigation between Company Deep Dive pages and AI/Semiconductor Value Chain pages in Study Hub. Provide “Related Context” cards on company pages and “Companies in This Layer” cards on value chain pages to improve reader flow.

## Goals
- Surface relevant value chain context from each Company Deep Dive.
- Surface relevant company deep dives from each value chain layer.
- Preserve existing Study Hub visual system and layout structure.

## Non-Goals
- No redesign of existing pages or global styles.
- No changes to content outside the new cross-link sections.

## Scope
- Insert “Related Context” sections before jargon decoders on five company deep dives.
- Insert “Companies in This Layer” sections before jargon decoders on specified value chain pages.
- Use existing card styling, CSS variables, and hover behaviors.

## Requirements
### Related Context (Company Deep Dives)
- Section title: “🔗 Related Context”.
- Card list with value chain links and short relevance blurbs.
- Insert before jargon decoder section.

### Companies in This Layer (Value Chain)
- Section title: “🔍 Companies in This Layer”.
- Card list with deep dive links and short blurbs.
- Insert before jargon decoder section.

## Success Metrics
- New sections render cleanly on desktop and mobile.
- Links resolve correctly with proper relative paths.
- No layout regressions or ID conflicts.

## Open Decisions
- None.
